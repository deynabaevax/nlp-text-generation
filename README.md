# Text Generation with Natural Language Processing
  <img width="500px" src="https://www.history.com/.image/c_fill%2Ccs_srgb%2Cfl_progressive%2Ch_400%2Cq_auto:good%2Cw_620/MTU3ODc5MDg2MTY3NjMxMTc3/plato-2.jpg">

# Introduction
A language model can predict the probability of the next word in the sequence, based on the words already observed in the sequence. Neural network models are a preferred method for developing statistical language models because they can use a distributed representation, where different words with similar meanings have similar representation and because they can use a large context of recently observed words when making predictions.

# Goals
    1. Prepare text for developing a word-based language model.
    2. Design and fit a neural language model with a learned embedding and an LSTM hidden layer.
    3. Use the learned language model to generate new text with similar statistical properties as the source text.

# The Dataset
The Republic is the classical Greek philosopher Plato's most famous work. It is structured as a dialog on the topic of order and justice within a city state. I got the file from the Project Gutenberg's website. <a href="http://www.gutenberg.org/cache/epub/1497/pg1497.txt">Link</a> to the dataset.

# Steps
    1. Getting the Data
    2. Data Preparation
    3. Encode the Sequences
    4. Sequence Inputs and Output
    5. Train the Language Model
    6. Use the Language Model
