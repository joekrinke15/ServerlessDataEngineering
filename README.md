# Serverless Medical NLP Pipeline
A serverless medical NLP pipeline hosted on AWS. This project loads names of medical conditions stored in a Dynamo DB database, reads in text from the corresponding Wikipedia article, and performs entity extraction on the text using AWS Medical Comprehend. The extracted entities are saved to .txt files that are stored in an S3 bucket.
# Pipeline Diagram
![Serverless Architecture](https://raw.githubusercontent.com/joekrinke15/ServerlessDataEngineering/master/AWSServerlessMedical.png)
# Database Structure
![Database Structure](https://raw.githubusercontent.com/joekrinke15/ServerlessDataEngineering/master/DynamoDB.PNG)
# Sample Output
![Sample Entity Output](https://raw.githubusercontent.com/joekrinke15/ServerlessDataEngineering/master/SampleEntity.PNG) 
 
