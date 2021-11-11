# <img src="https://media.giphy.com/media/iY8CRBdQXODJSCERIr/giphy.gif" width="30px"> Realtime-Emotion-Recognition <img src="https://media.giphy.com/media/iY8CRBdQXODJSCERIr/giphy.gif" width="30px">

This project classifies the emotions like happy, neutral, angry, disgusted, fearful, sad and surprised at real-time using face detection. 

## Dependencies

```

numpy==1.21.2 

opencv-python==4.5.3.56

tensorflow>=2.6.1

```

or just execute `pip install -r requirement.txt`
in your command shell.

---

## Dataset

The FER-2013 dataset was created by gathering the results of a Google image search of each emotion and synonyms​​ of ​​the ​emotions. 

Download:- [fer2013.csv](https://www.kaggle.com/deadskull7/fer2013)

---

## Exection 

In the `emotion.py` file -

- To train the model:

`python emotions.py --mode train`

- You can download the pre-trained model from the model folder and then run:

`python emotions.py --mode display`

---

## Algorithm

- First, the **haar cascade** method is used to detect faces in each frame of the webcam feed.

- The region of image containing the face is resized to **48x48** and is passed as input to the CNN.

- The network outputs a list of **softmax scores** for the seven classes of emotions.

- The emotion which has the **maximum score** is displayed on the screen.

---

## Results

The result of the algorithm performance is as follows:

![Accuracy plot](https://raw.githubusercontent.com/hrugved06/Realtime-Emotion-Recognition/main/images/accuracy_plot.png)

---

## <img src="https://media.giphy.com/media/iY8CRBdQXODJSCERIr/giphy.gif" width="30px">My Profile :
<div align="center">
<a href="https://github.com/hrugved06"><img src="https://avatars.githubusercontent.com/u/59966943?s=400&u=445f4a7598547c0ecdeb22a265dd1a3dad9e297d&v=4" width="100px;" alt=""/><br /><sub><b> Hrugved Kolhe</b></sub></a>
</br>

</br>

[![GitHub followers](https://img.shields.io/github/followers/hrugved06.svg?label=Follow%20@hrugved06&style=social)](https://github.com/hrugved06) 
[![Twitter Follow](https://img.shields.io/twitter/follow/HrugVed_?style=social)](https://twitter.com/HrugVed_)
</div>
</br>

---