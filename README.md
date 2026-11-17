# SWP391 - Job Seeking System

## I. General information
### 1. Information of Subject

| Class    | **SE1868-NJ**                             |
|----------|-------------------------------------------|
| Subject  | **Application Development Project (SWP391)** |
| Semester | **Fall 2024**                             |
| Instructor | **Nguyen Manh Hung (HungNM142)**        |
| Group | **4**        |

### 2. Member of Team

| ID Student | Fullname | Assigned Tasks & Features |
|:---:|---|---|
| **HE173048** | **Tran Van Tuan** | • Login, Logout, Change Password<br>• Recruiter Verification<br>• Add New Job Posting<br>• View Job Posting Details<br>• Edit 1 Job Posting<br>• Manage Job Posting<br>• Seeker Management<br>• Dashboard Recruiter<br>• View Job Seeker Education<br>• View Job Seekers' Work Experience<br>• View CV Job Seeker<br>• Email Confirmation |

### 3. Link of Google Drive for Project

- [Google Drive Folder](https://drive.google.com/drive/folders/19U7SNAP5B_OhYPR-Kq8EUCoOhFxdbl3L)

---

## II. Information of Topic Project

### 1. Problem
Job seekers work hard to gain the right skills and knowledge to give them an edge over others in the role they seek. However, at times, despite their best efforts, one may find it difficult to move a step closer to this sought-after job. Hence a platform for listing out the availability of jobs irrespective of the field is required. Furthermore, a job site serves a dual purpose. On one hand, it lists out the availability of jobs to candidates, and on the other, it serves as a database of registered candidate’s profiles for companies to shortlist. The objective is to develop a software solution to predict the availability of jobs based on location, sectors, package, platform, interest and eligibility. As it is important to keep the candidates engaged during their job search, it is important to provide facets on the above - mentioned criteria so that they can narrow down to the jobs of their choice.

### 2. Features and UC Model

#### 2.1. Actor Specification
1.	Admin – Verifies the company/seeker and maintains the system.
2.	Recruiter – Posts job vacancies and its requirements.
3.	Seeker – Can apply for a job posting.

#### 2.2. Usecase Specification

##### 1. Approve New Companies
**Description**: Checks the credibility of the company and admits the company into the system.

- **Flow of Events**: Verifies the Company’s information. 
- **Pre-Conditions**: Checking the proofs submitted. 
- **Post-Conditions**: Background checks.


##### 2. Deletion of Fraudulent Companies
**Description**: The admin can delete the company from the system if it is proven to be a false/fraudulent company.

- **Flow of Events**: Deletion of a company from the system. 
- **Pre-Conditions**: Rechecking the submitted proof.
- **Post-Conditions**: Based on feedback from job seekers.


##### 3. Maintenance/Updating
**Description**: Refers to change an existing information in the system to fix errors or enhance functionality and deleting outdated information and updating new data into the system.

- **Flow of Events**: Modifying and updating of the database based on various criteria.
- **Pre-Conditions**: Status of each company/seeker.
- **Post-Conditions**: Based on feedback from recruiters/seekers.


##### 4. Feedback
**Description**: Getting input from recruiters/seekers to verify the credibility of the users and to modify/update the system for better enhancements/quality.

- **Flow of Events**: Input from both recruiters and seekers.
- **Pre-Conditions**: The feedback collected must be from the registered users of the system.
- **Post-Conditions**: Nil.


##### 5. Registration
**Description**: Every recruiter/seeker must first register to avail the opportunity to use the system.

- **Flow of Events**: Every user must submit the needed requirements for registration.
- **Pre-Conditions**: The proofs/ID must be credible.
- **Post-Conditions**: Nil.


##### 6. Profile
**Description**: Contains the information which will be displayed to all other users of the system.

- **Flow of Events**: The information available in the profile should be credible.
- **Pre-Conditions**: Only required information to be displayed.
- **Post-Conditions**: Additional information can be added.


##### 7. Recruiter Login
**Description**: The recruiter/company login through a separate login page.

- **Flow of Events**: Login into the system using the recruiter password.
- **Alternative Flow**: Login through alternate means provided by admin (Forgot_password).
- **Pre-Conditions**: Username and password must be correct.
- **Post-Conditions**: Can change username/password.


##### 8. Manage Profile
**Description**: Displays the information about the company.

- **Flow of Events**: Display Company information.
- **Pre-Conditions**: Can input credible information about the company.
- **Post-Conditions**: Update the required information.


##### 9. Post Job Vacancy
**Description**: Can post a job vacancy and provide details about the field, category, salary, and other job requirements.

- **Flow of Events**: Post a job vacancy with the required details.
- **Pre-Conditions**: Should post all the details that the seeker must know.
- **Post-Conditions**: Can post what is needed from the seeker for the required post.


##### 10. Job Requirements
**Description**: Displays the information of the job posted.

- **Flow of Events**: Job requirement information.
- **Pre-Conditions**: Information about what is to be expected from the seeker.
- **Post-Conditions**: Additional requirements along with the existing information from the company.


##### 11. Delete Job Vacancy
**Description**: If a job vacancy is filled or no longer needed, the company can delete the job posting from the system.

- **Flow of Events**: Deletion of job posting if the post is filled.
- **Alternative Flow**: Deletion of job post if it’s no longer needed.
- **Pre-Conditions**: The recruiter should delete the job posting for an appropriate reason.
- **Post-Conditions**: Can notify the admin after the change is made.


##### 12. Communicate with Job Seeker
**Description**: If a job seeker applies for a job vacancy, the recruiter should communicate with the seeker to provide information like interview date, company tests, etc.

- **Flow of Events**: Communication between recruiter and seeker through the system.
- **Alternative Flow**: Nil.
- **Pre-Conditions**: The seeker must satisfy the required job specifications for the posting.
- **Post-Conditions**: Nil.


##### 13. Manage Account
**Description**: Details actions such as change/update username and password, and deletion of the recruiter account.

- **Flow of Events**: Account updation/deletion.
- **Alternative Flow**: Nil.
- **Pre-Conditions**: Must be a registered user.
- **Post-Conditions**: Nil.


##### 14. Seeker Login
**Description**: The job seeker logs in through a separate login page.

- **Flow of Events**: Seeker login through password.
- **Alternative Flow**: Login through alternate means provided by admin (Forgot_password).
- **Pre-Conditions**: Username and password must be correct.
- **Post-Conditions**: Can change username/password.


##### 15. Manage Profile/Seeker Details
**Description**: Displays the information of the seeker provided during registration.

- **Flow of Events**: Information about the seeker.
- **Alternative Flow**: Nil.
- **Pre-Conditions**: Nil.
- **Post-Conditions**: Nil.


##### 16. Upload/Update CV
**Description**: The CV/resume, submitted in the profile section, is a requirement for applying for jobs.

- **Flow of Events**: Upload/update resume.
- **Alternative Flow**: Nil.
- **Pre-Conditions**: Only credible information must be presented in the resume.
- **Post-Conditions**: Can update the resume whenever required.


##### 17. View Job Vacancy
**Description**: A job seeker can browse through various job postings, based on category and field and further constraints.

- **Flow of Events**: Browsing job vacancies.
- **Alternative Flow**: Nil.
- **Pre-Conditions**: Must be a registered user.
- **Post-Conditions**: Nil.


##### 18. Apply for Job Vacancy
**Description**: A job seeker, if interested in a certain job posting, can apply for that posting.

- **Flow of Events**: Applying for a job vacancy.
- **Alternative Flow**: Nil.
- **Pre-Conditions**: Should meet the required requirements of the posting.
- **Post-Conditions**: Upload CV.


##### 19. Modify Account
**Description**: Details actions such as change/update username and password, and deletion of the account of the job seeker.

- **Flow of Events**: Account modification/updation.
- **Alternative Flow**: Nil.
- **Pre-Conditions**: Must be a registered user.
- **Post-Conditions**: Nil.

---

## III. Tech Stack

### 1. Backend & Server
* **Language & Runtime:** Java 17
* **Framework / Standards:** Jakarta EE 10 / Jakarta Servlet API 5.0+, JavaServer Pages (JSP)
* **Tag Library:** Jakarta Standard Tag Library (JSTL 2.0)
* **Web Server & Servlet Container:** Apache Tomcat 10.1.x *(Jakarta EE compliant)*
* **Architecture:** MVC (Model - View - Controller) pattern using DAO layer with raw JDBC

### 2. Database
* **Database Management System:** Microsoft SQL Server (MSSQL)
* **JDBC Driver:** Microsoft JDBC Driver for SQL Server (`sqljdbc42`)

### 3. Third-Party Libraries & Dependencies
* **Email & Notifications:** Jakarta Mail 2.0.1 & Jakarta Activation 2.0.1
* **Excel Processing:** Apache POI 4.0.1, POI-OOXML, XMLBeans
* **Data Serialization:** Google Gson 2.8.2
* **HTTP & Utilities:** Apache Commons (Codec 1.11, Collections4 4.2, Compress 1.18, Logging 1.2, HttpClient 4.5.5, HttpCore 4.4.9)

### 4. Frontend
* **Core Technologies:** HTML5, CSS3, JavaScript (ES6)
* **Styling & Layout:** Bootstrap 5, Custom CSS, Responsive Dashboard Layouts
* **UI Plugins & Components:** jQuery, NiceSelect, Slick Slider, Feather Icons, FontAwesome

### 5. Build Tools & Development Environment
* **Build System:** Apache Ant (`build.xml`)
* **IDE:** Apache NetBeans 17+ / IntelliJ IDEA Ultimate

---

## IV. Project Structure

```text
swp391-jobseeker/
├── build.xml                    # Apache Ant build script
├── lib/                         # External JAR dependencies (JSTL, Mail, POI, SQL Server driver...)
├── nbproject/                   # NetBeans project configuration files
├── src/                         # Java source code
│   ├── conf/                    # Manifest and configuration resources
│   └── java/
│       ├── constant/            # Application-wide constants (e.g. CommonConst.java)
│       ├── controller/          # Servlet Controllers handling HTTP requests
│       │   ├── admin/           # Admin servlets (Dashboard, Company, Seeker, JobPosting, Feedback)
│       │   ├── recruiter/       # Recruiter servlets (JobPost, Company, Applicant, Verify, DownloadCV)
│       │   ├── seeker/          # Job Seeker servlets (CV, Education, Experience, Application, Jobs)
│       │   ├── AuthenticationController.java # Auth operations (Login, Register, Logout, OTP)
│       │   ├── HomeController.java           # Landing / Home page servlet
│       │   └── ViewDetailJobServlet.java     # Job details viewing
│       ├── dao/                 # Data Access Objects (DBContext, AccountDAO, JobPostingsDAO...)
│       ├── filter/              # Servlet filters for security & role access (Admin, Recruiter, Seeker)
│       ├── model/               # Entity models (Account, JobPostings, Recruiters, JobSeekers, CV...)
│       ├── utils/               # Utility helper classes (Email sender, etc.)
│       └── validate/            # Form and parameter validation helpers
├── web/                         # Web root (presentation layer & static assets)
│   ├── assets/                  # Static resources (CSS, JS, images, vendor libraries)
│   ├── META-INF/                # Context configuration
│   ├── WEB-INF/                 # Web application descriptor (web.xml) and bundled libraries
│   └── view/                    # JSP views categorized by module
│       ├── admin/               # Admin management pages
│       ├── authen/              # Authentication pages (login, register, forgot password, OTP)
│       ├── common/              # Shared components (headers, footers, sidebars, breadcrumbs)
│       ├── recruiter/           # Recruiter portal pages (dashboard, post job, review CVs)
│       ├── user/                # Job seeker portal pages (profile, CV, applied jobs, bookmarks)
│       └── home.jsp             # Main public landing page
└── README.md                    # Project documentation
```

---

## V. Installation & Local Development

### 1. Prerequisites
Ensure you have the following installed on your machine:
* **JDK 17 or higher**: [Oracle JDK 17](https://www.oracle.com/java/technologies/downloads/#java17) / [OpenJDK 17](https://adoptium.net/)
* **Apache Tomcat 10.1.x**: [Download Apache Tomcat 10.1](https://tomcat.apache.org/download-10.cgi) *(Do NOT use Tomcat 9 as the project depends on Jakarta EE / `jakarta.servlet` packages)*
* **Microsoft SQL Server**: With SQL Server Management Studio (SSMS)
* **IDE**: [Apache NetBeans 17+](https://netbeans.apache.org/) *(Recommended)* or **IntelliJ IDEA Ultimate**

---

### 2. Database Setup
1. Launch **SQL Server Management Studio (SSMS)** and connect to your local SQL Server instance.
2. Open and execute the database script `DB_NewV6.sql` (found in the project directory/parent folder).
3. Confirm that the `JobSeeker` database has been created with all tables and initial seed data.
4. Verify database credentials in [`src/java/dao/DBContext.java`](file:///d:/Nen/SWP391/swp391-jobseeker/src/java/dao/DBContext.java):
   ```java
   String username = "sa";
   String password = "123";
   String url = "jdbc:sqlserver://localhost:1433;databaseName=JobSeeker";
   ```
   *If your SQL Server uses a different port, username, or password, update them accordingly in `DBContext.java`.*

---

### 3. Running with Apache NetBeans (Recommended)
1. Open **Apache NetBeans**.
2. Go to **File > Open Project...** and select the `swp391-jobseeker` folder.
3. Configure **Apache Tomcat 10.1**:
   * Navigate to the **Services** tab (window) > right-click **Servers** > choose **Add Server...**
   * Select **Apache Tomcat or TomEE** and click **Next**.
   * Browse to your Tomcat 10.1 installation directory, provide manager credentials (if configured), and click **Finish**.
4. Configure Project Properties:
   * Right-click the **`swp391-jobseeker`** project > select **Properties**.
   * Under **Run**:
     * **Server**: Select your **Apache Tomcat 10.1**.
     * **Java EE Version**: Select **Jakarta EE 10 Web**.
   * Under **Libraries**:
     * Ensure **Java Platform** is set to **JDK 17**.
     * Check that all required JARs in `lib/` are included in the Compile classpath.
5. Build and Deploy:
   * Right-click the project > select **Clean and Build**.
   * Right-click the project > select **Run** (or press `F6`).
6. Access the application in your browser:
   ```
   http://localhost:8080/swp391-jobseeker/home
   ```

---

### 4. Running with IntelliJ IDEA Ultimate
1. Open the project root `swp391-jobseeker` in IntelliJ IDEA.
2. Go to **File > Project Structure (`Ctrl + Alt + Shift + S`)**:
   * **Project**: Set SDK to **Java 17**.
   * **Libraries**: Click `+` > **Java** > select all `.jar` files inside the `lib/` directory.
   * **Facets**: Add **Web** facet pointing to the `web/` directory.
   * **Artifacts**: Add **Web Application: Exploded** from the Web facet.
3. Add a Run Configuration:
   * Click **Run > Edit Configurations...** > `+` > **Tomcat Server > Local**.
   * **Application server**: Select your Tomcat 10.1 path.
   * **Deployment** tab: Add `swp391-jobseeker:war exploded` with Application context `/swp391-jobseeker`.
4. Run the configuration to start Tomcat and preview the application.

---

© 2024 by SE1868-NJ - Group 4. All rights reserved.