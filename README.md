# FirebaseTrial

PROCEDURE :
1)Create a new procet in Android Studio with Empty Activity.
2)Login to Firebase (https://firebase.google.com/) with your google account.
3)Create new Project.
  Enter the project name.
  Enable Google Analytics for this project.
  Select default account for Firebase.
  Create project.
4)Then you have your own Firebase console for the project.
5)Select Android and register your app.
6)Download the json file and add in Project >> app.
7)Add Plugins and Dependency file in build.gradle file.
 And now the connection is established.
 
TO TEST :
1)Create a Database >> build >> Firestore Database.
  Create Database >> Test mode >> Enable
2)Add FirebaseFirestore dependency (implementation 'com.google.firebase:firebase-firestore').
3)Initialize a Map.
4)Add collection(Map name) to the FirebaseFirestore that you created.
5)Add addOnSuccessListener and addOnFailureListener.
6)Call getInstance() before you add the data.

PROBLEMS FACED :
Added wrong Dependency for FirebaseFirestore.Got the right one from Firebase site.
