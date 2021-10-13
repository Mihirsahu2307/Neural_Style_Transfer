# Neural_Style_Transfer


### Description:
The Neural Style Transfer (NST) algorithm from [this paper](https://arxiv.org/pdf/1508.06576.pdf) was implemented in TensorFlow. Gradient Tape was used for automatic calculation of gradients. The original Kaggle notebook can be found [here](https://www.kaggle.com/masterofsnippets/neural-style-transfer) and the same notebook is also available in this repository.


## Installation

Install all dependencies using requirements.txt like so:

```shell
pip install -r requirements.txt
```  

## Examples

Input images (left = content, right = style):
<p float="left">
  <img src="https://github.com/Mihirsahu2307/Neural_Style_Transfer/blob/master/Examples/content_5.jpg" height = "300" width="300" />
  <img src="https://github.com/Mihirsahu2307/Neural_Style_Transfer/blob/master/Examples/style_4.jpg" height = "300" width="300" /> 
</p>

Generated image:
<p float="left">
  <img src="https://github.com/Mihirsahu2307/Neural_Style_Transfer/blob/master/Examples/Generated_C5_S4.jpg" height = "500" width="500" />
</p>

Input images (left = content, right = style):
<p float="left">
  <img src="https://github.com/Mihirsahu2307/Neural_Style_Transfer/blob/master/Examples/content_4.jpg" height = "300" width="300" />
  <img src="https://github.com/Mihirsahu2307/Neural_Style_Transfer/blob/master/Examples/style_1.jpg" height = "300" width="300" /> 
</p>

Generated image:
<p float="left">
  <img src="https://github.com/Mihirsahu2307/Neural_Style_Transfer/blob/master/Examples/Generated_C4_S1.jpg" height = "500" width="500" />
</p>

Input images (left = content, right = style):
<p float="left">
  <img src="https://github.com/Mihirsahu2307/Neural_Style_Transfer/blob/master/Examples/content_3.jpg" height = "300" width="300" />
  <img src="https://github.com/Mihirsahu2307/Neural_Style_Transfer/blob/master/Examples/style_3.jpg" height = "300" width="300" /> 
</p>

Generated image:
<p float="left">
  <img src="https://github.com/Mihirsahu2307/Neural_Style_Transfer/blob/master/Examples/Generated_C3_S3.jpg" height = "500" width="500" />
</p>

## Generating Your Own Images

* It is advisable to use a decent GPU for generating images if you don't want to wait for hours. You may directly access the Kaggle notebook in case you don't have a GPU.
* If you are running it locally, install all dependencies first as shown under 'Installation' and then change the style_path and content_path strings in the notebook to the path of your images.
* Tune the hyperparameters according to your preference.

## To Be Added

Easily accessible demo for style transfer.

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Acknowledgements
* [This documentation](https://www.tensorflow.org/api_docs/python/tf/GradientTape) provided valuable information about Gradient Tape.
* Some code was borrowed from [this tutorial](https://www.tensorflow.org/tutorials/generative/style_transfer).
