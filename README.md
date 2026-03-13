# Kanban Task Manager

Task management backend application implementing a Kanban-style board with tasks, epics and subtasks.

The project demonstrates building a backend application with in-memory storage and file persistence.

---

## Features

* Create and manage tasks
* Support for epics and subtasks
* Track task status and history
* Detect time overlaps between tasks
* Persist tasks to file storage

---

## Architecture

The application follows a simple layered structure:

* **Manager layer** — task management logic
* **Model layer** — domain entities
* **Persistence layer** — file storage

The system maintains task relationships and supports history tracking.

---

## Tech Stack

* Java
* Collections Framework
* File I/O
* Maven

---

## Running the project

### Requirements

* Java 21
* Maven

### Run locally

```bash
mvn clean package
```

---

## Project Structure

```
manager      — task manager implementations
model        — tasks, epics and subtasks
history      — task history tracking
persistence  — file-based storage
```

---

## Key Backend Concepts

This project demonstrates:

* object-oriented design
* data modeling
* task relationship management
* file-based persistence
