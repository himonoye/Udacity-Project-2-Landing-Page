# Landing Page Project

This is a landing page that uses HTML, CSS, and javascript. The landing page contains a sticky navigation bar that hightlights the anchor link of a section that is currently in the user view. 

## Javascript Function Breakdown 

All the javascript functions are contained in the app.js file. The followings are the javascript function included in this file.


### buildNavigation()

This function will automatically run on page load. It doesn't take in any parameters. Instead, it builds out the navigation as soon as the DOM is ready. 


### srollToActive(e)

This function takes in an event object and listens on "click" action performed on the navigation links. When a link is clicked, the page scrolls to the section that is associated with the link. 


### setToActive()

This function doesn't take any parameters. It listens on "scroll" action performed by the users. When a user scroll, it checks if a existing section has entered the user's window view. If so, the associated link will be set to active and hightlighted in the UI. 