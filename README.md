# QR Code Generator

This web application allows users to generate QR codes for any text or link input. It is built using Django and utilizes the qrcode library for generating QR codes.

## Features

- Enter any text or link to generate a corresponding QR code.
- Download the generated QR code as a PNG image.
- Share the QR code through various platforms.

## Installation

1. Clone the repository to your local machine:

   ```
   git clone https://github.com/sobit-nep/QRCodeGenerator.git
   ```

2. Navigate to the project directory:

   ```
   cd qrg
   ```

3. Create a virtual environment:

   ```
   python -m venv venv
   ```

4. Activate the virtual environment:

   - For Windows:

     ```
     venv\Scripts\activate
     ```

   - For macOS/Linux:

     ```
     source venv/bin/activate
     ```

5. Install the dependencies:

   ```
   pip install -r requirements.txt
   ```

6. Run the development server:

   ```
   python manage.py runserver
   ```

7. Access the application in your web browser at `http://localhost:8000`.

## Usage

1. Enter any text or link in the provided input field.
2. Click the "Generate" button to generate the corresponding QR code.
3. The generated QR code will be displayed on the screen.
4. Click the "Download" button to download the QR code as a PNG image.
5. Click the "Share" button to share the QR code through various platforms.

![qr4](https://github.com/sobit-nep/Django-QRCodeGenerator/assets/65544518/ca054874-11dd-4e2d-80f1-362acd0f1f6e)
![qr3](https://github.com/sobit-nep/Django-QRCodeGenerator/assets/65544518/ecd1e01d-4ff7-4bf0-85b9-b159cf456857)


## Contributing

Contributions are welcome! If you have any suggestions, improvements, or bug fixes, please submit a pull request.
