# Tunker

## Description
Tunker is a simple Perl application that creates a local web server and generates a static homepage for demonstration purposes and learning.

## Features
- **Automatic Directory Creation:** The script automatically creates a \`TunkerApp\` directory if it does not already exist.
- **Local Web Server:** Uses HTTP::Server::Simple::CGI to start a local web server on port 5556.
- **Homepage Generation:** Creates a static HTML page (\`index.html\`) displaying a welcome message and demo information.
- **User Interaction:** Interactive command-line interface allows for directory generation, server startup, and application exit.

## Usage
1. **Installing Dependencies:** Ensure necessary modules are installed by running \`perl tunker.pl\`.
   
2. **Generating TunkerApp Directory:** Run the script and enter \`tunker generate\` to create the \`TunkerApp\` directory with necessary files.

3. **Starting the Web Server:** Once the directory is generated, use \`tunker bell\` to start the local web server.

4. **Accessing the Application:** Access the application via your browser at \`http://localhost:5556\`.

## Available Commands
- **exit:** Exit the application.
- **tunker generate:** Create the \`TunkerApp\` directory with necessary files.
- **tunker bell:** Start the local web server to access the application.

## File Structure
- **TunkerApp/**
  - **tunker.tuk:** Main Perl script for the web server.
  - **index.html:** Static homepage of the application.
  - **readme.md:** Description file.
