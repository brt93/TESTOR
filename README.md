# TESTOR
A methodology to convert scene descriptions into a storyboard. To do so we integrate several
models and dataset to convert a textual scene description into an editing sequence, a concatenation
of shots to represent the scene. The different models, datasets and scripts used to convert the
scene description into a storyboard will be gradually loaded here by November 15 2024. 

The Sequenced CMD is the Condensed Movie Dataset characterized with the scene descriptions, the sequence of shots ,
the shots duration and the video id. The sequences of shot size we obtained using a finetuned Vision Transformer, 
that for space reasons we have uploaded here (https://drive.google.com/file/d/1xHf87rjN8i08GEveepeONNv575xvrgEy/view?usp=share_link)

The notebook "CMD_ extract text and edit embedding" starts from the sequenced CMD dataset and extract textual embedding and editing 
embedding, while "CMD_seq2seq_models train-test" show the different implementatioons of the seq2seq model.

Finally the Stable diffusion algorithm was finetuned using the LoRa weights
