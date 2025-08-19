# Tech Challenge – Ruby on Rails (Backend)

### Context

This is a backend-focused technical challenge for a real project within a U.S.-based wellness startup. The goal is to evaluate your backend skills, code structure, validations, and ability to reason through constraints.

---

### Objective

Create a simple scheduling system for booking consultations with professionals. Each appointment must follow the rules below.

---

### Business Rules

- Each consultation has a **fixed duration of 30 minutes**
- Professionals are only available during **business hours (09:00 to 17:00)**, Monday through Friday
- A professional **cannot have overlapping appointments**
- Users can book with any available professional
- No authentication needed — simulate `current_user`

---

### Suggested Models

- `User` (name, email)
- `Professional` (name, specialty)
- `Appointment` (user_id, professional_id, start_time)

---

### Required API Endpoints

- `POST /appointments` → create appointment  
- `GET /appointments` → list current user's appointments  
- `DELETE /appointments/:id` → cancel appointment

---

### Requirements

- Ruby on Rails 6+ or 7
- PostgreSQL or SQLite
- Clean, idiomatic Rails code
- Validations and error messages implemented
- Include instructions in this README for running the project

---

### Submission

- Create a public or private GitHub repo and share the link via form 
- Include a README with setup instructions  
- Deadline: 2 days after receiving the challenge (can be extended upon request)

---

### Evaluation Criteria

- Code organization and clarity
- Business logic implementation
- Use of Rails conventions and best practices
- Communication and documentation
- Ability to reason through edge cases

---

Thank you for participating!
