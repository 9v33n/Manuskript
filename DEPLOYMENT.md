# 🚀 How to Deploy Manuskript

## Option 1: Deploy to Vercel (Easiest - 5 minutes)

### Step 1: Create GitHub Repository
1. Go to [GitHub.com](https://github.com) and create a new repository
2. Name it `manuskript` or any name you prefer
3. Make it public (required for free Vercel deployment)

### Step 2: Upload Your Code
1. Download the `manuskript-working` folder
2. Upload all files to your GitHub repository
3. Commit and push the code

### Step 3: Deploy to Vercel
1. Go to [vercel.com](https://vercel.com)
2. Sign up with your GitHub account
3. Click "New Project"
4. Import your GitHub repository
5. Click "Deploy"
6. Wait 2-3 minutes for deployment
7. Get your live URL! 🎉

## Option 2: Deploy to Netlify (Alternative)

1. Go to [netlify.com](https://netlify.com)
2. Sign up and connect GitHub
3. Import your repository
4. Deploy automatically

## Option 3: Run Locally (If npm works)

1. Open terminal in `manuskript-working` folder
2. Run: `npm install`
3. Run: `npm run dev`
4. Open: http://localhost:3000

## What You'll Get

✅ **Live Website**: Your own knowledge sharing platform
✅ **Custom Domain**: You can add your own domain later
✅ **Automatic Updates**: Push to GitHub = automatic deployment
✅ **Free Hosting**: Vercel provides free hosting
✅ **HTTPS**: Secure by default
✅ **Global CDN**: Fast loading worldwide

## After Deployment

1. **Test Your Site**: Browse articles, try writing an article
2. **Customize**: Update colors, add your branding
3. **Add Supabase**: For real database functionality
4. **Share**: Tell people about your knowledge platform!

## Troubleshooting

**If deployment fails:**
- Check that all files are uploaded to GitHub
- Make sure `package.json` is in the root folder
- Check Vercel logs for specific errors

**If local development doesn't work:**
- Try running as administrator
- Check Node.js version (need 18+)
- Try deleting `node_modules` and running `npm install` again

## Next Steps

Once deployed, you can:
- Add Supabase for real database
- Customize the design
- Add more features
- Get users to start publishing articles!

Your knowledge sharing platform will be live and ready to use! 🚀
