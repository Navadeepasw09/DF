# Ex. No. 5 – Use Autopsy to Create a Case and Import Evidence

## Digital Forensics Lab

### Aim

To create a forensic case using Autopsy and import a forensic disk image as evidence for digital forensic analysis.

---

## Software Used

- Autopsy 4.23.1
- Windows
- Digital Forensic Disk Image (.E01)

---

## Case Information

| Property | Details |
|---|---|
| Case Name | laptop theft |
| Case Number | case 1 |
| Examiner | Navadeep |
| Evidence Image | 4Dell Latitude CPi.E01 |
| Timezone | Asia/Calcutta |
| Autopsy Version | 4.23.1 |

---

## Description

Autopsy is an open-source digital forensics platform used for analyzing and extracting data from digital devices.

In this experiment, a new forensic case was created in Autopsy and the forensic image `4Dell Latitude CPi.E01` was imported. Ingest modules were configured to analyze the evidence and extract forensic artifacts.

An HTML forensic report was also generated after the analysis.

---

# Procedure

## 1. Create a New Case

Autopsy was opened and a new case was created.

The case information was entered as follows:

- Case Name: `laptop theft`
- Case Number: `case-001`
- Examiner: `Rakesh`

<img width="992" height="583" alt="Screenshot 2026-08-25 101033" src="https://github.com/user-attachments/assets/3805e27b-7519-400c-bfa4-abdb8d6c8d49" />


---

## 2. Select Host

A new host was generated based on the data source name.

<img width="1070" height="682" alt="Screenshot 2026-08-25 101145" src="https://github.com/user-attachments/assets/7e3e16f7-6795-4f0e-b5c3-58da4cb34944" />
---

## 3. Select Data Source

The forensic evidence image was selected as the data source.

**Evidence:**

`4Dell Latitude CPi.E01`

<img width="1071" height="678" alt="Screenshot 2026-08-25 101223" src="https://github.com/user-attachments/assets/ac4be528-6d0a-468c-8640-0b5ed8625099" />

---

## 4. Configure Ingest Modules

The required ingest modules were configured for forensic analysis.

The selected modules included:

- Recent Activity
- Hash Lookup
- File Type Identification
- Extension Mismatch Detector
- Embedded File Extractor
- Picture Analyzer
- Email Parser
- Encryption Detection
- Interesting Files Identifier
- Central Repository
- PhotoRec Carver
- Virtual Machine Extractor

<img width="1708" height="898" alt="Screenshot 2026-08-25 101237" src="https://github.com/user-attachments/assets/4d39c44b-2ef4-4003-9fa0-652f2b374f35" />


---

## 5. Analyze Evidence

After the evidence was added, Autopsy processed the forensic image using the configured ingest modules.

The results were displayed in the Autopsy interface.

<img width="1717" height="908" alt="Screenshot 2026-08-25 101412" src="https://github.com/user-attachments/assets/1bf36b01-3dd5-4229-9fa3-c7dde0f8490e" />


---

## 6. Generate Report

After the analysis was completed, the **Generate Report** option was selected.

The **HTML Report** module was selected to generate the forensic report.

<img width="1082" height="672" alt="Screenshot 2026-08-25 101507" src="https://github.com/user-attachments/assets/ba4a756d-8d58-4dc0-a961-90baca5c16c4" />

---

## 7. View Generated Report

Autopsy generated an HTML forensic report containing information about the case and analyzed evidence.

<img width="1065" height="667" alt="Screenshot 2026-08-25 101518" src="https://github.com/user-attachments/assets/365d8931-7335-4ae5-a995-6a96b445ab8c" />
---

## 8. Report Generation Completed

The report generation process was completed successfully and the HTML report was saved in the Reports directory.

<img width="955" height="962" alt="Screenshot 2026-08-25 101609" src="https://github.com/user-attachments/assets/164bf757-ea45-4564-bdd5-a0860e6a7856" />

---


---

# Evidence Information

| Property | Details |
|---|---|
| Case Name | laptop theft |
| Case Number | case 1 |
| Examiner | Navadeep |
| Data Source | 4Dell Latitude CPi.E01 |
| Sector Size | 512 Bytes |
| Timezone | Asia/Calcutta |
| Autopsy Version | 4.23.1 |

---

# Analysis Performed

The forensic image was analyzed using Autopsy ingest modules.

The analysis included:

- File Type Identification
- Hash Lookup
- Extension Mismatch Detection
- Embedded File Extraction
- Picture Analysis
- Email Parsing
- Encryption Detection
- Interesting Files Identification
- Recent Activity Analysis
- File Carving

---

# Result

The forensic disk image was successfully imported into Autopsy and analyzed using the configured ingest modules.

Various forensic artifacts were extracted and categorized by Autopsy.

An HTML forensic report was successfully generated containing the case and analysis information.

---

# Conclusion

The experiment successfully demonstrated how to create a forensic case in Autopsy, import a forensic disk image, configure ingest modules, analyze the evidence, and generate an HTML forensic report.

---

# Experiment Workflow

```text
Create New Case
       ↓
Enter Case Information
       ↓
Select Host
       ↓
Select Data Source
       ↓
Import 4Dell Latitude CPi.E01
       ↓
Configure Ingest Modules
       ↓
Analyze Evidence
       ↓
Generate HTML Report
       ↓
Review Report
       ↓
Complete
