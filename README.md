# rust-recipe-app
a web app in written in rust to piss off the JS devs (jk i like js, who cares)

This is a very simple app that shows the user some recipes ChatGPT came up with.

## Tech-Stack 


- **Rust + Axum** for the backend API and to flex epic programming skills
- **SQLx + SQLite** for all things DB related
-  **Askama templates** for our lord and savior HTML
- **utoipa + Swagger UI** for OpenAPI docs
- **Leptos** (in the `client/` submodule) because we miss using react sometimes


# How to use this app

## start the client 
- cd into the client module
- type "trunk serve"
- fix whatever errors it gives you 
- type "trunk serve" again

## start the server

- cd into server module
- type "cargo build"
- type "cargo run"
- fix errors again
- repeat steps 2 and 3 and possibly 4 if necessary

type ** http://127.0.0.1:8080/ ** to the browser and hopefully it works

if not idk

enjoy :)


