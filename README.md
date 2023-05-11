# Labeled-Crack-Dataset
*Index files for pavement crack databases*

This this repository contains the index files with label of several images of seven datasets as well as the datasets used in our research work entitled *"DDR4CC: Efficient data dimensionality reduction method for improving road crack classification algorithms"*. The *".txt"* files only contains the image name and the corresponding label into the following classes: *G-alligator, G-Transverse, G-Longitudinal, Healthy-pavement*.


* **File: Cubero-Fernandez-et-al-label-index.txt**
  * Total labels: 600 labels.
    - 100 alligator crack labels (*G-alligator*).
    - 200 transverse crack labels (*G-Transverse*).
    - 200 longitudinal crack labels (*G-Longitudinal*)
    - 100 Healthy pavement lables (*Healthy-pavement*)
  * The original images of the datasets can be found in the author’s respective work: 
    * *A. Cubero-Fernandez, F. J. Rodriguez-Lozano, R. Villatoro, J. Olivares, and J. M. Palomares, “Efficient pavement crack detection and classification,” EURASIP Journal on Image and Video Processing, vol. 2017, no. 1, Jun. 2017.*

* **File: Rodriguez-Lozano-et-al-label-index.txt**
  * Total labels: 2456 labels.
    - 380 alligator crack labels (*G-alligator*).
    - 558 transverse crack labels (*G-Transverse*).
    - 590 longitudinal crack labels (*G-Longitudinal*)
    - 928 Healthy pavement lables (*Healthy-pavement*)
  * The original images of the datasets can be found in the author’s respective work: 
    * *F. J. Rodriguez‐Lozano, F. León‐García, J. C. Gámez‐Granados, J. M. Palomares, and J. Olivares, “Benefits of ensemble models in road pavement cracking classification,” Computer-Aided Civil and Infrastructure Engineering, vol. 35, no. 11, pp. 1194–1208, Feb. 2020.*

* **File: CRACK500-label-index.txt**
  * Total labels: 1071 labels.
    - 7 alligator crack labels (*G-alligator*).
    - 674 transverse crack labels (*G-Transverse*).
    - 388 longitudinal crack labels (*G-Longitudinal*)
    - 2 Healthy pavement lables (*Healthy-pavement*)
  * The source of the images to make the labes were based on the available images in https://github.com/fyangneil/pavement-crack-detection/blob/master/README.md
  * The original images of the datasets can be found in the author’s respective works:   
    * *L. Zhang, F. Yang, Y. Daniel Zhang, and Y. J. Zhu, “Road crack detection using deep convolutional neural network,” 2016 IEEE International Conference on Image Processing (ICIP), Sep. 2016.*
    * F. Yang, L. Zhang, S. Yu, D. Prokhorov, X. Mei, and H. Ling, “Feature Pyramid and Hierarchical Boosting Network for Pavement Crack Detection,” IEEE Transactions on Intelligent Transportation Systems, vol. 21, no. 4, pp. 1525–1535, Apr. 2020.*

* **File: GAPs384-label-index.txt**
  * Total labels: 461 labels.
    - 117 transverse crack labels (*G-Transverse*).
    - 343 longitudinal crack labels (*G-Longitudinal*)
    - 1 Healthy pavement lables (*Healthy-pavement*)
  * The source of the images to make the labes were based on the available images in https://github.com/fyangneil/pavement-crack-detection/blob/master/README.md  
  * The original images of the datasets can be found in the author’s respective work: 
    * *M. Eisenbach, R. Stricker, D. Seichter, K. Amende, K. Debes, M. Sesselmann, D. Ebersbach, U. Stoeckert, and H.-M. Gross, “How to get pavement distress detection ready for deep learning? A systematic approach,” 2017 International Joint Conference on Neural Networks (IJCNN), May 2017.*

