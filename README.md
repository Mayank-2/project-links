# project-links

This repository contains links to all the parts of the project.

## Repositories

### 1. [Frontend Repository](https://github.com/Mayank-2/innocomm)
   - Description: The frontend of the project, built with React, Tailwindcss.

### 2. [Backend Repository](https://github.com/Mayank-2/Innoback)
   - Description: The backend of the project, built with Django And Django Rest Framework.

### 3. [Admin Frontend Repository](https://github.com/Mayank-2/innoAdmin)
   - Description: The admin panel, built with React , Tailwindcss.

## Note on Authentication Testing
Due to current compatibility issues between JWT-based authentication and deployment platforms Render (backend) and Vercel (frontend), some authentication features may not function correctly when accessed via the browser. Specifically, CORS and credential handling may cause challenges during API requests.

Recommended Testing Approach
To test the authentication endpoints and verify the full functionality of the application, we recommend using tools like Postman or cURL for making API requests directly. This will ensure that you can fully explore the backend capabilities without interference from deployment platform configurations.

I'm actively working on resolving these issues to ensure a seamless integration experience. Thank you for your understanding!
