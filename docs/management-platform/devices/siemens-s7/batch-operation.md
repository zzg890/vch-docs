# Batch Operation of SIEMENS S7 Devices

In industrial settings, it is often necessary to create multiple devices in bulk. VC Hub enables this through its export and import functions.

**Note:** To quickly create devices, it is recommended to first manually add a device to the list. Then, export the device and use the exported fields as a reference to add new devices.

## Batch Addition
#### 1.Export Devices

Click the "Export" button in the upper right corner of the list to export all device information.

**Example of an Exported File:**

<img width="890" height="150" alt="image" src="https://github.com/user-attachments/assets/d8066786-05e0-40fc-98e3-7c6b13db6291" />


- The content inside the red box represents the field information.

#### 2.Adding Devices in Excel

Select the devices , then drag the mouse to quickly copy.

![s7-1](../../../assets/images/s7-1.gif)


When batch creating devices, the model number does not need to increment. Instead, set the fill method to "Copy Cells" to fill the values.

<img width="853" height="454" alt="image" src="https://github.com/user-attachments/assets/4f3bf5d6-3c6e-4e21-9c35-23ea4e02b0d4" />



#### 3.Import Devices

Click the "Import" button in the upper right corner of the list to import the exported content. After importing, the newly added devices will have their enabled status set to "Disabled" by default.

<img width="1891" height="675" alt="image" src="https://github.com/user-attachments/assets/91bc5605-d616-4564-9412-9d36c5387478" />


## Batch Modification

You can batch modify device information through the exported Excel. After making changes in the Excel, import it back. During the import, the data will be updated based on the name.

- If the device name in Excel matches the name in the SIEMENS S7 list, the corresponding configuration from Excel will be used to update the data.
- If the device name in Excel does not exist in the SIEMENS S7 list, a new device will be added to the list.
- If a device name in the SIEMENS S7 list does not exist in the import file, the data in the list will remain unaffected after the import.

## Batch Deletion

After selecting the devices to be deleted, click the **Delete** button at the top of the list to perform batch deletion.

<img width="1898" height="675" alt="image" src="https://github.com/user-attachments/assets/43b32628-b780-4b9b-ace5-adc9b8f49314" />


Notes:

- Devices that are **Enabled** cannot be deleted.
- Only devices on the current page can be deleted; cross-page deletion is not supported.
