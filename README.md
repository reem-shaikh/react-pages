#### Testing the Deployment of the react app
https://reem-shaikh.github.io/react-pages/

-----
# Getting Started with React App Deployment 

### 1. Git bash in the drive you want to create the folder in the local and type these commands after creating a repo on Git
```bash 
 git clone https://github.com/reem-shaikh/react-pages.git
```
```bash 
cd react-pages/
```
```bash 
 npx create-react-app .
```
#### Install gh-pages package 
```bash 
npm install gh-pages --save-dev
```
### 2. Add homepage to package.json 
> Add this commands in package.json after "name"
```bash 
"homepage": "https://reem-shaikh.github.io/react-apps/react-pages",
```
### 3. deploy to scripts in package.json 
> Add this command in scripts 
```bash 
"predeploy": "npm run build",
"deploy": "gh-pages -d build",
```
### 4. To get the production code, run these commands in terminal of vscode, targetting the same react folder directory 
> run this in terminal 
```bash 
cd react-pages 

npm run deploy 
```
### 5. For a project page, ensure your project's settings use gh-pages branch 
> hover to settings -> hover over to github pages -> and use the gh-pages branch to host your website, then, copy paste the link for reference


