Run lstm_text_generation.py with python3 in interactive mode and call the function generateText() to produce some randomly generated text with the current weights.

The generatedText is written to out.txt, some generated text is already written in there.

The weights are the result of training over only one epoch, feel free to train this yourself but there seems to be some problem with either loading the weights or training the current weights as the loss function seems to steadily increase in the second epoch. It would probably be better to retrain the net (4~ hours per epoch).