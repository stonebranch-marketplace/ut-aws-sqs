# aws-sqs
This download is designed as a template to be adapted to your environment. In some cases, templates will need to be changed to work with your current Universal Automation Center (UAC) setup. This download is free to use. However, the download is not supported, and no warranty is provided by Stonebranch for this document and the related download.  The use of this document and the related download is at your own risk. Before using this download in a production system, please perform testing. 

Stonebranch assumes no liability for any issues caused by the performance of this download.

<p><strong>Request Support:</strong></p>
<ul>

Stonebranch offers paid support, by request, for select Universal Tasks. Paid support provides installation and on-going technical support. Universal Tasks that are eligible for paid support will be noted as “support eligible” within the Universal Task listing page. To learn more, please contact Stonebranch.

Introduction
Storing data in the cloud becomes an integral part of most modern IT landscapes. With Universal Automation Center you can securely automate your AWS, Azure, Google and MinIO File Transfers and integrate them into your existing scheduling flows.

As security is one of the key concerns when moving to the cloud, the provided solution supports multi-level of security:

<li>Credentials for AWS S3 (Access Key, Secret Access key and Region) are stored in an encrypted form in the database<li>
<li>IAM Role-Based Access Control (RBAC) is supported<li>
<li>Communication to AWS is done via the HTTPS protocol<li>
<li>A Proxy Server connection to AWS with basic authentication is supported<li>
<li>Secure access to AWS S3 buckets using AWS bucket policies can be configured in the AWS console<li>
<li>Restrict sending files only to specific buckets using AWS End Points can be configured in the AWS console<li>

This Universal Task focuses on the AMAZON AWS S3 file transfer, including support for MinIO. MinIO is an Open Source object storage server for private cloud environments based on Amazon’s S3 API. All file transfer scenarios supported for AMAZON AWS S3 are also support for MinIO. The scenarios described in this documentation are also valid for MinIO.

A similar solution as for AWS S3 is also available for Microsoft Azure Blob Storage and Google Cloud Storage.
