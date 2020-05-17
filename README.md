# Welcome to Examedic

![UI](https://raw.githubusercontent.com/wise-crab/wise-crab.github.io/Cristian/screens/logo.png)

# What does ExaMedic do?
The Laboratory (bacteriologist) wants a proper channel where can have a straight flow of information among him and the Doctor with the patient supervision. Due to the fact that the laboratory is aware that the patient wants to have a track report of the process, the laboratory developed Examedic in order to satisfy its clients informing on real-time about when his result of exam is available and a proper track of their information. 

There are three roles playing in this project:
    • Admin
    • Doctor
    • Bacteriologist
    • Patient


## Functionality Statements
      
## Description of the project at the functional level (requirements):
  This application has different types of user and role-based and it will take actions that will be reflected and directly linked to the rest of  user's role's workflow.

  The specific functions vary depending upon the user's role:

  ### Patient:
  - The patient can get a display charts about their latest clinical examination performed, this documents include dates and are online
  ![UI](https://raw.githubusercontent.com/wise-crab/wise-crab.github.io/Cristian/screens/Dekstop_1366px_=_–_2.png)

  - The patient can download the results in PDF format individually or select multiple results and download them together in the same document

  - In case that the an examination's result is still not available, the patient gets the examination's names that he performed and are awaiting for the Bacteriologist's results, the app displays an inactive download icon  and an unavailability result indicator message

  ### Doctor:
  - This profile is up to set the clinical examinations that a patient must perform and link them in the system

  - The doctor gets a display of a search engine that let him/her search a patient by ID and view his/her contact deatils and medical history. In this screen, the doctor can link a clinical examination to a patient, the App provides to the Doctor a window that let him/her to select from a preloaded list the different clinical examinations he/she could perform and add them to the patient one by one

  - When the doctor links a clinical examination to a patient, the patient is already able to see these examination from his/her profile's home screen even in case the results are unavaliable

  - In case the patient has logged in at the time the exams are being linked to him/her, he/she receives a near-real-time notifications to refresh the app and right after be able to track them

  ### Bacteriologist:
  - This health professional's profile gets a search engine that allows to the Bacteriologist search patient by his/her ID and pops up a window that enables to the Bacteriologist enter the clinical exam's results' data linked to the selected patient

  - Once the results are available, these are available to be downloaded from the patient's profile

  - Once the results get an available status and in case the patient is logged in,the app notices to the patient from his/her profile that the clinical exam results are ready to be downloaded

  ### Admin:
  - This profile must only be assigned to administrative personnel and it is who can get, create, delete and update the information from other users regardless of their role (including other administrators) to manage them. 

  - The admin can make a bulky upload from an .csv document to have multiple user's signs up log

  - Once an new user is created, he/she is going to receive an e-mail with his/her login credentials attached

  # General requirements
  - By creating an new user regarless of the role, the Admin must register the user's ID, name, last name, email and Phone number in order to ensure the data consistency

  - Every user has the following username structure: name.last_name.last4DigitsID 
    Ex: maria.jaramillo.4567 

  - Whenever an user is created the app verify its name does not match with an existing one. In case the assigned username match it, these last 4 digits is going to be randomly assigned

  - Every user profile is secured with its password encrypted

  - Every user signs-in in the same Login screen in the Laboratory's website regardless its role

  - Every single user in this app was signed-up by an Admin, it guarantees safety of DB content

## User Interface screens

### Login:
  #### mobile < 479px
  ![UI](https://raw.githubusercontent.com/wise-crab/wise-crab.github.io/Cristian/screens/Mobile_360px.png)
  #### 480px < Mobile < 767px
  ![UI](https://raw.githubusercontent.com/wise-crab/wise-crab.github.io/Cristian/screens/B_Mobile_480px-767px.png)
  #### 768 < Tablets < 1023px
  ![UI](https://raw.githubusercontent.com/wise-crab/wise-crab.github.io/Cristian/screens/Tablet_768px-1023px.png)
  #### 1024 < Laptops < 1364px
  ![UI](https://raw.githubusercontent.com/wise-crab/wise-crab.github.io/Cristian/screens/Laptop_1024px-1365px.png)
  #### 1365px < Desktops
  ![UI](https://raw.githubusercontent.com/wise-crab/wise-crab.github.io/Cristian/screens/Dekstop_1366px_=.png)


### Admin-dashboard
  #### mobile < 479px
  ![UI](https://raw.githubusercontent.com/wise-crab/wise-crab.github.io/Cristian/screens/Mobile_360px_–_6.png)
  #### 480px < Mobile < 767px
  ![UI](https://raw.githubusercontent.com/wise-crab/wise-crab.github.io/Cristian/screens/B_Mobile_480px-767px_–_5.png)
  #### 768 < Tablets < 1023px
  ![UI](https://raw.githubusercontent.com/wise-crab/wise-crab.github.io/Cristian/screens/Tablet_768px-1023px_–_5.png)
  #### 1024 < Laptops < 1364px
  ![UI](https://raw.githubusercontent.com/wise-crab/wise-crab.github.io/Cristian/screens/Laptop_1024px-1365px_–_5.png)
  #### 1365px < Desktops
  ![UI](https://raw.githubusercontent.com/wise-crab/wise-crab.github.io/Cristian/screens/Dekstop_1366px_=_–_6.png)


### Doctor-dashboard
  #### mobile < 479px
  ![UI](https://raw.githubusercontent.com/wise-crab/wise-crab.github.io/Cristian/screens/Mobile_360px.png)
  #### 480px < Mobile < 767px
  ![UI](https://raw.githubusercontent.com/wise-crab/wise-crab.github.io/Cristian/screens/B_Mobile_480px-767px_–_1.png)
  #### 768 < Tablets < 1023px
  ![UI](https://raw.githubusercontent.com/wise-crab/wise-crab.github.io/Cristian/screens/Tablet_768px-1023px_–_1.png)
  #### 1024 < Laptops < 1364px
  ![UI](https://raw.githubusercontent.com/wise-crab/wise-crab.github.io/Cristian/screens/Laptop_1024px-1365px_–_1.png)
  #### 1365px < Desktops
  ![UI](https://raw.githubusercontent.com/wise-crab/wise-crab.github.io/Cristian/screens/Dekstop_1366px_=_–_1.png)


### Bacteriologist-Dashboard
  #### mobile < 479px
  ![UI](https://raw.githubusercontent.com/wise-crab/wise-crab.github.io/Cristian/screens/Mobile_360px.png)
  #### 480px < Mobile < 767px
  ![UI](https://raw.githubusercontent.com/wise-crab/wise-crab.github.io/Cristian/screens/B_Mobile_480px-767px_–_1.png)
  #### 768 < Tablets < 1023px
  ![UI](https://raw.githubusercontent.com/wise-crab/wise-crab.github.io/Cristian/screens/Tablet_768px-1023px_–_1.png)
  #### 1024 < Laptops < 1364px
  ![UI](https://raw.githubusercontent.com/wise-crab/wise-crab.github.io/Cristian/screens/Laptop_1024px-1365px_–_1.png)
  #### 1365px < Desktops
  ![UI](https://raw.githubusercontent.com/wise-crab/wise-crab.github.io/Cristian/screens/Dekstop_1366px_=_–_1.png)


### Patient-Dashboard
  #### mobile < 479px
  ![UI](https://raw.githubusercontent.com/wise-crab/wise-crab.github.io/Cristian/screens/Mobile_360px_–_2.png)
  #### 480px < Mobile < 767px
  ![UI](https://raw.githubusercontent.com/wise-crab/wise-crab.github.io/Cristian/screens/B_Mobile_480px-767px_–_1.png)
  #### 768 < Tablets < 1023px
  ![UI](https://raw.githubusercontent.com/wise-crab/wise-crab.github.io/Cristian/screens/Tablet_768px-1023px_–_1.png)
  #### 1024 < Laptops < 1364px
  ![UI](https://raw.githubusercontent.com/wise-crab/wise-crab.github.io/Cristian/screens/Laptop_1024px-1365px_–_1.png)
  #### 1365px < Desktops
  ![UI](https://raw.githubusercontent.com/wise-crab/wise-crab.github.io/Cristian/screens/Dekstop_1366px_=_–_2.png)

## Dependences
  




This Web App allow an easy way to exchange the Results of exams Analysis.

### What are posible failure conditions and how the user could handle it?
if the user ask for a no avaliable route link, the app pops an a 404 screen warning.

### What one-time operations are done at the First execution?


### If the User creates any kind of entries, what are the limitations?


## Milestones


## Software Design Specification Example



# Statements


  
