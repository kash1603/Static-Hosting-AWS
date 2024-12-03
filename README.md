# Static-Hosting-AWS
#Tools Used:
AWS EC2: Host static website files.
Route 53: Manage domain and DNS.
CloudFront: Deliver content via CDN.
Steps:
Launch EC2 Instance:

Install and configure a web server (e.g., Apache).
Upload static files to /var/www/html/.
Configure Route 53:

Set up a hosted zone for your domain.
Update domain DNS to use Route 53's Name Servers.
Set Up CloudFront:

Create a distribution with your EC2 instance as the origin.
Update Route 53 to point to the CloudFront distribution.
Test the Setup:

Verify the website is accessible via your domain.
Tips:
Use SSL/TLS for security (AWS Certificate Manager).
Optimize costs by monitoring resources with CloudWatch.
