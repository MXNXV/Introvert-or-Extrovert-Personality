# Dataset
Context
The Myers Briggs Type Indicator (or MBTI for short) is a personality type system that divides everyone into 16 distinct personality types across 4 axis:

Introversion (I) – Extroversion (E)
Intuition (N) – Sensing (S)
Thinking (T) – Feeling (F)
Judging (J) – Perceiving (P)

So for example, someone who prefers introversion, intuition, thinking and perceiving would be labelled an INTP in the MBTI system, and there are lots of personality based components that would model or describe this person’s preferences or behaviour based on the label.

# Content
This dataset contains over 8600 rows of data, on each row is a person’s:

Type (This persons 4 letter MBTI code/type)
A section of each of the last 50 things they have posted (Each entry separated by "|||" (3 pipe characters)

 We will be using a TensorFlow recurrent neural network (with a bidirectional GRU) to make our predictions.
 # Personality Type Prediction
Given data about posts people have made, let's try to predict the personality type of a given person.

We will use a TensorFlow RNN to make our predictions

 If you call model.predict() on the test set, you will get back a set of probability values (one for each test example). 
 
 If the probability value is greater than or equal to 50%, the example is being classified as extrovert. If the value is less than 50%, the example is being classified as introvert.


![alt text](https://github.com/MXNXV/Introvert-or-Extrovert-Personality/blob/main/Introvert%20or%20Extrovert.ipynb%20-%20Colaboratory%20and%2011%20more%20pages%20-%20Personal%20-%20Microsoft%E2%80%8B%20Edge%203_8_2021%2011_43_14%20PM.png)
