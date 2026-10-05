I wanted to make sure my model wasn't just getting lucky with how the data was split. 
To test this, I shuffled the dataset 10 different times using 10 different random seeds. 
I trained the model each time, recorded the error scores, and then calculated the standard deviation across all of them. 
The standard deviation was very low (0.029), which proves the model is actually stable regardless of how the data is divided.
