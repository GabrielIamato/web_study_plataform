# Study Web Plataform

## Introduction

The web project was designed and developed by a team at the Industrial Technical School 'Prof. Isaac Portal Roldán' - UNESP (Bauru, Brazil) as a concluding project for the course, the specific project documentation is available at [project_documentation](project_documentation.docx.pdf). The objective of this website is to assist prep course students in obtaining a university position, and the development was directly accompanied by the company Intelecto Bauru. Thus, the platform provides materials, exercises, classrooms, essays, and other functionalities.

In this way, the goal is to develop an online content platform accessible via the web, featuring a variety of digital resources to ensure greater accessibility and ease of use.

On the developed platform, teachers and administrators will provide, in an organized and straightforward manner, educational materials for supplementary study, a bank of multiple-choice and essay questions, weekly essay submissions, periodic simulations, and facilitated access between students and on-duty teachers.

The management and learning software allows teachers, administrators, and even students to access the student’s progress. This progress will be assessed by tracking the student’s engagement with the lessons and the completion of the proposed questions in each activity, as well as checking the number of correct answers in the simulations conducted during the preparatory period.

## Technologies / Languages 
- Laravel (PHP Framework)
- JavaScript
- HTML
- CSS
- SQL
- Flask (Python Framework)
- Python (pandas, matplotlib)
- Figma
- Canva
- Photoshop
- Inkscape
- Git
- GitHub

## Features

### Student
  * **Materials**: Each material, sent by the teachers, is separated by one discipline and, more specifically, a subject, so the student can search exactly what they want, like the discipline Biology, subject Cytology.
    <br><br><img src="https://github.com/user-attachments/assets/5f47f804-50be-44ac-ae98-75c5e0a12d18" width="300"/><br><br>
    Disciplines page
    <br><br><img src="https://github.com/user-attachments/assets/744ff270-7aa9-4cd1-91b7-cc5c8e14ae9b" width="300"/><br><br>
    Classes / Subjects page
  * **Exercises**: The student can filter the multiple-choice exercises by year, type of selective process, discipline, and subject, so they can study the best exercises for their objectives.
     <br><br><img src="https://github.com/user-attachments/assets/49219fa6-ce5d-4ba2-bf3f-948147a0bfd1" width="300"/><br><br>
     Exercises page
  * **Essays**: The student can submit, edit, and delete one essay for each proposed assessment available on the website and also check the feedback from the teacher.
     <br><br><img src="https://github.com/user-attachments/assets/43a01bb8-273c-47d9-ac76-7b53185c7f5e" width="300"/><br><br>
     Submission of Essays page

### Teacher
  * **Menu**: Where the teacher can access the features.
    <br><br><img src="https://github.com/user-attachments/assets/937ddeed-663e-474a-b128-5074bb309636" width="300"/><br><br>
  * **Registration**: Disciplines, subjects, classes, essay themes, essay corrections, exercises, and alternatives.
    <br><br><img src="https://github.com/user-attachments/assets/9e78631a-d6ad-4480-b05a-bb6e1f290443" width="300"/><br><br>
    Exercises registration page (similar to the other registration pages)
  * **Listing, Edit, and Delete**: Disciplines, subjects, classes, essay themes, essays submitted by students, essay corrections, exercises, and alternatives.
   <br><br><img src="https://github.com/user-attachments/assets/959e4710-31e3-4899-88b5-cd2d65249419" width="300"/><br><br>
   Exercises listing page (similar to the other listing pages). Each can be edited by the first icon on the right and deleted by the second one.

### Admin 
  - The admin has access to the entire system, except the individual files and answers of each student. Therefore, they are responsible for creating access for the students, who can change their password by clicking "Esqueceu a Senha?", translated to "Forgot the Password?"

### Statistics 
- This part of the system is developed using Flask, a Python framework. Every time a student answers a question, the system saves their response in the database, and teachers can see charts of the responses, ensuring anonymity for students' responses and allowing teachers to direct study focus to subjects and topics that students are struggling with the most.
- Login
<br><br><img src="https://github.com/user-attachments/assets/bad103d8-becb-47b1-bcbb-bc7e00689cb4" width="300"/><br><br>
Login page (similar to the Laravel system shown above)
- Statistics pages: Teachers can select charts of correct and incorrect answers filtered by year's questions, university, discipline, and subject, by descending or ascending order of correct answers. There is also a timeline for the answers, so teachers can adjust their teaching methods based on the evolution of the students.
<br><br><img src="https://github.com/user-attachments/assets/223cca55-4d2b-4a19-88bf-02876985d04c" width="300"/><br><br>
Discipline's Chart

## Conclusion 

The platform developed by the team at the Industrial Technical School 'Prof. Isaac Portal Roldán' aims to enhance the learning experience of prep course students. By providing tailored educational resources, facilitating communication between students and teachers, and allowing for the monitoring of student progress, this project contributes significantly to the academic success of its users. The collaboration with Intelecto Bauru ensures that the platform meets the needs of both students and educators, making it an essential tool for those preparing for university admission.

## License

This project is licensed under the GNU General Public License V3.0, published by the Free Software Foundation.
