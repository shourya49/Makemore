# Makemore

Makemore takes one text file as input i.e **names.txt**, where each line is assumed to be one training thing, and generates more things like it.I have used and implement various models for the prediction of next character given a sequence of characters.<br><br>
I have implement these models from scratch using **PyTorch** library and with the help of some research papers. Following are the models and techniques which I used for this task - <br><br>
**1) Bigram Model<br><br>
2) MLP(Multilayer Perceptron)<br><br>
3) Backpropagation**<br><br>





### Usage

The included `names.txt` dataset, as an example, has the most common 32K names takes from [ssa.gov](https://www.ssa.gov/oact/babynames/) for the year 2018. It looks like:

```
emma
olivia
ava
isabella
sophia
charlotte
...
```
