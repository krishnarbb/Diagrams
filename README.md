# Diagrams
1.	When the user visits the web application’s URL, the URL’s DNS resolution is performed using the Route53 DNS service. 
2.	The browser then downloads the application’s HTML, CSS, and JavaScript files from Amazon S3 via Amazon CloudFront.
3.	The application authentication is performed using Cognito.
4.	The application then calls API Gateway endpoints to securely fetch and store dynamic data.
5.	AWS Lambda can be used for processing the business logic.
6.	For functions that need a durable store of user data, Amazon DynamoDB provides a highly scalable, low-latency, cost-effective database solution. 
