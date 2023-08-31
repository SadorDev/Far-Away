# Project Title
Far Away 

# Demo link

https://sadordev.github.io/Far-Away/

## Table of Content:

### About The App
A React app that allows travellers to add items they need for their next trip
The app will display the items that are added and packed and have a sort by option.
We will have a footer that displays the number of items on the list, the number of items 
that have been packed, and the percentage of items that have been packed. If there are no items 
in the list, the component will display a message asking the user to add some items.

### Screenshots

App
![App](far-away/screenshots/App.png)

Component layout
![Component layout](far-away/screenshots/Component-layout.png)

App Items
![App Items](far-away/screenshots/App-items.png)

Added App Items
![App Items](far-away/screenshots\App-items-(added).png)

### Technologies

- create-react-app (State, Event & Form Submission)

### Setup

`npx create-react-app travel-list
npm start`

### Approach

We first think about breaking down the app into 4 components
Logo, Form, PackingList & Stats

The Logo Component will render our Far Away Logo

The Form Component will handle our form submission using state

The Packing List Component will renders a list of items, which can be 
sorted by input order, description, or packed status. T

The Stats Component will render a footer that displays the number of items on the list, 
the number of items that have been packed, and the percentage of items that have been packed. 
If there are no items in the list, the component will display a message asking the user to add some items.

## Credits
This app was created with guidance from @JonasSchmedtmann.