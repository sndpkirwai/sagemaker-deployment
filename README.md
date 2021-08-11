# sagemaker-deployment

# Creating and Running a Notebook Instance
First, start by logging in to the AWS console, opening the SageMaker dashboard, selecting Notebook Instances and clicking on Create notebook instance.
You may choose any name you would like for your notebook. Also, using ml.t2.medium should be all that is necessary for the notebooks that you will encounter in this module. In addition, an ml.t2.medium instance is covered under the free tier.
Next, under IAM role select Create a new role. You should get a pop-up window that looks like the one below. The only change that needs to be made is to select None under S3 buckets you specify, as is shown in the image below.

Now scroll down and click on Create notebook instance.
Once your notebook instance has started and is accessible, click on open to get to the Jupyter notebook main page.


# Cloning the Deployment Notebooks
In order to clone the deployment repository into your notebook instance, click on the new drop down menu and select terminal. By default, the working directory of the terminal instance is the home directory, however, the Jupyter notebook hub's root directory is under SageMaker. Enter the appropriate directory and clone the repository as follows:

cd SageMaker
git clone https://github.com/sndpkirwai/sagemaker-deployment.git
exit

After above steps performed in AWS SageMaker, we are ready to use notebook.