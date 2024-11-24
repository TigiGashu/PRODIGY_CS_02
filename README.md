Image Encryption Tool
A Python-based tool to encrypt and decrypt images using pixel manipulation. This lightweight tool lets users secure their images with a custom key, offering a simple yet effective way to protect visual data.

🚀 Features
Encrypt Images: Transform pixel values using a user-provided key to create encrypted images.
Decrypt Images: Reverse the pixel manipulation using the same key to restore the original image.
Supported Formats: Compatible with common image formats like PNG, JPG, and BMP.
Simple Interface: Easy-to-use terminal-based interface with clear prompts for input.
🛠️ Installation
Prerequisites
Python 3.x installed on your machine.
Required Python libraries: Pillow and NumPy.
Install dependencies using:

bash
Copy code
pip install pillow numpy
📋 Usage
Clone the Repository:

bash
Copy code
git clone https://github.com/your-username/image-encryption-tool.git
cd image-encryption-tool
Run the Tool:

bash
Copy code
python image_encryption_tool.py
Follow the Menu Options:

Choose to encrypt or decrypt an image.
Enter the image file path, a numeric key, and the output file path.
The tool will process and save the image accordingly.
🔑 Example Workflow
Encrypt an Image:

Input: original_image.jpg
Key: 42
Output: encrypted_image.jpg
Decrypt an Image:

Input: encrypted_image.jpg
Key: 42
Output: restored_image.jpg
The decrypted image will match the original image only if the same key is used.

⚠️ Important Notes
The key used during encryption is mandatory for decryption.
The original image remains unmodified; the output is saved as a new file.
Make sure the key is a numerical value.
📦 Dependencies
Pillow: For image loading, manipulation, and saving.
NumPy: For efficient pixel-level transformations.
Install using:

bash
Copy code
pip install pillow numpy
