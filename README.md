### **Project Name: Netflix Clone**

**Netflix Clone** is a full-stack web application built with the MERN (MongoDB, Express, React, Node.js) stack, designed to replicate the functionality and user experience of Netflix. This project incorporates features like user authentication, dynamic movie browsing, and responsive design.

---

### **Mission and Objectives**

---

### **Mission:**
To create a Netflix-like streaming platform, allowing users to explore, search, and watch content dynamically.

---

### **Objectives:**

1. **User Authentication:**
   - Secure login and signup using JWT (JSON Web Tokens).
   - Persistent sessions with secure cookies.

2. **Movie and TV Show Management:**
   - Fetch movie details dynamically using external APIs.
   - Display trending, popular, top-rated, and upcoming movies.

3. **Search and Filter:**
   - Search by movie, TV show, or actor.
   - Implement filters for sorting content.

4. **Responsive Design:**
   - Ensure the application is fully responsive for various devices.

5. **Deployment:**
   - Host the application on reliable platforms for public access.

---

### **Technology Stack**

#### **Frontend**
1. **React.js**
   - **Why?**: Efficient UI library for dynamic web applications.
   - **Use Case**: Handles the application’s user interface and state management.

2. **Bootstrap**
   - **Why?**: Predefined responsive components for rapid development.
   - **Use Case**: Ensures a consistent and adaptive design.

---

#### **Backend**
1. **Node.js**
   - **Why?**: High-performance server-side platform.
   - **Use Case**: Manages API requests and real-time data.

2. **Express.js**
   - **Why?**: Simplifies API creation and routing.
   - **Use Case**: Handles RESTful services.

3. **JWT**
   - **Why?**: Secure user authentication and session management.
   - **Use Case**: Validates user access and protects routes.

---

#### **Database**
1. **MongoDB**
   - **Why?**: NoSQL database for flexible schema design.
   - **Use Case**: Stores user information, movie details, and search history.

---

#### **Deployment**
1. **Frontend Hosting: Vercel**
   - **Why?**: Optimized platform for React app hosting.
   - **Use Case**: Deploys the client-side application.

2. **Backend Hosting: Heroku**
   - **Why?**: Reliable and scalable backend hosting.
   - **Use Case**: Hosts APIs and manages database connections.

---

### **Workflow Overview**

The application workflow involves users browsing movies and TV shows, searching for specific content, and watching trailers. Admin users can manage movie data and content categories. Authentication ensures that only authorized users can access and manage their profiles and viewing history.

