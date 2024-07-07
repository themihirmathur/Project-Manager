# Project Manager 📂 A Full Stack Dribble Clone

<img width="1003" alt="Screenshot 2023-10-13 at 11 27 04 PM" src="https://github.com/themihirmathur/Project-Manager/assets/92594107/9b0c7dfc-bcbf-4cfe-932b-f97efae0fb43">

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>

## Table of Contents
- Introduction
- Tech Stack
- Features
- Quick Start
- Snippets
- Links
- More
- Tutorial

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>

## Introduction
`Project Manager` is a full-stack Dribble clone developed using modern web technologies such as Next.js, GraphQL, Next Auth, TypeScript, and Tailwind CSS. The application replicates all the essential features of Dribble, enabling users to share and showcase their projects seamlessly.

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>

## Tech Stack
- Next.js
- Next Auth
- TypeScript
- JSON Web Token
- GraphQL
- Grafbase
- Cloudinary
- Tailwind CSS
- Headless UI

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>

## Features

### Modern Design Home Page
Features a clean and modern design resembling Dribbble, with a visually appealing interface showcasing project previews and navigation.

### Browsing and Pagination
Browse different projects, filter them by category, and experience smooth pagination for seamless data exploration.

### Authentication & Authorization System
A fully functional authentication and authorization system allows users to log in securely using JWT and Google authentication.

### Create Post Page
Provides a dedicated space for users to share their projects with the community. It includes fields for project details, images, and other relevant information.

### Project Details and Related Projects
A detailed view with related projects functionality, enabling users to explore more projects within the same category or theme.

### Edit and Re-upload Images
Users have the capability to edit previously created projects, including the ability to re-upload images from their devices to the cloud for updates.

### Delete Projects
The delete functionality simplifies project removal with a one-click process, streamlining the user experience.

### Portfolio-Style User Profile Page
The user profile page adopts a portfolio-style layout, displaying the user's projects along with the project profiles of other users for easy exploration.

### Backend API Routes
Backend API routes for handling JWT token management for secure authentication and image uploading, supporting seamless integration with the frontend.

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>

## Quick Start
Follow these steps to set up the project locally on your machine.

### Prerequisites
Make sure you have the following installed on your machine:
- Git
- Node.js
- npm (Node Package Manager)

### Cloning the Repository
```bash
git clone https://github.com/themihirmathur/Project-Manager.git
cd Project-Manager
```

### Installation
Install the project dependencies using npm:
```bash
npm install
```

### Set Up Environment Variables
Create a new file named `.env` in the root of your project and add the following content:
```env
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
NEXTAUTH_URL=
NEXTAUTH_SECRET=
CLOUDINARY_NAME=
CLOUDINARY_KEY=
CLOUDINARY_SECRET=
GRAFBASE_API_URL=
GRAFBASE_API_KEY=
```
Replace the placeholder values with your actual credentials. You can obtain these credentials by signing up on the corresponding websites from Google Cloud, Cloudinary, and Grafbase. For the Next Auth secret, you can generate any random secret using a tool like `crytool`.

### Running the Project
```bash
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>
