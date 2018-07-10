# React Hoarder
> You are a hoarder. But not just any hoarder. You are an arrogant hoarder who wants to show off all of the stuff you hoard. You want an application that gives you a list of anything possible to hoard, and add them to your own personal collection as you acquire them. 

### Requirements
As a user, if I go to the application and I am not logged in, I should see a login or register page.
As a user, I should be able to login or register for the application with email and password.

As a user, when I first arrive at the application and I am logged in, I should see a "my stuff" page. This page should have a list of all of the items I have hoarded. These items will be in a UID-specific collection in Firebase.

As a user, I should be able to go to a page of "all the stuff". This page should load the data provided from the data list provided below. (In theory, this page represents all the stuff available in the world, whether or not I have it already or not). 
On the "all the stuff" page, each item should have a button that allows me to add the item to the "my stuff" page.

On the "my stuff" page, each item should have a button that allows me to delete it from "my stuff." 
On the "my stuff" page, I should be able to click on an item and see a full page version of it. This should bring the user to a new route. 

### Bonus
On the "my stuff" page, each item should have a button that allows me to edit it. This should bring up a form that auto populates with the item name, item description, and item image url, but allows me to edit any of them. 

On the "my stuff" page, each item should have a button that allows me to "increase the quantity" of any item I own. The quantity of each should be displayed.

### Data
[Use this JSON file to seed your "allStuff" collection in Firebase.](./allStuff.json)
