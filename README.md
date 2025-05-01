
# Face Detection with RetinaFace

This project demonstrates how to use the **RetinaFace** model for face detection using OpenCV and Matplotlib.

## Requirements

- Python 3.x
- `opencv-python`
- `matplotlib`
- `retinaface`

To install the necessary dependencies, you can use the following command:

```bash
pip install -r requirements.txt
```

## Project Structure

```
.
├── main.py  # Main script for face detection
├── test.jpg             # Example image for face detection
├── requirements.txt      # List of Python dependencies
└── README.md             # Project documentation
```

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME
```

2. Install the dependencies:

```bash
pip install -r requirements.txt
```

3. Run the face detection script:

```bash
python retinaface_detect.py
```

This will read an image (`test.jpg`), detect faces, and display the image with rectangles drawn around the detected faces.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
