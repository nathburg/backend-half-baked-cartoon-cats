# Cartoon Cats

## Demo

[Cartoon Cats API](https://alchemy-cartoon-cats.herokuapp.com/)

## Getting Started

Use [this template](https://github.com/alchemycodelab/backend-half-baked-cartoon-cats) to get started.

### Learning Objectives

- Create a GET endpoint using Express that returns an array of objects
- Create a GET endpoint using Express that returns a single object based on the id and `req.params.id`
- Test Express controller routes expectations using Jest and Supertest
- Explain how Express tries routes, in what order, and when it will stop or continue

### Description

Welcome to your first Express app! We're going to be building out two different endpoints that returns information about cartoon cats listed in the `data/cats.js` file. For today's deliverable, you will be focused on the `controllers` section of the `lib` folder.

Your tests have been provided for you -- before you start, read through the tests to understand what is expected to be returned from your endpoints.

### Acceptance Criteria

- A user should be able to visit `/cats` and see a list of cats with their `id` and `name` (note: do NOT return the entire array of cats - only the id and name)
- A user should be able to visit `/cats/:id` and see all the detailed information about the cat with the corresponding `id`

### Rubric

| Task                                                              | Points |
| ----------------------------------------------------------------- | ------ |
| All tests passing                                                 | 2      |
| Home page should return HTML showing the list of routes available | 2      |
| `/cats/` route returns list of cats' names and ids                | 2      |
| `/cats/:id` route returns detailed cat information                | 4      |
