# face-recognition

a normal face-recognition model which is made using 4 simple steps
1) Face Detection
2) Data Gathering 
3) Data Comparison
4) Face Recognition

Opencv has three in-built face recognizers in it 

1) EigenFaces – cv2.face.createEigenFaceRecognizer() #command to implement them
2) FisherFaces – cv2.face.createFisherFaceRecognizer()
3) Local Binary Patterns Histograms (LBPH) – cv2.face.createLBPHFaceRecognizer()

Here in this model i have used Local Binary Patterns Histograms(LBPH Face recognizer) as we know that Eigenfaces and Fisherfaces are both affected by light and, in real life, we can't guarantee perfect light conditions. LBPH face recognizer is an improvement to overcome this drawback.
The idea with LBPH is not to look at the image as a whole, but instead, try to find its local structure by comparing each pixel to the neighboring pixels. 

dependencies used 
1) opencv
2) python
3) numpy
4) spyder
