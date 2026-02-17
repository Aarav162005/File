# File
Kindly Note: The current instalation was unable to support the code. However, the code is correct and was run on another device for verification.
This code detects faces in a picture. From the detected faces, it extracts color based features like hue and saturation.
Finally, the faces are clustered with help of K-Means Algorithm. Once this is accomplished a new face(Dr. Tharoor) is introduced which is classified
into one of the pre-existing clusters. 
Aim: 
To implement face detection with the help of Haar-Cascade classifiers and extract features like saturation and hue from the detected faces.
Methodolgy:

1. The group photo is loaded and duly converted to grayscale enabling face detection.
2. We then use pre-trained Haar Cascade Classifier to detect faces. We set the parameters minsize and maxsize to minimise error.
3.Then we extract features of each detected face , namely Hue and Saturation
4.These extracted features are then stored in vectors. K-Means clustering is used to group faces based on thses HSV features.
5.Now we use a new image- that of Dr. Tharoor. Face detection is implemented on this image and HSV features are extracted.
6. We now use these features to assign the new face to one of the existing clusters.
7. Finally, the clusters are visualised along with their centroids.
Desired Outputs:

1. Faces detected in the group image with bounding boxes in a window.
2. Scatter plots for Hue and Saturation features.
3. Facial clusters with centroids.
4. The plot which has clusters which includes the  new image that is assigned to the cluster,
5. Visualised clusters with their centroids after including new image.
Key Findings:

1. The trained K-Means model assigns a cluster to the new image data.
2. We need to adjust parameters to detect all faces.
3. The model can be used for simple face detection. Eg: For attendance (If one needs tosimply  count the no. of people).
Conclusion:

This code trains a K-means model to assign a cluster to new image data. It can be used for practical purposes like Face Detection.
This code can further be developed for a more advanced applications and be used before preparing for face recognition.
 

   
