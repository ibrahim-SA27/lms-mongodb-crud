STEP-BY-STEP IMPLEMENTATION PROCESS

Step 1: Environment Setup
VS Code was used as the development environment
Node.js and MongoDB were installed and verified using command-line tools

Step 2: MongoDB Connection Using mongosh
MongoDB Shell (mongosh) was opened using Command Prompt
A new database named lmsDB was created and selected

Step 3: Collection Creation
A collection named courses was created automatically during data insertion

Step 4: Insert Data 
Course records were inserted into the courses collection using insertOne and insertMany commands

Step 5: Read Data
Course data was retrieved using find queries to view all courses courses by category and courses published after a specific year

Step 6: Update Data
Existing course records were updated using updateOne to modify available seats and course category details

Step 7: Delete Data
Course records were deleted using deleteOne based on conditions such as zero available seats

Step 8: Backend Integration
The backend was developed using Node.js and Express.js
MongoDB was connected using Mongoose and REST APIs were created to handle CRUD operations

Step 9: Frontend Integration
The frontend was developed using React.js.
The frontend interacted with backend APIs to perform CRUD operations and display course details

Step 10: Testing and Verification
CRUD operations were tested using MongoDB Shell MongoDB Compass Postman and browser output verification

6. TESTING
CRUD operations tested using MongoDB Shell 
Database verified using MongoDB Compass
Backend APIs tested using Postman
Frontend tested using browser

7. ERROR HANDLING
Course not found handling
Negative seat count prevention
Deletion restricted if available seats are not zero
Invalid update prevention.

