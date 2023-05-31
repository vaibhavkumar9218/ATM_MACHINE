# ATM Machine Application

This is a simple ATM (Automated Teller Machine) machine application implemented using Tkinter and OpenCV libraries in Python. The application allows users to log in to their accounts, check their account balance, withdraw money, and deposit money. Additionally, the application uses face recognition to authenticate the user before allowing any transactions.

## Prerequisites

- Python 3.x
- OpenCV library (`pip install opencv-python`)
- Tkinter library (should be included in most Python installations)

## Usage

1. Clone the repository or download the source code files.
2. Install the required libraries mentioned in the Prerequisites section.
3. Run the `atm_machine.py` file using the Python interpreter: `python atm_machine.py`.
4. The application window will appear with a welcome message.
5. Enter your account number and password in the provided fields.
6. Click the "Enter" button to log in.
7. The application will activate your webcam and start face recognition. Make sure your face is properly visible to the camera.
8. If your face is recognized, you will be logged in and the current balance will be displayed.
9. You can enter an amount and click the "Withdraw" button to withdraw money from your account, or click the "Deposit" button to deposit money into your account.
10. If you want to exit the application, click the circular "Exit" button.

## File Description

- `atm_machine.py`: The main Python script that contains the application code.
- `haarcascade_frontalface_default.xml`: The XML file used by OpenCV for face detection.
- `accounts.txt`: A text file that stores account information (account number, password, and balance) in a dictionary format. You can modify this file to add or remove accounts.

## Additional Notes

- This application is for educational purposes and not meant for real-world use.
- The face recognition feature is implemented using OpenCV's face detection algorithm. It may not be highly accurate and may require good lighting conditions for optimal performance.
- The account information is stored in a plain text file (`accounts.txt`). In a real-world scenario, you would use a secure database or encryption techniques to store sensitive data.
- The GUI is implemented using Tkinter, a standard Python library for creating graphical user interfaces. You can modify the appearance and layout of the GUI by modifying the code in the `atm_machine.py` file.

## License

This project is not licensed still. Feel free to modify and use the code according to your needs.

## Disclaimer

The application and code are provided as-is, without any warranty or guarantee. The authors are not responsible for any damages or liabilities caused by the use or misuse of the application.
