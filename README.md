# Programming Project: Photo-Mosaics

* Convert an input image into a mosaic art. Included caching mechanism to fetch the source images faster.


To install PIL:
* Install `virtualenv` and `pip`
* `virtualenv vendor`
* `pip install -r requirements.txt`

Then whenever you need to run the code, first run:
* `source vendor/bin/activate`
to load PIL.

Place all your source images in `./source_images` 
Then run:
`sudo python square_images.py` to convert them into squares.
Then run:
`sudo python mosaic.py`, making sure that the code points to
the location of your input image.
Final image gets created and stored in image called `final.jpg`



# Source Images Dataset:
* Example source images taken from [Flower Dataset](https://www.kaggle.com/alxmamaev/flowers-recognition) by Alexander Mamaev.
* Example input_image from local file. /Copyright Image/
