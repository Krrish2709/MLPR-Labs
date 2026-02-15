# Lab 5: Distance Metrics and Face Detection

### Aim
The aim of this lab was to learn how distance metrics work and how they are used in real ML tasks. We had to implement different distances like Euclidean and Manhattan, and also use Haar-cascade for detecting faces in an image and try out K-Means clustering.

---

### Method
1. **Face Detection:** I used `cv2` and the `haarcascade_frontalface_default.xml` file to find faces in the `Plaksha_Faculty.jpg` photo. I drew boxes around the faces that the model detected.

2. **Implementing Distances:** I wrote functions to calculate:
   * **Euclidean Distance:** The straight line path.
   * **Manhattan Distance:** The "city block" path.
   * **Hamming Distance:** Counting differences in bits/strings.
3. **Clustering:** Used `KMeans` from sklearn to group data points based on these distances.
4. **Analysis:** Looked at how cross validation helps the model generalize and how the "K" value in KNN affects the bias and variance.


---

### Conclusion
This lab showed that the choice of distance metric is super important because it change how the algorithm "sees" the data. If we pick a bad metric, the classification or clustering wont be accurate. I also learned that face detection with Haar-cascade is fast but it sometimes miss faces if the lighting or angle is weird. Overall, understanding the balance between bias and variance is the key to making a good model that doesnt overfit.
