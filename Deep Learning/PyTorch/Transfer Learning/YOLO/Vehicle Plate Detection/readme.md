# YOLOv8 Vehicle Plate Detection
This project based on [jonG312's repository](https://github.com/jonG312/YOLOv8-Vehicle-Plate-Recognition)

Before running the ipynb file, there are several things you need to be setting off:

1. Setting up the folder "our-own-training-set"
Please read the readme section within the folder

2. Path's related configuration
I've set up variables within `main.ipynb` and `config.yaml` for the path to training session since I'm not using Google Collab here. Consider to edit it and matching it so it is OS readable. 

3. Telegram notifier
Consider to replace the `":botid"` and `":chatid"` with your own bot id and chat id. Other wise it will not work. If you wish to not using that, you can just delete the functionality.

The whole training environment is using PIP, because it need ultralytics.

### Setting up environment

```shell
pip install -r requirements.txt
```