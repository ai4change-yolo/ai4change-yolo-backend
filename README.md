# ai4change-yolo-backend
The backend part of application - deployed on AWS
The repository contains the lambda function which is used to generate recommendations. The input to the lambda function is provided from the IoT Core service in AWS - all messages from the topic "products" generated in a device represented by a "Thing" are routed to the lambda function. The output of the lambda function is republished to the topic "advice".
For more information see the README file in the ai4change-yolo-device repository.
