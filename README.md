lof-loci-occ
============

Matlab implementations of the one-class classification versions of the Local Outlier Factor (LOF) and Local Correlation Integral (LOCI) algorithms as used in *Outlier Detection with One-Class Classifiers from ML and KDD* (see below for abstract and link to paper). 

Please note that the [Data Description Toolbox](http://prlab.tudelft.nl/david-tax/dd_tools.html) by David Tax (which includes the implementations of many other one-class classifiers) is required to run the Matlab files (the code was written at the time version 1.7.3, but may very well work with the latest version).

Outlier Detection with One-Class Classifiers from ML and KDD
------------------------------------------------------------

The problem of outlier detection is well studied in the fields of Machine Learning (ML) and Knowledge Discovery in Databases (KDD).
  Both fields have their own methods and evaluation procedures. In ML, Support Vector Machines and Parzen Windows are well-known methods that can be used for outlier detection. In KDD, the heuristic local-density estimation methods LOF and LOCI are generally considered to be superior outlier-detection methods. Hitherto, the performances of these ML and KDD methods have not been compared.
  This paper formalizes LOF and LOCI in the ML framework of one-class classification and performs a comparative evaluation of the ML and KDD outlier-detection methods on real-world datasets.
  Experimental results show that LOF and SVDD are the two best-performing methods. It is concluded that both fields offer outlier-detection methods that are competitive in performance and that bridging the gap between both fields may facilitate the development of outlier-detection methods.

J.H.M. Janssens, I. Flesch, and E.O. Postma. [Outlier detection with one-class classifiers from ML and KDD](https://www.researchgate.net/publication/221226413_Outlier_Detection_with_One-Class_Classifiers_from_ML_and_KDD). In M.A. Wani, M. Kantardzic, V. Palade, L. Kurgan, and Y. Qi, editors, *Proceedings of the Eighth International Conference on Machine Learning and Applications*, pages 147-153, Miami, FL, Dec. 2009.


License
-------

Copyright Jeroen Janssens. Distributed under the simplified BSD license.
