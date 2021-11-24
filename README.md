### Nick Covington

# Milestone 2 Bootstrap Xtra Credit

## Welcome & Logout
I used `class="d-flex justify-content-between sticky-top"` to make the welcome message and the user logout button scroll down the page so the it's always visible to the user. Also the `justify-content-between` quickly and easily placed the items to the left and right edges of the page without me needing to set up a flex box. Also the buttons on the page were given `class="btn btn-dark"` to add in Bootstrap's fancy looking button effects.

## Artist Submission
I used `class="d-flex flex-column"` to make a quick flexbox div that would position the form inputs vertically. And then added `justify-content-center` to keep everything pushed in the middle of the div. Also because it's flexbox, it should have some responsiveness when the user shrinks or grows the window.

## Sticky Artist List
I figured it would be convenient to the user if they could always see their list of currently favorited artists. So I gave it the `class="fixed-bottom"` to make it scroll up and down with the user, similar to the logout button above. Also I used the Bootstrap List Group features to make a neat looking block of list items.

## Artist Card
I gave the main showcase `class="card column"` to add nice looking puffed out div to display all the currently favorited artist's details. Then for the positioning I used `class="col-md-8 mx-auto"` to establish the main flex div, and then all the items within received the `class="d-flex justify-content-center"` to center them accordingly.

