
# Sleep Monitor  

A system for sleep monitoring, consisting of a custom PCB board and a desktop application for data visualization and analysis.  
 
## Features  
- EEG  measurement  
- Heart rate and blood oxygen saturation (SpO₂) monitoring  
- CO₂ measurement  
- Data acquisition and transfer via STM32 microcontroller  
- Desktop application for real-time visualization and analysis  
---
##  Block Schematic
<img width="986" height="512" alt="image" src="https://github.com/user-attachments/assets/aa52f35e-7ee8-4b49-8929-7a764cb14ed2" />


##  Hardware  

### Main Components  
| Component | Function |
|-----------|----------|
| **TI ADS1299-4** | EEG signal acquisition frontend |
| **Analog Devices MAX30102** | Heart rate & SpO₂ sensor |
| **Sensirion SCD40** | CO₂ sensor |
| **STM32F103C8T6** | Microcontroller, data handling & communication |
<img width="779" height="584" alt="swaw_1" src="https://github.com/user-attachments/assets/0997b98d-682d-4a6b-8eb0-2589b9750e11" />

## Application  
<img width="811" height="480" alt="swaw_2" src="https://github.com/user-attachments/assets/1c9fe6b1-d63d-42ec-9ed7-e52b8f72b2d0" />
<img width="808" height="415" alt="swaw_5" src="https://github.com/user-attachments/assets/a8d63ef4-818e-45ae-ad31-430cf9ab7980" />
<img width="474" height="487" alt="swaw_3" src="https://github.com/user-attachments/assets/37a78df7-ac6e-4a8b-9432-3669dccc0e54" />
 

