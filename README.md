# Forensic-on-JPG-with-Hidden-text
Simulate a scenario by deleting the file and making it inaccessible. Utilize FTK (Forensic Toolkit) to recover the deleted file from the disk image and extract the hidden text from the recovered JPG. This project highlights data-hiding methods and the forensic recovery process. <b>
# Real-time scenario
At a leading financial institution, concerns of a potential data breach arise when suspicious JPG images exchanged in routine emails mysteriously disappear from the system. Their seemingly harmless nature makes detection challenging, but unusual patterns in network activity raise red flags for the cybersecurity team. <b>
During an investigation, the security lead identifies a peculiar anomaly in the network logs: a deleted file with a lingering digital footprint. The team retrieves fragments of the file from deep storage and reconstructs it, revealing what appears to be an ordinary image. However, its presence raises further suspicion. <b>
After relentless efforts, the team discovers the truth—the image contains hidden data capable of compromising the institution’s security. This finding intensifies their investigation as they work to uncover the perpetrators and mitigate the risk before it escalates. <b>
# Industry Relevance
The following tools used in this project serve specific purposes within the industry <b>
* Steganography Tool (for example, SilentEye, StegHide): Is used to embed hidden data within JPG images to demonstrate data-hiding techniques <b>
* FTK (Forensic Toolkit): Enables recovery of deleted files and analysis of disk images for digital forensic investigations <b>
* File System (2GB NTFS Partition): Simulates real-world storage environments for practicing file recovery techniques <b>
* JPG Image Format: Represents a common file format used for embedding and concealing hidden data <b>
* Disk Image (2-Disk System): Provides a realistic scenario for recovering deleted files from storage environments <b>
# Task 1: Create a JPG Image and Hide Text Using Steganography
Step 1: Setup the Disk<b>
1.1 Double click on the VMware and select the “01-Windows Server 2022” then click on Settings.<b>
![yu](https://github.com/user-attachments/assets/2b172366-14fa-4b3b-9e0c-90b113ad16c2)<b>

1.2 Click on Hard Disk.<b>
![y1](https://github.com/user-attachments/assets/0355c0a2-c917-44e1-9d94-25846e8a4abf)<b>

1.3 Click on Hard Disk. Click Add<b>
![y2](https://github.com/user-attachments/assets/ce4116c5-85e1-4250-88e1-75c5d663cc56)<b>

1.4 Type diskmgmt.msc and click on ok.<b>
![1](https://github.com/user-attachments/assets/5d483b98-55a4-422a-b9b6-19cbf8c62271)

1.5 Click on Ok.
![2](https://github.com/user-attachments/assets/36b3d4a1-1e85-49a6-85b0-5f99b83bc0ce)

![3](https://github.com/user-attachments/assets/607a277d-f71f-4d23-8e73-31df41c7ae21)

1.6 Right-click on Disk 1 and select the “New Simple Volume”
![4](https://github.com/user-attachments/assets/de4bfc32-3f5e-4242-b362-e5d303198f03)

1.7 Click on Next.
![5](https://github.com/user-attachments/assets/a1381588-7281-49e2-80d3-5485740a9d85)

1.8 Check the radio button of “Assign the following drive letter” and click on Next.
![6](https://github.com/user-attachments/assets/7fc6c72a-0f54-46d7-b344-85d9011c4da8)

1.9 Write the Volume label as Data and click on Next
![7](https://github.com/user-attachments/assets/1fbc6c1d-633b-4d4f-af04-b263aaa1c872)

1.10 Click on Finish
![9](https://github.com/user-attachments/assets/dac9a30e-4f25-4dce-9bc6-2697c162146a)

1.30 Now, we can see that Disk1 is now a healthy partition.










