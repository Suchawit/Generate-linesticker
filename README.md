# Generate-LineSticker

## Preparing Datasets

Dataset contains 4 folders and each one is divided into category, taste and character and available to access [**line-sticker-data**](https://github.com/steerapi/line-sticker-data?fbclid=IwAR3cNJ9LHBSd9mmh-C8_Zsv7wfqgjswT3VyiGOzpNIDvCzvEfRCrVMEXjtc)<br>

**To install dataset**

     !pip install linestickerdata==0.0.12
**To see the list of available data** (Dict type)

     linestickerdata.list_available()

Use model https://github.com/qhgz2013/anime-face-detector to crop line sticker face

Also install face_recognition from https://github.com/ageitgey/face_recognition to seperate human face from sticker line face

    !pip3 install face_recognition
