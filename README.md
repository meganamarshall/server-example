# server-example
server example
npm init - package json created
add gitignore
add eslintrc (from class curriculum day 5)
add .env
npm i express dotenv
npm i -D eslint
if you uninstall your packages, you can run npm i
commit

add server.js (copy contents from marty)
add public folder, inside is index.html

run node server.js
go to localhost 3000 in browser and you should be able to see whatever you typed in your index.html

to quit the server, type control C in the terminal
add this to the package.json under scripts:
"start": "node server.js"

rm -rf public in terminal to remove public folder
cp -R ../component-pokedex public in terminal - this will copy pokedex into your new server app
now you have your pokedex and should see it on localhost

add this to your package.json under scripts:
"update": "rm -rf public && cp -R ../component-pokedex public && rm -rf public/.git"
this will allow you to recopy the current contents of your pokedex into your public folder (when you make changes to pokedex)

commit