* **File: CFD-label-index.txt**
  * Total labels: 110 labels.
    - 5 alligator crack labels (*G-alligator*).
    - 95 transverse crack labels (*G-Transverse*).
    - 10 longitudinal crack labels (*G-Longitudinal*)
  * The source of the images to make the labes were based on the available images in https://github.com/fyangneil/pavement-crack-detection/blob/master/README.md  
  * The original images of the datasets can be found in the author’s respective work: 
    * *Y. Shi, L. Cui, Z. Qi, F. Meng, and Z. Chen, “Automatic Road Crack Detection Using Random Structured Forests,” IEEE Transactions on Intelligent Transportation Systems, vol. 17, no. 12, pp. 3434–3445, Dec. 2016.*

* **File: AEL-label-index.txt**
  * Total labels: 63 labels.
    - 23 transverse crack labels (*G-Transverse*).
    - 37 longitudinal crack labels (*G-Longitudinal*)
    - 3 Healthy pavement lables (*Healthy-pavement*)
  * The source of the images to make the labes were based on the available images in https://github.com/fyangneil/pavement-crack-detection/blob/master/README.md 
  * This dataset has been extended with two smaller datasets called LRIS and TEMPEST2, available in https://www.irit.fr/~Sylvie.Chambon/Crack_Detection_Database.html
  * The original images of the datasets can be found in the author’s respective work: 
    * *R. Amhaz, S. Chambon, J. Idier, and V. Baltazart, “A new minimal path selection algorithm for automatic crack detection on pavement images,” 2014 IEEE International Conference on Image Processing (ICIP), Oct. 2014.*

* **File: Cracktree200-label-index.txt**
  * Total labels: 82 labels.
    - 18 transverse crack labels (*G-Transverse*).
    - 64 longitudinal crack labels (*G-Longitudinal*)
  * The source of the images to make the labes were based on the available images in https://github.com/fyangneil/pavement-crack-detection/blob/master/README.md 
  * The original images of the datasets can be found in the author’s respective work: 
    * *Q. Zou, Y. Cao, Q. Li, Q. Mao, and S. Wang, “CrackTree: Automatic crack detection from pavement images,” Pattern Recognition Letters, vol. 33, no. 3, pp. 227–238, Feb. 2012.*

The **DS folder** contains *".zip"* files representing the five datasets used in our work. These datasets only contains *".csv"* files with the data resulting of the application of each data dimensionality reduction methods used in out work. The original images of each dataset are the property of the authors of their respective works as shown in the list above and can be publicly accessed. Also, this folder contains the confusion matrices results of the execution of all the experiments carried out in the paper.

## Data availability
The content of this repository is no related to the availability of the data of the works of other authors or the possible modifications that they could make.

## License
This dataset is not licensed but if you use in your work consider to cite the following work:
```latex
@article{https://doi.org/10.1111/mice.13014,
author = {Rodriguez-Lozano, Francisco J. and Gámez-Granados, Juan C. and Palomares, Jose M. and Olivares, Joaquín},
title = {Efficient data dimensionality reduction method for improving road crack classification algorithms},
journal = {Computer-Aided Civil and Infrastructure Engineering},
volume = {n/a},
number = {n/a},
pages = {},
doi = {https://doi.org/10.1111/mice.13014},
url = {https://onlinelibrary.wiley.com/doi/abs/10.1111/mice.13014},
eprint = {https://onlinelibrary.wiley.com/doi/pdf/10.1111/mice.13014},
abstract = {Abstract Automatic crack classification plays an essential role in road maintenance. Using many features for the classification is inefficient for implementing embedded systems with low computational resources makes it difficult. Therefore, this work proposes a new data dimensionality reduction (DDR) for crack classification algorithms (DDR4CC). DDR4CC reduces the required information about the cracks to only four features. Using these features, the images can be classified into longitudinal, transverse, and alligator cracks or healthy pavement. DDR4CC is compared with eight DDR methods, and the reduced set of features is analyzed using five different classification algorithms. Besides, five different datasets, generated by a combination of several public datasets, are used. We are proposing a simple DDR method with high interpretability of the data, obtaining very fast computation and high accuracy. Experiments show that DDR4CC enhances the results of the classification algorithms, providing almost perfect classifiers with a minimum computation time.}
}
```
