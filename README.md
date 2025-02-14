Some staff to automate QA lead routine with UIPATH RPA
General description: 
1. Main.xaml - Flow of the web-scrapping prepared in the Jira user stories and creating list of the tasks for QA team

![image](https://github.com/user-attachments/assets/22365b29-f97d-407e-9925-d3bfc85a646e)

More detailed steps: 
1) Use Browser Edge: Issue Navigator - JIRA - Browser navigating action to the URL "https://projects.*.com/secure/RapidBoard.jspa?rapidView=1570&projectKey=QIP&view=planning.nodetail&quickFilter=10929&issueLimit=100#"

![image](https://github.com/user-attachments/assets/d3d7718f-1da8-4379-b0e3-abb76f8c311b)

2) Extract Table Data - extracting all data to the ExtractDataTable Variable

![image](https://github.com/user-attachments/assets/544b0017-0078-46ed-aa90-4ec56e43fff5)

3) Google sheet Write Range action -authorizing and inserting all data from variable to the AS (Sheet)

Result
![image](https://github.com/user-attachments/assets/9b29456c-0b8b-411c-b727-e71fb2d2e669)

2. Final_report_tracebility_matrix_googlesheet.xaml - generating final tracebility report
     ![image](https://github.com/user-attachments/assets/1a5da152-6e2a-401d-aac1-28d071f3701c)

   1a) For Each Row in Spreadsheet - Do -Read Cell from prepared sheet ![image](https://github.com/user-attachments/assets/36542200-4bdf-41f4-8d52-274c913b2df5)
   1b) Type Into 'Test cycles' ![image](https://github.com/user-attachments/assets/613bbf48-bc7a-4535-8577-f867f3315596)

   3) ![image](https://github.com/user-attachments/assets/dc16e1d4-7b36-473f-a6fb-1b34cd351a9a)


  
 
