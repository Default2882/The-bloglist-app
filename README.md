# The bloglist app

## Prerequisite: 

These are the requirement that should be installed locally on your machine.

- Node.js
- React


## How to setup node.js on your machine?

- Move to: [link](https://nodejs.org/en/download/) choose the operating system as per your machine and start downloading and setup by clicking recommended settings in the installation wizard.

## How to set up this project locally?

- Move to: https://github.com/Default2882/The-bloglist-app
- Fork the repo 
- Clone the repo using: 
```sh
    git clone https://github.com/Default2882/The-bloglist-app
```
- Now move to the project directory on your machine.
```
    cd The-bloglist-app
```
- Now move to the front-end directory on your machine.
```
    cd bloglist-frontend/
```

- Install all the dependencies using:
```sh
    npm install 
```
- Run the development server using:
```sh
    npm start 
```
- Now move to the back-end directory on your machine.
```
    cd ../bloglist-backend/
```

- Install all the dependencies using:
```sh
    npm install 
```
- Run the development server using:
```sh
    npm start
```

- Now the front-end is running on PORT 3000 and the back-end is running on the PORT 3001, you can also change the ports by mentioning it in environment **.env** variables


## Run unit test for the back-end
Use the given below command to run all the unit test cases.
```
npm run test
```
## Run unit test for the back-end
Use the given below command to run all the unit test cases.
```
npm run cypress open
```

## Allowed HTTPs requests for the back-end api:
<pre>
POST    : To create resource 
GET     : Get a resource or list of resources
DELETE  : To delete resource
</pre>

## Description Of API Server Responses:
<table>	
    <tr>
        <th>Code</th>	
        <th>Name</th>
        <th>Details</th>
    </tr>
    <tr>
        <td><code>200</code></td>
        <td><code>OK</code></td>
        <td>the request was successful.</td>
    </tr>
    <tr>
        <td><code>201</code></td>
        <td><code>Created</code></td>
        <td>the request was successful and a resource was created.</td>
    </tr>
    <tr>
        <td><code>400</code></td>
        <td><code>Bad Request</code></td>
        <td>the request could not be understood or was missing required parameters.</td>
    </tr>
    <tr>
        <td><code>401</code></td>
        <td><code>Unauthorized</code></td>
        <td>authentication failed or user doesn't have permissions for requested operation.</td>
    </tr>
    <tr>
        <td><code>403</code></td>
        <td><code>Forbidden</code></td>
        <td>access denied.</td>
    </tr>
</table>
<br></br>
