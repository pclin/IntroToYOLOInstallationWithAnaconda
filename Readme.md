# YOLO Installation with Anaconda

We introduce the installation of YOLOv3 object detection with Anaconda.

------

## Install Anaconda

Go to this web page to download Anaconda.

Be careful to choose the operating system that you use.

https://www.anaconda.com/distribution/#download-section

Make it executable.

```
chmod +x Anaconda3-2019.03-Linux-x86_64.sh
```

Install Anaconda.

```
./Anaconda3-2019.03-Linux-x86_64.sh
```

Deactivate conda's base environment on startup.

```
conda config --set auto_activate_base false
```

Close and re-open the terminal to let the configuration changes take effect.

------

## Create and Run a Virtual Environment for YOLO

Create a virtual environment.

```
conda create -n yolov3 python=3.7
```

you can change the name "yolov3" here to be any other name you want.

Activate the virtual environment.

```
conda activate yolov3
```

Note that there would be the name of the virtual environment ahead the command prompt.

From now on, we perform all the following operations in this virtual environment.

------

Install Software Packages

