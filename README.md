https://github.com/shetty12/spotify_etl/edit/main/README.md

# Spotify_Data_Pipeline


Technologies Used:
Spotipy Python library and AWS services including Lambda for computation, S3 for storage, CloudWatch for monitoring, and Athena for querying data.

📌 Extract Phase:
Data is extracted from the Spotify API using Python scripts with Spotipy.
AWS Lambda runs the extraction function, triggered automatically by AWS CloudWatch.
Raw data is stored in an S3 bucket under the "to_processed" folder.
📌 Transform Phase:
S3 triggers a Lambda function whenever new data is uploaded.
AWS Lambda transforms the data and organizes it in S3 by album, artist, and song.
Processed data is moved from the "to_processed" folder to the "processed" folder.
📌 Load Phase:
AWS Glue Crawler infers the schema of new data in S3.
AWS Glue Data Catalog manages the metadata.
The final dataset is accessible via Amazon Athena for in-depth analysis and querying.

# Spotify_Data_Pipeline


Technologies Used:
Spotipy Python library and AWS services including Lambda for computation, S3 for storage, CloudWatch for monitoring, and Athena for querying data.

📌 Extract Phase:
Data is extracted from the Spotify API using Python scripts with Spotipy.
AWS Lambda runs the extraction function, triggered automatically by AWS CloudWatch.
Raw data is stored in an S3 bucket under the "to_processed" folder.
📌 Transform Phase:
S3 triggers a Lambda function whenever new data is uploaded.
AWS Lambda transforms the data and organizes it in S3 by album, artist, and song.
Processed data is moved from the "to_processed" folder to the "processed" folder.
📌 Load Phase:
AWS Glue Crawler infers the schema of new data in S3.
AWS Glue Data Catalog manages the metadata.
The final dataset is accessible via Amazon Athena for in-depth analysis and querying.

## Badges



![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![AWS Lambda](https://img.shields.io/badge/AWS%20Lambda-FF9900?logo=amazon-aws&logoColor=white)
![Amazon S3](https://img.shields.io/badge/Amazon%20S3-569A31?logo=amazon-s3&logoColor=white)
![Amazon CloudWatch](https://img.shields.io/badge/Amazon%20CloudWatch-FF4F8B?logo=amazon-cloudwatch&logoColor=white)
![Amazon Athena](https://img.shields.io/badge/Amazon%20Athena-1B1F23?logo=amazon-athena&logoColor=white)
![AWS Glue](https://img.shields.io/badge/AWS%20Glue-3F3F3F?logo=amazon-aws&logoColor=white)
![AWS Glue Crawler](https://img.shields.io/badge/AWS%20Glue%20Crawler-232F3E?logo=amazon-aws&logoColor=white)







