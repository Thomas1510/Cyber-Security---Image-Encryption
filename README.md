# Image Steganography

This project is an Image Steganography tool that allows you to hide and extract text within image files. It uses a graphical user interface (GUI) built with Tkinter to facilitate user interaction.

## Features

- **Encode:** Hide a secret message within an image file.
- **Decode:** Extract the hidden message from an image file.
- **Supported Formats:** Works with PNG, JPEG, and JPG image formats.
- **User-Friendly Interface:** Simple and intuitive GUI for easy operation.

## Requirements

- Python 3.x
- Pillow (PIL Fork)
- Tkinter (comes pre-installed with Python)

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/Thomas1510/ImageSteganography.git
    ```
2. Navigate to the project directory:
    ```sh
    cd ImageSteganography
    ```
3. Install the required dependencies:
    ```sh
    pip install pillow
    ```

## Usage

1. Run the application:
    ```sh
    python steganography.py
    ```
2. Use the buttons on the main screen to either encode or decode a message in an image.
3. Follow the prompts to select an image and either hide or extract the secret message.

### Encode a Message

1. Click on the "Encode" button.
2. Select the image in which you want to hide the text.
3. Enter the message you want to hide in the text area provided.
4. Save the new image file with the hidden message.

### Decode a Message

1. Click on the "Decode" button.
2. Select the image from which you want to extract the hidden text.
3. The hidden message will be displayed in the text area.

## Project Demo
![Output](Output/Image Encryption.mp4).



## Project Structure

- `steganography.py`: Main script containing the Stegno class and the Tkinter GUI.
- `README.md`: Project documentation.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## Contact

For any questions or issues, please open an issue on GitHub.

---

This project was created as part of my internship at Slash Mark Company. Feel free to check out my other projects on [GitHub](https://github.com/Thomas1510).
