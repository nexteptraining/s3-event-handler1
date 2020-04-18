1. Run "mvn clean package"
2. Create Lambda function, name it "s3-event-handler1"
3. Upload your jar file
4. Configure your Lambda handler as "com.nextep.lambda.S3EventHandler::handleRequest"