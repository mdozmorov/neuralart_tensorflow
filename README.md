## NeuralArt

Implementation of [A Neural Algorithm of Artistic Style](http://arxiv.org/abs/1508.06576) by Tensorflow.

### Requirements
 - [Tensorflow](http://www.tensorflow.org/)
 - [VGG 19 model](https://drive.google.com/file/d/0B8QJdgMvQDrVU2cyZjFKU1RrLUU/view?usp=sharing) - download manually

```
# Requires Python 2.x and older dependencies
conda create --name tensorflow_old python=2.7
conda activate tensorflow_old
conda install tensorflow-gpu==1.9.0 scipy=1.1.0 pillow
python main.py
# Creates 'results' folder with intermediate PNG files, and the final 'results.png' image
```

### Examples

<p>
Content: <br/>
<img src="https://github.com/ckmarkoh/neuralart_tensorflow/blob/master/images/Taipei101.jpg?raw=true" width="50%"/> <br/>
Style: <br/>
<img src="https://github.com/ckmarkoh/neuralart_tensorflow/blob/master/images/StarryNight.jpg?raw=true" width="50%"/> <br/>
Output: <br/>
<img src="https://github.com/ckmarkoh/neuralart_tensorflow/blob/master/images/Taipei101_StarryNight.jpg?raw=true" width="50%"/> <br/>
</p>
