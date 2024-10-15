# NI-DAQmx Analog Voltage Acquisition

**NI-DAQmx Analog Voltage Acquisition** is a LabVIEW application that enables real-time acquisition and output of analog voltage signals using National Instruments hardware through the NI-DAQmx driver. This program is designed for continuous monitoring and manipulation of voltage signals from both analog input and output channels.

## Features:
- **Analog Voltage Acquisition**: Continuously reads voltage values from the specified analog input channel.
- **Analog Voltage Output**: Outputs a voltage signal to the specified analog output channel.
- **Customizable Voltage Range**: Allows users to define the voltage range for both input and output (default 0-5V).
- **Real-Time Data Display**: Monitors and displays live voltage values during operation.
- **Stop Control**: Includes a 'Stop' button to safely terminate the operation.

## How It Works:
1. **Device and Channel Configuration**: The user defines the NI device and selects the input/output channels to acquire and generate voltage signals.
2. **Voltage Read/Write**: The application reads voltage from the analog input, processes the data, and sends it to the output channel.
3. **Data Display**: Real-time voltage values are displayed for both input and output channels during execution.
4. **Safe Termination**: The user can stop the acquisition process by pressing the 'Stop' button, which ensures that data acquisition halts safely.

## Requirements:
- LabVIEW
- NI-DAQmx Driver installed
- National Instruments DAQ device with analog input/output capability

## Usage:
1. Set the desired device and channel configuration for analog input (AI) and analog output (AO).
2. Define the voltage range (e.g., 0-5V).
3. Run the program to start the continuous voltage acquisition and output process.
4. Use the 'Stop' button to terminate the program when needed.

## Code:
![image](https://github.com/user-attachments/assets/089c6fff-92a8-4025-8f11-dcdad771b475)
