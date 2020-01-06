# React Hoarder Part 2: CRUD on Items

## User Stories

### CREATE
* As a user, when I click New in the navbar I should be taken to the '/stuff/new' page where I should see a form for adding new items.
* As a user, when I add in details and hit save on the '/stuff/new' page my item should save to firebase and I should be redirected to '/stuff'.

### READ
* As a user, when I navigate to the /stuff route, I should see a "My Stuff" page. This page should have a list of all of the items I have hoarded.
* As a user, when I click on an item on the My Item page, I should be taken to the Single Item page and see details for that item

### UPDATE
* As a user, when I click a update button on the My Stuff page, I should be redirected to the edit page and should see a form pre-populated with all the information for the item I am editing.  Once I make edits and push the save button, Firebase should edit and I should be redirected to the '/stuff' page.
* As a user, when I click a update button on the Single Item page, I should be redirected to the edit page and should see a form pre-populated with all the information for the item I am editing.  Once I make edits and push the save button, Firebase should edit and I should be redirected to the '/stuff' page.

### DELETE
* As a user, when I click a delete button on the My Stuff page, the item should be removed from firebase and I should no longer see it.
* As a user, when I click a delete button on the Single Item page, the item should be removed from firebase and I should no longer see it, and I should be redirected to the My Stuff page.
