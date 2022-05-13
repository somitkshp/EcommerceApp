#Setup

##Angular CLI

npm install -g @angular/cli

ng version

ng help

##Create new project with Angular CLI

ng new <project name>

ng serve (builds the app (compile/transpile), starts the server, watches the source files, rebuilds the apps when source is updated.. By default listens on port 4200)

ng serve --open (same as above but opens up web browser with port 4200)

ng serve --port 5100

ng serve --port 5100 --open

##Troubleshooting
Error : .....cannot be loaded because running scripts is disabled on this system
	Set-ExecutionPolicy RemoteSigned

# EcommerceApp