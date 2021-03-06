# Style Transfer using Neural Nets

> How might Picasso have rendered an F1 car?

> Used Keras / Tensforflow 1 and 2 on Google colab. The notebooks relate to Google Colab.

tf1 - from Chapter 8.3 of
[Francois Chollet's Deep Learning book](https://www.amazon.co.uk/Deep-Learning-Python-Francois-Chollet/dp/1617294438/ref=sr_1_1?dchild=1&keywords=francois+chollet+deep&qid=1589190028&sr=8-1)

tf2 tipped off by Francois Chollet's tweet https://twitter.com/fchollet/status/1256744926550716417
https://colab.research.google.com/drive/18XPdEDVYdr_ODAvW0DrWRCRC25tvTuCE

The names of some of the input output files might have changed slightly. So please be careful.
The dog image has been added to be used as a reference to make sure hyperparameters are good.

Trained on Google Colab. As a result the '/content/drive/My Drive/ is used to link to the GDrive

I found the tf1 approach with L-BFGS to be quicker and more robust than ttf2 with vanilla SGD.

#Examples:

![Racing Point Input](https://github.com/DexterDSilva/f1car-styletransfer/blob/master/rp-20hg.jpg)
![Racing Point Output](https://github.com/DexterDSilva/f1car-styletransfer/blob/master/rp20-pic-1_at_iteration_49.png)

![Renault Input](https://github.com/DexterDSilva/f1car-styletransfer/blob/master/renault-hires-1.jpg)
![Renault Output](https://github.com/DexterDSilva/f1car-styletransfer/blob/master/renault-pic-1_at_iteration_49.png)
