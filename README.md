## NOTE:
- Download the data from the [drive link](https://drive.google.com/drive/folders/1puaSxRYmTT6RtoC-EfpuRezmv4C5AsoV?usp=sharing), the data is converted into the yolov5 datapipeline format

- Download the trained model from the [drive link](https://drive.google.com/drive/folders/1puaSxRYmTT6RtoC-EfpuRezmv4C5AsoV?usp=sharing)

- Navigate the downloaded data folder and model in this home directory

## Inference:
```
$ python detect.py --source 0  # webcam
                            file.jpg  # image 
                            file.mp4  # video
                            path/  # directory
                            path/*.jpg  # glob
                            'https://youtu.be/NUsoVlDFqZg'  # YouTube
                            'rtsp://example.com/media.mp4'  # RTSP, RTMP, HTTP stream
```
