# chat-bot

A chat bot using the cornell movie dialogue dataset.
Assuming a dialogue as the question and the reply would be the output of the model.

Mainly 2 layers of LSTM were used one was the encoder and the other one was the decoder.

the accuracy came out to be 70% after 40 epochs

![alt text](https://github.com/rishabh-vasudevan/chat-bot/blob/master/Screenshot%20from%202021-02-27%2005-34-54.png)

Here is an example of the conversation with the bot:

![alt text](https://github.com/rishabh-vasudevan/chat-bot/blob/master/Screenshot%20from%202021-02-27%2005-32-37.png)

I know most of the replies don't make sense but all of the replies are given by the network (nothing is hard coded) and the reason they don't make sense is that the training data were just lines of movies and not a proper question answer dataset.
