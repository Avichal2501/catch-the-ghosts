# Catch the Ghosts - Simple Duplicate Image Detector

This project detects duplicate images in a photo digitization system. It checks for identical images within and across customer orders and prints notifications to the console.

## How It Works
- Computes ph hashes of image files to find exact duplicates.
- Stores photo data (Order ID, Photo ID, hash) in a JSON file.
- Prints duplicate alerts to the console.
- Includes basic tests to check hash and duplicate detection.

## Setup
1. Clone the repository:
   ```bash
   git clone <repo-url>
   cd catch-the-ghosts


#### **6. Sample Images**
Create an `images/` directory with:
- `sample1.jpg`: Any image.
- `sample1_copy.jpg`: An exact copy of `sample1.jpg` (e.g., duplicate the file).
- `sample2.jpg`: A different image.

If you don’t have images, you can create them using a simple tool like Paint or download sample images. Ensure `sample1.jpg` and `sample1_copy.jpg` are identical.

### How to Run
1. **Setup**:
   - Create the `photos/` directory and add the sample images.
   - No dependencies to install since we’re using standard Python libraries.
2. **Run the Main Script**:
   ```bash
   python main.py