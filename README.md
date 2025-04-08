# Worldbuilding Chat Server

This is the backend server for the Worldbuilding Chat application.

## Environment Variables

Create a `.env` file in the server directory with the following variables:

```env
PORT=3002
ANTHROPIC_API_KEY=your_api_key_here
ALLOWED_ORIGIN=https://your-frontend-url.com
```

## Local Development

1. Install dependencies:
```bash
npm install
```

2. Start the server:
```bash
npm start
```

## Deployment

### Option 1: Deploy to Render

1. Create a new account on [Render](https://render.com)
2. Create a new Web Service
3. Connect your GitHub repository
4. Set the following:
   - Build Command: `npm install`
   - Start Command: `npm start`
5. Add your environment variables in the Render dashboard

### Option 2: Deploy to Railway

1. Create a new account on [Railway](https://railway.app)
2. Create a new project
3. Connect your GitHub repository
4. Add your environment variables in the Railway dashboard
5. Deploy! 