# PalmTracking

This is a Palm tracking python program. It uses machine learning to track the movements of your palm using 21 reference points. It is made with the help of mediapipe(https://google.github.io/mediapipe/solutions/hands) a library built by google.

Download mediapipe with the following command- 

  ```pip install mediapipe```

The palm is tracked using 21 reference points. These reference points are predefined. The reference points are as follows-

![image](https://user-images.githubusercontent.com/47482433/121740885-5bd25a80-cb1b-11eb-8501-9270fb396746.png)

After executing the program a camera window will open up, you will be able to see your palm/s being tracked in this camera window. The program is able to track only 2 palms at a time. This program also shows the frame rate in the top left corner of the camera window once the program is executed.

Libraries used-> opencv(cv2), mediapipe, time.

Image of the output-

![palm_img](https://user-images.githubusercontent.com/47482433/121741927-cafc7e80-cb1c-11eb-86b4-122df81206f1.jpeg)
