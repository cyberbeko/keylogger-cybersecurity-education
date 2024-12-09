# Keylogger-Cybersecurity-Education
A Python-based keylogger built in a virtual environment for ethical hacking and cybersecurity education.

 ### [YouTube Demonstration🎥](https://youtu.be/4kLb7yub7fU)

<h2>Description</h2>
This project demonstrates how a keylogger works in a controlled virtual environment for educational purposes. It provides insights into how attackers might exploit such tools and emphasizes the importance of defensive strategies in cybersecurity. By setting up and testing a basic keylogger, this project contributes to ethical hacking knowledge and awareness.

<h2>Main Goal</h2>
The main goal of this project is to educate viewers on the mechanics of keyloggers and promote cybersecurity awareness. By understanding how keyloggers work, viewers can learn how to detect and defend against them, contributing to safer practices in the digital world.

## Programming Language💻
- **Python**: Chosen for its ease of use and extensive libraries, which allow us to demonstrate keylogging functionality efficiently.

## Utilities Used 💼
- **Virtual Machine:**: Used to create a safe and isolated environment for testing. Examples: UTM, VirtualBox, or VMware.
- **Linux Distribution**: Kali Linux or Ubuntu, installed on the virtual machine.

- **Python Standard Libraries**:
pynput: Used for capturing and recording keystrokes.

<h2>Environments Used </h2>

- <b>**macOS**</b>
- <b>**Kali Linux**</b>

<h2>Program Walk-through 🦺</h2>

<p align="center">
Created a new virtual machine (VM) environment for testing the keylogger. I used UTM 3.2.4 since new version didn't work. <br/>
<img src="https://i.imgur.com/xbExKO6.png" height="80%" width="80%" alt="Virtual Machine Setup"/>
<img src="https://i.imgur.com/ccAWTE9.png" height="80%" width="80%" alt="Virtual Machine Setup"/>
<br />
<br />
Upload Python and updated here. <br/>
<img src="https://i.imgur.com/ecdyKST.png" height="80%" width="80%" alt="Keylogger Code"/>
<p align="center">
Created a Python file named `keylogger.py`. <br/>
<img src="https://i.imgur.com/l9fPzeZ.png" height="80%" width="80%" alt="Keylogger Code"/>
<br />
<br />
Write the Python keylogger script using the `pynput` library to capture keyboard events and save them to a file. <br/>
<img src="https://i.imgur.com/Fd3k0MF.png" height="80%" width="80%" alt="Keylogger Script"/>
<br />
Save and Exit: To save the file in nano and exit. <br/>
<br />
Run the Python keylogger script: <br/>
<img src="https://i.imgur.com/UMmXWBU.png" height="80%" width="80%" alt="Install pynput and Run Script"/>
<br />
<br />
Now we are ready to test the keylogger! <br/>
<img src="https://i.imgur.com/qG2ldQc.png" height="80%" width="80%" alt="Testing Keylogger"/>
<br />
<br />
Once you run the keylogger, every keystroke will be logged to `keylog.txt`. Here is an example of captured keystrokes. <br/>
<img src="https://i.imgur.com/Yy1JSY7.png" height="80%" width="80%" alt="Captured Keystrokes"/>
<br />
The file will store every key pressed along with timestamps for further analysis. <br/>
Also, when you press **Esc**, the keylogger stops capturing input. <br/>

# Ethical Keylogger: Hands-On Cybersecurity Awareness

## Project Summary

This project demonstrates the creation of an **ethical keylogger** in Python, designed for educational purposes only. It captures keystrokes within a **secure virtual machine environment** to raise awareness about cyber threats and help learn defensive strategies.

### Summary of Steps:

1. **Step 1:** Set up a **virtual machine** (VM) environment using a **Linux-based OS** like **Kali Linux** or **Ubuntu**.
2. **Step 2:** Install **Python** and necessary libraries like `pynput` to capture keyboard events.
3. **Step 3:** Write the **keylogger script** in Python that listens for keypress events and logs them to a text file.
4. **Step 4:** Run the Python script with the command: `python3 keylogger.py` to start logging keystrokes.
5. **Step 5:** Test the keylogger in the isolated VM environment to capture keystrokes for **educational purposes only**.
6. **Step 6:** Review captured keystrokes stored in the `keylog.txt` file for analysis.

## Disclaimer

This project is strictly for **educational purposes** and **ethical hacking training**.

- The keylogger demonstrated here is designed to run only in a **secure and isolated virtual machine environment**.
  
- **Unauthorized use** of keyloggers on any system without explicit permission is **illegal** and **unethical**.
  
- This project aims to **raise awareness about cyber threats** and teach **defensive strategies** against such attacks.
  
- The creator is not responsible for any **misuse** of the information provided. Always adhere to **local laws** and **ethical guidelines** when engaging with cybersecurity tools or techniques.

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
