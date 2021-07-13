# Weekenders_APP
This repository includes the technical description from the team Weekenders of the Tech Challenge 2021 posted by  the Technical University of Munich.

## Weekenders App – iOS application for patient food ordering in hospitals
The food ordering process in many hospitals is still manually and takes a lot of time for the staff to complete. Therefore, we want to simplify and digitalize the food order process for Sana Clinics Munich. With the Weekenders App we provide an application for patients, which they can use on their personal mobile phone, to increase patient’s satisfaction and decrease staff’s workload.

### Development standards of this project
**Software:**
AdobeXD: https://www.adobe.com/de/products/xd.html
Optional AdobeXD Mobile App 

**Hardware:**
Optional: iPhone X (the Adobe XD file was optimized for an iPhone X)

## Story
Weekenders App is a software solution, which was developed by students of the Technical University of Munich during the Tech Challenge in the summer semester 2021. Business partner and provider of the challenge was Sana Clinics Munich. As patient food satisfaction is key to the recommendation of the hospital to friends and family Sana Clinics stated the challenge to develop a scalable, cost-efficient and patient centric hospital catering process. 

### What is the Weekenders App?
“99% of all patients cannot evaluate the medical quality of the treatment they receive (aside from pain level). Instead, oftentimes the whole stay is judged based on factors which can be assessed by them – the quality/timely delivery/accuracy of meals” – Sana Clinics
As most of the medical procedures and hospital stays at Sana Clinics are planned and not time critical (e.g., a patient decides to have a replacement knee), Sana Clinics heavily relies on patient recommendations for their hospital. To provide the patients with a pleasant food ordering process, we developed the Weekenders App.
The Weekenders App is planned to be an application for iOS and android mobile end devices. Based on several rounds of interviews our team decided on four key user needs our application should satisfy:

  -	Simplicity: Easy to use for everyone
  -	Integration: Integrable into the current systems
  -	Transparency: More information about the food for the patient
  -	Hybrid: Not fully replacing the human interaction

