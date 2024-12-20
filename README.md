# Activating Windows 10 Using CMD

## Steps to Follow

1. **Open CMD as Administrator**.

2. **Paste the following commands one by one into the CMD** in the order listed below.

### Commands

1. Replace `SERIAL NUMBER HERE` with the appropriate key for your Windows 10 installation type:

    - **Home/Core**:   
      `TX9XD-98N7V-6WMQ6-BX7FG-H8Q99`
      
    - **Home/Core (Country Specific)**:   
      `PVMJN-6DFY6-9CCP6-7BKTT-D3WVR`
      
    - **Home/Core (Single Language)**:   
      `7HNRX-D7KGG-3K4RQ-4WPJ4-YTDFH`
      
    - **Home/Core N**:   
      `3KHY7-WNT83-DGQKR-F7HPR-844BM`
      
    - **Professional**:   
      `W269N-WFGWX-YVC9B-4J6C9-T83GX`
      
    - **Professional N**:   
      `MH37W-N47XK-V7XM9-C7227-GCQG9`
      
    - **Enterprise**:   
      `NPPR9-FWDCX-D2C8J-H872K-2YT43`
      
    - **Enterprise N**:   
      `DPH2V-TTNVB-4X9Q3-TJR4H-KHJW4`
      
    - **Education**:   
      `NW6C2-QMPVW-D7KKK-3GKT6-VCFB2`
      
    - **Education N**:   
      `2WH4N-8QGBV-H22JP-CT43Q-MDWWJ`
      
    - **Enterprise 2015 LTSB**:   
      `WNMTR-4C88C-JK8YV-HQ7T2-76DF9`
      
    - **Enterprise 2015 LTSB N**:   
      `2F77B-TNFGY-69QQF-B8YKP-D69TJ`
      
    - **Enterprise 2016 LTSB**:   
      `DCPHK-NFMTC-H88MJ-PFHPY-QJ4BJ`
      
    - **Enterprise 2016 LTSB N**:   
      `QFFDN-GRT3P-VKWWX-X7T3R-8B639`

2. Run the following commands:

    - Activate the product key:
      ```cmd
      cscript slmgr.vbs /ipk "SERIAL NUMBER HERE"
      ```

    - Set the KMS server:
      ```cmd
      cscript slmgr.vbs /skms kms.lotro.cc
      ```

    - Activate Windows:
      ```cmd
      cscript slmgr.vbs /ato
      ```

## Note

Make sure to replace `SERIAL NUMBER HERE` with the correct product key corresponding to your Windows 10 edition.
