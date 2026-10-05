 🎵 Music Generation with RNNs

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)](https://www.tensorflow.org/)
[![License](https://img.shields.io/badge/License-Educational-green.svg)](#license)

Generate original Irish folk music in **ABC notation** using a character-level Recurrent Neural Network (LSTM).

This project implements **Lab 1** from the [MIT Introduction to Deep Learning](http://introtodeeplearning.com/) course.

---

 Overview

The model learns the structure and patterns of traditional Irish folk songs and generates new tunes one character at a time. After training, the generated ABC text is converted into playable audio.


## 📊 Dataset

| Property              | Value                          |
|-----------------------|--------------------------------|
| Source                | Irish folk songs (ABC notation)|
| Number of songs       | 817                            |
| Total characters      | ~200,679                       |
| Vocabulary size       | 83 unique characters           |

**Example song (ABC notation):**

```abc
X:1
T:Alexander's
Z: id:dc-hornpipe-1
M:C|
L:1/8
K:D Major
(3ABc|dAFA DFAd|fdcd FAdf|gfge fefd|(3efe (3dcB A2 (3ABc|!
dAFA DFAd|fdcd FAdf|gfge fefd|(3efe dc d2:|!

