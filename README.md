## PHD08 Conversion

> Save the [phd08](https://www.dropbox.com/s/69cwkkqt4m1xl55/phd08.alz?dl=0) dataset as .png or convert it to a npy file format that can be converted directly into a numpy array.
The image / text will be blurred with the Gaussian filter that was in the original binary.

## Requirements
- python3
- numpy
- matplotlib
- scipy

## Usage
### phd08_to_png.py
- **help**
```
python phd08_to_png.py --help
```

- **phd08** to **png**
```
python phd08_to_png.py --data_dir=DATA_DIR [--width=WIDTH] 
                       [--height=HEIGHT] [--gaussian_sigma=GAUSSIAN_SIGMA]  
```
> result in ./phd08_png_results/

### phd08_to_np_arr.py
- **help**
```
python phd08_to_np_arr.py --help
```

- **phd08** to **npy**
```
phd08_to_npy.py [-h] --data_dir DATA_DIR [--one_hot] [--width WIDTH]
                     [--height HEIGHT] [--gaussian_sigma GAUSSIAN_SIGMA]
```
> result in ./phd08_npy_results/

## Example & Screenshot
```
python phd08_to_png.py --data_dir=phd08_png_results --width=10 --height=10
```
![screenshot2](./images/screenshot_2.png)

![screenshot1](./images/screenshot_1.png)
