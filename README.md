# Bindu's Portfolio

Welcome to my portfolio project! This page showcases my professional profile, including my name, profile photo, LinkedIn link, and a QR code to my resume. The portfolio is designed to be responsive, ensuring a consistent experience on both mobile and desktop devices.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This portfolio page is a simple and clean representation of my professional information. It includes:
- A header image
- My name and profile picture
- A link to my LinkedIn profile
- A QR code that directs to my resume

## Features

- **Responsive Design**: Ensures the portfolio looks great on both mobile and desktop devices.
- **Clean Layout**: A straightforward and professional layout that highlights key information.
- **Easy Navigation**: Direct links to important resources like LinkedIn and my resume.

## Technologies Used

- **HTML5**: Markup language for structuring the page.
- **CSS3**: Styling the page for a clean and professional look.
- **AWS S3**: Hosting the portfolio page and assets.

## Setup Instructions

Follow these steps to set up and deploy the portfolio page:

### Prerequisites

- [Git](https://git-scm.com/)
- [GitHub account](https://github.com/)
- [AWS account](https://aws.amazon.com/)
- [AWS CLI](https://aws.amazon.com/cli/)

### Step 1: Clone the Repository

1. Go to your GitHub account and create a new repository named `portfolio`.
2. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/your-username/portfolio.git
    cd portfolio
    ```

### Step 2: Add Project Files

1. Place the following files in the repository directory:
    - `index.html`
    - `id-card.jpg`
    - `profilepic.jpeg`
    - `your-qr-code.png`
    - `resume.pdf`
2. Commit and push the changes to GitHub:
    ```bash
    git add index.html id-card.jpg profilepic.jpeg your-qr-code.png resume.pdf
    git commit -m "Initial commit with portfolio files"
    git push origin main
    ```

### Step 3: Deploy to AWS S3

1. Log in to the AWS Management Console.
2. Navigate to S3 and create a new bucket (e.g., `portfolio-website`).
3. Go to the **Properties** tab, enable **Static website hosting**, set the index document to `index.html`, and save changes.
4. Upload `index.html`, `id-card.jpg`, `profilepic.jpeg`, `your-qr-code.png`, and `resume.pdf` to the S3 bucket.
5. Ensure all files have public read permissions.

### Step 4: Verify Your Website

1. Go to the **Properties** tab of your S3 bucket and find the **Bucket website endpoint** URL.
2. Open the URL in a web browser on both a desktop and a mobile device to ensure your portfolio displays correctly.

## Deployment

Your portfolio is now live and can be accessed via the S3 bucket's website endpoint. Share this link on your resume or with colleagues to showcase your work.

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request with your proposed changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

