# Setup Enviroment:
- Clone YOLOv3 with link:
git clone https://github.com/experiencor/keras-yolo3.git $lab_path
- download libary:
pip install -r $lab_path/requirements.txt
- download weight: 
!wget https://pjreddie.com/media/files/yolov3.weights -O $lab_path/yolov3.weights"
- download raccoon dataset:
git clone https://github.com/experiencor/raccoon_dataset.git $lab_path/raccoon_dataset
- Change raccoon config: keras-yolov3/zoo/config_raccoon.json
![metric history](https://user-images.githubusercontent.com/22994077/87879218-97e86280-ca13-11ea-868f-d48e4e4c7609.png)
- loss function: 1.44
- raccoon: 0.97




