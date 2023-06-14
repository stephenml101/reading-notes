# Amazon S3

[Introduction to Amazon S3](https://docs.aws.amazon.com/AmazonS3/latest/dev/Introduction.html)

1. What is Amazon S3?

- Amazon S3 is a scalable object storage service offered by Amazon Web Services (AWS) that allows users to store and retrieve large amounts of data.

2. List at least 3 features that it offers to its users.

- Durability and high availability: S3 is designed to provide 99.999999999% (11 nines) durability of objects and 99.99% availability over a given year.
- Scalability and performance: It can handle virtually unlimited amounts of data and concurrent user requests, offering high performance.
- Data management: S3 provides features like versioning, lifecycle policies, and cross-region replication to manage and control data storage.

3. What is an object key?

- An object key in Amazon S3 is a unique identifier for an object stored in a bucket. It is a string that can be used to retrieve or manipulate the object within the bucket.

[S3 with Amplify](https://docs.amplify.aws/lib/storage/getting-started/q/platform/android/)

1. Which dependencies are needed to install Amplify AWS S3 to your android application?

- To install Amplify AWS S3 in an Android application, you need to add the following dependency in your app-level build.gradle file:

``` java
implementation 'com.amplifyframework:aws-storage-s3:1.24.0'
```

2. What is needed in order to upload data to your bucket?

- In order to upload data to your bucket using Amplify AWS S3, you need to have valid AWS credentials, including an access key and a secret access key, which provide the necessary permissions to access and upload data to the bucket.

3. What method(s) initialize(s) the Amplify Auth and Storage categories?

- The Amplify Auth and Storage categories can be initialized using the Amplify.addPlugin() method. For example, in Android, you would typically initialize them in the onCreate() method of your application's main activity using:

``` java
Amplify.addPlugin(new AWSCognitoAuthPlugin());
Amplify.addPlugin(new AWSS3StoragePlugin());
Amplify.configure(getApplicationContext());
```