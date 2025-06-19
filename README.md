DATASET CONTENTS
----------------
1.) README.txt - this file
2.) capture_surface_illustration.jpg - an illustration of the capture surface, camera, and lighting
3.) train_coded - folder containing all images intended for training
4.) test_coded - folder containing all images intended for testing
5.) train_sizes.csv - map of train images to the their sizes
6.) test_sizes.csv - map of test images to the their sizes
7.) train_bboxes.csv - map of train images to the bounding box of the micro-pcbs within the images
8.) test_bboxes.csv - map of test images to the bounding box of the micro-pcbs within the images
9.) train_angles.csv - map of train images to the angle of the micro-pcbs within the images
10.) test_angles.csv - map of test images to the angle of the micro-pcbs within the images
11.) train_ratio_top_to_bottom.csv - map of train images to the ratio of the length of the top edge of the micro-pcbs within the images relative to its bottom edge
12.) train_ratio_top_to_bottom.csv - map of test images to the ratio of the length of the top edge of the micro-pcbs within the images relative to its bottom edge


Image Name Codes
----------------
1st character: Identifies the model of the micro-pcb within the image
				A - Raspberry Pi A+
				B - Arduino Mega 2560 (Blue)
				C - Arduino Mega 2560 (Black)
				D - Arduino Mega 2560 (Black and Yellow)
				E - Arduino Due
				F - Beaglebone Black
				G - Arduino Uno (Green)
				H - Raspberry Pi 3 B+
				I - Raspberry Pi 1 B+
				J - Arduino Uno Camera Shield
				K - Arduino Uno (Black)
				L - Arduino Uno WiFi Shield
				M - Arduino Leonardo

2nd character: Identifies the rotation of the micro-pcb within the image
				A - Wide left rotation
				B - Shallow left rotation
				C - Neutral rotation
				D - Shallow right rotation
				E - Wide right rotation

3rd character: Identifies the X coordinate the micro-pcb was in on the capture surface
				A - 12 inches left of the camera position
				B - 6 inches left of the camera position
				C - centered horizontally relative to the camera
				D - 6 inches right of the camera position
				E - 12 inches right of the camera position

4th character: Identifies the Y coordinate the micro-pcb was in on the capture surface
				A - 12 inches above the camera position
				B - 6 inches above the camera position
				C - centered vertically relative to the camera
				D - 6 inches below the camera position
				E - 12 inches below the camera position

5th character: A serial number of the capture in the rotation and position identified by the 2nd-4th characters.
				1-4 - Images numbered 1-4 are train images
				 5  - Images numbered 5 are test images.
