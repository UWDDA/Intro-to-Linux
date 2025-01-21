# Getting Started

If you have a CFT device you can do all the labs from the device to avoid any configuration changes to your personal computer.

1. Start by powering on the device by attaching a micro-usb power cable and adapter in to the device.
2. From your computer connect to the WIFI Access point called `CFT` with the password `CFT2025!`
3. Next, from your computer open a web browser like Chrome, Safari, or Firefox and navigate to `cft.local`
   - If `cft.local` fails to load try `http://192.168.10.1` this is where `cft.local` is pointing to by default on the device.
4. Now you will be automatically redirected to setup internet on your device by connecting it to an acces point.
   - Select the WIFI Access point you would like to connect to from the dropdown and type the password.
   - Make sure the password is correct otherwise you will have to repeat `Step 3`.
   - Once confirmed, click `Save Settings`
   - You may get an error screen or a timeout, this is expected and ok because the device is restarting.
5. Once its finished restarting connect to the `CFT` WIFI access point from your computer again.
6. Once connected you can SSH into the device across SSH (port 22) using `ssh cft@cft.local` and password `cft2025!`
   - Remeber is `cft.local` doesnt work you can use `ssh cft@192.168.10.1`
   - If you are on windows you can use Putty (https://www.putty.org/)
   - If you are on Linux or Mac OS you can use the terminal app to connect.
7. Once connected you can now run commands and start doing challenges from the device.
8. Get familiar with the Command Line Interface (CLI). We will be using this for this study group rigorously.
