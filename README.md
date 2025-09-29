# Social-Media-Plaform
A full-stack **Social Media Platform** built with **Spring Boot (backend)** and **React (frontend)**.
This project allows users to create accounts, post content, like, comment, and interact in real-time and more coming soon.

---

## Tech Stack

* **Backend**: Spring Boot (Java, Maven)
* **Frontend**: React.js (JavaScript)
* **Database**: MySQL
* **Version Control**: Git & GitHub

---

## Project Structure

```
/social-media-platform
  /backend      -> Spring Boot application
  /frontend     -> React application
  README.md
```

---

## Getting Started

### 1. Clone Repository

```bash
git clone https://github.com/your-org/social-media-platform.git
```

### 2. Backend Setup

```bash
cd backend
./mvnw clean install
./mvnw spring-boot:run
```

Backend runs on: **[http://localhost:8080](http://localhost:8080)**

### 3. Frontend Setup

```bash
cd frontend
npm install
npm start
```

Frontend runs on: **[http://localhost:3000](http://localhost:3000)**

### 4. Database Setup

Create a MySQL database:

```sql
CREATE DATABASE social_media;
```

Update `application.properties` (backend):

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/social_media
spring.datasource.username=root
spring.datasource.password=yourpassword
```

---

## Git Collaboration Workflow

1. **Branching Strategy**

   * `main` → stable code
   * `dev` → ongoing development
   * `feature/<name>` → for new features

2. **Basic Git Commands**

```bash
# Clone repo
git clone <repo-url>

# Create new branch
git checkout -b feature/login

# Stage and commit
git add .
git commit -m "Add login feature"

# Push to remote
git push origin feature/login
```

3. **Pull Requests**

   * Always create PRs into `dev`.
   * Get code reviewed before merging.

---

## Contribution Guidelines

* Write clear commit messages.
* Keep PRs small and focused.
* Update documentation if you add/change features.
