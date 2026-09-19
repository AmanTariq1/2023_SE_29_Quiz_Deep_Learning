### 🧾 DeepLearning-Quiz02_2023-SE-29 ###

### Quiz 2 — Receipt and Slip Image Segmentation
This project uses OpenCV to segment multiple receipts/slips from a combined image.

### Features
* Removes unwanted scanner/image borders
* Detects individual receipts using contour detection
* Crops each detected slip separately
* Identifies very tall combined receipts
* Splits tall receipts at horizontal gaps
* Saves a preview image with detected slip boundaries
* Downloads all cropped slips as a ZIP file

### Technologies Used
- Python
- OpenCV
- NumPy
- Google Colab

### How to Run
- Open the provided code in Google Colab.
- Run the complete code cell.
- Upload the combined receipt image when prompted.
- The program detects and saves each individual receipt.
- A segmentation preview is displayed.
- The cropped receipt images are downloaded as a ZIP file.

### Output
The output ZIP file contains:

output_slips/

├── slip_1.jpg

├── slip_2.jpg

├── slip_3.jpg

├── slip_4.jpg

├── slip_5.jpg

└── Segmentation.jpg

segmentation_preview.jpg shows the final detected receipt regions with bounding boxes.

### Result
The system successfully separates standard receipts and splits extra-tall combined slips into individual receipt images.
