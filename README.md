# Android-Classpath
Adding Classpath on new Android Studio Versions



I was having issue to where should I add classpath in newer Android Versions 

Here is the solution

Step 1: Open Android Studio

Step 2: Syncing Gradle

Step 3: Open Gradle Script 

Step 4: Open build.gradle (Project: Your Application Name)   
![image](https://user-images.githubusercontent.com/101948486/217161012-e6fa2244-6046-4563-a247-a54bb1da02e1.png)


Step 5: An Interface will popup 
![image](https://user-images.githubusercontent.com/101948486/217161222-b7617894-b997-45a5-899a-7350909e45ef.png)


Step 6: now add the path under plugins
(id 'com.google.gms.google-services' version "4.3.10" apply false) 

Step 7: Click on Sync Now
![image](https://user-images.githubusercontent.com/101948486/217161415-8b9165ad-025d-4611-8cd2-ded011b524d9.png)

Step 8: The project will syncronize and is able to use 
Cheers :)
