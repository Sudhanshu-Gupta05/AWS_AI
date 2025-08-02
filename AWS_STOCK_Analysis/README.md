Overview of Project

This project builds a real-time stock market data analytics pipeline using AWS, leveraging event-driven architecture and serverless technologies. The architecture ingests, processes, stores, and analyzes stock market data in real-time while minimizing costs.


Key tasks include:

- Streaming real-time stock data from sources like yfinance using Amazon Kinesis Data Streams.
- Processing data and detecting anomalies with AWS Lambda.
- Storing processed stock data in Amazon DynamoDB for low-latency querying.
- Storing raw stock data in Amazon S3 for long-term analytics.
- Querying historical data using Amazon Athena.
- Sending real-time stock trend alerts using AWS Lambda & Amazon SNS (Email/SMS).

Architecture Diagram attached

LambdaCode - Attached

Services Used 🛠
 - Amazon Kinesis Data Streams – Ingests stock data in real-time.
 - AWS Lambda – Processes stock data and detects stock trends.
 - Amazon DynamoDB – Stores structured stock data for quick lookups.
 - Amazon S3 – Stores raw stock data for historical analysis.
 - Amazon Athena – Queries stock data directly from S3.
 - Amazon SNS – Sends stock trend alerts via Email/SMS.
 - IAM Roles & Policies – Manages permissions securely.

 OUTPUT :

 A fully functional near real-time stock analytics pipeline built using AWS services, featuring:

- Event-driven architecture with Amazon Kinesis for real-time data ingestion
- Lambda-based anomaly detection and stock trend evaluation
- Low-latency storage in DynamoDB for fast access to processed data
- Historical data archiving in Amazon S3 and querying via Athena
- Real-time alerts via Amazon SNS (Email/SMS) for significant stock movements
- Secure and cost-optimized design using IAM and serverless technologies

Conclusion :

Conclusion
This project successfully demonstrates how to build a near real-time stock market data analytics pipeline using AWS’s fully managed, serverless services. By integrating Amazon Kinesis, AWS Lambda, Amazon DynamoDB, Amazon S3, Amazon Athena, and Amazon SNS, we've created a robust and scalable architecture capable of streaming, processing, storing, analyzing, and alerting on stock data with minimal operational overhead.

Key outcomes include:
Real-time data ingestion and processing with event-driven architecture.
Anomaly detection and trend alerts using AWS Lambda and SNS.
Separation of raw and processed data for efficient storage and analytics.
Low-cost implementation suitable for learning and prototyping.
