# Setting Up Your Cloud Account

(Work in progress)

This page contains setup information for setting up your google cloud account to use various google services. 

### Create a Google Account

You will need to create a google cloud account. You may already have one if you have a gmail address or have used Google Colab.

### Set up Billing

To use the services in Google Cloud, you will need to create a billing acount, which requires a credit card or other payment info.
You should not incur any charges from the excercises in this tutorial, as our use will remain on the free tier. 

As of this writing, google cloud provides an initial credit of $300 for new accounts. You may want to use this for your own projects,
though this tutorial should not incur any charges or make any use of thsse credits.  

### Create a Project

### Create Credentials

Open APIS and Services->Credentials
Create a Service Account
On the service account, click on Keys
Create new key
Download as JSON
Enter the path to this key in google_application_credentials in the properties.yaml file

### Create a Cloud Storage Bucket
Create a cloud bucket (I dont think this needs public access)
Enter the bucket name in the properties file

### All set, you're good to go!
