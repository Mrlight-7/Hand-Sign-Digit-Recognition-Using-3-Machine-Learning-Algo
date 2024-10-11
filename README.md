# Sign Language Detector using Custom ML Model

This project is capable of reading 31 different signs, including 26 alphabets and 5 words.

![Reference Images](ref_1.png)
![Reference Image 2](ref_2.jpg)

The following words can be recognized: Yes, No , Please, Thank You, Hello

## Required Libraries
To install all the required libraries, run the following command in your terminal:

```bash
pip install -r requirements.txt
```
## Getting Started
Follow these steps to get the program up and running:

->Run collect_data.py to collect images.

->Run create_dataset.py to generate the data.pickle file.

->Run train_model.py to generate the ML model.

->Finally, run main.py to run the application!

**Note: The repository already contains the model and data files. You only need to install the required libraries and run main.py. The above steps are required only if you want to create your own dataset/ML model.**
