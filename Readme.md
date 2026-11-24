DEPARTMENT OF SOFTWARE ENGINEERING*

SOFTWARE CONFIGURATION MANAGEMENT (SCM)
PRACTICAL ASSIGNMENT: OPEN-SOURCE SOFTWARE MODIFICATION AND VERSION CONTROL USING GIT AND GITHUB

*Course:* Software Configuration Management
*Number of Students:* 4
*Submission Platform:* GitHub
*Lecturer's GitHub Username:* eleiflorence

### 1. ASSIGNMENT OBJECTIVE

The purpose of this assignment is to provide students with practical experience in using Git and GitHub for software configuration management.

Rather than developing applications from scratch, each student is required to select an assigned open-source software project, obtain its source code, modify existing features, track changes and submit their contributions through GitHub.

Students are expected to demonstrate their understanding of version control, collaborative software development, branching, merging, commits, repository management and Pull Requests.

### 2. ASSIGNMENT DISTRIBUTION

Each student has been assigned a different open-source software project.

*STUDENT 1: STUDENT MANAGEMENT SYSTEM*

Source code:
https://github.com/aashi1310/student-management-system

Required modifications:
1. Improve the student registration interface.
2. Add student search functionality.
3. Improve student record display.
4. Implement additional validation for student information.

*STUDENT 2: ATTENDANCE MANAGEMENT SYSTEM*

Source code:
https://github.com/theshivajisingh/Attendance-system

Required modifications:
1. Improve the attendance recording interface.
2. Add date-based attendance filtering.
3. Improve attendance reports.
4. Implement attendance percentage calculation.

*STUDENT 3: LIBRARY MANAGEMENT SYSTEM*

Source code:
https://github.com/shriramdawange/Library-Management-System

Required modifications:
1. Improve the book registration interface.
2. Add book search functionality.
3. Improve book borrowing and returning features.
4. Implement book availability status.

*STUDENT 4: SCHOOL MANAGEMENT SYSTEM*

Source code:
https://github.com/Erhanalp35/school-management-system-web-template

Required modifications:
1. Improve the student management interface.
2. Add teacher management features.
3. Improve the attendance interface.
4. Implement or improve grade management features.

Note: Students must inspect the project documentation and licence before making modifications. If an assigned repository is unavailable or does not support the required modification, contact the lecturer before selecting an alternative.

### 3. REQUIRED PRACTICAL ACTIVITIES

Every student must perform the following activities independently.

*Activity 1: Repository Forking*
- Open your assigned GitHub repository.
- Read the README and licence.
- Fork the repository into your personal GitHub account.

*Activity 2: Cloning the Repository*

Open Visual Studio Code terminal and execute:

bash
git clone YOUR_FORKED_REPOSITORY_URL


Navigate into the project folder.

*Activity 3: Git Configuration*

Configure your Git identity:

bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"


*Activity 4: Branch Management*

Create your own development branch:

bash
git switch -c student-modifications


*Activity 5: Software Modification*

Modify at least three existing features in your assigned application.

You must make meaningful changes to the source code and ensure that the application runs.

*Activity 6: Commit Management*

Stage and commit your changes:

bash
git add .
git commit -m "Implemented software improvements"


Make meaningful commits throughout the development process.

*Activity 7: Push Changes to GitHub*

bash
git push -u origin student-modifications


*Activity 8: Pull Request Submission*

Submit a Pull Request to the lecturer's designated assignment repository.

The Pull Request must clearly explain:
- What you modified.
- Why the modifications were necessary.
- The files you changed.
- The new features implemented.

### 4. VERSION CONTROL REQUIREMENTS

Your practical demonstration must show evidence of the following:

1. Forking an existing open-source repository.
2. Cloning the repository.
3. Creating a development branch.
4. Modifying existing source code.
5. Tracking changes using Git.
6. Making at least three meaningful commits.
7. Pushing changes to GitHub.
8. Submitting a Pull Request.
9. Demonstrating the modified application.
10. Explaining how Git helped you manage the development process.

### 5. SUBMISSION REQUIREMENTS

Each student must submit the following:

1. Full name and registration number.
2. Assigned project title.
3. Original open-source repository link.
4. Forked GitHub repository link.
5. GitHub username.
6. Screenshot of the created development branch.
7. Screenshot of commit history.
8. Screenshot of the modified application.
9. Pull Request link.
10. A brief practical report explaining the modifications and challenges encountered
