# Google Admin CSV Generator

## Overview
This is a simple web application that generates CSV files formatted for Google Admin bulk user imports. The application allows you to input first names, last names, passwords, email patterns, and domains to generate properly formatted CSV files for each domain.

## Features
- Generate multiple CSV files at once (one per domain)
- Customize email patterns
- Simple and intuitive interface
- No server-side processing - everything happens in your browser

## How to Use
1. Enter first names, last names, and passwords (one per line)
2. Enter email patterns (e.g., `name@`, `admin@`, `info@`)
3. Enter domains (e.g., `example.com`, `company.org`)
4. Click "Download All CSVs"
5. Each CSV will contain rows based on your patterns

## Deployment on Vercel

This application can be easily deployed on Vercel by following these steps:

1. **Create a Vercel Account**
   - Sign up at [vercel.com](https://vercel.com) if you don't have an account

2. **Install Vercel CLI** (Optional)
   ```
   npm install -g vercel
   ```

3. **Deploy via GitHub**
   - Push this code to a GitHub repository
   - Log in to your Vercel account
   - Click "New Project"
   - Import your GitHub repository
   - Click "Deploy"

4. **Deploy via Vercel CLI** (Alternative)
   - Open a terminal in the project directory
   - Run `vercel login` and follow the prompts
   - Run `vercel` to deploy
   - Follow the prompts to complete deployment

5. **Configuration**
   - The included `vercel.json` file contains the necessary configuration for deployment
   - No additional configuration is required for this simple static site

After deployment, Vercel will provide you with a URL where your application is hosted.