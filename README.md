# Prisma MongoDB Branch

Welcome to the Prisma MongoDB branch of the MovieHub project! In this phase, we've conducted a significant refactoring to enhance our backend architecture.

## Refactoring with Prisma

In this branch, we've refactored our backend codebase to utilize Prisma, a modern database toolkit, for interacting with our MongoDB database. Prisma simplifies database access and management by generating type-safe database client code based on our data model definitions.

## Removal of Models

As part of the refactoring process, we no longer need separate model files for our data entities. Instead, we define our data models directly in the `schema.prisma` file. Prisma uses these model definitions to generate database tables and client code automatically, eliminating the need for manual model definitions.

## MongoDB Integration

Despite the switch to Prisma, we continue to use MongoDB as our database solution. Prisma seamlessly integrates with MongoDB, allowing us to benefit from MongoDB's flexible document-based data storage while leveraging Prisma's powerful query capabilities.

Feel free to explore the codebase in this branch to see how we've streamlined our backend architecture with Prisma and MongoDB.
