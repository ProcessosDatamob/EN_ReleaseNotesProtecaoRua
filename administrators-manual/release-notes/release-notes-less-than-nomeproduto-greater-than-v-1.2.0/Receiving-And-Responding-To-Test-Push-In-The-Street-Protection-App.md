# Receiving and Responding to Test Push in the Street Protection App

**ID: US-BTC-356**

Description: The Street Protection app can now receive test notifications sent by the BackEnd. When the app receives this notification, it sends a message back to confirm that everything went well, including a unique device identifier in this return. If this response is not successfully sent, the app logs the error to retry later. This helps ensure that test notifications are functioning correctly on the mobile device.