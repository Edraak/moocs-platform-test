MOOC Platform Challenge
================
## Table of contents
1. [The Challenge](#the-challenge)
1. [Requirements](#requirements)
1. [Submission](#submission)
1. [Tips](#tips)
1. [API Documentation](#api-documentation)
1. [Assessment Criteria](#assessment-criteria)

## The Challenge

The challenge, if you choose to accept it, is to create a platform to help the world learn online. You may use any 3rd party tools or libraries that will help you implement the solution. Please read on for the description and details on the project.

## Requirements

1. Build a web application that handles listing and editing courses.
1. The app should include the following pages (or features):
    * Landing page (we want you to be creative in this page)
    * List courses
    * View course
    * Add new course
    * Edit existing course
    * Delete course
    
1. The app must consume a backend that will serve the above features

2. The web application must include a sorting features that operates at the backend level

4. Write API unit tests.
5. Make sure that only authorized and authenticated users can Edit, add, or delete courses.
6. Make sure that your application will handle cases where a course does not exist, or unauthenticated operations.

## Bonus Or Senior Requirements
The following are bonus requirements that can get you more noticed, but feel free to add more to the app as you please. 
**NOTE** if you are applying as a senior, the following are **REQUIRED**
1. Add a new ```category``` model where it meets the following criteria
    * a Categories page that lists all categories
    * a Category details page (which shows category name and the courses under that category).
    * Add a new category page (Only admin user can add a new category)

1. Implement a flux based application architecture on your FrontEnd

1. Use OAuth2 in the project.

1. Use youtube API to add videos to the courses you are building

1. Use a continuous integration (CI) tool.

1. Deploy the app

### Tech stack
You can use the tech stack you prefer (**except** for PHP and .NET), however we **prefer** the following:
1. Django and/or DRF with Python3 on the backend
1. Database
1. ReactJS on the FrontEnd

## Submission
Create a repository on your git hosting service of choice (Gitlab is highly recommended) with clear instructions on installation and running scripts.

Upon starting the development please send an email to salomari@qrf.org and add Salomari1987 as a contributor on your repository.

## Guidelines
   * Open Source. We have a strong affinity for open source technology. If your go-to technology stack includes proprietary software, you won't be helping yourself to use it in this project.

   * Decoupled Backend. We are looking for candidates with a strong understanding of the entire web application stack. The best projects will completely decouple the backend and the front end and communciate via API.

   * Test Suites with Continuous Integration. Enterprise production requires rock solid stability, so we favor candidates with experience writing quality tests.

   * Automated Deployment. Speaking of deployment, the most valuable engineers understand how their code is deployed and practice "infrastructure as code". The best projects integrated CI with a fully automated deployment to AWS, Digital Ocean, or similar.

   * Usable, Responsive Interface. There are many accessible CSS frameworks out there such as Bootstrap. All modern web applications should be responsive and these frameworks make it very easy to create a modern interface that adheres to established design principles and formats well on all devices.

   * Flux and MVVM architectures. The modern web is highly interactive. Projects like ReactJS and VueJS make it very easy to deploy HTML bindings that interact with interface elements dependably and efficiently.

**Good Luck!** — not that you need any ;)

-------------------------------------------------------------------------

## Assessment Criteria
These are what we will look for in the solution:

* **Readability:** Coding style, method/variable/class/etc.
* **Structure:** Object design and code architecture. Try not to overarchitect your solution.
* **Documentation:** Clarity of communication in your documentation (code comments, documents if needed). Also, the quality of your commit messages.
* **Testing:** Approach to testing.
* **Creativity:** in choosing how to present the landing page
