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
![qr1](https://github.com/sobit-nep/Django-QRCodeGenerator/assets/65544518/17a4e212-de1e-45ad-8126-ae70d099c508)
![qr2](https://github.com/sobit-nep/Django-QRCodeGenerator/assets/65544518/96d6a5df-4f28-4761-a9e2-b9fd1357ce02)

1. Enter any text or link in the provided input field.
2. Click the "Generate" button to generate the corresponding QR code.
3. The generated QR code will be displayed on the screen.
4. Click the "Download" button to download the QR code as a PNG image.
5. Click the "Share" button to share the QR code through various platforms.

## Contributing

Contributions are welcome! If you have any suggestions, improvements, or bug fixes, please submit a pull request.
