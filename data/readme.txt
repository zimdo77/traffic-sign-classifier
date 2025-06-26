Directory Structure:
--------------------
The project is organized as follows:

- train\
    Folder with training image
	- train_metadata.csv
    		Metadata for training images (ids, image filenames and class labels)

- test\
    Folder with test images 
	- test_metadata.csv
    		Metadata for test images (ids, image filenames only, no labels)

- README.txt
    This file

Data:
-----
- 5488 training images with class labels
- 2353 test images without labels
- 43 total traffic sign classes

Submission Format (Kaggle) (CSV):
------------------------
Final submission should follow this structure:

Id,ClassId
67.jpg,4
94,2
...
521.jpg,12