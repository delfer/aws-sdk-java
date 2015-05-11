# Amazon Simple Email Service JavaMail Sample

This sample demonstrates how to send email using the AWS Simple Email Service JavaMail provider from the AWS SDK for Java.

## Prerequisites

*   You must have a valid Amazon Web Services developer account.
*   Requires the AWS SDK for Java. For more information on the AWS SDK for Java, see [http://aws.amazon.com/sdkforjava](http://aws.amazon.com/sdkforjava).
*   You must be signed up for the following services:
    *   Amazon Simple Email Service. For more information, see [http://aws.amazon.com/ses](http://aws.amazon.com/ses).

## Running the Sample

The basic steps for running this sample are:

1.  Open the `AwsCredentials.properties` in the sample folder.

2.  Locate the following section and fill in your Access Key ID and Secret Access Key:  

    ```
    # Fill in your AWS Access Key ID and Secret Access Key  
    # http://aws.amazon.com/security-credentials  
    accessKey =  
    secretKey =
     ```

3.  Save the file.

4.  Run the `AWSJavaMailSample.java` file, located in the same directory as the properties file. The sample prints information to the standard output.

**NOTE:** The sample also includes an Ant build.xml file to run the sample.