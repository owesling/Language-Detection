Creating a neural network to recognize what language is spoken
## Team members
Owen Wesling (owesling), Emanuel Borror (EmanuelBorror)

## Project decription

A language detection model based on neural networks to identify the language spoken out of 20 different languages. This model will be built on datasets of .wav and .txt files containing words in each respective language. The datasets used are listed below. 

The goal is to identify and print out the language that is spoken in an audio file of a sentence. The neural network will determine if words in the tested audio file contains any of the "most common words" of certain languages. Early iterations will detect from languages that are distinctly different from each other. Success of the model will allow more languages to be added into detection that are similar to previously added. A possible biomedical application might be isolating symptomatic terms from different languages. 

This model will use the language dataset from https://huggingface.co/datasets/papluca/language-identification to be trained. This dataset has 90k samples from 20 languages. 

Alternatively for .wav files for audio detection, we will use the language detection dataset from https://github.com/Kyubyong/css10/blob/master/README.md. 

