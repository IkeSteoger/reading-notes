# 401 Reading 19

## AWS: Events

### What is the difference betweeen SQS and SNS?

SNS is a distributed publish-subscribe service.  
SQS is a distrbuted queueing service.

### What are some use cases for both SNS and SQS?

SNS should be used if you want to be able to publish and consume batches of messages, or if you would like to allow the same message to be processed in multiple ways, and many subscribers are needed (think push notifications on phones!)

SQS should be used if you need a simpe queue with not particular requirements. Decoupling two applications and allowing parallel async processing. Only one subscriber instead of multiple.

### Describe how to use SQS and SNS in a “fanout” pattern

the SNS sends multiple notifications out to many SQS queues!

### Explain how “push notifications” work, using SNS

"Push notification services, such as APNs and FCM, maintain a connection with each app and associated mobile device registered to use their service. When an app and mobile device register, the push notification service returns a device token. Amazon SNS uses the device token to create a mobile endpoint, to which it can send direct push notification messages. In order for Amazon SNS to communicate with the different push notification services, you submit your push notification service credentials to Amazon SNS to be used on your behalf." - [docs.aws.amazon.com]

### How might a large scale, distributed application make use of a Queue system like SQS?

They could use a system like SQS to create a bunch of messages to send to clients but never lose them because they are in a queue.

### What are your learning goals after reading and reviewing the class README?

Looks like queues are back - hoping I can grasp them properly!
