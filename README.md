# Image_Processing
Some code to process pictures via OpenCV + Creation of keypoints with ORB algorithms + Clustering of the keypoints to create histograms in order to do some classification with classic machine learning algorithms

Dans ce répertoire on pourra voir comment :
- Récupérer un certains nombre de photos sur mon drive
- Traiter ces photos ( histogram equalization, contraste, sharpening, gaussian filters ) 
- Data augmentation (rescaling, rotation, gaussian noise, inversion)
- Utilisation  d'extracteurs de textures (local and globals) 
- Utilisation d'algorithme de détéction de keypoints  (ORB)
- Clustering de ces keypoints avec K-Means
- Visualisation de ces keypoints via T-Sne
- Création d'histogrammes de fréquences de keypoints par photos
- Classification des photos via différents algorithmes de machine learning 
- Evaluation des modèles avec certaines métriques ( f1 micro score, matrice de confusion..)
