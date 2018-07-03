# ArchitectingWithGCP_Fundamentals_Course3_EssentialCloudInfrastructureCoreServices

Cloud Identity and Access Management (IAM).  Use Cloud IAM to implement access control. Grant and revoke IAM roles, first to a user, Username2.  Restrict access to specific features or resources.  Allocate Service Account User credentials and “bake” them into a virtual machine to create specific-purpose authorized bastion hosts.   



Cloud Storage.  Create and use buckets. Learn about the following features:  customer-supplied encryption key (CSEK), use your own encryption keys, rotate keys, access control list (ACL), set an ACL for private, and modify public. Lifecycle management, set policy to delete objects after 31 days, versioning, create a version and restore a previous version, directory synchronization, recursively synchronize a VM directory with a bucket, cross-project resource sharing using IAM, use IAM to enable access to resources across projects.   



Cloud SQL.  Create a Cloud SQL instance and a client VM instance to serve as a database client. Install software.  Restrict access to the Cloud SQL instance to a single IP address.  Download sample GCP billing data in CSV format and load that into the database.  Improve security by requiring SSL certificates--configure the Cloud SQL instance and the client to use SSL encryption.   



Cloud Datastore.  Initialize Cloud Datastore.  Create content (populate with data entities) in the Datastore database.  Query the content running both “Query by kind” and “Query by GQL” queries.  Access the Cloud Datastore Admin console.  Enabled the Cloud Datastore Admin console to clean up and remove test data.   



Examining Billing Data with BigQuery.  Sign in to BigQuery from the GCP console. Import billing data into BigQuery that had been generated as a CSV file. Create a dataset. Create a table.  Run a simple query on the file.  Access a shared dataset containing more than 22,000 records of billing information. Run queries on the data to explore how to use BigQuery to ask and answer questions.   



Resource Monitoring (Stackdriver).  Create a Stackdriver account. Enable Stackdriver Monitoring to monitor projects. Add charts to dashboards. Create alerts with multiple conditions. Create resource groups. Create uptime checks for services.   



Error Reporting and Debugging (Stackdriver).  Launch a Google App Engine application.  Introduce a code bug to break the application.  Explore Stackdriver Error Reporting to identify the issue, and then analyze the problem, finding the root cause using Stackdriver Debugger.  Modified the code to fix the problem. Monitor the change by examining the results through Stackdriver.
