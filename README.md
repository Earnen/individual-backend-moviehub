# Prisma PostgreSQL Branch

Welcome to the Prisma PostgreSQL branch of the MovieHub project! In this phase, we've transitioned from MongoDB to PostgreSQL as our database solution, requiring significant adjustments to our backend architecture.

## Migration to PostgreSQL

In this branch, we've migrated our backend infrastructure to PostgreSQL, a powerful relational database management system. This transition necessitated adaptations to our data schema and controllers to align with the SQL-based nature of PostgreSQL.

## Schema Adaptation

As part of the migration process, we've modified our data schema to better suit the relational model of PostgreSQL. Unlike MongoDB's document-based storage, PostgreSQL requires a structured schema with defined relationships between tables. We've updated our schema definitions to reflect these changes and ensure compatibility with PostgreSQL.

## Controller Adjustments

Additionally, we've made adjustments to our controllers to accommodate the differences between MongoDB and PostgreSQL. This includes updating database query logic and handling of relational data structures to align with PostgreSQL's SQL-based operations.

## Database Migration

Once the schema and controllers were adapted for PostgreSQL, we performed a database migration to transfer existing data from MongoDB to PostgreSQL. This ensured a seamless transition without data loss or disruption to the application's functionality.

Feel free to explore the codebase in this branch to see how we've successfully migrated our backend infrastructure to PostgreSQL and adapted our schema and controllers accordingly.
