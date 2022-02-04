#### Testing the Deployment of the react app
https://reem-shaikh.github.io/react-pages/

-----
# Getting Started with React App Deployment 

1. Create an empty folder (eg: named react-apps), git bash and type these commands 
```bash 
 git clone https://github.com/reem-shaikh/react-pages.git
```
```bash 
cd react-pages/
```
```bash 
 npx create-react-app .
```
```bash 
npm install gh-pages --save-dev
```
2. Add this commands in package.json after "name"
```bash 
"homepage": "https://reem-shaikh.github.io/react-apps/react-pages",
```
3. Add this command in scripts 
```bash 
"predeploy": "npm run build",
"deploy": "gh-pages -d build",
```
4. run this in terminal 
```bash 
cd react-pages 

npm run deploy 
```
5. hover to settings and copy the github pages link 
