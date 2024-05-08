# Tobbe0xFF fork of bigquery-oreilly-book

This fork focuses on fixing a couple of bugs/limitations in the bigquery scripts of the blog directory. Namely:
* Prevents file does not exist errors
* Removed verbose schema declaration in logs
* Creates output files with expected table name correctly in GCP
* Prevents invalid paths when running on Windows machine
* Handles dataset paths including GCP project name correctly

# Original information about this repository

Source code accompanying:

<table>
<tr>
  <td>
  <img src="cover.jpeg" height="100"/>
  </td>
  <td>
  <a href="https://www.oreilly.com/library/view/google-bigquery-the/9781492044451/">BigQuery: The Definitive Guide</a> <br/>
  by Valliappa Lakshmanan and Jordan Tigani <br/>
  O'Reilly, Nov 2019
  </td>
  <td>
    <a href="https://amazon.com/Google-BigQuery-Definitive-Warehousing-Analytics/dp/1492044466">Buy on Amazon</a>
  </td>
  <td>
    <a href="https://www.oreilly.com/library/view/google-bigquery-the/9781492044451/">Read online on Safari</a>
  </td>
</table>

## After June 2020
Articles that update parts of the book
* [Remote Functions in BigQuery](https://towardsdatascience.com/remote-functions-in-bigquery-af9921498438)
* [Working with JSON data in BigQuery](https://medium.com/google-cloud/working-with-json-data-in-bigquery-24ca8fd6e90c)
* [An Agile Architecture for Analytics and AI on Google Cloud](https://medium.com/google-cloud/an-agile-architecture-for-analytics-and-ai-on-google-cloud-6415e692591f)
* [Explaining a BigQuery ML model](https://lakshmanok.medium.com/explaining-a-bigquery-ml-model-5cf8d9636ec9)
* [Anomaly detection in time series data using BigQuery ML](https://lakshmanok.medium.com/anomaly-detection-in-time-series-data-using-bigquery-ml-b70e10a9f3ff)
* [Hyperparameter tuning BigQuery ML: BigQuery ML can use Vertex AI to tune common model parameters](https://medium.com/google-cloud/hyperparameter-tuning-directly-within-bigquery-ml-a0affb0991ae)
* [Quickly create BigQuery demo/dev environments using SQL](https://lakshmanok.medium.com/quickly-create-bigquery-demo-dev-environments-using-sql-b14f734f7f96)
* [PIVOT in BigQuery](https://towardsdatascience.com/pivot-in-bigquery-4eefde28b3be)
* [Speeding up small queries in BigQuery with BI Engine](https://lakshmanok.medium.com/speeding-up-small-queries-in-bigquery-with-bi-engine-4ac8420a2ef0)
* [How to Trigger Cloud Run Actions on BigQuery Events](https://lakshmanok.medium.com/how-to-trigger-cloud-run-actions-on-bigquery-events-e818ee910560)
* [Loading complex CSV files into BigQuery using Google Sheets](https://cloud.google.com/blog/topics/developers-practitioners/loading-complex-csv-files-bigquery-using-google-sheets)
* [Building SQL pipelines in BigQuery with Dataform](https://medium.com/google-cloud/building-sql-pipelines-in-bigquery-with-dataform-part-1-9e96f14ec664)
* [Validating successful execution of BigQuery scripts using ASSERT](https://medium.com/google-cloud/validating-successful-execution-of-bigquery-scripts-using-assert-c82f7ff9cfa8)
* [RANGE_BUCKET](https://stackoverflow.com/questions/62355815/how-do-you-replace-a-value-by-its-percentile-in-bigquery)
* [How to right-size your flat-rate and flex slots reservations in BigQuery](https://medium.com/google-cloud/how-to-move-from-on-demand-pricing-to-reservations-in-bigquery-65552cbebd45)
* [How to do text similarity search and document clustering in BigQuery](https://towardsdatascience.com/how-to-do-text-similarity-search-and-document-clustering-in-bigquery-75eb8f45ab65)
* [Trying out Data QnA on BigQuery and Google Sheets](https://medium.com/daas-labs/trying-out-data-qna-on-bigquery-and-google-sheets-e47939fddf25)
* [How to load XML data into BigQuery using Python Dataflow](https://medium.com/google-cloud/how-to-load-xml-data-into-bigquery-using-python-dataflow-fd1580e4af48)
* [The best of both worlds: Calling Auto ML from BigQuery](https://towardsdatascience.com/the-best-of-both-worlds-calling-auto-ml-from-bigquery-9dfd433a45d6)
* [Loading and transforming data into BigQuery using dbt](https://medium.com/google-cloud/loading-and-transforming-data-into-bigquery-using-dbt-65307ad401cd)


## January 2020 to June 2020
Articles that update parts of the book, and incorporated into text in June 12, 2020 edition.
* [Integration between TensorFlow 2.0 and BigQuery](https://towardsdatascience.com/how-to-read-bigquery-data-from-tensorflow-2-0-efficiently-9234b69165c8)
* [How to query geographic raster data in BigQuery efficiently](https://medium.com/google-cloud/how-to-query-geographic-raster-data-in-bigquery-efficiently-b178b1a5e723)
* [Backing up and restoring a BigQuery table/view/dataset](https://medium.com/google-cloud/how-to-backup-a-bigquery-table-or-dataset-to-google-cloud-storage-and-restore-from-it-6ef7eb322c6d)
* [How to copy a BigQuery dataset from one region to another](https://medium.com/google-cloud/how-to-copy-a-bigquery-dataset-from-one-region-to-another-8388d74da2ac)
* [Training a recommendation model for Google Analytics data using BigQuery ML](https://towardsdatascience.com/training-a-recommendation-model-for-google-analytics-data-using-bigquery-ml-2327f9a2e8e9)
* [Using BigQuery (and BigQuery ML) from Kubeflow Pipelines](https://medium.com/google-cloud/using-bigquery-and-bigquery-ml-from-kubeflow-pipelines-991a2fa4bea8)
* [Displaying BigQuery results on Google Maps using Data Studio](https://medium.com/google-cloud/displaying-bigquery-results-on-google-maps-using-data-studio-bded264bfd53)
* [Using BigQuery Flex Slots to run machine learning workloads more efficiently](https://medium.com/google-cloud/using-bigquery-flex-slots-to-run-machine-learning-workloads-more-efficiently-7fc7f400f7a7)
* [How to export a BigQuery ML model and deploy it for online prediction](https://medium.com/@lakshmanok/how-to-export-a-bigquery-ml-model-and-deploy-it-for-online-prediction-a7e4d44c4c93)
