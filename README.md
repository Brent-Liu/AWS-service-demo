This project involves developing a responsive web user interface using React and TailwindCSS. The interface is designed to collect text input and files from users. 

The front-end of this application is hosted on Amazon S3, ensuring high availability and reliability.

The backend functionality is managed through AWS services. When a user uploads a file, it is stored in an S3 bucket, while the text data is sent to DynamoDB. This process is facilitated by an API Gateway that routes the requests, and AWS Lambda functions that process these requests.

Additionally, the system is configured to automate the launch of a new EC2 instance upon specific triggers. This new EC2 instance is programmed to execute pre-defined AWS CLI commands and Bash scripts. After successfully completing its tasks, the instance is set up to terminate itself automatically, optimizing resource usage and cost-efficiency.

This architecture demonstrates a seamless integration of various AWS services, showcasing a scalable and efficient cloud-based solution.
