# t-spark-ml-test
## Results:
1

![image](https://github.com/AlexTsikhun/t-spark-ml-test/assets/83775762/5de5dec6-9275-4a6a-94e3-880b5c51f7e7)
![image](https://github.com/AlexTsikhun/t-spark-ml-test/assets/83775762/1fe81f8d-c8ae-4c53-a84f-785b31b0dc73)

2

![image](https://github.com/AlexTsikhun/t-spark-ml-test/assets/83775762/3fe25a7f-d3e8-4cd3-ba62-432a19bb3b1e)
![image](https://github.com/AlexTsikhun/t-spark-ml-test/assets/83775762/7f14ea74-b4b0-4a77-965f-8db314b2d008)

3

![image](https://github.com/AlexTsikhun/t-spark-ml-test/assets/83775762/8c415df5-cfc9-4a47-837b-0f665cfb7ea9)
![image](https://github.com/AlexTsikhun/t-spark-ml-test/assets/83775762/f76ef22a-1dad-472c-8646-61b710ce4612)

For all classes combined:

- Precision (P): 0.744
- Recall (R): 0.581
- Mean Average Precision (mAP) at IoU threshold 0.50: 0.659
- Mean Average Precision (mAP) at IoU thresholds 0.50 to 0.95: 0.382

The model is working, the results will be better if you train it longer (1 epoch is not enough for reach good output. It confirms the misclassificated chair as a person (images above), or bounding box that include part of horse)
