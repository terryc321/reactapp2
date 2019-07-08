# reactapp2

created a new repository on github

cloned the github repository to local drive
git clone https://github.com/terryc321/reactapp2.git

cd reactapp2

npm install react react-dom typescript @types/react @types/react-dom --save

git add README.md

# add other files as needed

# when wish to push changes to remote repository

git push origin

# ask for username and password for github

# see changes made to the project

git log

# see if any files created that need to be added

git status

# you'll need to configure a new TypeScript tsconfig.json
##
{
  "compilerOptions": {
    // No module system, concatenated file
    "module": "none",

    // Set React as the JSX factory
    "jsx": "react",

    // Resolve modules using Node-resolution algorithm
    "moduleResolution": "node",

    // Target ES6 for more modern browsers
    "target": "es6",

    // Include typings from built-in lib declarations
    "lib": ["es2015", "dom", "dom.iterable"],

    // Include module source maps for debugging
    "sourceMap": true,

    // Output to single concatenated file
    "outFile": "dist/bundle.js"
  },
  "include": ["src"]
}
##

https://www.pluralsight.com/guides/typescript-react-getting-started


#
npm run build


