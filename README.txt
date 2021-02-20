1. 
I have stored all my personal keys in a file called keys.js and added it to .gitignore

so for running the project you need to create a file called keys.js in the root directory with the following format:

////////////////////////////////////////////////////////////////
var mongoDb = {
    username : "",
    password : ""
};

var admin = {
    email : "",
    password : ""
};
var adminBrowserPassword = '';
var secret = '';

module.exports = {
    mongoDb,
    admin,
    adminBrowserPassword,
    secret
}
////////////////////////////////////////////////////////////

2.
you would have to create a folder named uploads too in the roo directory.