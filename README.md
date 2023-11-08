# Task

You will be given a fresh server and jenkin - the interviewer will pass the credentials to log in.

1. **Login to the Server**
   - use cmd/terminal | ssh request to the server 

2. **Install Docker and Run a MongoDB Container**
   - Install Docker on the server | recommended to refer official docker doumentation.
   - Run a MongoDB container. This is your database for the application.

3. **Run the Node.js Sample Application**
   - Prepare the server environment to run Node.js Application.
   - Clone the project.
   - Inspect the branches using Git and Checkout to the correct branch.
   - Install the dependencies | recommended to go throught the documentation.
   - Serve the project | serving using pm2 will be recommended. | refer to the pm2 official docs

4. **Install Nginx and map a sample domian**
   - Using sample Nginx conf file Map the given domain.

5. **Ceate a sample pipline for CI/CD**
   - create the required credentis for acess jenkins and your teset server |root ssh private key is recommended.
   - add your server a new node
   - crete a  groovy script for above file
   - create a running pipe line to show case the ci/cd
