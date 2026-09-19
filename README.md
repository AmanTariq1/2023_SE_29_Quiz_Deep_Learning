# DeepLearning-Quiz02_2023-SE-29

## Quiz 2 — Receipt and Slip Image Segmentation

This project uses **OpenCV** to segment multiple receipts/slips from a single combined image. The system detects individual receipts, separates them, and saves the cropped results automatically.

## Features

* Removes unwanted scanner/image borders
* Detects individual receipts using contour detection
* Crops each detected receipt separately
* Identifies unusually tall combined receipts
* Splits tall receipts using horizontal gaps
* Generates a segmentation preview with detected boundaries
* Saves all cropped receipts into a ZIP file

## Technologies Used

* **Python**
* **OpenCV**
* **NumPy**
* **Google Colab**

## How to Run

1. Open the provided notebook in **Google Colab**.
2. Run the complete code.
3. Upload the combined receipt/slip image when prompted.
4. The system detects and separates the individual receipts.
5. A segmentation preview is generated.
6. The cropped receipt images are saved and downloaded as a ZIP file.

## Output

The generated ZIP file contains the segmented receipt images:

```text
output_slips/
├── slip_1.jpg
├── slip_2.jpg
├── slip_3.jpg
├── slip_4.jpg
├── slip_5.jpg
└── Segmentation.jpg
```

The segmentation preview shows the detected receipt regions with bounding boxes.

## Result

The system successfully separates standard receipts and handles extra-tall combined slips by splitting them into individual receipt images.

## Student Information

**Name:** Aman Tariq
**Roll No:** 2023-SE-29
**Course:** Deep Learning
**Quiz:** Quiz 02
