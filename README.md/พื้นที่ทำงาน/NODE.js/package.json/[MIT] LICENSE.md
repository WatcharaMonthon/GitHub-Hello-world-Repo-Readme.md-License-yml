{ "_" } , 
{[]} , "string" , 
"work area assignment", 
"Workspaces are usually defined through the workspaces property.  package.json file" 

{
  "name": "my-workspaces-powered-project",
  "workspaces": [
    "packages/a"
  ]
} 

# "run":  
{ "node lib/index.js" }, 

# "Let's create a Node.js script that will require a  Workspace", example modules such as
"npm install abbrev -w a" 

{ 
// ./packages/a/index.js
module.exports = 'a' } 

{ 
// ./lib/index.js
const moduleA = require('a')
console.log(moduleA) // -> a } 

# "by running the command using the workspace option  It is possible to run commands given in the context of that specific workspace", for example:
# "npm run test --workspace=a " 
"cd packages/a && npm run test" 
# Here's a short example.  About how to use npm  run commands in the context of nested workspaces  For projects with multiple workspaces, for example:
+-- package.json
`-- packages 

{:   +-- a
   |   `-- package.json
   `-- b
       `-- package.json } 
