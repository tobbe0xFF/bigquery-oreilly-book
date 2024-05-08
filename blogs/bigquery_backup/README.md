## Backup (and restore) a BigQuery table or dataset

Accompanies the blog post:
https://medium.com/google-cloud/how-to-backup-a-bigquery-table-or-dataset-to-google-cloud-storage-and-restore-from-it-6ef7eb322c6d

### Example usage

1. Backup a table/view to GCS
```
python.exe bigquery_backup.py --input project_name:dataset_name.table_name --output gs://BUCKET_NAME/.../
```
Subfolders with the dataset and table names resepctively are automatically created under the specified GCS path. Inside a schema.json, a tabledef.json, and extracted data in AVRO format is saved. In case of views only the schema and table definitions are created but no data is stored.


2. You can also backup all the tables/views in a data set:
```
python.exe bigquery_backup.py --input project_name:dataset_name --output gs://BUCKET_NAME/.../
```
Works as in example 1 but iterates over all tables and views in the dataset.

3. Restore tables/views one-by-one by specifying a destination data set
```
python.exe bigquery_restore.py --input gs://BUCKET_NAME/.../dataset_name/table_name --output project_name:dataset_name
```


### Dependencies
These require gcloud and bq command-line utilities to be installed.