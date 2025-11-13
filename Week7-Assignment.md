# 🚀 Week 7: Deployment and DevOps Essentials – Launching Your MERN App

## 🚀 Objective
Learn how to deploy a full MERN stack application to production, implement CI/CD pipelines, configure environment variables, and set up monitoring for your application.

## 📂 Tasks

### Task 1: Preparing the Application for Deployment
- Optimize your React application for production
  - Run build process to generate static assets
  - Implement code splitting for better performance
  - Configure environment variables for different environments
- Prepare your Express.js backend for production
  - Implement proper error handling
  - Set up secure HTTP headers
  - Configure environment variables
  - Implement logging for production
- Create a production-ready MongoDB setup
  - Set up a MongoDB Atlas cluster
  - Configure proper database user permissions
  - Implement database connection pooling

### Task 2: Deploying the Backend
- Deploy your Express.js backend to a cloud platform (Render, Railway, or Heroku)
  - Set up a new project/application
  - Configure environment variables
  - Set up continuous deployment from GitHub
- Configure a custom domain (optional)
- Implement HTTPS with SSL/TLS certificate
- Set up server monitoring and logging

### Task 3: Deploying the Frontend
- Deploy your React frontend to a static hosting service (Vercel, Netlify, or GitHub Pages)
  - Configure build settings
  - Set up environment variables
  - Configure continuous deployment from GitHub
- Set up a custom domain (optional)
- Configure HTTPS
- Implement caching strategies for static assets

### Task 4: CI/CD Pipeline Setup
- Set up GitHub Actions for continuous integration
  - Create workflows for running tests
  - Configure linting and code quality checks
  - Implement automated building of the application
- Implement continuous deployment
  - Configure automatic deployment on successful builds
  - Set up staging and production environments
  - Implement rollback strategies

### Task 5: Monitoring and Maintenance
- Set up application monitoring
  - Implement health check endpoints
  - Configure uptime monitoring
  - Set up error tracking (e.g., Sentry)
- Implement performance monitoring
  - Set up server resource monitoring
  - Configure API performance tracking
  - Implement frontend performance monitoring
- Create a maintenance plan
  - Schedule regular updates and patches
  - Plan for database backups
  - Document deployment and rollback procedures

## 🧪 Expected Outcome
- A fully deployed MERN stack application accessible on the internet
- Continuous integration and deployment pipelines
- Proper environment configuration for development, staging, and production
- Monitoring and logging setup for the application
- Documentation of the deployment process and maintenance procedures

## 🛠️ Setup
1. Make sure you have a completed MERN stack application from previous weeks
2. Create accounts on the following services:
   - GitHub (for source code and CI/CD)
   - MongoDB Atlas (for database hosting)
   - Render, Railway, or Heroku (for backend hosting)
   - Vercel, Netlify, or GitHub Pages (for frontend hosting)
3. Install any required CLI tools for the chosen platforms

## ✅ Submission Instructions
1. Accept the GitHub Classroom assignment invitation
2. Clone your personal repository that was created by GitHub Classroom
3. Complete all the tasks in the assignment
4. Commit and push your code regularly to show progress
5. Include in your repository:
   - The complete MERN stack application code
   - CI/CD configuration files
   - Environment variable templates (.env.example)
   - Deployment scripts and configuration
   - A comprehensive README.md with deployment instructions
6. Update your README.md with:
   - URL of the deployed frontend application
   - URL of the deployed backend API
   - Screenshots of your CI/CD pipeline in action
   - Documentation of your monitoring setup
7. Your submission will be automatically graded based on the criteria in the autograding configuration
8. The instructor will review your submission after the autograding is complete 
 
## ✅ Progress Checklist
 
- **Initialization**
   - [ ] Confirm working MERN repo is ready (link/path): <repo-link-or-path>
   - [ ] Choose hosting
     - [ ] Backend: Render / Railway / Heroku
     - [ ] Frontend: Vercel / Netlify / GitHub Pages
   - [ ] Create MongoDB Atlas cluster and DB user
   - [ ] Capture Atlas connection string (no secrets in repo)
 
- **Task 1: Prep for Production**
   - [ ] React build optimized (code-splitting, prod build)
   - [ ] Frontend env vars configured (e.g., `VITE_API_BASE_URL` or `REACT_APP_API_BASE_URL`)
   - [ ] Express error handling and centralized logger
   - [ ] Secure headers (e.g., `helmet`) and CORS as needed
   - [ ] Backend env vars and config
   - [ ] DB connection pooling and health check endpoint
 
- **Task 2: Deploy Backend**
   - [ ] Create project on chosen platform
   - [ ] Add env vars (DB URI, JWT secrets, origins)
   - [ ] Enable CI/CD from GitHub
   - [ ] HTTPS enabled (platform default or custom cert)
   - [ ] Monitoring/logging configured
 
- **Task 3: Deploy Frontend**
   - [ ] Build settings configured
   - [ ] Env vars set (API base URL points to deployed backend)
   - [ ] CI/CD from GitHub enabled
   - [ ] HTTPS enabled
   - [ ] Asset caching strategy verified
 
- **Task 4: CI/CD Pipelines**
   - [ ] GitHub Actions workflow for lint/test/build
   - [ ] Auto-deploy on successful builds
   - [ ] Staging and production environments
   - [ ] Rollback strategy documented
 
- **Task 5: Monitoring & Maintenance**
   - [ ] Health checks and uptime monitoring
   - [ ] Error tracking (e.g., Sentry) wired
   - [ ] Server resource and API performance tracking
   - [ ] Maintenance plan (updates, backups, rollback docs)
 
- **Documentation**
   - [ ] `.env.example` added (no secrets)
   - [ ] Deployment configs/scripts committed
   - [ ] README updated with deployment instructions
 
## 🔗 Deployment URLs
- **Frontend URL**: <https://your-frontend.example>
- **Backend API URL**: <https://your-backend.example>
 
## 🖼️ Screenshots To Collect
- [ ] CI pipeline run (passing)
- [ ] CD deployment logs
- [ ] Uptime monitor dashboard
- [ ] Error tracker dashboard
 
## 📝 Notes
- Add any platform-specific caveats or decisions here.