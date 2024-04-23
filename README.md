#react #express #typescript #postgres #prisma #cloudinary #backend #assembler-institute-of-technology #master-in-software-development

# 🎬 Welcome to MovieHub Backend Project

Welcome to MovieHub, an exciting application designed to help you keep track of the movies you're watching! This project was crafted as part of the backend curriculum for my Master's program in Software Development at the prestigious Assembler Institute of Technology.

## 🗄️ Data Model

In MovieHub, we focus on three key entities: Users, Movies, and Genres. Here's a breakdown of each:

### 👤 Users

The Users collection stores vital information about our application's users. Each user is unique and has the following attributes:

- **id:** A unique identifier for the user.
- **name:** The user's name.
- **email:** The user's email address.
- **password:** The user's password, securely stored.
- **movies:** A curated list of movies added by the user.

### 🎬 Movies

The Movies collection holds detailed information about the movies users have added to their lists. Dive into a world of cinema with these attributes:

- **id:** A unique identifier for the movie.
- **name:** The movie's title.
- **poster_image:** The URL of the movie's captivating poster image, securely stored on Cloudinary.
- **score:** A user-assigned rating for the movie.
- **genre:** The movie's genre, linked to our comprehensive Genres collection.

### 🏷️ Genres

The Genres collection offers a wide range of movie genres for users to choose from when adding movies to their lists. Get ready to explore diverse cinematic experiences with these attributes:

- **id:** A unique identifier for the genre.
- **name:** The genre's name.

## 📝 Branches and Phases

Our project development is structured into four main branches:

- **Main Branch:** This branch contains the README file you're currently reading.
- **Branch 01_mongoose_express:** Here, we leverage Mongoose to establish a connection between the server and a MongoDB database.
- **Branch 02_prisma_mongoDB:** A significant refactor using Prisma for database interactions, continuing to utilize MongoDB.
- **Branch 03_prisma_postgresql:** Building on Prisma, this phase integrates PostgreSQL as the primary database solution.

Feel free to explore this repository to gain insights into database management. Don't forget to create your own .env files based on the provided .env.example, and ensure you install the necessary modules for the stacks used.

Project created by Paula Wilshaw Muñoz.
