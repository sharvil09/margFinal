# margFinal
This is our final project for QTM 350.

## You will find the following notebooks and tools in this repo. 

### Blog Post 
Here you can find the background and rationale behind our experiments and the high-level explanation of the AWS resources used in our project.

### Data Preparation
This notebook is a well-documented showcase of how we prepared and analyzed our data while running the experiments. It also contains code for a real-time Reddit data comparator usin clustering to analyze and compare similar cities in GA. To access this data, go [here](https://marg-final-views.s3.amazonaws.com/Data+Preparation+and+Analysis.html).

### Potential Application
To access our tool showcase, go to [this link](https://mybinder.org/v2/gh/sharvil09/margFinal/HEAD). After it loads, choose the notebook labeled, "Comprehend Showcase.ipynb". After the notebook loads, navigation to the kernel option and click "Restart and run all cells". At the bottom of the page, choose a city from the list and generate your insights!

## Workflow

To see more specific details on: 
* how things were set up through the AWS console, use the blog post notebook
* what code was used to clean and analyze the data, use the data preparation notebook
* how to set up your own visualization tool for big data, use the potential application notebook'

We will provide a high-level explanation of our workflow for the experiments so that anyone can replicate our results.

1. Create an AWS account.
2. Set up an S3 bucket to store your input data in or use the raw files from the github.
3. Create a SageMaker instance that has permissions to connect to the Comprehend API and S3 buckets.
4. Run our code in your SageMaker notebook.
5. Manipulate the data and generate new insights. Have fun with it!!

We hope you enjoyed our work, and if this of further interest feel free to let us know so we can do some more work with it.

## Resources

### AWS Services
* Amazon S3 Buckets (x2)
* Amzon Comprehend
* Amazon Sagemaker
* Amazon Identity and Access Management

### External Services 
* myBinder
* Pushshift's Reddit API
