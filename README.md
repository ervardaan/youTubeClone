# youTubeClone

# steps of creation
- make a new folder and run cmd on it
- `node -v` is 21.7.1
- `npm -v` is 10.5.0
- - running the file(not needed when nitializing the app)- use `node <filename-with-extension>`
- initialize node npm in this folder usin `npm init` command and put in required details
- to create this app, use the exact same command: `npm i -g create-react-app` and then maybe use if asked and prompted: `npm fund`
- NOTE:ALL OF THE ABOVE COMMANDS SHOULD BE RUN ON THE CREATED FOLDER/DIRECTORY WHERE WE INITIALIZE NODE,NPM etc
- now make a new subdurectory in this main directory with name in ALL LOWERCASE LETTERS(this is the nam of the application)
    - go inside this directory and run `create-react-app ./` to make the react app with this name and directory
    - again do `npm fund`
    - now do `npm audit fix --force
  - now install dependencies(in one folder above-not in this app subdirectory)
        - install axios for making api calls using `npm i --save axios`
        - install material ui's core: `npm i --save material-ui`
        - actually we can install material ui using `npm install @material-ui/core`
    - NOTE:run this command in this subdirectory before using the app for the first time in COMMAND PROMPT(by `npm start`) : `set NODE_OPTIONS=--openssl-legacy-provider`

## getting started when we have to again only run the app
- `npm update`
- `npm install`
- `npm update`
- `npm fund`
- `npm audit fix --force`

 # SAMPLE MESSAGE AFTER ALL OF THE REACT APP IS SET UP
 ![image](https://github.com/ervardaan/youTubeClone/assets/86986617/f96b677b-83ac-4a81-bfd3-0e875ec5fd65)

 ## USING API ROM YOU TUBE
 - create a project using a google account in google developers console
 - authenticate it and enable to use you tube v3 api out of 3 available you tube apis


