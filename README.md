# Music Tagging

This project aims to study and classify music styles based on the features extracted using the LibROSA library, used for audio and music processing. Results achieve an average of 68% accuracy for 10 different genres. In particular, Classical music, and Metal are the easiest to identify (with F1 Score abiove 90%); while Disco, Reggae, or Rock, have results around 50%.

## Dataset

The [dataset](https://www.kaggle.com/datasets/insiyeah/musicfeatures) used for this project has 1000 values with 10 different genres: 

```
'blues', 'classical', 'country', 'disco', 'hiphop', 'jazz', 'metal', 'pop', 'reggae', 'rock'
```

Some of the predictive variables include: tempo, chroma_stft, rmse, spectral_centroid, spectral_bandwidth, rollof, zero_crossing_rate, or mfcc coefficients.