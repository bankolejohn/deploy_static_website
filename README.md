# Stage 0  Task - DevOps Track


## Task: Static Website Deployment


In this stage, you'll step into the shoes of a DevOps engineer and deploy a static website onto a cloud platform.
Cloud Platform: Choose a cloud platform of your preference (AWS EC2, Azure, etc) to deploy your website.
Web Server: Select a web server software like NGINX or Apache to serve your static website content.
Website Preparation: Ensure your static website files (HTML, CSS, Javascript) are ready for deployment.
Server Configuration: Configure the chosen web server (NGINX or Apache) on your cloud instance to serve your website content.
:scroll:Requirements:
Cloud Platform: AWS EC2 or Azure or GCP (your choice)
Web Server: NGINX or Apache
Static Website: A ready-to-deploy static website project (HTML, CSS, Javascript) which includes your Name, username and your email.


### Acceptance Criteria:
Successful Deployment: Your static website is accessible through a public IP address or a domain name after deployment. The IP address shouldn’t include ports asides port 80.
Web Server Configuration: The chosen web server (NGINX or Apache) is configured correctly to serve your website content.

### Submission Mode:
Submit your task through the designated submission form. Ensure you've:
Double-checked all requirements and acceptance criteria.
Provided a link to your deployed website in the submission form.
Thoroughly reviewed your work to ensure accuracy, functionality, and adherence to the specified guidelines before you submit it.
The website should mention HNG Internship and contain a link to https://hng.tech


## IMPROVEMENTS
So i have made some improvements to the task. 

### Automated Website Deployment with CI/CD Pipeline

This GitHub Actions workflow implements a robust Continuous Integration and Continuous Delivery (CI/CD) pipeline for your static website.

Key Features:

Automated Updates: Upon any push to the main branch, the workflow automatically triggers, streamlining the deployment process.
Streamlined Workflow: Manual updates to the S3 bucket are no longer necessary. Changes to your website's source code seamlessly synchronize with the S3 bucket, ensuring your website reflects the latest version.
Improved Efficiency: This automation saves time and effort, allowing you to focus on website development and maintenance tasks.

Benefits:

Reduced Errors: Manual updates are prone to human error. Automating deployment minimizes the risk of errors and inconsistencies.
Increased Reliability: Consistent and automated deployment ensures a reliable and up-to-date website experience for your users.
Faster Deployment: Updates are deployed swiftly, minimizing downtime and maintaining a smooth user experience.

This CI/CD pipeline empowers you to efficiently manage your website deployments and deliver the latest version to your users promptly.