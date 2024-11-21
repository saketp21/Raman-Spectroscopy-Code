#Raman Spectroscopy Control Application
Overview
This project is a customized application for controlling a portable Raman spectroscopy device using the Hamamatsu Minispectrometer SDK (WRRUSB2_DLL). It allows users to interact with the device, acquire spectral data, and perform various configurations through a command-line interface.

The project is based on a sample application provided by Hamamatsu, and it has been modified to include additional functionality and usability improvements.

#Features
Device Initialization & Connection:
Automatically detects and connects to the spectrometer.
Initializes the device for use.
#Data Acquisition:
Supports multiple capture modes:
Frequency-Specified Measurement Mode.
Continuous Measurement Mode.
Trigger Mode.
Captures Raman spectra data and displays it in the console.
#Device Configuration:
Adjusts exposure time and cycle time.
Configures LD (Laser Diode) power levels.
Retrieves calibration coefficients.
Monitors device and board temperatures.
#Error Handling:
Comprehensive error messages for failed operations.
Extensible Design:
Ready to be customized for file export, real-time visualization, or automated workflows.
##System Requirements
#Hardware
A compatible portable Raman spectrometer.
USB interface for connecting the spectrometer to the computer.
#Software
Operating System: Windows 10/11 (64-bit recommended).
#Development Tools:
Microsoft Visual Studio 2019 or later.
.NET Framework (if needed for C++/CLI projects).
#Dependencies:
WRRUSB2_DLL (included with the SDK for the spectrometer).
