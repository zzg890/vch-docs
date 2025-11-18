# Batch Instantiate Models

You can batch instantiate models in the following way.

1. In the "Instances" tab, click the "Add" button and select "Instance."

<img width="374" height="229" alt="image" src="https://github.com/user-attachments/assets/08de2e98-652a-4645-8dd5-ec1845496360" />


2. In the "Instances" tab, right-click on the folder and select "Add Instance" from the context menu.

<img width="300" height="320" alt="image" src="https://github.com/user-attachments/assets/8b3c2ac4-1ed5-4b9d-8efc-c251342190d8" />


3. In the "Models" tab, right-click on the model and select "Add Instance" from the context menu.

<img width="304" height="341" alt="image" src="https://github.com/user-attachments/assets/5ef6d852-5159-443c-b5fc-54ae221d4cc3" />


## Modify instance properties through the page

Click the "Generate" button in the batch instance section, enter the number of instances to generate and the starting sequence number, and generate multiple instances.

<img width="903" height="295" alt="image" src="https://github.com/user-attachments/assets/1673fb00-32bc-4850-bfbc-115973479255" />


In the custom list, display the generated instances along with their corresponding custom attributes. You can modify the cell content as needed.

<img width="895" height="739" alt="image" src="https://github.com/user-attachments/assets/6011ac35-6333-475c-b5ab-55e8b2cd61aa" />


When the number of instances or custom attributes is large, performing operations directly on the page may be inconvenient. Therefore, we also provide an export and import function. You can export the data, edit it in Excel, and then import it back.

## Modify instance attributes through the exported file

#### Export 

After generating instances, click the **Export** button to export the instances.

<img width="893" height="739" alt="image" src="https://github.com/user-attachments/assets/c3156a36-652c-422e-a283-3009f8363c0b" />


After the export is successful, edit the file in Excel according to the exported format. Each row represents an instance. The first column is the instance name, and the remaining columns are the custom parameters of the selected model.The first column is the instance name, and the remaining columns are the custom parameters of the model.Each row corresponds to an instance.

<img width="497" height="335" alt="image" src="https://github.com/user-attachments/assets/541e063c-5150-4765-a75d-d2b272260751" />


**Notes:**  1. Columns created manually in Excel will not appear in the custom list after import. 2. If a custom property column is deleted in Excel, the corresponding values in the custom list will be empty after import. 


#### Import 

After modifying the file, click the "Import" button to import the file.

<img width="895" height="742" alt="image" src="https://github.com/user-attachments/assets/7e9a4483-feaa-435f-9bd5-3be521f13dc6" />


After the import is complete, click the "OK" button to generate multiple instances in the asset tree.


