# LiteLink - Your Lightweight Thin Client Operating System 🚀

LiteLink is a customized Ubuntu-based operating system tailored to serve as an efficient thin client OS. Designed to be incredibly lightweight and minimalistic, LiteLink simplifies thin client computing without breaking the bank.

## Motivation and Inspiration 🌟

The main inspiration for creating LiteLink was the need for accessible, straightforward thin client solutions. Existing options either came at a steep price or were needlessly complex. LiteLink aims to fill this gap by providing a simple and cost-effective alternative.

## System Requirements 📋

- **Processor:** 64-bit
- **Memory:** 1GB
- **Storage:** 8GB

## How to Use LiteLink 🛠️

1. **Download:** Obtain the LiteLink ISO file from the [Release Section](https://github.com/ibnsultan/LiteLink-OS/releases).

2. **Create a Bootable Drive:** Use your preferred tool to create a bootable drive with the LiteLink ISO.

3. **Installation:** Boot your device from the bootable drive and follow the installation prompts.

4. **Auto-Login:** Upon startup, LiteLink will automatically log in with the "kiosk" user and prompt you for your RDP (Remote Desktop Protocol) credentials the first time.

5. **Connect to RDP Server:** Enter your RDP server credentials, either by using the hostname.local or the IP address.

6. **Automatic RDP Connection:** On subsequent power-ups, LiteLink will use the provided credentials to automatically establish an RDP connection with your server.

7. **Modify Credentials:** To change your RDP credentials, open the terminal with `ctrl+alt+T`, execute the command `/home/kiosk/start_freerdp.sh -g`, and re-enter your new credentials.

## Devices Tested On 🧪

LiteLink has been successfully tested on the following devices:

- **Wyse 3040 Thin Client**

⚠️ **Disclaimer:** LiteLink is a new operating system and hasn't undergone extensive testing. While I have made my best efforts to ensure its functionality, there may be unforeseen issues. Please use LiteLink with caution and report any problems you encounter on the [Issues Section](https://github.com/ibnsultan/LiteLink-OS/issues).


## Software and Credits 📦

LiteLink is built on the foundation of:

- **Ubuntu Server 1804** by Canonical LTD
- **FreeRDP** for seamless remote desktop connections
- **Clonezilla** for image creation

Feel free to explore LiteLink and contribute to its development. For more information, visit our [GitHub Repository]([#github-repository](https://github.com/ibnsultan/LiteLink-OS)).

Let's simplify thin client computing together! 🌐
