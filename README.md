## Sauron-doc-rotation

[![PyPI version](https://badge.fury.io/py/alyn.svg)](https://badge.fury.io/py/alyn)
![Static Badge](https://img.shields.io/badge/python-3.10.*-blue)
![Static Badge](https://img.shields.io/badge/license-MIT-blue)

The Sauron DOC rotation is a simple project that aims to rotate a base64 image to keep it in the correct direction.

### How to use?

You can use the **rotate_image_base64** method in **sauron_rotate** to rotate your base64 image.

The following code shows how you can use this method.

```python
from sauron_doc_rotate.sauron_rotate import SauronRotate

sr = SauronRotate(enable_logging=False)

sr.rotate_image_base64(img_base64)
```

* Method / Class parameters
  * `enable_logging` - whether or not to show logs during code execution 

* Method returns
  * A dict with two values:
    * `angles_for_rotation` - the angles tuple used to rotate the imagem  
    * `rotated_img_base64` - the base64 image in the correct direction
