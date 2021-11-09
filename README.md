# TailwindCSS Installation
## There are 3 different ways to install TailwindCSS.
1. Install from CDN
2. Install as PostCSS Plugin
3. Install Tailwind CLI ( Best Approach ).
## Prerequisite of installing Tailwind CSS
Your local mechine already should have installed node >= 12.3.0 version.\
To check node version on pc, terminal -> node -v
## Setup Procedure step by step
### Make a Directory
1.make a directory by any name ,such as "tailwindCSS".\
2.cd tailwindCSS\
3.Now follow the below procedures. 

### 1. "npm init -y" 
Apply this command on terminal, To initialize Node Project.
### 2. "npm i -D tailwindcss"
Apply this command on terminal, To install tailwindCSS as developer dependency.
### 3. "Tailwind CSS Intellisense" VS code Plugin by Brad Cornes
Install this vs code plugin from vs code extension.
### 4 . "npx tailwindcss init"
Apply this command on terminal, To make a configuration file for tailwind css. (tailwind.config.js)
### 5. output & src folder
create 2 folder, named "src" and "output" under the main directory "tailwindCSS".\
output-> tailwind compiler compailed the src tailwindCSS and provide compiled vanilla css in this output folder.\
src-> This is the source folder of tailwindCSS.

### 6. create "src/tailwind.css" file
create a "tailwind.css" file under "src" folder.

### 7. Edit "tailwind.css" file
Edit the tailwind.css file and write these 3 line,\
@tailwind base;\
@tailwind components;\
@tailwind utilities;

### 8. Create ".vscode/settings.json" file
To create this file you have to,
1. first go "vs code settings", (shortcut->  " ctrl+, "  )
2. Click "workspace"
3. click top right corner "file sign" -> (open settings JSON)

### 9. edit ".vscode/settings.json" file
{\
  "css.validate" : false,\
  "tailwindCSS.emmetCompletions": true,\
}

### 10. create a "build" script
edit "package.josn" file,\
{  ....\
  .....\
  ......\
  "scripts":{\
    "build": "tailwindcss -i ./src/tailwind.css -o ./output/tailwind.css -w"\
  },
  
  .....\
  ....\
}

### 11. create "index.html" file
create a "index.html" file under the main directory "tailwindCSS".

### 12. Add "link" tag in "index.html" 'head' tag.

head\
  .....\
  ....\
  link rel="stylesheet" href="./output/tailwind.css"\
  .....\
  ....\
  head
  
  
  ### 12. "pm run build"
  Give this command on terminal , To build tailwind.
  
  ## After this you are now ready to rock with tailwind CSS. This is your full installation Procedure and also your tailwind css boilerPlate.
  
  ## If you want direct boilerPlate of tailwind CSS, Then
  ### 1. Copy Below Link
  #### Link: https://github.com/Md-Rony-Khan/TailwindCSS.git
  ### 2. Git clone by this link on your local mechine
  #### git clone https://github.com/Md-Rony-Khan/TailwindCSS.git
  Give this command in your local mechine terminal.
  ### 3. Go into TailwindCSS directory
  #### cd TailwindCSS
  Give this command in your local mechine terminal.
  ### 4. Checkout to "boilerPlate" Branch
  #### git checkout boilerPlate
  Give this command in your local mechine terminal.
  ### 5. open this project on your vsCode by this Command
  #### code .
  Give this command in your local mechine terminal.
  ### 6. Install node modules
  #### npm i
  Give this command on your vs code terminal

## Now you can use this boilerPlate as your tailwind CSS project.
  
   
 
