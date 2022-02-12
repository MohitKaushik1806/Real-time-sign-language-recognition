# Real-time-sign-language-recognition

The proposed work aims at converting american sign language gestures into English that can be understood by everyone.

![image](https://user-images.githubusercontent.com/79049411/153720375-638221e5-a14a-4b01-8a9d-d4842f02a4c7.png)

## Dataset
The dataset is made manually by running the Data_collection jupyter notebook that collects images from your webcam for all the signs mentioned above in the American Sign Language.
Data has been collected for 24 alphabets only (not collected for 9=J and 25=Z because of gesture motions).
For each alphabet 15 images with there annotations has been collected from which 10 images with there annotations has been used for training the ssd_mobnet model and 5 images with there annotations has been used for testing our ssd_mobnet model (I have only uploaded the test images with there annotations similarly train images were also used to train the ssd_mobnet).

The image annotations is done with the help of LabelImage file which you can use by simply git cloning the following- [Link](https://github.com/tzutalin/labelImg)


## Testing

![image](https://user-images.githubusercontent.com/79049411/153720898-44019469-bf62-49e4-830f-24ac18b473d9.png)

## Resources used 
- wget.download('https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/_downloads/da4babe668a8afb093cc7776d7e630f3/generate_tfrecord.py')
- Tensirflow Setup https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/install.html
- https://www.youtube.com/watch?v=pDXdlXlaCco


