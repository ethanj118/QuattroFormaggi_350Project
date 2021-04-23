# Quattro Formaggi Final Project: ReadMe
Final project repo for Quattro Formaggi

## Guide to this repo:

### Sections:

*Blog:*

This section contains a link to the blog we created for this project, as well as images and screenshots used in the blog.

A link to the blog can also be found here: [link](https://project-blog-final.s3.amazonaws.com/Project_Blog_Final.html)

*Python Notebooks:*

This folder contains Python notebooks that we used for this project, whether for data analysis, creating blogs or markdown pages, or organizing data.

*Charts and Diagrams:*

This folder contains a copy of our infrastructure diagram, as well as any other plots or diagrams created.

*Raw Data*

This folder contains a copy of raw data used for our project. It contains all the image files that were uploaded to S3 buckets and later used for analysis.

### Amazon Services Used

Certain Amazon services were used in this project. More detail is in the blog, but basic information can be found here.

*[Amazon SageMaker](https://docs.aws.amazon.com/sagemaker/?id=docs_gateway)*

Amazon SageMaker serves as a platform to use Machine Learning models. SageMaker can also run Jupyter notebooks and terminal instances.

*[Amazon S3](https://docs.aws.amazon.com/s3/index.html)*

Amazon S3 provides storage services. Files stored in buckets can be accessed when using other Amazon services.

[Use documentation](https://docs.aws.amazon.com/s3/index.html)

*[Amazon IAM](https://docs.aws.amazon.com/iam/?id=docs_gateway)*

Amazon Identity and Access Management (IAM) provides ways to secure files and Amazon services so that only certain users (or groups of users) can access them.

[Use documentation](https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html)

*[Amazon Rekognition](https://docs.aws.amazon.com/rekognition/?id=docs_gateway)*

Amazon Rekognition is the main Amazon ML service used in this project. Rekognition can analyze pictures and return a prediction of the features and elements in the pictures. 

[Use documentation](https://docs.aws.amazon.com/rekognition/latest/dg/getting-started.html)

## **Replication**

For replication of this project, the AWS services listed above are necessary. It is recommended to clone this repository and open the notebooks in SageMaker.
