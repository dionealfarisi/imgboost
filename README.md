# ImgBoost

ImgBoost is a Python package for enhancing images by adjusting brightness, contrast, and sharpness. It also includes noise reduction using OpenCV.

## Installation

You can install the package using pip:

```bash
pip install imgboost
```
Usage

To enhance an image, use the following command:

boost input_image.jpg output_image.jpg --brightness 1.5 --contrast 1.4 --sharpness 1.8

Command Line Options

input_image: Path to the input image file.

output_image: Path to save the enhanced image file.

--brightness: Factor to adjust brightness (default: 1.2).

--contrast: Factor to adjust contrast (default: 1.3).

--sharpness: Factor to adjust sharpness (default: 2.0).


Example

boost example.jpg enhanced_example.jpg --brightness 1.5 --contrast 1.4 --sharpness 1.8

This command will read example.jpg, enhance it with the specified parameters, and save the result as enhanced_example.jpg.

License

This project is licensed under the MIT License - see the LICENSE file for details.

Author: Dione Alfarisi
Email: ardionefarisi1322@gmail.com
GitHub: dionealfarisi
