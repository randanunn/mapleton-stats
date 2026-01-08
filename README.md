# Mapleton Stats

A simple webpage that embeds the Mapleton statistics Google Spreadsheet.

## Deployment to Netlify

### Option 1: Deploy via Netlify CLI

1. Install Netlify CLI:
   ```bash
   npm install -g netlify-cli
   ```

2. Login to Netlify:
   ```bash
   netlify login
   ```

3. Deploy the site:
   ```bash
   netlify deploy --prod
   ```

### Option 2: Deploy via Netlify Web UI

1. Go to [Netlify](https://app.netlify.com/)
2. Click "Add new site" > "Deploy manually"
3. Drag and drop this folder
4. Your site will be live at the generated URL

### Option 3: Deploy via Git

1. Push this repository to GitHub
2. Go to [Netlify](https://app.netlify.com/)
3. Click "Add new site" > "Import an existing project"
4. Connect to your GitHub repository
5. Netlify will automatically detect the configuration and deploy

The site will automatically serve `index.html` at the root URL.