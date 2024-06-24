# YOLO-Aircraft-detection
YOLO to Classify Different Types of Aircraft


dataset:
Military Aircraft Detection Dataset from kaggle:
https://www.kaggle.com/datasets/a2015003713/militaryaircraftdetectiondataset
dataset encompasses 50 different military aircraft types, with some types merged as one class along with their variants

Data preprocessing:
Default csv labels: width, height, class, xmin, ymin, xmax, ymax
Target label structure: class_num, x_center, y_center, width, heigth

Input dataset for training will be in below format:
yolo_final_dataset/

    images/
        train/*.jpg
        val/*.jpg
        test/*.jpg

    labels/
        train/*.txt
        val/*.txt
        test/*.txt  

Results from various experiments:

<img width="464" alt="Screenshot 2024-06-24 at 11 24 57" src="https://github.com/sneha-h/YOLO-Aircraft-detection/assets/7019246/b6420ee7-3ddd-4b3a-bf0d-ec2ec679ad0a">

