<h1>OCI Data Integration Postman Examples</h1>
<h2>Introduction</h2>
This contains one Postman Environment for OCI and two collections with example of OCI Data Integration. 
Download the repository's Postman collections and environment.
Import the environment into Postman using the ‘Import’ button at the top, and activate it by selecting it from the top right drop-down.
Open and Edit the newly imported environment, and set the OCI REST variables tenancy_ocid, user_ocid, fingerprint and private_key.
Now import the two collections into Postman.


<h2>OCI Environment</h2>
To use this you will have to update the OCI Environment.
Update the environment (OCI_Credentials) with your tenancy ocid, user ocid, fingerprint and private key.


<h2>Data Integration REST Tasks</h2>
Edit the REST Task Library collection, go to the variables and update the workspace OCID, project key (to create the examples in) and also the region if different.
You can then run the collection and all of these REST tasks will be created in the project.

<h2>Data Integration APIs</h2>
Edit the Data Integration APIs collection, go to the variables and update the workspace OCID, project key (to create the examples in), application keys and also the region if different. There are others there for copy application and sync application along with some of the other APIs.

<h2>Data Integration REST Utilities</h2>
Edit the Data Integration REST Utilities collection, go to the variables and update the workspace OCID, project key (to create the examples in)  and also the region if different. You can then run the collection and all of these REST tasks will be created in the project. These REST tasks are dependent on the sftp blog and zipper blog.

