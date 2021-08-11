## Malaria Detection
### Use of Deep convolutional neural networks for automatic identification of malaria infected cells.

Malaria is a life-threatening disease that is spread by the Plasmodium parasites. It is detected by trained microscopists who analyze microscopic blood smear images. Modern deep learning techniques may be used to do this analysis automatically. The need for the trained personnel can be greatly reduced with the development of an automatic accurate and efficient model.

### Data-Set

Malaria dataset contains 27,558 cell images classified into two groups called test and train, where train set contains about 25000 images and the test set contains 2600 images. The data is further divided into 2 groups of parasitized and uninfected cells, where each cell contains an equal number of instances.
![image](https://user-images.githubusercontent.com/86013104/129008717-f809312d-8b8d-4dde-b249-32d4da290cca.png)


### Data Preprocessing

In supervised learning, the behaviour and performances of the model entirely depends on the data that is fed. Therefore, data preprocessing plays a vital role towards conducting experiments. Considering that, in this work manually corrected images were resized as per the model input, which led to getting faster convergence.

