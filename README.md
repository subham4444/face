**1.Introduction**
The student attendance system using facial recognition has been developed to address the need for 
an efficient and automated approach to track and monitor student attendance in educational 
institutions. Manual attendance recording methods, such as paper-based sign-in sheets or barcode 
scanning, have limitations in terms of accuracy, time consumption, and the inability to verify 
student identity effectively.

**Technological Foundations:**
The development of a facial recognition-based student attendance 
system relies on the following technological foundations: - 

Computer Vision: Computer vision algorithms are used to detect and localize faces in images 
or video frames. - 

Facial Detection: Facial detection algorithms identify and locate facial landmarks and regions 
of interest within a given image or frame. 

- Feature Extraction: Deep learning models, such as Convolutional Neural Networks (CNNs), 
extract high-level features from facial images.

- Facial Recognition: By comparing the extracted features with pre-registered student profiles, 
facial recognition algorithms determine the identity of individuals. - Data Management: The attendance system requires a robust database management system to 
store and manage student profiles, attendance records, and relevant information.

**About Haar cascade classifier**
The Haar cascade classifier played a crucial role in the dataset generation process. It is a machine 
learning-based approach that allows for efficient and accurate face detection in images and video 
frames. The classifier is trained to identify specific patterns in images that correspond to facial 
features such as eyes, nose, and mouth.The Haar cascade classifier operates by analyzing the 
intensity differences in different regions of an image using rectangular features. These rectangular 
features are derived from a set of positive and negative training samples. 

<img width="442" alt="image" src="https://github.com/subham4444/face/assets/105392902/97fb63c8-274f-4260-bd9b-a7bc8a36b4df">

**3. Labeling and Annotation:**
Each image in the dataset was assigned a label corresponding to 
the individual's identity. This labeling process was carried out manually, ensuring the association 
between the facial features and the respective individuals. Facial landmarks were also annotated 
using the OpenCV library, providing valuable reference points for subsequent feature extraction 
and alignment steps. Labels were one hot encoded as shown in the following snippet. 

<img width="224" alt="image" src="https://github.com/subham4444/face/assets/105392902/7a5129ef-55a8-4998-9faa-01e41b1b6f69">

**Network Architecture **

<img width="484" alt="image" src="https://github.com/subham4444/face/assets/105392902/69aebb9e-f930-43b0-903e-ae06a1e4283e">

