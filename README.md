# Fire and Gun Detection


### How to use yolo.py:
```
usage: yolo.py [-h] [--webcam WEBCAM] [--play_video PLAY_VIDEO]
               [--image IMAGE] [--video_path VIDEO_PATH]
               [--image_path IMAGE_PATH] [--verbose VERBOSE]

optional arguments:
  -h, --help            show this help message and exit
  --webcam WEBCAM       True/False
  --play_video PLAY_VIDEO
                        Tue/False
  --image IMAGE         Tue/False
  --video_path VIDEO_PATH
                        Path of video file
  --image_path IMAGE_PATH
                        Path of image to detect objects
  --verbose VERBOSE     To print statements
```

### Weights File Backup

If the GitLFS file is not accessible - Download [Weights](https://1drv.ms/u/s!Aj0l1DM1G5wOm0Vg2n7RI5Q4_ZOq?e=gGvvMy) and keep inside the project folder.


### Move inside the project folder and use the following command:
```
python yolo.py --play_video True --video_path videos/fire1.mp4
```

[Dataset](https://www.kaggle.com/atulyakumar98/fire-and-gun-dataset)



