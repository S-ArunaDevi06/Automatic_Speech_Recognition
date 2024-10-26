# Automatic_Speech_Recognition

##Overview
  This is the method and the model that I have used to participate in a shared task in ACL anthology 2023. The task focuses on converting audio collected from vulnerable individuals such as elderly people and uneducated people to tamil text so that it would be easier for them to communicate with others through various technologies for example chat application and filling forms and etc..

##Methodology
  I have used a pretrained wav2vec transformer model. First the input audio is tokenised. Then it is passed into the transformer. Then the output from model is decoded into tamil text.

##Conclusion
   I used Word error rate(WER) as the performance metric and on the test set WER was 37.73. In this shared task, I have secured 4th place using this model.

##Published paper
  Access paper through https://aclanthology.org/2024.ltedi-1.31v2.pdf
