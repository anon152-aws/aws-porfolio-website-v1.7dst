AWS Developer Portfolio Website

This project is a professional portfolio designed to highlight AWS cloud development skills and experience. It is built using React, Vite, and TailwindCSS, and showcases AWS projects, certifications, and professional background in a clear and modern layout.

Features

Highlights AWS skills including serverless, containers, networking, and IaC

Displays real project work with details and technologies used

Includes certifications and professional experience

Contact form section for inquiries

Fully responsive layout for mobile and desktop

Dark and light theme toggle

What I Learned

This project helped strengthen the following skills:

Building modern UI applications using React and Vite

TailwindCSS component styling and layout design

Optimizing app structure and performance for production

Debugging environment issues on Windows including npm execution policies

Preparing a frontend project for deployment on AWS hosting services

Tech Stack

React (Frontend)

Vite (Build Tool)

TailwindCSS (Styling)

Framer Motion (Animations)

lucide-react (UI icons)

npm (Package Management)

AWS experience showcased in this portfolio includes:
API Gateway, Lambda, DynamoDB, ECS/Fargate, EKS, S3, Route 53, CloudFront, IAM, CDK/Terraform.

Getting Started

Install dependencies:

npm install


Run development server:

npm run dev


Then open the local URL printed in the terminal (usually http://localhost:5173
)

Troubleshooting

If npm commands fail due to execution policy restrictions on Windows PowerShell:

Set-ExecutionPolicy RemoteSigned -Scope CurrentUser


Press Y, restart VS Code, and try again:

npm -v


If npm reports that package.json is missing, ensure you are in the correct folder:

cd path\to\aws-portfolio
npm run dev

Deployment

Can be deployed using:

AWS S3 + CloudFront (recommended)

GitHub Pages

Netlify or Vercel

A deployment script using AWS CDK can be added later.

License

Free to use and customize for personal or educational purposes.
