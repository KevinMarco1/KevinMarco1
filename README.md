# Hi there! 👋 I'm Kevin Marco

I am a passionate software engineer graduated from **Faculty Of Computers And Artificial Intelligence Cairo University**. 

I follow the T-Shape model in my work, primarily focusing on backend development.
However, I am also proficient in modern frontend technologies for web, mobile, and desktop applications.
I love coding, solving problems, and creating user-friendly applications. Here’s a little about me and the projects I have worked on.


### About Me

- 👯 I’m looking to collaborate on open source projects.
- 📫 How to reach me: kevinmarcory@gmail.com

### Experience

- **Front-end:** HTML, CSS, Tailwind, JS, React, Next.js
-  **Mobile:** Flutter, Kotlin
- **Desktop:** Python (tkinter)
- **Backend:** Node.js, NestJS
- **Database:** SQL Server, Postgres, Cloud Firestore
- **Tools & Platforms:** Git, GitHub, VS Code, Docker

---

## Projects

### 1. HorusEyeIntelliCancerSystem (Graduation Project):

**Description:**
HorusEye is an advanced cancer management system (combining both knowledge in information systems and artificial intelligence technqiues) that supports adding doctors, patients, and radiation therapists, with authenticated doctor accounts enabling patient registration, information exploration, and profile updates. Each patient has follow-ups created by doctors, including classification follow-ups using the HorusBlink feature (based on the EfficientNet-B7 CNN model) to classify histopathology samples as malignant or benign, and detection follow-ups using the HorusVision feature (based on the YOLOv9 model) to segment tumors in mammograms, extract tumor images and dimensions, and allow for modification and detailed annotation. The system generates comprehensive medical reports incorporating model results and doctor notes, stores these reports for future access, and distributes them via email to both patients and responsible radiation therapists, enhancing the accuracy and efficiency of cancer diagnosis and treatment.

**Features:**

- HorusVision: allow doctors to detect tumors in MRI scans and measure their sizes.
- HorusBlink: enables doctors to classify histopathology samples as benign or malignant with high efficiency.
- Report Generation: Each followup generates a detailed report that formalizes the model results alongside the doctor's notes and
conclusions. Notably, doctors can refine tumor predictions, adjust sizes, and add notes or conclusions
-  Each patient profile maintains a list of follow-ups for thorough and organized tracking.


**Technologies:**
- Deep Learning: Python, Numpy, Pandas, Matplotlib, Seaborn, OpenCV, TensorFlow,
Keras, AutoKeras, Ultralytics Yolo, Roboflow
- Software: 
    - Frontend: Next.js.
    - Backend:  NestJS.
- Storage: PostgreSQL, Supabase
- Version Control: Git, GitHub


### 2. **MMDB (Movie Management Database System)**

   **Description**: MMDB is a comprehensive movie database web application inspired by IMDB, designed to provide detailed information about movies and their cast members. The application offers users the ability to search, sort, and paginate through movies, view detailed movie and cast profiles, and securely access the system via Firebase authentication. The design is fully responsive, ensuring an optimal viewing experience across all devices. Additionally, the project is containerized and integrated with CI/CD pipelines through GitHub Actions for streamlined deployment and testing.

   **Features**:

   - **User Ratings**: 
     - **Rate Movies**: Users can rate movies they have watched, providing valuable feedback and contributing to the overall rating displayed on each movie’s profile.
     - **Rate Actors**: Users can also rate actors based on their performances, influencing the average rating shown on each actor’s profile.
     - **Dynamic Rating System**: The system dynamically updates movie and actor ratings as more users submit their feedback, ensuring that ratings are always up-to-date and reflective of the latest opinions.
   
   - **Search, Sort, and Pagination**: Efficient navigation through the movie database with search by keyword, sorting by release date or rating, and pagination.
   - **Movie Details**: Access comprehensive information for each movie, including trailers, ratings, duration, genre, director, writers, language, and cast details.
   - **Cast Details**: View detailed profiles for each cast member, including their biography, past movies, awards, and personal information.
   - **Responsive Design**: The application is fully responsive, providing a seamless viewing experience on any device, whether desktop, tablet, or mobile.
   - **Authentication**: Secure user authentication implemented using Firebase.
   - **Containerization and CI/CD**: The application is fully containerized using Docker, with CI/CD pipelines set up using GitHub Actions for automated deployment and testing.

   **Technologies**:

   - **Frontend (Web)**: Next.js, Pure css
   - **Backend**: NestJS
   - **Mobile**: Kotlin
   - **Database**: Postgres
   - **Authentication**: Firebase
   - **CI/CD**: GitHub Actions
   - **Containerization**: Docker


### 3. Flight Messages Parser EgyptAir

**Description:**

The Flight Messages Parser is a robust desktop application developed for EgyptAir. This program automates the extraction of critical flight information from large text messages, which can be received manually or read directly from the email inbox. The application parses the text, extracts necessary details such as flight numbers, departure and arrival times, passenger information, and reference numbers...etc, and stores this data in an organized Excel sheet. Additionally, the software provides analytical capabilities, allowing users to generate comprehensive reports and insights based on the parsed data, thereby improving operational efficiency and decision-making.