![image](https://user-images.githubusercontent.com/58587500/125456130-5dcfa624-fc67-4cf8-ab72-d42c473e0973.png)

### How does the Weekenders App work?
The Weekenders app will be implemented in the normal patient journey. When the patient has already scheduled a procedure, he/she will receive a QR code with all patient information together with additional information about the procedure itself. The patient can then sign-in to the Weekenders App before the actual hospital stay, can review all data and correct it if necessary. After checking the information for correctness, the patient will receive a short introduction to the functionalities of the app and how to use and access them. Thereafter, the patient can pre-order food for every day during their hospital stay. It is possible to switch options until the day before the actual food delivery. 
It is important to note that the Weekenders App is an addition to the normal food ordering process, not a replacement. By providing an easy way for the patient to order food, we want to increase transparency for the patient and reduce the time expenditure of hospital staff, so they can focus on their core tasks. 
It is important to note that the Weekenders App is an addition to the normal food ordering process, not a replacement. By providing an easy way for the patient to order food, we want to increase transparency for the patient and reduce the time expenditure of hospital staff, so they can focus on their core tasks. 

### Advantages of the Weekenders App
*For patients:*
Patients are provided with a simple to use application. The app delivers additional information about each menu, nutrition scores to compare different menus, and automatically excludes all options with ingredients the patient is allergic to. All this information is presented in an intuitive and transparent way. Additionally, the patient has an overview of all the ordered menus, so that incorrect orders can be avoided. 

*For service staff:*
Taking orders from patients is a time consuming and error-prone process. Language barriers and other factors may lead to incorrect orders, which then reflect negatively on the service staff. By reducing the number of patients who need the service staff to order their food, the service staff has more time to take orders from the remaining patients and thus minimize the frequency of errors. Moreover, the service staff has more time on their hand for other important tasks.

*For hospitals:*
Hospitals are enabled to decrease the amount of thrown away food, as patients only order menus they intend to eat. Furthermore, an improved food experience will lead to increased patient satisfaction. Hospital staff is relived and it is possible to achieve cost savings by reducing the number of FTEs needed for the food ordering process. 

## Build:
### Preparation:
How to recreate the Weekenders App:
When we started to build our prototype, we kept the end user, i.e. the patient, in the center of the process. Therefore, we highly recommend using an additional hardware device (e.g., an iPhone X) to simulate the patients experience with the Adobe XD prototype while using the application. 
The first step towards our finished prototype were sketches, which helped us define the key features of the application and a rough overview of the patient’s user journey within the app.

![Bildschirmfoto 2021-07-13 um 15 10 00](https://user-images.githubusercontent.com/58587500/125457372-6b8dd4b0-1e3f-4eec-822e-9725f94ea059.png)

To develop a functional prototype from our sketches in a fast and reliant way we used the software Adobe XD. 
In the following a complete overview of the Weekenders App is given. The high number of screens are a result of the attempt to better simulate the normal user flow of a patient to validate the product idea.

![image](https://user-images.githubusercontent.com/58587500/125457490-bb6f0aaf-d785-48e5-ae24-20e5a55edfd2.png)

Moving forward we are going to give a short description of each screen concept. As mentioned above, we implemented the same screens in different settings, but explaining every single screen will not provide further inside into our prototype. 
It is important to mention that we connected the screens with the prototype function of Adobe XD. This allows us to simulate a normal app flow for our testers. We will not mention every single connection between screens, but will provide a flowchart and the link to the Adobe XD file of our prototype to help understand the connections between all the options our application provides.

### Welcome and Intro
We first welcome our patient and give a short explanation of the core functionality and features of the application. The patient can click through each screen or skip the intro and directly start with the sign-in and registration process.

![image](https://user-images.githubusercontent.com/58587500/125457606-6a6a79aa-f3de-4c2f-ba04-ff10c188b12e.png)

### Sign in and Registration
After the welcome and intro screens, the patient can sign in into the application. Here we implemented one of our unique selling propositions (USP) features compared to other solutions. As the hospital has a lot of information about the patient (e.g., allergies, duration of stay, etc.), the patient will be provided by the hospital staff with a QR code or activation code, which contains all this information. As a result, the patient only needs to scan or type in the activation code to have all the relevant information in the systems. Of course, it is still possible to alter information for the patient, if needed.

![image](https://user-images.githubusercontent.com/58587500/125457872-f6a98f13-6a75-429a-8e49-a0e7fce01c3f.png)

### User tutorial
To help the patient with the functionalities of the application, we present a short introduction to the most important features of our prototype. This should further push the patient satisfaction and willingness to use the application during and before the actual stay at the hospital. The patient can always revisit the user tutorial at a later point if some functionalities become unclear.

![image](https://user-images.githubusercontent.com/58587500/125458859-19f6a7d2-171d-4d44-a852-9e2ffecbd51a.png)

![image](https://user-images.githubusercontent.com/58587500/125458872-2b9339e5-dc1a-4377-a51f-a72446a2c4a9.png)



### Dashboard
The dashboard is the beating hearth of our application. From here the patient can reach all the functionalities we provide in the Weekenders App. The dashboard has two different appearances, depending on whether the patient has already ordered food for the day or still has to order breakfast, lunch, and dinner. On the top left the user can open the sidebar menu with further details about the profile and links to the feedback and FAQ. The calendar enables the patient to switch between the days of the hospital stay and lets the patient preorder food for the upcoming days. The patient is also only able to order food for days during his stay. If the patient has not ordered food yet, a time reminder is in the center of the screen is shown. Otherwise, an overview of all the ordered menus is provided. The patient can switch these menus until the deadline of the order process (e.g., until the day before food delivery). The bottom two buttons will bring the patient to the feedback and FAQ section of the application. In general, we decided to use rather big buttons, as most of the patients are between 60 and 85. Therefore, the dashboard must be clearly arranged and simple to understand.


![image](https://user-images.githubusercontent.com/58587500/125458076-786a2618-e37c-44c3-b6f5-d78baa6ffa11.png)

### Sidebar
The sidebar provides similar options as the dashboard, but in a more comprehensive way. Additionally, the patient can edit the user profile.

![image](https://user-images.githubusercontent.com/58587500/125458141-9598d0f4-6495-4eb9-afa7-6ff7cc51f69f.png)

### Menu selection
The menu selection is the core feature of the Weekender app. The patient can order breakfast, lunch, and dinner. Furthermore, it is possible to order additional components to each meal ranging from drinks to soup and dessert. The patient is always guided through all three meals in one go. For a faster indication of the healthiness of each meal we implemented a nutrient score next to each menu and additional component. When the patient wants additional information about the ingredients of a meal it is possible to click on the info icon next to each menu and a new screen with a transparent presentation of ingredients and allergens will appear. At the end of the menu selection, the patient sees an overview of all the menu selections to further decrease the number of wrongly ordered food.

![image](https://user-images.githubusercontent.com/58587500/125458213-65aef09d-f7ae-405d-b852-3a3a5a52eae0.png)
![image](https://user-images.githubusercontent.com/58587500/125458224-88f00e2d-7c94-406a-af06-cd9a31e8b2e0.png)
![image](https://user-images.githubusercontent.com/58587500/125458237-6aa5432b-ca11-4661-b552-a0277d423da0.png)

### FAQ and Feedback
To provide additional transparency to our patient and further improve the food ordering process by receiving feedback from the patients, we included a feedback and a FAQ section into the application. In the feedback section the patient can choose between 1 and 5 stars and provide additional comments to the food ordering process. We deployed a section for frequently asked questions (FAQs) to give answers to the most urgent problems of the patients. Additionally, a link to the user tutorial is provided. Both, the feedback and the FAQ section, will guide the patient back to the dashboard after completion.

![image](https://user-images.githubusercontent.com/58587500/125458319-9e401d50-4f16-4970-852e-ac8de30ddcd5.png)

### Further functions
The more patients use the application, the more the service stuff is relieved. Therefore, we implemented a notification function to remind patients to order their food for the day. 
Another feature is the possibility to exclude all the menus, which contain any ingredients the patient is allergic to. As we have all the relevant patient data due to the QR Code, we know which meals are suitable for each patient and can individualize the offer for each patient during the hospital stay.

![image](https://user-images.githubusercontent.com/58587500/125458783-7ed6c1d0-afef-42c0-84e4-16ed98f68c19.png)


### Flowchart
The following flowchart represents the flow of a patient in the Weekenders app. After the welcome and registration, the patient can navigate from the dashboard to every available function. Keep in mind that a box is not always equal to a single screen but represents the predefined working path of our users.

![Bildschirmfoto 2021-07-13 um 15 21 55](https://user-images.githubusercontent.com/58587500/125459148-7bc10e57-48a2-4e3a-92c9-c947bc44a402.png)


The following flowchart represents the flow of a patient in the Weekenders app. After the welcome and registration, the patient can navigate from the dashboard to every available function. Keep in mind that a box is not always equal to a single screen but represents the predefined working path of our users.

## Code
### Flutter
This is the flutter code for the dashboard screen to illustrate how our app was implemented from the AdobeXD prototype which focuses on the design part to the actual app. The advantage of flutter code is that you can run it on Android as well as iOS and web as well.

### Dashboard
Implementation of the structure of the dashboard-page. Consisting of five different boxes including different parameters such as sizes and colors (picture below). The code is shown as the example of the dashboard.

1. Header
2. Date
3. Menu
4. FAQ
5. Feedback

Bildschirmfoto 2021-07-13 um 15.25.53![Bildschirmfoto 2021-07-13 um 15 25 53](https://user-images.githubusercontent.com/58587500/125459798-9ceb0f65-8ecf-4ded-b6db-564c298ae408.png)

### Desing Header
White box with sideboard -and profile-icon and the text “Hallo Stefan!”:

![image](https://user-images.githubusercontent.com/58587500/125459958-2fdf2bd8-ccfd-4982-91c5-71056da393d4.png)

Setting the size of the header box and the color:

![image](https://user-images.githubusercontent.com/58587500/125459999-78cfe3d1-a04c-49f7-99a4-cf88c9d72223.png)

Creating sidebar icon:

![image](https://user-images.githubusercontent.com/58587500/125460127-1c6564e9-e809-468c-8b85-e373f05ade05.png)

Creating profile (consisting of circle, heda and shoulder):

![image](https://user-images.githubusercontent.com/58587500/125460317-f2712881-08ed-4157-b2ae-e2cf9101aca9.png)

Adding text "Hallo Stefan":

![image](https://user-images.githubusercontent.com/58587500/125460364-7bcfe5be-84bf-465b-bd4c-ece0fd144b4d.png)

### Design Date
The date selection component consists of the actual selected date with a calendar-icon and the selection of the upcoming days.

![image](https://user-images.githubusercontent.com/58587500/125460422-7277186c-a618-4263-be86-dac451856ad9.png)

Setting the size of the box and the color:

![image](https://user-images.githubusercontent.com/58587500/125460472-83134413-f875-4298-817a-e4c73da94a81.png)

Creating the acutal selected date and the icon:

![image](https://user-images.githubusercontent.com/58587500/125460513-e477fd2e-efc9-4f18-b36c-46cb17322e87.png)

Adding the days and the ticking boxes:

![image](https://user-images.githubusercontent.com/58587500/125460557-877512b7-dffd-415f-a5ec-3c2ed2a158d4.png)
![image](https://user-images.githubusercontent.com/58587500/125460572-b0e403b6-126c-467d-8a44-f3580d383617.png)

### Menu
The chosen menu consists of the meals which have been selected for breakfast, lunch and dinner:

![image](https://user-images.githubusercontent.com/58587500/125460628-c93a960c-71d7-4bbf-b617-09f1d7ae4628.png)

Example "Breakfast-Selection"

![image](https://user-images.githubusercontent.com/58587500/125460666-d0640dd8-64ab-435a-947d-5189358982c1.png)

Nutrition Score:

![image](https://user-images.githubusercontent.com/58587500/125460725-1e45f69e-7ed9-48be-a45e-4f671e29fbe6.png)

Meat icon:

![image](https://user-images.githubusercontent.com/58587500/125460755-c8c24174-6c0b-4ab7-9f13-6749da025ef2.png)

### Design FAQ

![image](https://user-images.githubusercontent.com/58587500/125460788-b9933595-222b-40ad-84c8-8acd2457d125.png)
![image](https://user-images.githubusercontent.com/58587500/125460816-4d4baf67-c905-4161-a011-b8d663a1f6f1.png)

### Design Feedback

![image](https://user-images.githubusercontent.com/58587500/125460882-17b73d88-111e-44c8-bf27-a36f461932b9.png)
![image](https://user-images.githubusercontent.com/58587500/125460903-3257f61b-fd5d-4d45-9468-1f0e32364be9.png)


