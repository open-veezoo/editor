# Technical Assessment: Online Editor

## Scope

Implement an Online Editor using ReactJS that supports the following functionalities:

- View files in a directory-like tree view in a sidebar
- Click on a file in the sidebar to open it in the editor
- Save button to save modified file content
- Delete button to delete open file

## API Definition

GET /filetree 

GET /files/{fileId}

PUT /files/{fileId}

DELETE /files/{fileId}

## Mock Server

Access the API over https://my-json-server.typicode.com/open-veezoo/editor.

Example: https://my-json-server.typicode.com/open-veezoo/editor/filetree
