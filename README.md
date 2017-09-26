# backend-building-blocks
A collection of commonly used backend controllers and models for use with express and foundation.


# How to use
For now, I suppose this will be copy and paste for the most part... My long term goal would be to have run via a CLI.

## Goal / CLI example
Install globally
``` npm i -g backend-building-blocks
```
Install individual "blocks"
``` backend-building-blocks install authentication
```
This command for example would read your package.json file and check your dependancies. Then it would compare that with with package.json file in the "block" and install any dependancies. For example it would look at controller/authentication/package.json and then if you don't have passport and connect-flash installed, then it will be installed for you.
