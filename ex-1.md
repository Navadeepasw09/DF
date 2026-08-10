# Digital Forensics – Evidence Acquisition Using FTK Imager

## Experiment No. 1

### Aim
To acquire volatile and non-volatile digital evidence using AccessData FTK Imager.

## Introduction
FTK Imager is a Windows-based digital forensics tool used to acquire and analyze computer forensic evidence. It can be used to acquire volatile memory (RAM) and non-volatile memory such as hard disk images.

## Types of Evidence Acquisition

1. **Volatile Memory Acquisition**
   - Captures the contents of RAM.
   - The acquired memory is saved with a `.mem` extension.
   - Pagefile and AD1 files can also be included.

2. **Non-Volatile Memory Acquisition**
   - Creates a forensic disk image of storage devices.
   - FTK Imager can acquire:
     - Physical drives
     - Logical drives
     - Image files
     - Contents of folders
     - CDs/DVDs

## Procedure

### A. Acquiring Volatile Memory

1. Open FTK Imager.
2. Select **Capture Memory**.
3. Select the destination folder.
4. Enter the destination filename.
5. Select **Include pagefile** if required.
6. Select **Create AD1 file** if required.
7. Click **Capture Memory**.
8. Wait until the memory acquisition is completed.
9. The captured memory is saved as a `.mem` file.

### B. Acquiring a Disk Image

1. Open FTK Imager.
 
   <img width="171" height="121" alt="1 - Copy" src="https://github.com/user-attachments/assets/ac979b85-be79-4cbe-823d-768c0a3c8832" />

2. Select **Create Disk Image**.

  
   <img width="340" height="275" alt="2" src="https://github.com/user-attachments/assets/a5e79d4b-1a99-48e1-8697-260259aef266" />

3. Select the required source type.
   
   <img width="340" height="272" alt="3" src="https://github.com/user-attachments/assets/341cbf6a-e377-4fba-a0a2-d15f5e9e7149" />

4. Select **Physical Drive** to acquire a complete physical drive.

   <img width="343" height="246" alt="4" src="https://github.com/user-attachments/assets/0317fc5c-06c2-4dc5-8e47-ce71eaf1542c" />

5. Select the required drive.

   <img width="1461" height="1076" alt="5 (2)" src="https://github.com/user-attachments/assets/93263e29-4027-4068-b381-2084ad16daee" />

7. Click **Finish**.

   <img width="347" height="247" alt="6" src="https://github.com/user-attachments/assets/1fb40dd2-cf86-4c84-9e1d-46badd6cc5eb" />

8. Select the required image format.

   <img width="351" height="299" alt="7" src="https://github.com/user-attachments/assets/1ad110f1-3fc3-48eb-99e5-09d2c619de96" />
 
9. Enter the case details.

   <img width="309" height="221" alt="8" src="https://github.com/user-attachments/assets/917f7690-c8e6-4f73-aa06-04da12a35811" />

10. Select the destination folder.

   <img width="326" height="194" alt="9" src="https://github.com/user-attachments/assets/c7f0df47-f4cb-425e-9650-35f39b9913a4" />
 
11. Enter the image filename.

   <img width="959" height="272" alt="10" src="https://github.com/user-attachments/assets/b584ab04-24fb-4165-92e6-0b2ae84d2675" />

12. Set the image fragment size.

   <img width="1239" height="1270" alt="11 (2)" src="https://github.com/user-attachments/assets/feb1e576-5751-4716-a818-0d7fad43f9b6" />

13. Enable **Verify images after they are created**.

   <img width="310" height="322" alt="12" src="https://github.com/user-attachments/assets/24cdcfd6-2d3f-4934-afbc-6b60795aeedc" />

14. Click **Start** to begin acquisition.
15. Wait for the acquisition to complete.
16. Verify the hash values.

## Image Formats

### Raw (dd)
A commonly used raw forensic image format. It does not contain headers or metadata.

### SMART
A disk image format designed for Linux file systems.

### E01
A proprietary forensic image format developed by Guidance Software's EnCase. It supports compression and contains case information and hash values.

### AFF
Advanced Forensic Format (AFF), designed to avoid dependence on a proprietary format.

## Importance of Hash Verification

Hash verification is used to check the integrity of the acquired evidence. After acquisition, the hash values are matched to ensure that the evidence has not been altered.

## Result

The volatile memory and disk image were successfully acquired using FTK Imager, and the hash values were verified to maintain the integrity of the digital evidence.

## Tool Used

- AccessData FTK Imager
- Windows Operating System

## Conclusion

FTK Imager provides a method for acquiring digital forensic evidence from volatile memory and storage devices while maintaining evidence integrity through hash verification.
