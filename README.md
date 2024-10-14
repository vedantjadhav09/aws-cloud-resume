# Project Title

A brief overview of your project and what it does.

## Table of Contents

1. [Technologies Used](#technologies-used)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Deployment](#deployment)
6. [View Counter](#view-counter)
7. [Contributing](#contributing)
8. [License](#license)

## Technologies Used

- **HTML**
- **CSS**
- **JavaScript**
- **Visual Studio Code**
- **AWS**:
  - S3
  - CloudFront
  - Route 53
  - CloudWatch
  - ACM

## Features

- Personal resume website
- Responsive design
- View counter feature using AWS Lambda and DynamoDB

## Installation

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
Navigate to the project directory:
bash
Copy code
cd <project-directory>
Usage
Open the index.html file in your web browser to view the websites locally.
Ensure all files are linked correctly for styles and scripts.
Deployment
Create S3 Buckets for each website.

Enable static website hosting.
Upload Files to the S3 bucket.

Set Up CloudFront Distribution:

Create a CloudFront distribution.
Configure SSL settings using ACM.
Set up caching and invalidation for rapid content updates.
DNS Configuration:

Purchase a custom domain.
Use Route 53 to point to your CloudFront distribution.
View Counter
Implemented a view counter using AWS Lambda and DynamoDB.
The view count is incremented each time the page is loaded.
Contributing
If you would like to contribute, please fork the repository and submit a pull request.
