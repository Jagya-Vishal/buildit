# Shree Ganpati Handprint - B2B Textile Manufacturing Platform

## Netlify Deployment Steps

1. **Create a Netlify Account**
   - Go to [Netlify](https://www.netlify.com)
   - Sign up for a new account or log in

2. **Connect Your Repository**
   - Click "New site from Git"
   - Choose your Git provider (GitHub, GitLab, or Bitbucket)
   - Select your repository

3. **Configure Build Settings**
   The `netlify.toml` file is already configured with:
   - Build command: `npm run build`
   - Publish directory: `dist/public`
   - Node.js version: 20

4. **Environment Variables**
   Add the following environment variables in Netlify's settings:
   - DATABASE_URL (copy from your development environment)
   - Any other sensitive data used in the application

5. **Deploy**
   - Click "Deploy site"
   - Wait for the build process to complete

6. **Domain Setup (Optional)**
   - Go to "Domain settings"
   - Add your custom domain if needed
   - Enable HTTPS

## Local Development
```bash
npm install
npm run dev
```
