# CUDA Applications

CUDA Applications

This alwaysAI application set use a CUDA (Compute Unified Device Architecture) interface which allows CNN models to execute on  NVIDIA  GPUs found on Jetson devices.  CUDA APIs give applications executing on the CPU direct access to NVIDIA’s GPU’s virtual instruction set and parallel computational elements.

The application set covers all major CNN types like classification, object detection, semantic segmentation and instance segmentation.## Repo Programs
| Folder                     	| Description                                                                                              	|
|----------------------------	|----------------------------------------------------------------------------------------------------------	|
| bottle-classifier   | Program use googlenet classifier to find water bottles|
| bottle-detector 	  | Program uses tiny-yolo3 object detection network to find water bottles|
| bottle-segmentation | Program uses fcn semantic segmentation to find water bottles|
| bottle-instance     | Program uses instance segmentation to find water bottles|
| csi-camera          | Program uses csi camera using object detectionto find water bottles|
| autonomous-vechicle | Program demostartes how semantic segmentation is used in autonomous car applications|

## Setup

This app requires an alwaysAI account. Head to the [Sign up page](https://www.alwaysai.co/dashboard) if you don't have an account yet. Follow the instructions to install the alwaysAI tools on your development machine.

Next, create an empty project to be used with this app. When you clone this repo, you can run `aai app configure` within the repo directory and your new project will appear in the list.

## Usage

Once the alwaysAI tools are installed on your development machine (or edge device if developing directly on it) you can run the following CLI commands:

To set up the target device & install path

```
aai app configure
```

To install the app to your target

```
aai app install
```

To start the app

```
aai app start
```
