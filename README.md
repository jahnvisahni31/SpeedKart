# Walmart Sparkathon: speedkart

## Project Overview

The **speedkart** is an innovative video streaming platform designed to streamline the checkout process in retail environments. By integrating YOLO (You Only Look Once) for real-time object detection and a Raspberry Pi for processing, this solution allows customers to automatically scan and bill items directly at the cart. The system generates a receipt and a QR code for easy checkout, enhancing the shopping experience.

## Key Features

- **Automatic Item Detection:** Utilizes YOLO for accurate and real-time object detection to identify items placed in the cart.
- **Seamless Checkout:** Bills items directly at the cart, eliminating the need for traditional checkout counters.
- **Receipt Generation:** Automatically generates a digital receipt for the purchased items.
- **QR Code Integration:** Provides a QR code for quick and secure checkout.

## Components

1. **Raspberry Pi:** Acts as the central processing unit for running the YOLO model and managing the video stream.
2. **YOLO (You Only Look Once):** Real-time object detection algorithm for identifying items in the cart.
3. **Camera Module:** Captures video footage of the cart's contents for processing by YOLO.
4. **Receipt Printer (Optional):** Prints a physical receipt if required.
5. **QR Code Generator:** Creates a QR code that contains checkout information for easy payment processing.

## Installation and Setup

1. **Hardware Requirements:**
   - Raspberry Pi (Model 3B+ or later)
   - Camera module compatible with Raspberry Pi
   - Access to a receipt printer (if required)

2. **Software Requirements:**
   - Raspberry Pi OS (or any compatible Linux distribution)
   - YOLO pre-trained model
   - Python 3.x
   - OpenCV library
   - Additional Python libraries for QR code generation and receipt handling

3. **Installation Steps:**
   1. **Set up the Raspberry Pi:**
      - Install Raspberry Pi OS and update it.
      - Connect the camera module and ensure it's functioning correctly.

   2. **Install YOLO:**
      - Follow YOLO installation instructions from [YOLO GitHub repository](https://github.com/AlexeyAB/darknet) or other reliable sources.
      - Download the pre-trained YOLO weights.

   3. **Install Python Dependencies:**
      ```bash
      pip install opencv-python
      pip install qrcode[pil]
      ```

   4. **Clone the Project Repository:**
      ```bash
      git clone https://github.com/yourusername/smart-checkout-cart.git
      cd smart-checkout-cart
      ```

   5. **Configure YOLO:**
      - Place the YOLO weights and configuration files in the appropriate directories.

   6. **Run the Application:**
      ```bash
      python walmartsparkathon.ipnyb
      ```

## Usage

1. **Place Items in Cart:**
   - As items are added to the cart, the system uses the camera to capture video and YOLO to detect the items.

2. **Automatic Billing:**
   - The detected items are billed automatically without requiring additional actions from the user.

3. **Checkout and Receipt:**
   - Upon completing the shopping, the system generates a digital receipt and a QR code.
   - The QR code can be scanned at a payment terminal for secure checkout.

## Troubleshooting

- **Camera Not Detected:**
  - Ensure the camera module is properly connected and enabled in the Raspberry Pi settings.
- **YOLO Errors:**
  - Verify that the YOLO configuration files and weights are correctly placed and accessible.

## Future Improvements

- **Enhanced Object Recognition:** Implement custom models for better accuracy in detecting specific items.
- **Integration with Payment Systems:** Develop APIs to integrate with various payment processors for a more seamless checkout experience.

## Contributing

Contributions are welcome! If you have ideas for improvements or bug fixes, please submit a pull request or open an issue on the [GitHub repository](https://github.com/jahnvisahni31/SpeedKart).

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For any questions or further information, please contact:


