# Smart-Traffic-Optimisation
Optimise traffic flow with ease using AI

# Colab workspace - 
https://colab.research.google.com/drive/15tmr25W2pm3PhkyKjbxVPWXs1pdgoVJX?usp=sharing

<div align="center">
<img src="assets/output.gif" width="1000px" height="600px">
</div>

## Pre-requisites : 

1) Clone the Repository [vehicle-counting-yolov5](https://github.com/Yashwanth-Chandrakumar/Smart-Traffic-Optimisation.git)

```bash
git clone https://github.com/Yashwanth-Chandrakumar/Smart-Traffic-Optimisation.git

cd Smart-Traffic-Optimisation
```

2) Clone the legacy Yolo-v5 Repository

```bash
git clone https://github.com/ultralytics/yolov5.git
```
   
4) Install the libraries
```bash
pip install -r requirements.txt
```


## Directory Structure :

After completing the above steps your directory should look like somewhat as of below structure

- `Smart-Traffic-Optimisation`
   - deep_sort
   - yolov5
   - input.mp4
   - yolov5s.pt
   - tracker.py
   - requirements.txt

## Run the algorithm 

``` bash
python tracker.py 
# This will download model weight - yolov5s.pt to base folder on first execution.
```

