# Chat-Box -- v1

A multi-thread chat box application using Polymer 2.0 and Firebase.

Authentication through Google.

View Live Demo here: https://mgchatbox.com/

v2 To-do's -
* Implement warning messages when user is offline telling them data cant be loaded offline
* Image Upload option
* Cloud Translation Implementation
* Time stamps on each message
* Load more messages option when user scrolls all the way up
* Add pop up window explaining how to use the PWA features (add to homescreen button)
* Lazy load and service worker optimizations
* (Maybe) - Ability to upvote people's messages

### To run application on local machine

Clone the Repo

    git clone https://github.com/michaelgee22/chat-box.git

Required Dependencies
* bower -g
* polymer cli -g

Install the Dependencies

    bower install
    polymer build

Application also requires firebase database implementation (src/ceg-auth-example.html) to run without errors locally.

Serve the application

    polymer serve
    polymer serve build/es5-bundled
    polymer serve build/es6-unbundled

(Served to localhost:8081)  
