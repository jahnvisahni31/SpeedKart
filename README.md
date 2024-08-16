# SpeedKart

## Project Overview

SpeedKart is an innovative solution developed for the Walmart Sparkathon that revolutionizes the in-store shopping experience. By integrating a video streaming platform with YOLO object detection and Raspberry Pi, we've created a system that automatically bills items as they're placed in the shopping cart, enabling a seamless self-checkout process.

## Key Features

- **Real-time Item Detection:** Uses YOLO (You Only Look Once) algorithm to detect and identify items as they're added to the cart.
- **Automated Billing:** Keeps a running total of items in the cart, updating in real-time.
- **Self-Checkout:** Allows customers to complete their purchase directly at the cart.
- **Digital Receipt:** Generates a digital receipt for the transaction.
- **QR Code Generation:** Creates a QR code for easy digital payment or record-keeping.

## Technology Stack

- YOLO (You Only Look Once): For real-time object detection
- Raspberry Pi: As the computing unit attached to the cart
- Video Streaming: To capture items being added to the cart
- Python: Primary programming language for integration and processing

## How It Works

1. A camera attached to the shopping cart streams video of the cart's contents.
2. The YOLO algorithm processes the video stream in real-time, identifying items as they're added to the cart.
3. Each identified item is added to the customer's bill automatically.
4. When shopping is complete, the customer can check out directly at the cart.
5. The system generates a digital receipt and a QR code for the transaction.

## Benefits

- Reduces checkout times and eliminates queues
- Enhances shopping experience through convenience
- Minimizes human error in scanning and billing
- Provides real-time total cost to shoppers
- Enables easy integration with digital payment systems

## Future Enhancements

- Integration with inventory management systems
- Personalized shopping recommendations based on cart contents
- Expansion to include produce and items sold by weight
- Mobile app integration for expanded features and easier payment

## Contributors

1. **Sahil Jain**
2. **Yash Gupta**
3. **Girendra Sinsinwar**
4. **Gunesh Gupta**
5. **Jahnvi Sahni**

## Acknowledgments

We'd like to thank Walmart for organizing the Sparkathon and providing us with this opportunity to innovate in the retail space.