**Features:**
- **Automated Data Extraction:** Seamlessly reads and processes large text messages or emails to extract flight details.
- **Email Integration:** Connects directly to email inboxes to fetch and process flight messages automatically.
- **Data Parsing:** Accurately parses text to extract relevant flight information such as flight numbers, timings, and passenger details.
- **Excel Integration:** Stores extracted data in Excel sheets for easy access, manipulation, and sharing.
- **Report Generation:** Generates detailed reports and analytics based on the extracted data, offering insights into flight operations and performance.
- **User-Friendly Interface:** Provides a simple and intuitive interface for manual data input and processing.
- **Data Analysis:** Offers tools for analyzing flight data, identifying trends, and making data-driven decisions.

**Technologies:**

- **Frontend:** Tkinter (for the graphical user interface)
- **Backend:** Python (for data processing, parsing and analyzing)
- **Storage:** File System (for storing and managing Excel sheets)

### 4. MyDay App
**Description:**
MyDay App is a comprehensive wedding planner application designed to streamline the planning process for couples. This MVP (Minimum Viable Product) allows users to browse various categories of wedding services, explore vendor details, search and filter vendors, and mark their favorite vendors. Users can also create and manage a budgeted plan for their wedding. From the admin perspective, the app provides full CRUD (Create, Read, Update, Delete) capabilities for managing categories and vendors. The app ensures secure access through JWT token-based authentication and integrates with third-party services like Google and Facebook for OAuth-based login.

**Features:**
- **Category Browsing:** Easily browse through various categories of wedding services.
- **Vendor Exploration:** Explore detailed information about vendors in each category.
- **Search & Filter:** Efficiently search for vendors and filter results based on preferences.
- **Favorites:** Mark and save favorite vendors or plans for quick access.
- **Budget Planning:** Create and manage a comprehensive budget plan for the wedding.
- **Admin CRUD Operations:** Admins can perform full CRUD operations on categories and vendors.
- **Authentication & Authorization:** Secure access with JWT token-based authentication.
- **OAuth Integration:** Simplified login with Google and Facebook integration.

**Technologies:**

- **Frontend:** Dart, Flutter
- **Backend:** TypeScript, NestJS, Prisma
- **Database:** Postgres (Supabase, DBaaS)

  
### 5. Te-Parthenos App
**Description:** 
Te-Parthenos App is a production-released system designed to manage the operations of St. Mary church's school of hymns. It features an admin dashboard and supports multiple users of different ages. The system efficiently handles user account management, material distribution, church calendar updates, exam scheduling and reservations, and certificate generation upon passing exams. Additionally, the app includes a notification system to keep users informed of important updates, and admins can review and accept sign-up forms for new users.

**Features:**
- **User Account Management:** Create, update, and manage user accounts for different age groups.
- **Material Distribution:** Provide access to hymn materials and resources for different classes.
- **Church Calendar Updates:** Update and manage the church's calendar with events and schedules.
- **Exam Scheduling & Reservations:** Schedule exams and manage reservations for participants.
- **Certificate Generation:** Automatically generate certificates for users who pass exams.
- **Notification System:** Send notifications to users about important updates and events.
- **Admin Dashboard:** Comprehensive admin dashboard for managing users, materials, and events.
- **Sign-Up Form Management:** Admins can review and accept or reject sign-up forms for new users.


**Technologies:**

- **Frontend:** Dart, Flutter
- **Backend:** Firebase Functions 
- **Database:** NoSQL Firebase Database (Cloud Firestore)



### 6. Student’s Affairs System


**Description:**
The Student’s Affairs System is a comprehensive web application designed to streamline and enhance the operations of the student affairs department within a faculty. This system allows for efficient management of student data, providing an easy-to-use interface for adding, removing, updating, and displaying student records. It also includes powerful search and filter functionalities to quickly locate students by name, ID, and academic level.

**Features:**

- **Add, Remove, Update, Show Students:** Easily manage student records with intuitive forms and interfaces.
- **Search and Filter:** Quickly find students using advanced search and filter options by name, ID, and academic level.
- **Responsive Design:** Ensures usability across various devices, including desktops, tablets, and smartphones.
- **Real-time Updates:** Leveraging Ajax for seamless, real-time updates without page reloads.
- **Data Validation:** Robust validation checks to ensure data integrity and accuracy.

**Technologies:**

- **Frontend:** HTML, CSS, Javascript, Ajax
- **Backend:** Django
- **Database:** SQLite



### 7. Game rental System
**Description:** Game rental software that helps shop owners to manage adding, removing, updating games and
vendors also in renting, returning and payments of games. 

**Technologies:** C#, Microsoft SQL server.


### 8. Garage Management System

**Description:** 
Garage software that helps owners manage space in garage using different configurations,
calculate each vehicle fees and generate instant reports. involves steps from requirements
elicitation until delivery and maintenance.


**Technologies:** Software engineering principles, Java, Solid principles, design patterns, clean code.


### 9. Math Solver

**Description:** 
Math solver software that can solve complex problems in linear algebra and frequency-time
analysis problems (Fourier, Laplace ).


**Technologies:** Mathematics, problem solving, python and UI/UX.


---

<h3 align="left">Connect with me:</h3>
<p align="left">
  <a href="https://www.linkedin.com/in/kevinmarcomarcory/" target="blank">
    <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="maher-mohsen" height="30" width="40" />
  </a>
  <a href="https://leetcode.com/u/KevinMarco/" target="blank">
    <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/leet-code.svg" alt="maher-mohsen" height="30" width="40" />
  </a>
</p>

---
