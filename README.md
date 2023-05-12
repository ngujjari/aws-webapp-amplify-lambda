# aws-webapp-amplify-lambda

API gateway URL for Lambda
 https://uov47e7w4i.execute-api.us-east-1.amazonaws.com/Dev

DynamoDB ARN: arn:aws:dynamodb:us-east-1:123227712048:table/PowerOfMath

Lamda IAM DynamoDB Exection policy - attach to the lambda execution role.
{
"Version": "2012-10-17",
"Statement": [
    {
        "Sid": "VisualEditor0",
        "Effect": "Allow",
        "Action": [
            "dynamodb:PutItem",
            "dynamodb:DeleteItem",
            "dynamodb:GetItem",
            "dynamodb:Scan",
            "dynamodb:Query",
            "dynamodb:UpdateItem"
        ],
        "Resource": "arn:aws:dynamodb:us-east-1:123227712048:table/PowerOfMath"
    }
    ]
}

Reference:
https://www.youtube.com/watch?v=7m_q1ldzw0U

 
