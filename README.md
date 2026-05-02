# Backend Class 
This is the code for the backend class. It is a simple express server that serves files from the "files" directory. The files are rendered using ejs templates. The server listens on port 3000.

## Installation
1. Clone the repository
2. Navigate to the project directory
3. Run `npm install` to install the dependencies
4. Run `npx nodemon index.js` to start the server
5. Open your browser and navigate to `http://localhost:3000` to see the home page
## File Structure
- index.js: The main server file
- views: The directory containing the ejs templates
- files: The directory containing the files to be served
## Routes
- GET /: The home page that lists all the files in the "files" directory
- GET /file/:filename: The page that shows the contents of the file with the given filename
## Example
1. Create a file named "example.txt" in the "files" directory with some content.
2. Start the server and navigate to `http://localhost:3000` to see the list of files.
3. Click on the "example.txt" link to see the contents of the file rendered on the page.
