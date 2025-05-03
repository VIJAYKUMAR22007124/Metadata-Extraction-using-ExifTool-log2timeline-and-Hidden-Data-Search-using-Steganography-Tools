# Metadata-Extraction-using-ExifTool-log2timeline-and-Hidden-Data-Search-using-Steganography-Tools
## AIM:
To extract metadata, perform timeline analysis, and search for hidden data using forensic tools like ExifTool, log2timeline, and steganography detection tools.

## DESIGN STEPS:
### Step 1:
Use exiftool to extract metadata from files such as images, documents, and videos.

### Step 2:
Use log2timeline and plaso to create and analyze event timelines from system logs and file metadata.

### Step 3:
Apply steganography detection tools like steghide, zsteg, or binwalk to uncover hidden data in media files.

## PROGRAM:
Metadata and Timeline Forensics, Steganography Analysis Steps

```
   sudo apt update
   sudo apt install exiftool -y
   sudo apt install plaso -y
   sudo apt install steghide -y
   sudo apt install binwalk -y

   exiftool image path
   exiftool png.jpeg

   steghide embed -cf /home/vijay/Desktop/vk.jpeg -ef /home/vijay/Desktop/abc.txt
   steghide extract -sf /home/vijay/Desktop/vk.jpeg -p 1234 -xf /home/vijay/Desktop/abc.txt
   steghide extract -sf /home/vijay/Desktop/vk.jpeg -p 1234 -xf /home/vijay/Desktop/secret.txt
   
    binwalk /home/vijay/Desktop/vk.jpeg

```



## OUTPUT:
Extracted Metadata, Timeline Events, and Hidden Data Detection Results

![image](https://github.com/user-attachments/assets/f5e52ff4-6278-4432-b6ff-ba0bdde257bf)

![image](https://github.com/user-attachments/assets/254cbbf7-04be-4178-bda7-29484fc83a77)

![image](https://github.com/user-attachments/assets/1dfa5058-d0dd-4b71-9561-a63fe3c87881)

![image](https://github.com/user-attachments/assets/4c81195f-ad05-4e2c-b7ec-4bef340288dd)


## RESULT:
Metadata was successfully extracted, timeline analysis was completed, and hidden data was identified using steganography tools.

