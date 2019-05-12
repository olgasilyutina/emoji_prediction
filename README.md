## Predicting emojis here, folks

![](https://i.kym-cdn.com/photos/images/original/001/274/468/20b.gif)

So, how it all works:

But first, pip install

```
!pip install -e git+https://github.com/olgasilyutina/emopok.git#egg=emopok
from emopok import emopok
emopok.textfeatures()
```

* data is [here](https://drive.google.com/open?id=1IF_KS-BoSlyDIlaxgBtFCiRwKeGusSs1)
* models are [here](https://drive.google.com/open?id=1mj8Rj-cDu9st358iSPZ3iLbFnZKFjfKI)
* you can repeat data preparation process [here](https://github.com/olgasilyutina/emopok/blob/master/emopok_data_pipeline.ipynb)
* run xgboost [here](https://github.com/olgasilyutina/emopok/blob/master/emopok_xgboost.ipynb)
* sentiments were predicted [here](https://github.com/olgasilyutina/socialsent3/blob/master/example.ipynb)

### Project presentation

[DataFest 6](https://datafest.ru/) presentation video is [right here](https://youtu.be/tpuKgWVrbMU) ~ 4:22:15

### Prediction example

**message**: Я в тюрьме всем нашим **ауе** здесь так плохо и одиноко лучше сюда непопадать здесь ломается моя жизнь 

**recommended emojis**: 😭😔😒😪😢

**original emoji**: 😪

more examples [here](http://htmlpreview.github.io/?https://github.com/olgasilyutina/emopok/blob/master/example_predictions.html)

### References

Authored by [Aina Nurmagombetova](https://github.com/anurma) 🤙 [Alina Cherepanova](https://github.com/alinacherepanova) 🙋 [Anya Bataeva](https://github.com/fyzbt/) 🤯 [Olya Silyutina](https://github.com/olgasilyutina) 🤔

