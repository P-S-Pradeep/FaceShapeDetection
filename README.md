
# <p align = "center"> Face-Shape-And-Hair-Style-Matching-System </p>


## <br>PROBLEM STATEMENT
The problem at hand is to develop a hairstyle recommendation system based on face shape detection. The objective is to create an automated solution that can analyze the user's face shape and suggest suitable hairstyles that complement their unique features.

The primary challenge is to accurately detect and classify the user's face shape using computer vision techniques. Face shape detection involves analyzing facial landmarks, such as the position of the eyes, nose, and mouth, and determining the overall structure of the face. Once the face shape is identified, the system needs to provide personalized hairstyle recommendations that enhance the user's natural features, taking into account factors such as hair texture, length, and thickness.

Overall, the goal is to create a reliable and efficient hairstyle recommendation system that utilizes face shape detection technology to offer personalized and aesthetically pleasing hairstyle suggestions to users, promoting self-expression and confidence in their appearance.
  
## ARCHITECTURE DIAGRAM:

![Screenshot 2023-05-29 113117](https://github.com/Dineshkumar200/MINIPROJECT/assets/75235789/5e2d748f-e107-4c5b-bf64-2922da598d77)

## METHODOLOGY:

### Detecting the Forehead Point using Bounding Box

In this step, we utilize dlib to perform face detection on the input image, which provides us with the bounding box coordinates of the detected face.

### Extracting Facial Features with Dlib

Once the face is detected, the subsequent task involves identifying the facial landmarks or key points on the face, including cheekbones, chin, jawline, and the highest point on the forehead.

### Calculating Distances between Extracted Points

Upon obtaining the facial landmarks, we can proceed to analyze the face shape by applying predefined criteria or rules. This analysis typically involves comparing the relative measurements of specific facial features, such as the forehead width, cheekbones, jawline, or the distance between certain points.

### Determining the Face Shape

Based on these measurements, we can classify the face shape into various categories, such as oval, round, square, heart-shaped, and more.

### Recommendations for Hairstyles based on Face Shape

Once the face shape is determined, we can employ a set of predefined rules or recommendations to suggest suitable hairstyles that complement the specific face shape.

## REQUIREMENTS:
Jupyter notebook (or) Google colab
<br>
Dlib(python library)


## RESULTS

Facial landmarks are specific points on the face that are used to detect and analyze various facial features. These landmarks are typically identified using facial detection algorithms and can be represented as coordinates (x, y) on the face.
Here are some commonly used facial landmarks for detecting face shape:
1. Chin: The points along the chin outline, typically ranging from 1 to 17.
2. Eyebrows: The points along the eyebrow contours, including the inner corner, arch, and outer corner.
3. Eyes: The points around the eye contours, including the corners, eyelids, and eyebrows.
4. Cheekbones: The points on the cheekbones, usually located at the outer corners of the eyes.
5. Forehead: The points on the forehead, typically used to determine the hairline and forehead shape.
These landmarks provide important information about the facial structure, such as the position, size, and shape of different facial components. By analyzing the distances and proportions between these landmarks, it is possible to infer the face shape and determine features like the jawline, forehead width, cheekbone prominence, and chin length.

Face shape detection algorithms often utilize these landmarks to calculate ratios and distances between specific points, which are then compared against predefined thresholds or ranges to classify the face shape into categories such as oval, round, square, heart-shaped, diamond, triangle, or oblong.


### Facial Landmarks
![111](https://github.com/Dineshkumar200/Face-Shape-And-Hair-Style-Matching-System/assets/75235789/6f4d6c1c-76ef-420c-837e-8b9140fcf76a)


### Forhead Distance
![114](https://github.com/Dineshkumar200/Face-Shape-And-Hair-Style-Matching-System/assets/75235789/116ee38f-151e-42ff-93c5-5296c82f60c2)

### Jawline Distance
![115](https://github.com/Dineshkumar200/Face-Shape-And-Hair-Style-Matching-System/assets/75235789/26d54e4a-85b7-41be-97ec-f11300ac0cd4)


### Face Length
![112](https://github.com/Dineshkumar200/Face-Shape-And-Hair-Style-Matching-System/assets/75235789/ee1c02d5-e47b-4026-945b-5ed3ed745bdd)

### Cheek Bone Distance
![117](https://github.com/Dineshkumar200/Face-Shape-And-Hair-Style-Matching-System/assets/75235789/a32f0e5f-ebbd-49f9-a383-835cdf8bea66)


Overall, facial landmarks play a crucial role in facial analysis and shape detection algorithms, enabling the identification and measurement of various facial features for tasks like face recognition, emotion detection, virtual try-on, and personalized styling recommendations. Finally this system recommend hairstyle based on the face shape

![Screenshot 2023-06-21 232457](https://github.com/Dineshkumar200/Face-Shape-And-Hair-Style-Matching-System/assets/75235789/ab63d4e2-5b7d-44f1-b01d-687f52369b56)



## <br><br><br><br>CONCLUSION:

Facial shape detection and analysis for hairstyle recommendation systems holds great potential for providing personalized and accurate hairstyle recommendations to users.
By utilizing computer vision and machine learning techniques, facial landmarks and geometric features can be extracted to accurately analyze the user's facial shape. 
Ultimately, the use of facial shape detection and hairstyle recommendation systems can provide a more efficient and satisfying experience for individuals looking to change their hairstyle.