### **FlowChart**
![image](https://github.com/user-attachments/assets/d1a39116-b29a-42c7-9469-0c3df7204e0b)

---

### **Project Structure for Feature Implementation**

This project is structured to ensure a systematic and incremental development process. Each week builds upon the previous deliverables, enabling a smooth transition from basic to advanced functionalities.

**NOTE:** Participants are encouraged to customize the design and functionality to make the application unique.

---

## **Week-by-Week Learning Plan**

---

### **Week 1: Project Setup and UI Design**

- **Goal:** Set up the foundational structure and design the app UI.

- **Tasks:**
  1. Initialize a **React.js** project with Bootstrap.
     - **Reading:** [React.js Official Docs](https://reactjs.org/docs/getting-started.html)
     - **Video:** [React.js Crash Course](https://www.youtube.com/watch?v=w7ejDZ8SWv8)
  2. Build the basic layout for the homepage, login, and movie browsing pages.
     - **Reading:** [Bootstrap Components](https://getbootstrap.com/docs/5.0/components/alerts/)
     - **Video:** [Bootstrap Crash Course](https://getbootstrap.com/docs/5.0/getting-started/introduction/)

- **Deliverables:**
  - Responsive UI with basic navigation and placeholders for movie components.

---

### **Week 2: User Authentication**

- **Goal:** Implement secure user authentication.

- **Tasks:**
  1. Set up user schema with Mongoose.
     - **Reading:** [MongoDB Schema Design](https://mongoosejs.com/docs/guide.html)
     - **Video:** [Mongoose Models Tutorial](https://www.youtube.com/watch?v=DZBGEVgL2eE&t=30s)
  2. Build authentication APIs using JWT.
     - **Reading:** [JWT Basics](https://jwt.io/introduction/)
     - **Video:** [JWT Authentication Guide](https://www.youtube.com/watch?v=mbsmsi7l3r4)
  3. Create login and signup forms in React.
     - **Reading:** [React Forms](https://reactjs.org/docs/forms.html)
     - **Video:** [React Form Tutorial](https://www.youtube.com/watch?v=SdzMBWT2CDQ&t=590s)

- **Deliverables:**
  - Functional login/signup system with secure authentication.

---

### **Week 3: Movie Browsing and Search**

- **Goal:** Develop movie browsing and search functionality.

- **Tasks:**
  1. Create APIs for fetching movies and TV shows dynamically.
     - **Reading:** [RESTful API Design](https://restfulapi.net/)
     - **Video:** [Building REST APIs](https://www.youtube.com/watch?v=pKd0Rpw7O48)
  2. Implement search and filter features.
     - **Reading:** [React State Management](https://reactjs.org/docs/hooks-state.html)
     - **Video:** [React State Tutorial](https://www.youtube.com/watch?v=-bEzt5ISACA&t=465s)

- **Deliverables:**
  - Functional movie browsing with search and filter capabilities.

---

### **Week 4: Movie Details and Trailers**

- **Goal:** Build a detailed movie page with trailers and related content.

- **Tasks:**
  1. Display movie details fetched from APIs.
     - **Reading:** [React Router](https://reactrouter.com/en/main)
     - **Video:** [React Router Tutorial](https://www.youtube.com/watch?v=Law7wfdg_ls)
  2. Add video player functionality for trailers.
     - **Reading:** [React Player Docs](https://github.com/cookpete/react-player)
     - **Video:** [React Video Player Guide](https://www.youtube.com/watch?v=iu-LBY7NXD4&t=8s)

- **Deliverables:**
  - Movie details page with working trailers.

---

### **Week 5: Deployment and Testing**

- **Goal:** Deploy the application and ensure it’s production-ready.

- **Tasks:**
  1. Test all features using Postman and React Testing Library.
     - **Reading:** [Testing REST APIs](https://www.postman.com/api-testing/)
     - **Video:** [Postman Tutorial](https://www.youtube.com/watch?v=VywxIQ2ZXw4)
  2. Deploy the frontend and backend to Vercel and Heroku.
     - **Reading:** [Deploying MERN Apps](https://vercel.com/docs)
     - **Video:** [MERN Deployment Guide](https://www.youtube.com/watch?v=22Rywce_kcg&t=127s)

- **Deliverables:**
  - Fully deployed and functional Netflix Clone accessible via a public URL.

---
### Screenshots
![Screenshot (459)](https://github.com/user-attachments/assets/8b089074-a022-4a66-aaf7-57fcf0514083)
![Screenshot (460)](https://github.com/user-attachments/assets/df8e738d-e74f-470e-b233-2238f8f02355)
![Screenshot (461)](https://github.com/user-attachments/assets/bade8f0a-4f7c-436e-baea-13a6f8ba398c)
![Screenshot (462)](https://github.com/user-attachments/assets/3775703c-2126-4889-9168-c8bcc6e04c1c)
![Screenshot (463)](https://github.com/user-attachments/assets/3ba4e8c5-f864-4885-a67d-048c806c47d8)
![Screenshot (458)](https://github.com/user-attachments/assets/2b5ac704-9fc9-4ef6-bb8d-c99c3dc6e81c)

---

### **References**
1. [React Documentation](https://reactjs.org/docs/getting-started.html)
2. [MongoDB Documentation](https://www.mongodb.com/docs/manual/)
3. [Bootstrap Documentation](https://getbootstrap.com/docs/5.0/getting-started/introduction/)
4. [JWT Documentation](https://jwt.io/introduction/)
5. https://www.youtube.com/watch?v=gRroBZczKAU
6. https://github.com/burakorkmez/mern-netflix-clone
