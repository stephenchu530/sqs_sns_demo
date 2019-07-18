# SQS Demo

This is to demo AWS' Simple Queue Service using Java apps

## Instructions:

#### Step 1: Download Files
```
 $ git clone git@github.com:stephenchu530/sqs_sns_demo.git
```
or
```
 $ git clone https://github.com/stephenchu530/sqs_sns_demo.git
```

#### Step 2: Create an AWS Queue
- Make sure the queue is a `Standard Queue`
- Note the queue name
- Note the queue URL
- If you're not sure how to do this, google search it

#### Step 3: Edit the QPublisher and QClient code
For QPublisher, edit the following: `qpublisher/src/main/java/qpublisher/App.java`
- On line 19, change `QueueA` to whatever you named your queue

For QClient, edit the following: `qclient/src/main/java/qclient/App.java`
- On line 17, change `QueueA` to whatever you named your queue

#### Step 4: Ensure in your terminal environment that `AWS configure` is setup correctly
From the command line, run the following:
```
 $ aws configure
```
Add in your AWS client key and secret key

If you do not have an AWS client and secret key, then google search it.

If you do not have AWS CLI installed in your terminal, then google search it.

## Resource:
https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/standard-queues-getting-started-java.html



