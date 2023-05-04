# **Gurukul**

**Project Description**:</br>
 It is an one stop solution for students of WCE, Sangli which solves multiple problems like uploading assignments, dowloading 
 notes and documents, marking the attendance, etc. It also has a forum where students can interact with other students in case
 they have some doubt about the college.
 For the students, we have created an android application for students and a website for admins where they can assign assignments,
 upload notes, documents, etc.

 We have also created a whatsapp bot for reminding the students about the assignments submission. It can also provide some coding
 problems if student asks for it.

 For the attendance, we have used the location of students so that only those student who are present inside class can give attendance using
 the pin set by teacher. If teacher is taking online session, he can choose not to add location in the session.

 
 ![Snapshots](https://firebasestorage.googleapis.com/v0/b/gurukul-5a194.appspot.com/o/WhatsApp%20Image%202022-06-25%20at%207.30.03%20PM.jpeg?alt=media&token=8127e5cf-1133-4599-8399-8bf64c127bc3)

Functionality and concepts used:
 * **Libraries**: Glide for displaying images, volley for making network requests
 * **Layouts**: Constraint Layout, Linear Layout, Relative Layout, CardView
 * **Recycler View**: To display subject list, assignments, notes, documents list Recycler View is used
 * **SharedPreference**: To store authentication token, username of students in local storage
 * **Firebase Storage** : For uploading the assignments, notes, documents
 * **Fragments** : There is a bottom navigation and user can navigate between different fragments like profile, home and Forum. 
       For navigating in different fragments, we have used navigation component

How to use our project : 
* **App Link** : https://drive.google.com/drive/folders/1Ujk4Znb_sX9-pqH7dZeF2OAXMjfSV3yU </br>
* **WEBSITE**: 1.Clone this repository 2.Open Gurukul-web directory in your terminal 3.run "npm i" command 4.run "npm start" command to start the admin portal 5.superadmin credentials: username:'wcegurukul',password : 'wcegurukul' 6.You can create a admin account from super admin.</br>
