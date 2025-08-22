# 👋 My IT Learning Journey
Welcome! I'm transitioning into IT with a focus on support, cloud and AI. This repo tracks everything I've learned. Strting with the Google IT Support Certificate and moving toward AWS, scripting, backend and more.
# google-it-cert-journal #
If I am feeling stuck or defeated I will, practice discipline, stay focused, research, breathe, focus on bigger picture. 
This repository tracks my progress through the [Google IT Support Certificate on Coursera](https://www.coursera.org/professional-certificates/google-it-support). It includes summaries, lab notes, scripts, and personal insights.


## 🎯 Current Goal
- ✅ Complete Google IT Support Certificate
- - 🔜 Land an entry-level IT or Help Desk job (Target: [August]) - Begin AWS Cloud Quest
  - - - Practice Python

## ✅ Progress
- [x] Week 1: Intro to IT support
- [Key Takeaways] : Logic gates represent different rules for taking one or more binary inputs and outputting a specific binary value (“on” or “off”).
- Logic gates can be linked so that the output of one gate serves as the input for other gates.
- Circuits are complex electrical systems built by linking logic gates together. Computers are this kind of complex electrical system.
-
  - [x] Week 2: Hardware
       - [Key Takeaways] : Understanding the various levels of CPU cache is essential for optimizing performance and making informed decisions in high-performance server configurations.
       - The process of overclocking CPUs can significantly enhance processing speeds, which is a valuable skill for IT support professionals.
       - The number and power consumption needs of the computer’s internal components
       - The motherboard model and form factor engineering specifications and requirements.
       - The two main technologies used in mobile displays are Liquid Crystal Display (LCD) and Organic Light Emitting Diodes (OLED). Each technology has its own benefits and drawbacks when used in mobile device displays, among other consumer goods. 
Common LCDs include:
In-Plane Switching (IPS) displays, Twisted Nematic (TN) displays , VA-Vertical Alignment displays, Common and upcoming OLED displays include, Active Matrix Organic Light Emitting Diode (AMOLED) displays, Inorganic mini-LEDs (mLEDs) displays, Inorganic micro-LEDs (μLEDs) displays
  
  
  - [x] Week 3: Operating Systems and Netowrking
      - [Key Takeaways] : In this lesson we go over installing Operating Systmes such as Chrome, Mac OS, and Linux. Starting to use Quicklabs VM to emulate windows desktop and Linux.
      - Mkdir Super-Secret-Folder would be the correct way to create a folder in Linux.
      - Data is written to the hard drive in Data Blocks.
      - OS that interacts with a systems hard ware is The kernal.
      - Key Glossary terms: Domain Name System (DNS): A global and highly distributed network service that resolves strings of letters, such as a website name, into an IP address.
      -  Network Address Translation (NAT): A mitigation tool that lets organizations use one public IP address and many private IP addresses within the network.
      Transmisson Control Protocol (TCP): A protocol that handles reliable delivery of information from one network to another.


        Networking In Depth:
       - the data link layer is responsible for defining a common way of interpreting these signals so network devices can communicate. Lots of protocols exist at the data link layer, but the most common is known as Ethernet.
       - 


      
   
   [x] Week 4: Software
      - A basic knowledge of scripting is an important tool for IT professionals. You may need to improve workflow efficiency by automating basic functions with a scripting language. Some common scripting languages include: Windows environments: batch scripts (.bat), Powershell (.ps1), Visual Basic Script (.vbs)
Linux/Unix environments: shell scripts (.sh)
Most OS environments: javascript (.js), Python (.py)
Scripts have multiple helpful uses, such as: Basic Automation Restarting Machines Remapping Network Drives Installing Applications Automating Backups. Gathering of information/ data Initiating Updates. There are risks in using scripts, including: Unintentionally introducing malware, Inadvertently changing system settings. Browser or system crashes due to mishandling of resources.
 - The apt command is used to do installs of software packages.
-  Adding sudo before the apt command tells Linux you are authorized to install software.
-  To quickly check if a program is installed on Linux, you can use the command dpkg -s followed by the unique package name for that program. The -s flag in dpkg stands for "status," and can also be written as --status. This flag allows you to verify if a program is installed on your machine. For example, we know that Firefox isn't currently installed, but GIMP is. Running dpkg -s firefox-esr shows this output: dpkg -s firefox-esr
-  output: dpkg-query: package 'firefox-esr' is not installed and no information is available
Use dpkg --info (= dpkg-deb --info) to examine archive files. this shows you that Firefox isn't currently installed on the system. To check GIMP, modify the earlier command and enter dpkg -s gimp to see the output below. (Note that only part of the output is shown.) dpkg -s gimp
Update VLC media player
VLC media player is already installed on your computer, but the version that's installed is out of date. You'll fix that now by updating it to the newest version. To do that, force an update of the package manager, using this command: sudo apt-get install -f
This kicks off the update process. It will print out lots of text to your terminal, and ask you if you'd like to continue. Enter y for "yes". When the process is finished, type dpkg -s vlc again to verify the installation. : dpkg -s vlc
 
- [ ] Week 5: IT Infrastructure: TCP/IP: Transmission Internet Protocal:
      

- [ ] 
- [ ] Week 6: IT Security: Defense Against the Digital Dark Arts 

## 📁 Directory Structure
- `week-0X`: Notes and lab exercises by week
- `scripts`: Practice scripts (PowerShell, Bash)
- `resources.md`: Links to useful learning material

## 🧠 Goal
Complete the course and build a foundation for CompTIA A+ and my first IT role.
