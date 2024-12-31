# Control-PC
We are excited to present our project, "CONTROL PC VIA EMAIL", a C++-based application designed to provide a seamless and engaging experience. This tool allows users to control their PC remotely through email, offering both practicality and innovation in a user-friendly package.

This project is developed by Nguyen Trong Hoa and myself under the guidance of Teacher Đỗ Hoàng Cường.

We are proud to share our work and are eager to receive your feedback. Thank you for your interest, and we look forward to your thoughts!

Best regards.
## 📦Installation
>>>Extract the "Code.zip" file:

Right-click the zip file and choose "Extract All" to unzip the folder to a desired location.

>>>Set Up vcpkg (for C++ package management):

Download vcpkg from <https://github.com/microsoft/vcpkg>
Follow the instructions in the repository to install vcpkg.
Once installed, navigate to the folder where you installed vcpkg and run the following command to integrate it with Visual Studio: ./vcpkg integrate install
Use vcpkg to install the necessary libraries: ./vcpkg install <library-name>

>>>Set Up FFmpeg (for multimedia handling):

Download FFmpeg 7.1 Full Build from FFmpeg official website: <https://ffmpeg.org/download.html> or a trusted source.
Extract the FFmpeg folder and add its bin directory to your system’s PATH environment variable so the executables (e.g., ffmpeg.exe, ffplay.exe, ffprobe.exe) can be accessed from any directory.

## 🚀How to use
To get started, run the "server.exe" and "mail.exe" files located in the "Code" folder you downloaded. 
## ▶️Demo
Youtube: <https://youtu.be/sA2D-Jq7oHI>
## 💻 Program Features and User Options
In this program, you can perform a variety of actions to control your PC remotely via email commands. The "LOGIN" section allows you to securely log in using your email, while the "START" button launches the application, enabling you to execute various commands. You can list, start, or stop applications in the "APPLICATIONS" section, and manage system services by starting or stopping them in the "SERVICES" section. The program also gives you the option to start your webcam, take screenshots, and manage files by getting or deleting them. To shut down your PC remotely, simply use the appropriate command. For additional information about the program, you can visit the "ABOUT" section. When you're finished, the "EXIT" button allows you to close the program.
## 🧠Algorithms
To power the remote control functionality, we leverage a combination of advanced technologies and algorithms. The program utilizes Socket Programming to establish reliable communication between the client and server. For email communication, the Gmail API is integrated, while Google OAuth 2.0 ensures secure and efficient authentication. These technologies work together to provide seamless control over your PC, allowing you to manage applications, services, files, and more through simple email commands.
## 📌Conclusion
We are pleased to present this control application developed by our team for educational and practical purposes. While we have put great effort into ensuring its functionality, we acknowledge that there may be some areas for improvement. We deeply appreciate your understanding and patience as we continue to fine-tune the application. Your feedback and suggestions are incredibly valuable to us and will play a key role in enhancing its performance. Thank you for your support, and we look forward to bringing you an even more refined and feature-rich version in the future!
