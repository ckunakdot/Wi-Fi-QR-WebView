# Wi-Fi QR WebView

Control4 Wi-Fi QR WebView Driver

The **Wi-Fi QR WebView** driver displays a QR code image on Control4 touchscreens, mobile apps, and other Navigators. It includes a built-in web server that serves a clean, styled HTML page designed to match the Control4 interface aesthetic.

This driver is ideal for displaying **Wi-Fi network credentials, guest access information, or any other QR code content**. Simply replace the bundled QR code image with your own.

---

## Features

- **Built-in Web Server**  
  Runs on port **1111** to serve the QR code display page.

- **Burn-in Prevention**  
  Content automatically shifts position every **60 seconds** to help prevent screen burn-in.

- **Customizable Styling**  
  Configure colors for:
  - Background
  - Title text
  - QR code container

- **Responsive Design**  
  Automatically adapts to **any screen size or orientation**.

- **Control4 Theme**  
  Styled to closely match the **Control4 interface aesthetic**.

- **Easy QR Code Replacement**  
  Simply replace the **PNG file inside the driver package** with your own QR code.

- **Server URL Display**  
  The driver shows the **local web server URL inside Composer Pro** for easy access.

---

## Customizing the QR Code

1. Rename `Wifi_QR_WebView.c4z` to `Wifi_QR_WebView.zip`
2. Extract the ZIP file
3. Navigate to the folder: www/images/

4. Replace `qrcode.png` with your own QR code image
5. Select all files and create a new ZIP archive
6. Rename the ZIP file back to the `.c4z` extension

---

## Example Display

![Wi-Fi QR WebView](https://github.com/user-attachments/assets/5042dee1-0363-497e-a907-382c7b2fbc94)
