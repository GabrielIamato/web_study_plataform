
# Introduction

The web project was design and desenvolved by a team at the Industrial Technical School 'Prof. Isaac Portal Roldán' - UNESP (Bauru, Brazil), and the specific project documentation is avaliable at [project_documentation](project_documentation.docx.pdf). The objective of this website is assistant prep course students to get a university position, and the development was directly accompanied by the company Intelecto Bauru. So , the plataform provide materials, exercises, classrooms, essays, and other funcionalities.

In this way, the goal is to develop an online content platform accessible via the web, featuring a variety of digital resources to ensure greater accessibility and ease of use.

On the developed platform, teachers and administrators will provide, in an organized and straightforward manner, educational materials for supplementary study, a bank of multiple-choice and essay questions, weekly essay submissions, periodic simulations, and facilitated access between students and on-duty teachers.

The management and learning software allows teachers, administrators, and even students to access the student’s progress. This progress will be assessed by tracking the student’s engagement with the lessons and the completion of the proposed questions in each activity, as well as checking the number of correct answers in the simulations conducted during the preparatory period.

# Tecnologies / Languages 
- Laravel (Framework PHP)
- Javascript
- HTLM
- CSS
- SQL
- Flask (Framework Python)
- Python (pandas, matplotlib)
- Figma
- Canva
- Photoshop
- Inkscape
- Git
- Github

# Features
## Student
  * <b>Materials</b>: each material, send by the teachers, is separetad by one discipline and , more specific, a subject, so the student can search exatactaly what he want, like the discipline biology, subject citology.
    <br><br><img src="https://github.com/user-attachments/assets/5f47f804-50be-44ac-ae98-75c5e0a12d18" width="300"/><br><br>
    Disciplines page
    <br><br><img src="https://github.com/user-attachments/assets/744ff270-7aa9-4cd1-91b7-cc5c8e14ae9b" width="300"/><br><br>
    Classes / Subjects page
  * <b>Exercises</b>: the student can filter the multiple-choice exercises by year, type of selective process, discipline and subject, so he can study the best exercises for his objective
     <br><br><img src="https://github.com/user-attachments/assets/49219fa6-ce5d-4ba2-bf3f-948147a0bfd1" width="300"/><br><br>
     Exercises page
  * <b>Essays</b>:  the student can send, edit and delete one essay by each propose avaliable at the website, and also check the feedback of the teacher
     <br><br><img src="https://github.com/user-attachments/assets/43a01bb8-273c-47d9-ac76-7b53185c7f5e" width="300"/><br><br>
     Send of Essays page
## Teacher
  * <b>Menu<b>: where the teacher can acess the features
    <br><br><img src="https://github.com/user-attachments/assets/937ddeed-663e-474a-b128-5074bb309636" width="300"/><br><br>
  * <b>Registration<b>: disciplines, subjects, classes, essays theme, essays correction, exercises and alternatives.
    <br><br><img src="https://github.com/user-attachments/assets/9e78631a-d6ad-4480-b05a-bb6e1f290443" width="300"/><br><br>
    Exercises registration page (similar to the other registration pages)
  * <b>Listing, edit and delete<b>: disciplines, subjects, classes, essays themes, essays send by the students, essays correction, exercises and alternatives.
   <br><br><img src="https://github.com/user-attachments/assets/959e4710-31e3-4899-88b5-cd2d65249419" width="300"/><br><br>
   Exercises listing page (similar to the other listing page). Each one can be edit by the first icon on the right, and deleted by the second one.
## Admin 
  - The admin has access to all the sistem, except the individual files and answers of each student. So, he is responsable to create an acess to the student, that can change this password by clicking "Esqueceu a Senha?", translate to "Forgot the Password?"

## Statistics 
- This part of the system is develop by using Flask , a framework of Python. Every time that a student response a question, the system saves his response at the database and the teachers can see charts of the responses, ensuring anonymity for students' responses, and allowing teachers to direct study focus to subjects and topics that students are struggling with the most.
- Login
<br><br><img src="https://github.com/user-attachments/assets/bad103d8-becb-47b1-bcbb-bc7e00689cb4" width="300"/><br><br>
Login page (similar to the Laravel system shown above)
- Statistics pages: the teachers can select charts of write and wrong answers filtered by year's question, university, discipline and subject, by number decrescent or crescent of write answers. There also avaliable a temporal line to the answers, so the teachers can change or not the studying method by the evolution of the students.
<br><br><img src="https://github.com/user-attachments/assets/223cca55-4d2b-4a19-88bf-02876985d04c" width="300"/><br><br>
Discipline's Chart


# License
This project is licensed under the GNU General Public License V3.0, published by the Free Software Foundation.
