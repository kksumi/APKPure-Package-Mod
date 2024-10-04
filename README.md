# Getting started

This guide will help you access a directory listing from your host device:

## Prerequisites

- Android device with the application installed. 

## Steps to Access the directory listing

### 1. Enable Hotspot on the Host Device

1. Open **Settings** on your Android device.
2. Navigate to **Network & Internet** > **Hotspot & tethering**.
3. Tap on **Wi-Fi Hotspot** and enable it.

### 2. Connect to Hotspot

1. Go to **Wi-Fi Settings**.
2. Look for the Hotspot Name (SSID) of the host device and connect using the provided password.
3. Ensure that you are connected successfully.

### 3. Find the Host Device's Local IP Address

1. On the host device, go to **Settings** > **About phone** > **Status** (or **Network**).
2. Locate the **IP Address**. It should look something like `192.168.43.x`.

### 4. Access the directory listing

1. Open a web browser on the second device.
2. In the address bar, enter `http://<Host_IP_Address>:8081`, replacing `<Host_IP_Address>` with the IP address you noted earlier.
   - For example: `http://192.168.43.1:8081`.
3. You should now see the directory listing of the files available on the server. Note that this version allows **view-only access** to the files.


![Screenshot from 2024-10-04 00-52-00](https://github.com/user-attachments/assets/08c44879-53cf-44e4-937e-1bf796c68d10)


## Troubleshooting

- Consider force stopping and restarting the application incase of unresponsive behaviour.


![Screenshot_20241004-005827](https://github.com/user-attachments/assets/af5eff8c-18d2-462f-9f21-5e3b6a5b73fa)

  
## Conclusion

We are NOT liable for any damages that may result from the use of this software!
