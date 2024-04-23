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

Our project development is structured into five distinct phases:

- **Main Branch:** For project setup and this delightful README file.
- **Branch 01_node_express:** The foundational branch for setting up our server using the versatile Express framework.
- **Branch 02_mongoose_express:** Where we seamlessly integrate Mongoose to connect our server to a MongoDB database.
- **Branch 03_prisma:** A refactor using Prisma for enhanced database interactions.
- **Branch 04_prisma_postgresql:** Building on Prisma, this phase sees the integration of PostgreSQL as our database solution.

Feel free to explore this repository to gain insights into database management. Don't forget to create your own .env files based on the provided .env.example, and ensure you install the necessary modules for the stacks used.

Project created by Paula Wilshaw Muñoz.
