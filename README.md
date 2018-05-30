## Serverless Telegram bot on AWS Lambda

### Description
Simple proof of concept of Telegram chatbot + Python 3 + AWS Lambda + Serverless framework.

### Deploying

Install Serverless framework:

`npm install -g serverless`

Export credentials:

```
export AWS_ACCESS_KEY_ID=<Access key ID>
export AWS_SECRET_ACCESS_KEY=<Secret access key>
export TELEGRAM_TOKEN=<Your Telegram Token>
```

Install pip requirements:

`pip install -r requirements.txt -t vendored`

Deploy to AWS:

`serverless deploy`