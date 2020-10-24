# Programming Projects for Advanced Beginners #4: Photomosaics

Example code for [Programming Projects for Advanced Beginners #4: Photomosaics](https://robertheaton.com/2018/11/03/programming-project-4-photomosaics).

## To run

To install PIL:

* Install `virtualenv` and `pip`
* `virtualenv vendor`
* `pip install -r requirements.txt`

Then whenever you need to run the code, first run:

* `source vendor/bin/activate`

to load PIL.

Place all your source images in `./source_images`, then run
`sudo python square_images.py` to convert them into squares. Then
run `sudo python mosaic.py`, making sure that the code points to
the location of your input image.

# PHOTO CREDITS

* Example source images taken from [Flower Dataset](https://www.kaggle.com/alxmamaev/flowers-recognition) by Alexander Mamaev.
* Example input image from [u/ownnc-nz on Reddit](https://www.reddit.com/r/WTF/comments/16fnfn/visited_monkey_bay_in_thailand_everyone_fucking/).
