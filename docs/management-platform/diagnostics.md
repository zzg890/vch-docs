# Diagnostics

Diagnostic module is usually a tool for operation and maintenance personnel to carry out system diagnosis and troubleshooting, and is mainly used to query server status, logs and other information.

You can view related log data under the "Diagnostics" menu.

<img width="285" height="253" alt="image" src="https://github.com/user-attachments/assets/71b597e8-becb-43e7-b927-dbcf3c25c86a" />


## **Dashboard**

The dashbaord is used to monitor and display the key indicators and data in real time to help users better understand the system operation and find and solve possible problems in time.

Indicators to be monitored:

- CPU Average Utilization
- Memory Utilization
- Memory Utilization

#### **CPU Average Utilization**

View the current CPU average utilization status through numerical values and line graphs. When the CPU average utilization exceeds 100%, it does not mean that the CPU is overloaded, but it is related to the number of cores of the CPU, for example, if the server CPU has 8 cores, then the percentage base of CPU utilization is 800%.

<img width="1892" height="799" alt="image" src="https://github.com/user-attachments/assets/76adcd75-d2f6-495e-9a30-b7fe78c2ea8b" />


#### **Memory Utilization**

View the current server memory utilization percentage by value and line graph.

<img width="1899" height="880" alt="image" src="https://github.com/user-attachments/assets/28b7413e-aafb-4934-9a16-8199519b5ca4" />


#### **Memory Usage**

With the specific memory usage values in the graph, you can clearly see how many MB of server memory is currently being used.

<img width="1895" height="802" alt="image" src="https://github.com/user-attachments/assets/8ba4bf9d-de7a-4342-8f5b-62510d1d5585" />


## **System Logs**

You can view the system logs recorded by the program on the System Logs page.

| **Icon**                                                                                                                                                                                                                              | **Level** |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------|
| <img width="18" height="19" alt="image" src="https://github.com/user-attachments/assets/37e98f96-0ee6-479e-b041-d293d1bcc9f8" />
 | Debug     |
| <img width="18" height="19" alt="image" src="https://github.com/user-attachments/assets/532fa859-eea1-465c-b028-b9f1f0fa006f" />
 | Info      |
| <img width="18" height="19" alt="image" src="https://github.com/user-attachments/assets/bab34694-25a6-40bc-9fa8-7f10cde301e7" />
 | Warn      |
| <img width="18" height="19" alt="image" src="https://github.com/user-attachments/assets/e94db302-71a0-4fbb-9adf-67b8365f2336" />
 | Error     |

<img width="1896" height="818" alt="image" src="https://github.com/user-attachments/assets/ce1ca940-5576-4df2-bf8a-c38f4cb15d48" />


Users can click on the "Details" button to the right of any data to view the specific log content.

**Filter**

- Time Range: the default range is from 00:00 of the current day to 00:00 of the next day, users can modify the time range for filtering query according to their needs, but the time span cannot exceed 24 hours.
- Log Level: Users can filter logs by log level, currently supports 4 levels, Debug, Info, Warn, Error, under the condition of selecting All, logs of all levels will be queried.
- Log content: Users can input the keywords of log content for fuzzy matching.

Click "Query" button after inputting conditions.

**Export**

Users can click the Export button to export all the data queried under the current filtering conditions and download it as an Excel file.

## **Performance Logs**

On the Performance Logs page, you can view the execution efficiency of core modules. 

<img width="1895" height="831" alt="image" src="https://github.com/user-attachments/assets/928b2a3a-6e61-482d-b5db-359503b36032" />


## **Running Status**

You can view the execution status of a module on the Runninge Status page. Click the "Detail" button on the right to view the details.

<img width="1849" height="800" alt="image" src="https://github.com/user-attachments/assets/bc95931f-5fbd-441a-813f-3fb60d56f8fb" />


## **Log Configuration**

You can configure the storage policy of system logs.

The default storage policy is to record only Error type logs and keep them for 7 days only. You can change it according to your needs. When you change it, you should consider the size of the hard disk, and it is not recommended to set the number of days to keep the logs too long. 

<img width="1511" height="805" alt="image" src="https://github.com/user-attachments/assets/7c5723c1-e8ec-4c5d-9164-1af51cfdd689" />


## **Event Configuration**

Used to configure the storage policy of tag events. The events recorded here can be displayed on the "Real-time Events" and "Historical Events" controls.

The default event expiration date is 180 days, and the system will clean up the stale data regularly according to the set expiration date. 

<img width="1503" height="800" alt="image" src="https://github.com/user-attachments/assets/c3eaceac-8366-448c-bdc4-f5ea85771e1f" />


