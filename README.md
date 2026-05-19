# Patient view model 

### Add patient Model
****


This is a view model  which  represents the presentation logic of a system, not the core business logic. 

It acts as a bridge between the User Interface (the View) and the underlying data layer (the Model). 


## **This PatientViewModel is responsible for:**

1.Uploading an image to Cloudinary

2.Getting the returned image URL

3.Saving patient data to Firebase Realtime Database

4.Showing success/failure messages using Toast

5.Navigating to another screen using NavController

6.Running all heavy work in background threads using Coroutines


