# Invisible Cloak

Invisible Cloak is a Python project that creates a visual effect similar to an invisibility cloak using computer vision techniques. By leveraging color detection and masking, the program makes a specific colored object (e.g., a red cloth) appear invisible against a live video feed.

## Features

- **Real-time Invisibility Effect**: Applies the invisibility effect in real-time using your webcam.
- **Customizable Cloak Color**: Easily set the target color to be rendered invisible.

## Prerequisites

Before running the project, ensure you have the following installed:

- **Python 3.x**: The programming language used for this project.
- **OpenCV**: Library for computer vision tasks.

You can install the required packages using pip:

```bash
pip install opencv-python
```

## Usage

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/thedevbarbie/invisible_cloak.git
   cd invisible_cloak
   ```

2. **Run the Script**:

   ```bash
   python main.py
   ```

3. **Using the Cloak**:

   - Ensure your webcam is connected.
   - Wear or hold an object of the target color (default is red).
   - Stand in front of the camera; the object should appear invisible in the video feed.

## Customization

To change the target color:

1. Open `main.py` in a text editor.
2. Locate the section where the color range is defined (using HSV values).
3. Adjust the HSV range to match the desired cloak color.

For example, to set the cloak color to blue:

```python
# Define the HSV range for blue color
lower_blue = np.array([94, 80, 2])
upper_blue = np.array([126, 255, 255])
```

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.


## Acknowledgments

- Inspired by various computer vision projects demonstrating invisibility cloaks.
- Thanks to the OpenCV community for their extensive documentation and support.

---

Feel free to explore, modify, and enhance the Invisible Cloak project. Happy coding! 
