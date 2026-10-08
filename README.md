# TaskBoard

A simple task list app. Add tasks, mark them complete, and delete them. Tasks are
stored in memory and are cleared when the server restarts.

## Run locally

Requires Node.js 20 or newer.

```bash
npm install
npm start
```

Open <http://localhost:3000>. Stop the server with `Ctrl+C`.

## Test

```bash
npm test
```

## Run with Docker Compose

```bash
docker compose up --build
```

Open <http://localhost:3000>. Stop the container with:

```bash
docker compose down
```

## Beginner guide

`docs/TaskBoard-Explained-for-Beginners.docx` explains the whole project in plain
language, with seven pictures: what each tool is for, where every file lives and why,
how the app works, and how the Docker and GitHub Actions chains fit together.
