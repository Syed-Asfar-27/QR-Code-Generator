# QR Code Generator in Python

This is a simple Python script that allows you to generate QR codes from URLs and save them as image files. You can use this tool to quickly create QR codes for any URL and share them with others.

## Prerequisites

Before using the script, make sure you have the following Python libraries installed:

- `qrcode`: for generating QR codes
- `PIL` (Pillow): for working with images

You can install these libraries using the following command:

```bash
!pip install qrcode[pil]
```

## Usage

1. Clone this repository or download the `qrcode_generator.ipynb`  script to your local machine.

2. Run the script using a Python environment. It will prompt you to enter a URL for which you want to generate a QR code.

3. Enter the URL and specify the filename for the QR code image. You can provide the filename with or without the ".png" extension. If you don't provide an extension, the script will automatically add ".png."

4. The QR code will be generated and saved in the current working directory with the specified filename.

5. You can share the saved QR code with others by sending the image file.

## Example

Here's an example of how to run the script:

```bash
python qrcode_generator.ipynb
```

The script will guide you through the URL and filename input process.


## Acknowledgments

- This project uses the `qrcode` library to generate QR codes.
- The QR code image is created and saved using the `PIL` (Pillow) library.

Feel free to use, modify, and share this script as needed. If you encounter any issues or have suggestions for improvements, please open an issue or create a pull request.
