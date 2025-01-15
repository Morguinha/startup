# eCook

[My Notes](notes.md)

This is an application that not only stores the user's recipes, but also will recommend new recipes, can add new recipes, and also has a function where you can input ingredients and the application will recommend a recipe based upon the ingredients listed.


> [!NOTE]
>  This is a template for your startup application. You must modify this `README.md` file for each phase of your development. You only need to fill in the section for each deliverable when that deliverable is submitted in Canvas. Without completing the section for a deliverable, the TA will not know what to look for when grading your submission. Feel free to add additional information to each deliverable description, but make sure you at least have the list of rubric items and a description of what you did for each item.

> [!NOTE]
>  If you are not familiar with Markdown then you should review the [documentation](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) before continuing.

## 🚀 Specification Deliverable

> [!NOTE]
>  Fill in this sections as the submission artifact for this deliverable. You can refer to this [example](https://github.com/webprogramming260/startup-example/blob/main/README.md) for inspiration.

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [x] Proper use of Markdown
- [x] A concise and compelling elevator pitch
- [x] Description of key features
- [ ] Description of how you will use each technology
- [x] One or more rough sketches of your application. Images must be embedded in this file using Markdown image references.

### Elevator pitch

If you were to open your fridge right now, you would see a concophony of lost ingredients. You make a recipe, and when the recipe asks for half of an onion, the other half sits sadly in your fridge. We present the solution. Not only a hub to store your home recipes, but a way to discover new recipes, and most important of all, a place to ask what you can do with all of your leftover scrap that will turn into another delicious meal. eCook is your one stop shop for everything cooking, because the only thing better than cooking is eating!

### Design

![Home](https://github.com/user-attachments/assets/eafdefc1-d0c9-487a-a22d-6ff45c8faf60)
![Recommended](https://github.com/user-attachments/assets/7872ab8a-070e-470c-b279-0770ad333836)
![Fridge](https://github.com/user-attachments/assets/38ef6fa9-f2a1-4689-bbbc-f3d858479090)
![My Recipes](https://github.com/user-attachments/assets/378ac501-7f24-4c84-b0eb-223ed87864b1)
![Recipe](https://github.com/user-attachments/assets/3e082569-23fa-4ec0-a7da-9f6c0e8f11c0)

There is a home page with all features laid out across the page directing users towards different functions, a recommended page that recommmends certain types of recipes to the user, a fridge page that based off of the input ingredients will suggest either saved recipes or recommended recipes to the user, and finally, when a recipe is selected it will appear in a pop up window to the user, with options to save or exit.

![SequenceDiagram](https://github.com/user-attachments/assets/81717321-6f1a-4e5c-96c1-ba682de36d1f)


### Key features

- Home page, featuring a search bar at the top for searching recipes, a main hub to look at recommended recipes, sign in, and button directing to fridge page.
- Fridge function that will take ingredients input and analyze recipes for said ingredients and provide matches to the user.
- Ability to input recipes and add recipes from recommended.

### Technologies

I am going to use the required technologies in the following ways.

- **HTML** - Four pages, with a pop up for login, and another for a recipe.
- **CSS** - Good blend of colors across the website that are engaging but not overpowering, side scrolling menus animated, home page animation.
- **React** - Login provides user with saved recipes, recommendions change based on saved recipes
- **Service** - Backend service with endpoints for retriving recipes, submitting ingredients and retriving recipes. Third party call to spoonacular API and/or TheMealDB
- **DB/Login** - Store users recipes, recommendations in database. Can access recipes, but cannot save recipes without login. Credentials stored in database securely.
- **WebSocket** - Suggestions for recipes from other users, and a specific part of the home page displaying what other users are cooking.

## 🚀 AWS deliverable

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [ ] **Server deployed and accessible with custom domain name** - [My server link](https://yourdomainnamehere.click).

## 🚀 HTML deliverable

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [ ] **HTML pages** - I did not complete this part of the deliverable.
- [ ] **Proper HTML element usage** - I did not complete this part of the deliverable.
- [ ] **Links** - I did not complete this part of the deliverable.
- [ ] **Text** - I did not complete this part of the deliverable.
- [ ] **3rd party API placeholder** - I did not complete this part of the deliverable.
- [ ] **Images** - I did not complete this part of the deliverable.
- [ ] **Login placeholder** - I did not complete this part of the deliverable.
- [ ] **DB data placeholder** - I did not complete this part of the deliverable.
- [ ] **WebSocket placeholder** - I did not complete this part of the deliverable.

## 🚀 CSS deliverable

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [ ] **Header, footer, and main content body** - I did not complete this part of the deliverable.
- [ ] **Navigation elements** - I did not complete this part of the deliverable.
- [ ] **Responsive to window resizing** - I did not complete this part of the deliverable.
- [ ] **Application elements** - I did not complete this part of the deliverable.
- [ ] **Application text content** - I did not complete this part of the deliverable.
- [ ] **Application images** - I did not complete this part of the deliverable.

## 🚀 React part 1: Routing deliverable

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [ ] **Bundled using Vite** - I did not complete this part of the deliverable.
- [ ] **Components** - I did not complete this part of the deliverable.
- [ ] **Router** - Routing between login and voting components.

## 🚀 React part 2: Reactivity

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [ ] **All functionality implemented or mocked out** - I did not complete this part of the deliverable.
- [ ] **Hooks** - I did not complete this part of the deliverable.

## 🚀 Service deliverable

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [ ] **Node.js/Express HTTP service** - I did not complete this part of the deliverable.
- [ ] **Static middleware for frontend** - I did not complete this part of the deliverable.
- [ ] **Calls to third party endpoints** - I did not complete this part of the deliverable.
- [ ] **Backend service endpoints** - I did not complete this part of the deliverable.
- [ ] **Frontend calls service endpoints** - I did not complete this part of the deliverable.

## 🚀 DB/Login deliverable

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [ ] **User registration** - I did not complete this part of the deliverable.
- [ ] **User login and logout** - I did not complete this part of the deliverable.
- [ ] **Stores data in MongoDB** - I did not complete this part of the deliverable.
- [ ] **Stores credentials in MongoDB** - I did not complete this part of the deliverable.
- [ ] **Restricts functionality based on authentication** - I did not complete this part of the deliverable.

## 🚀 WebSocket deliverable

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [ ] **Backend listens for WebSocket connection** - I did not complete this part of the deliverable.
- [ ] **Frontend makes WebSocket connection** - I did not complete this part of the deliverable.
- [ ] **Data sent over WebSocket connection** - I did not complete this part of the deliverable.
- [ ] **WebSocket data displayed** - I did not complete this part of the deliverable.
- [ ] **Application is fully functional** - I did not complete this part of the deliverable.
