# Batch Operation of MQTT SparkplugB Devices

In industrial settings, it is often necessary to create multiple devices in bulk. VC Hub enables this through its export and import functions.

**Note:** To quickly create devices, it is recommended to first manually add a device to the list. Then, export the device and use the exported fields as a reference to add new devices.

## Batch Addition

#### 1.Export Devices

Click the "Export" button in the upper right corner of the list to export all device information.

When exporting MQTT SparkplugB devices, the exported file will include node information.

**Example of an Exported File:**

<img width="340" height="154" alt="image" src="https://github.com/user-attachments/assets/558f5ba5-b6bd-4e15-8f18-dee5f62af346" />


- The content inside the red box represents the field information.
- If it is a group, the "IsGroup" field is set to **True**.
- Node information is listed directly under the corresponding device .For example, in the image above, the group **"Group1"** has 1 node：Node1.

#### 2.Adding Devices in Excel

Select the groups and nodes, then drag the mouse to quickly copy.

![sparkplugb](../../../assets/images/sparkplugb.gif)


#### 3.Import Devices

Click the "Import" button in the upper right corner of the list to import the exported content. After importing, the newly added devices will have their enabled status set to "Disabled" by default.

<img width="1892" height="478" alt="image" src="https://github.com/user-attachments/assets/d0f5201a-e667-4ed0-9f6f-67456a10d515" />


## Batch Modification

You can batch modify device information through the exported Excel. After making changes in the Excel, import it back. During the import, the data will be updated based on the name.

- If the group name in the Excel matches the name in the MQTT SparkplugB list, the data in the Excel for that entry will be used to update the data.
- If the group name and node in the Excel match the entries in the MQTT SparkplugB list, the data in the Excel for that entry will also be used to update the data.
- If the group name or frame name in the Excel does not exist in the MQTT SparkplugB list, the group and node will be added to the list.
- If a group in the MQTT SparkplugB list does not exist in the imported file, the data for that group will remain unaffected in the list.

## Batch Deletion

After selecting the devices to be deleted, click the **Delete** button at the top of the list to perform batch deletion.

<img width="1901" height="474" alt="image" src="https://github.com/user-attachments/assets/5149f6e8-55e8-473d-95fa-944ade2e17c3" />


Notes:

- If there are **Enabled nodes** under the group, the group is not allowed to be deleted.
- Only groups on the current page can be deleted; cross-page deletion is not supported.
- When a group is deleted, its associated nodes will also be deleted.
