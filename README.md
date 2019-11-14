# express_mySQL
Connecting to mySQL using Express. 

Install mySQL: https://dev.mysql.com/downloads/installer/ 

COMMAND PROMPT

(1) Run the following to navigate to your Desktop: 

    cd Desktop

(2) Create a new folder on Desktop: 

    mkdir Express

(3) Navigate to the Express directory: 

    cd Express

(4) Run the following command to install the Express generator globally onto your computer: 

    npm install express-generator -g

(5) Enter the following command to generate the Express starter app. This will set the view to use Handlebars and will name the app express_mySQL: 

    express --view=hbs express_mySQL

(6) Once the process is complete, navigate into the express_mySQL directory: 

    cd express_mySQL 

(7) Now in the express_mySQL directory, run the following: 

    npm install

(8) Install Nodemon globally: 

    npm install -g nodemon
    
(9) Install Nodemon as a devDependency in the package.json file within the express_mySQL directory:

    npm install -save-dev nodemon
    
(10) Install mySQL:

    npm install --save mysql

(11) Start the server with Nodemon with the following command: 

    nodemon

(12) Open in VS code:

    code . 


VS CODE

(13) Navigate to the routes/index.js file and update. Need to require the mySQL: ![open index js file (express_mySQL)](https://user-images.githubusercontent.com/35668707/67824032-7361ea00-fa82-11e9-9598-86352a4e7743.JPG)

![add require mySQL index js file (express_mySQL)](https://user-images.githubusercontent.com/35668707/67824086-9b514d80-fa82-11e9-8c03-8a9d48fcbe5d.JPG)

(14) Add the connection information to connect to mySQL in routes/index.js file: ![add info to connect to mySQL index js file (express_mySQL)](https://user-images.githubusercontent.com/35668707/67824123-bc19a300-fa82-11e9-80bc-70af20f8a10f.JPG)

![connected to mySQL (express_mySQL)](https://user-images.githubusercontent.com/35668707/67824171-e5d2ca00-fa82-11e9-9a01-12d9384ff2ae.JPG)

NODEMON NOTE

Sometimes nodemon crashes in Windows 10 and there is a simple fix:

(1) Open Task manager (press Ctrl+Alt+Delete)

(2) Select the 'Processes tab'

(3) Search for 'Node.js: Server-side JavaScript'

(4) Select it and click on 'End task' button

Now you can run npm start.

