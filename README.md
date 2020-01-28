Welcome to our Area.
=================

Getting Started
--------------

The goal of this project is to create a system of actions reactions on mobile and web.
We built an action-reaction system with webhooks.
You will have seven services at your disposition, for example Facebook, twitch.
Each service have some specific actions reactions link to it.
For example if you sent a message on your Facebook account your account twitter
will post a twit.
You will be able to link any actions available with any reactions.

Prerequisites
------------

To use our project you will need to complete some prerequisites:
   you will need an account for each service you have planned to use.

   Our application is usable on smartphone or on your computer.

   If you want use the computer version you will need to install node to do that
   you can use the site of node https://nodejs.org/en/ and download all the packages or you can use
   a package manager.

   Example with package manager:
   
        "sudo apt update && sudo apt install yarn"
        
   The download of yarn will also add node.js at your computer.


   If you want use the mobile version you will need a smartphone on android or
   you can download android studio if you want test the mobile version on your
   computer. You will also need to have node and Android SDK.

Launch the program:
    on mobile: "react-native run-android"
    on computer: "npm start"




Developer part


Registration:
    The registration is handle for the web part in DEV_area_2019/web/src/components/auth/SignUp.js

    state = {
        email: "",
        password: "",
        firstName: "",
        lastName: ""
    };

Login:
    The registration is handle for the web part in DEV_area_2019/web/src/components/auth/SignIn.js

    state = {
        email: "",
        password: ""
    };



Running the tests:
    Our project have a series of automated tests, if you want to use them you will
    need to do:
                
                "yarn test"



########################################################################################################

Authors:

Arthur Perno
Itagiba Alix
Alexandre loiseau
Félix Barthes
Charles Raimbault
Raphael Maisonnave
