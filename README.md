# RecipeHub

Allrecipes is a user-friendly culinary hub that offers a wealth of features for food enthusiasts of all skill levels. This online platform is designed to inspire, connect, and share the joy of cooking with a community of like-minded individuals.

With Allrecipes, you can explore a diverse array of recipes, save your favorite ones, and create personalized feeds filled with mouthwatering dishes that match your tastes and dietary preferences. The platform makes it easy to connect with fellow foodies through a convenient messaging system, allowing you to exchange cooking tips, recommendations, and ideas in a friendly and engaging environment.

One of the standout features of Allrecipes is its ability to post your own culinary creations, similar to the way you'd share photos on Instagram. You can showcase your cooking prowess by uploading your recipes, complete with mouthwatering images, step-by-step instructions, and ingredient lists. Whether you're a seasoned chef or just starting your culinary journey, Allrecipes is the perfect digital kitchen companion, offering you a place to discover, share, and communicate with a vibrant community of fellow food enthusiasts.

Live : 

## Key Features

- **Name**: description.

## Tech Stack

- Frontend: React.js
- Backend: Node.js
- Database: MongoDB
  <br>![](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![](https://img.shields.io/badge/Babel-F9DC3E?style=for-the-badge&logo=babel&logoColor=white)
![](https://img.shields.io/badge/Chakra--UI-319795?style=for-the-badge&logo=chakra-ui&logoColor=white)
![](https://img.shields.io/badge/Redux-593D88?style=for-the-badge&logo=redux&logoColor=white)

# Different Pages of Website


## Backend

The backend is built on Node.js.

### Endpoints and Usage
# Backend Application Routes

This documentation outlines the available routes and endpoints for the backend application. These routes are responsible for handling various operations, including user authentication, recipe management, user management, and comment handling.

### Login and Authentication Routes

#### POST `/auth/signup`

- Creates a new user with a profile image.
- Requires user registration information.
- Example usage: `/auth/signup`

#### POST `/auth/login`

- Logs in a user.
- Requires user login credentials.
- Example usage: `/auth/login`

#### GET `/auth/logout`

- Logs out a user.
- No additional parameters required.
- Example usage: `/auth/logout`

### Private Routes (Authentication Required)
### 
#### GET `/feed`

- Retrieves the user's feed of recipes.
- Example usage: `/feed`

#### GET `/getMyRecipe`

- Retrieves the recipes created by the authenticated user.
- Example usage: `/getMyRecipe`

#### GET `/getSingleRecipe/:id`

- Retrieves a single recipe by its ID.
- Example usage: `/getSingleRecipe/:id`

#### GET `/getAllRecipe`

- Retrieves all available recipes.
- Example usage: `/getAllRecipe`

#### PATCH `/update/:id`

- Updates a recipe by its ID.
- Example usage: `/update/:id`

#### GET `/requests`

- Retrieves user friend requests.
- Example usage: `/requests`

#### GET `/friends`

- Retrieves the user's friends.
- Example usage: `/friends`

#### GET `/notfriends`

- Retrieves users who are not yet friends with the authenticated user.
- Example usage: `/notfriends`

#### GET `/:id`

- Retrieves a single user by their ID.
- Example usage: `/:id`

#### GET `/`

- Retrieves the profile of the currently logged-in user.
- Example usage: `/`

#### PATCH `/update/:id`

- Updates a user's information by their ID.
- Example usage: `/update/:id`

#### PATCH `/addFriend/:id`

- Adds a friend to the authenticated user's friend list.
- Example usage: `/addFriend/:id`

#### DELETE `/delete/:id`

- Deletes a user by their ID.
- Example usage: `/delete/:id`

### Comment Routes (No Authentication Required)

#### GET `/`

- Retrieves all comments (No authentication required).
- Example usage: `/`

#### POST `/add`

- Adds a new comment to a recipe (No authentication required).
- Example usage: `/add`

#### PATCH `/update/:id`

- Updates a comment by its ID (No authentication required).
- Example usage: `/update/:id`

#### DELETE `/delete/:id`

- Deletes a comment by its ID (No authentication required).
- Example usage: `/delete/:id`

Please ensure that proper authentication and authorization mechanisms are in place for private routes, as they require user authentication.





# What I've Learned


