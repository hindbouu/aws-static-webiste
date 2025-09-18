# AWS Static Website Project

This project is a simple static website built with HTML and hosted on **Amazon S3**.  
It was part of a cloud computing coursework assignment to demonstrate how AWS can be used to host and serve web applications without the need for a traditional web server.

## Features
- **Static Hosting with AWS S3**: The website files (HTML + images) are uploaded to an S3 bucket configured for public access.
- **Multiple Pages**: `index.htm` serves as the homepage and links to subpages (`cs79a.htm`, `cs79b.htm`, `cs79c.htm`, `cs79d.htm`).
- **Media Support**: Includes images (`college.jpg`, `banner.jpg`) to make the site visually engaging.
- **Scalability & Reliability**: By hosting on AWS S3, the website benefits from AWS’s infrastructure for high availability.

## AWS Work Explanation
- **Bucket Setup**: An S3 bucket was created and configured for static website hosting.  
- **File Upload**: HTML files and image assets were uploaded into the bucket.  
- **Permissions**: Public access settings were enabled so anyone with the URL can view the site.  
- **Hosting**: AWS automatically serves the files over the web, making the site live without needing a server or backend.
