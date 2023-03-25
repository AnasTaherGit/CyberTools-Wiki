# Cybersecurity Wiki

## Table of contents

- [Cybersecurity Wiki](#cybersecurity-wiki)
  - [Table of contents](#table-of-contents)
  - [Pentest Tools](#pentest-tools)
    - [Informations Gathering](#informations-gathering)
      - [Gobuster - Brut force Web Enumeration tool](#gobuster---brut-force-web-enumeration-tool)
      - [Nmap - Network Scanning and Host Detection](#nmap---network-scanning-and-host-detection)
    - [Metasploit - A Framework for Penetration Testing and Exploitation](#metasploit---a-framework-for-penetration-testing-and-exploitation)
  - [Forensics Security](#forensics-security)
    - [Analyzing pdf files Metadata](#analyzing-pdf-files-metadata)
    - [Analyzing images metadata](#analyzing-images-metadata)

## Pentest Tools

### Informations Gathering

#### Gobuster - Brut force Web Enumeration tool

#### Nmap - Network Scanning and Host Detection

### Metasploit - A Framework for Penetration Testing and Exploitation

## Forensics Security

### Analyzing pdf files Metadata

```pdfinfo``` can be used to display various metadata related to a PDF file, such as title, subject, author, creator, and creation date.

to install ```pdfinfo``` :

```bash
sudo apt install poppler-utils
pdfinfo <DOCUMENT_NAME>.pdf
```

### Analyzing images metadata

EXIF stands for Exchangeable Image File Format; it is a standard for saving metadata to image files. Whenever you take a photo with your smartphone or with your digital camera, plenty of information gets embedded in the image. The following are examples of metadata that can be found in the original digital images:

* Camera model / Smartphone model
* Date and time of image capture
* Photo settings such as focal length, aperture, shutter speed, and ISO settings

Because smartphones are equipped with a GPS sensor, finding GPS coordinates embedded in the image is highly probable. The GPS coordinates, i.e., latitude and longitude, would generally show the place where the photo was taken.

```exiftool``` is used to read and write metadata in various file types, such as JPEG images.

you can install it using 

```bash
sudo apt install libimage-exiftool-perl
```
