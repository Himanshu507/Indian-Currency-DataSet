# Indian Currency Dataset for YOLO

This dataset contains images of Indian currency notes of various denominations including 10 rupees, 20 rupees, 50 rupees, 100 rupees, 200 rupees, and 500 rupees. The dataset is prepared for training object detection models, particularly YOLO (You Only Look Once).

## Dataset Contents

- Images: Contains images of Indian currency notes in various lighting conditions, orientations, and backgrounds.
- Annotations: Annotation files in YOLO format (.txt) corresponding to each image, containing bounding box coordinates and class labels.
- Classes: Information about the classes represented in the dataset, i.e., Indian currency denominations.
- detect.yaml: Configuration file for YOLO, containing paths to images, validation data, and class information.

## Directory Structure

<pre>
Indian_Currency_Dataset/
│
├── Images/
│   ├── 10_rupee/
│   ├── 20_rupee/
│   ├── 50_rupee/
│   ├── 100_rupee/
│   ├── 200_rupee/
│   └── 500_rupee/
│
├── Annotations/
│   ├── 10_rupee/
│   ├── 20_rupee/
│   ├── 50_rupee/
│   ├── 100_rupee/
│   ├── 200_rupee/
│   └── 500_rupee/
│
├── Classes.txt
│
└── detect.yaml
</pre>



## Usage

1. Download or clone the dataset.
2. Ensure YOLO is properly set up on your system.
3. Modify the `detect.yaml` file to specify the paths to your dataset images and validation data, and update class information if necessary.
4. Train your YOLO model using the provided dataset.

## License

This dataset is provided under GPL license. Please review the license file before using the dataset for any purpose.

## Contributors

- Himanshu

## Contact

For any inquiries or issues regarding the dataset, please contact himanshu.ducs19@gmail.com
