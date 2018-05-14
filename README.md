# Comics_Generation
MLDS2017 Project 4

Project Link: https://www.csie.ntu.edu.tw/~yvchen/f106-adl/A4

Conditional Generative Adversarial Network (CGAN) is implemented to automatically generate anime images based on the given constraints (ex: green hair, blue eyes).
## Dataset
Download Link: https://drive.google.com/drive/folders/1bXXeEzARYWsvUwbW3SA0meulCR3nIhDb. tag_clean.csv includes multiple tags (hair color, eyes color, etc..) for each anime image. 
## Quick start
1. Download Dataset from link above.

2. Run the shell script!
```
./run.sh [test file]
```
[test file] should be <testing_text.txt> in the main folder. You can modify content if want different result.
## Training
In image_generation.py, change mode = 1 (line 20) to be mode = 0, then do the Quick Start!
## Demo Results
We test our model with test file below (testing_text.txt)

```
1,blue hair blue eyes
2,grey hair green eyes
3,green hair red eyes
4,red hair green eyes
5,green hair blue eyes
```

Generated Samples will be like

![image](https://github.com/danielchyeh/Comics_Generation/blob/master/assets/samples.png)

## References
- [paarthneekhara/text-to-image](https://github.com/paarthneekhara/text-to-image)

- [carpedm20/DCGAN-tensorflow](https://github.com/carpedm20/DCGAN-tensorflow)
