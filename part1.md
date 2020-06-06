# React Hoarder Part 1: Authentication and Routing

## User Stories - Authentication
As a user, if I go to the application and I am not logged in, I should see a google authentication button.

As a user, I should be able to authenticate via google.

As a user, I should always see a navbar.

As a user, when I am logged out, the navbar should only display the brand name.

As a user, when I am logged in, the navbar should display links to home, My Stuff, New, and logout.

As a user, when I click the logout button in the navbar I should be logged out and should see the google authentication button.


## User Stories - Routing
As a user if I click the home link in the navbar, I should navigate to '/home'  and see an h1 tag that says 'Home'.

As a user if I click the New link in the navbar, I should navigate to '/new'  and see an h1 tag that says 'New Stuff'.

As a user if I click the My Stuff link in the navbar, I should navigate to '/stuff'  and see an h1 tag that says 'My Stuff' and two buttons - on that says Edit and one that says Single.

As a user when I click the Edit button on the My Stuff page I should be redirect to '/edit/12345' and I should see an h1 tag that says 'Edit';

As a user when I click the Single button on the My Stuff page I should be redirect to '/stuff/12345' and I should see an h1 tag that says 'Single Stuff';
