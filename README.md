# node-mongo-docker

## Project Overview
This project is a Node.js web application that utilizes Express.js as a framework and MongoDB as a database. It's designed to run in a Docker container for portability and isolation.

## Prerequisites
  <li>Docker installed on your system</li>
  
## Installation
### 1. Clone the repository:
git clone https://github.com/Anushka-codergirl/node-mongo-docker.git

### 2. Navigate to the project directory:
cd node-mongo-docker

### 3. Install dependencies:
npm install

### 4. Running the Application
<li> Build the Docker image:</li>
    docker build -t <your-image-name> .
<li> Run the Docker container:</li>
    docker run -p 5000:5000 --name <container-name> <your-image-name>
    
The application will be accessible at http://localhost:5000.

## Project Structure
- Dockerfile: Defines the Docker image build instructions.
- docker-compose.yml: Configures multiple services for the project.
- app.js: Defines the Express application and exports it.
- index.js: Handles database connection, server startup, and error handling.
- package.json: Contains project metadata and dependencies.
- package-lock.json: Records the exact versions of dependencies used.
- node_modules: Stores installed project dependencies.

## Usage
<b> <li> Customize the application:</b> Modify the app.js file to add routes, controllers, and models for your specific use cases.
<b><li>Interact with MongoDB:</b> Use the mongoose module in index.js to interact with the MongoDB database.
<b><li>Extend functionality:</b> Add more features, such as user authentication, data validation, and error handling.

## Contributing
Contributions are welcome! Please follow these guidelines:

1. Fork the repository.   
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.   
4. Push your changes to your branch.
5. Submit a pull request to the main repository.

## License
This project is licensed under the Apache License.   
