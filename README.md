# Fullstack Takehome Exercise Starter Project

Welcome! Feel free to use this starter project to get you going on your takehome exercise.

## Installation

Getting setup:

- First clone the project into your own github account. This will allow us to have access to it when you are done.
- Then clone it locally to your development environment.
- `npm i`

Now you are free to develop features. Please use a feature branch for each so we can more easily follow what you have done.

## Notes on the database

We have configured Prisma ORM to use a sqlite database located in `prisma/dev.db`. If you want to modify the schema, use these steps:

- update `prisma/schema.prisma`
- run `npx prisma migrate dev` to create the migration

If you need to you can always reset the databased with `npx prisma reset`

## Running the application locally

`npm run dev`
