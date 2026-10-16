# Threat Model for Digital Media Assets

## 1. Introduction
A threat model identifies potential security threats to digital media assets and defines measures to protect files from unauthorized access, modification, theft, and loss.

## 2. Assets to Protect
- Images and textures
- Audio files
- Animation files
- 3D models
- Project documentation
- Source code and scripts
- Repository credentials

## 3. Potential Threats
- Unauthorized repository access
- Accidental deletion of important files
- Malware and ransomware attacks
- Exposure of confidential information
- Unauthorized modification of digital assets
- Loss or corruption of files

## 4. Threat Model Diagram

```text
             Potential Threats
                    |
       +------------+------------+
       |            |            |
   Unauthorized   Malware     Data Loss
      Access         |            |
       |             |            |
       +-------------+------------+
                     |
              Digital Assets
                     |
          +----------+----------+
          |          |          |
       GitHub    Git LFS    Backups
          |          |          |
          +----------+----------+
                     |
             Security Controls
                     |
       +-------------+-------------+
       |             |             |
   Strong Login   Access       Recovery
   and 2FA        Control      Procedures
