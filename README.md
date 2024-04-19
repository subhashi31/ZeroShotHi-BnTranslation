# zero_shot_hi-bn_translation
Zero Shot Neural Machine Translation: Hindi to Bengali

In this experimentation, a pre-trained model: mT5 which is a T5 variant is fined tuned for translation task. The fine tuning is done on a custom dataset that contains 40,000 samples. The language pairs in the dataset are: English-Hindi, Hindi-English, English-Bengali, Bengali-English. The dataset is prepared from PMIndia dataset which contains highly accurate translations. 
This fine tuned model was then tested for Hindi-Bengali translation.
