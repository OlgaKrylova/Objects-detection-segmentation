# Objects detection & segmentation
Решение задач детекции и сегментации изображений с использованием предобученных моделей
faster_rcnn_R_50_DC5 и mask_rcnn_R_50_DC5 с использованием библиотеки [detectron2](https://github.com/facebookresearch/detectron2).

<p align="center">
<img src="images/Hard_hats.gif" alt="bash" width="400" height="400"/>
</p>
Выше изображено обнаружение строительных касок на дообученной модели детекции. 

AP по каске и голове без каски - 34.3 и 41.3 соответственно.

В блокноте реализован как простой инференс с использованием предобученных моделей так и дообученные модели.
Простой инференс отлично работает на кофейных чашках:
<p align="center">
<img src="images/Cup detection.png" alt="bash" width="300" height="200"/>
<img src="images/Cup segmentation.png" alt="bash" width="300" height="200"/>
</p>
При этом не определяет строительные каски рабочих:
<p align="center">
<img src="images/Person detection.png" alt="bash" width="300" height="200"/>
<img src="images/Person segmentation.png" alt="bash" width="300" height="200"/>
</p>

