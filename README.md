# Assignment
step 1: I have imported necessary packages required for the task such as  cmd: npm install express body-parser mysql read-excel-file. 
step 2: make a localhost connection with database and made a table 'pets' and columns : id(primary and auto-incremented), name, type, breed, age.
step 3: ROUTES:
- A POST route "/" to read the excel file and store their data into database.
- A POST route “/api/pet” to add pets to the databse
- A GET route “/api/pet” to get all the pets in the database and route “/api/pet/<petId>” to get a specific pet (eg. /api/pet/id=1)
- A PATCH route “/api/pet/<petId>” to update the details of a specific pet (eg. /api/pet/id=1).
- A DELETE route “/api/pet/<petId>” to delete a specific pet (eg. /api/pet/id=1).
 
 step 4: start the server and hit the APIs in postman.
