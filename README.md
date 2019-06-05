# Learn to calculate with seq2seq model
I implemented a seq2seq model using tensorflow to perform arithmetic operations 

Seq2Seq models are very popular these days because they achieve great results in Machine Translation, Text Summarization, Conversational Modeling and more.

Using sequence-to-sequence modeling I build a calculator for evaluating arithmetic expressions, by taking an equation as an input to the neural network and producing an answer as it's output.

The resulting solution for this problem will be based on state-of-the-art approaches for sequence-to-sequence learning.

## Libraries
For this task I used the following libraries:

TensorFlow — an open-source software library for Machine Intelligence.

scikit-learn — a tool for data mining and data analysis.

## Data
One benefit of this task is that I didn't need to download any data — I can generate it on my own! We will use two operators (addition and subtraction) and work with positive integer numbers in some range. Here are examples of correct inputs and outputs:

Input: '1+2'
Output: '3'

Input: '0-99'
Output: '-99'


