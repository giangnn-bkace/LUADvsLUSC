# LUADvsLUSC
## Libraries Requirement
* numpy
* pandas
* scikit-learn
* jupyter
* tqdm

## Dataset
The original dataset can be download from:
* LUAD: https://portal.gdc.cancer.gov/files/0458c57f-316c-4a7c-9294-ccd11c97c2f9 
* LUSC: https://portal.gdc.cancer.gov/files/95258183-63ea-4c97-ae29-1bae9ed06334

## Prepare data (Optinal - Because the 2 data files are already uploaded to this github)
To prepare data in right format for training a classifier, run all commands in **_data_prepare.ipynb_** jupyter notebook.
```
jupyter notebook data_prepare.ipynb
```
After finish running all commands, **2 data files** will be generated:
 * **_data_LUAD.csv_**
 * **_data_LUSC.csv_**

## Apply Feature Selection and Classification
After prepare the data, run all commands in **_Feature_Selection_Tutorial.ipynb_** jupyter notebook to perform feature selection and classification.
```
jupyter notebook Feature_Selection_Tutorial.ipynb
```

## References
* For studying about **Feature Selection**
  * A good introduction article about **Feature Selection**
    * https://www.analyticsvidhya.com/blog/2016/12/introduction-to-feature-selection-methods-with-an-example-or-how-to-select-the-right-variables/
  * How to implement some feature selection methods by using **_scikit-learn_** library
    * http://scikit-learn.org/stable/modules/feature_selection.html
* For studying about **Support Vector Machine**
  * Lessons about SVM from Andrew Ng
    * Lecture 1: https://www.youtube.com/watch?v=hCOIMkcsm_g
    * Lecture 2: https://www.youtube.com/watch?v=Ccje1EzrXBU
    * Lecture 3: https://www.youtube.com/watch?v=QKc3Tr7U4Xc
    * Lecture 4: https://www.youtube.com/watch?v=mTyT-oHoivA
  * More intuitive lecture about **kernel trick** which is used in SVM
    * Kernel trick: https://www.youtube.com/watch?v=7_T9AdeWY3k
  * How to implement **SVM** by using **_scikit-learn_** library
    * http://scikit-learn.org/stable/modules/svm.html
* How to do **Cross Validation** by using **_scikit-learn_** library
  * http://scikit-learn.org/stable/modules/cross_validation.html
