# Next.js + Firebase CRUD app

## Intro

A starter app for bootstrapping a next + firebase app. 

CRUD = create, read, update, and delete

Stores data in Firebase, uses Next.js as the frontend. 

Use case here will be a todo list app. 

This will act as a starting point for building a Blogging app.

## Prereqs

Know how to start up a firebase project and integrate the credentials from their into your web app. 

Know how to deploy a Next.js app to vercel. 

## Not covered

For now, authentication is not covered in this. It's open to everyone. 

I will fork this repository and add auth to it later. 

## Design notes and useful commands

Start off with a create next app: 

```
npx create-next-app .
```

change from yarn to npm, clean up and add add tailwind:

```
rm -rf node_modules; rm yarn.lock; npm i; rm -rf node_modules;
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

