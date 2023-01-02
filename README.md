# Bicep Rep Counter

A Bicep Rep counter kernel built using OpenCV and Mediapipe framework. Each rep is calculated when the angle between 3 landmarks (Arm , Wrist , Shoulder) crosses a threshold value. Rep counter works for one hand reps and also when with two hands. Check my kernel for a detailed explanation.

## MediaPipe Landmarks
![pose_tracking_full_body_landmarks](https://user-images.githubusercontent.com/97725657/210265393-b75238f8-f61c-4665-abc3-2a3bddd1eca5.png)


## Dependencies

- Mediapipe 
- Pandas
- Numpy
- OpenCV 

## Sample Output

**Left Arm SOLO**

https://user-images.githubusercontent.com/97725657/210265554-30eaf2f2-9579-4eb8-ae8b-380227726eaa.mp4

**Right Arm SOLO**

https://user-images.githubusercontent.com/97725657/210265603-78b40d7f-de41-4548-949d-c18b7ecacd77.mp4

**Both Arms**


https://user-images.githubusercontent.com/97725657/210265652-5d70e4d4-dd4b-45bf-94ab-6b704104c278.mp4

