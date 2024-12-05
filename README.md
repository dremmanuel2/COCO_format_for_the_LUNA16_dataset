the LUNA16 dataset should tansform to Coco format when we need use it to train our modle
the COCO_format_for_the_LUNA16_dataset.zip possesses 3 file.
.
├── annotations/
│ ├── PN_train.json
│ ├── PN_test.json
│ └──
├── PN_train/
│ ├── img_00008.jpg
│ ├── img_00634.jpg
│ └──
├── PN_test/
│ ├── img_00877.jpg
│ ├── img_01085.jpg
│ └──
└──
the number of PN_train's images is 869,the number of PN_test's images is 217,total is 1085.
Hence, the dataset is split into a training set and a testing set at a ratio of 80% to 20%.
PN_train.json and PN_test.json have the similar content.
{
   
    "images": [
        {
            "file_name": "img_00000.jpg",
            "id": 1
        },
        ...
    ],
    "annotations": [
        {
            "id": 31,
            "image_id": 32,
            "category_id": 1,
            "segmentation": [
                [
                    382,
                    304,
                    389,
                    304,
                    389,
                    311,
                    382,
                    311
                ]
            ],
            "bbox": [
                382,
                304,
                7,
                7
            ],
            "area": 49,
            "iscrowd": 0
        },
        ...
    ],
    "categories": [
        {
           "supercategory": "PN",
            "id": 1,
            "name": "yes"
        },
        ...
    ]
}
