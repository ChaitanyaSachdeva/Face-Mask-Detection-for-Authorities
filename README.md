# Face-Mask-Detection-for-Authorities

SafetyScan is a revolutionary product which fits really well with our current global pandemic scenario. Safety Scan is a website which can be used by governments or corporate organizations having >20 people in a room to monitor the use of facemasks by the people. It uses computer vision and CNN to detect the face mask in a live streaming platform, and utilizes Django to connect the webpage with the live streaming service. This will help better manage safety standards and precautions and help flatten the pandemic curve.

In addition to the face detection system, the SafetyScan website provides detailed stats and analysis of the pandemic, for regular users to track the spread of the virus in their location. SafetyScan is looking to provide a wholesome package, engineered towards both regular users and duty personnel.


# SafetyScan 1.0
1. We made a basic Neural networks model(CNN) for detecting wheather the user have worn a mask or not.


2. Now for testing the live implementation of th CNN model made, open Detect_mask_video file(python file), import all the libraries 
written in the CNN model code.


3.Also download the dataset required to train this model using command line: python train_mask_detector.py --dataset dataset


4.Now to execute the model on the website open the website by streamapp/templates/streamapp/home.html


5. This is the final prototype  made and ready to be implemented, it contains live stream on the security camera based on which the authorities can allow the access or not, also it has a full view dashboard that contains all the information related to Covind-19 such as live stats on the active cases of this pandamic and the current news, updates, related to the pandamic. It is a one stop solution for everyone - the authorities, and the users to be updated with each on the major happening around the world related to this pandamic.


6. This live stream feature is execlusively for the concerned authorities to keep a check on every individual enterring through the entrance in the respective building. In the live stram you can clearly see that the person is wearing a mask or not for the safety purpose in this pandamic.

You can also look at the overall overview of our project in the file HackJaipur.pdf
