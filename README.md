# Create this app using
npx create-react-app fiazbilal.github.io

# Run this app using 
npm start

# Run this for production build
npm run build

# Run for deployment
git checkout -b gh-pages
mv build/* ./
git add .
git commit -m "Deploy app to GitHub Pages"
git push origin gh-pages