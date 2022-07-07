# Microsoft-Sentinel-As-A-Code
Export Microsoft Sentinel artifacts like Analytical Rules, Hunting Queries, Workbooks in order to support new feature Repositories CI/CD Pipeline
- Currently supporting
	- Scheduled Analytical Rules
	- Automation Rules
	- Parsers (Saved Searches - KQL Functions)
	- Workbooks

# How to use
1. Download the Tool  
   [![Download](./images/Download.png)](https://github.com/sreedharande/Microsoft-Sentinel-As-A-Code/archive/refs/heads/main.zip)

2. Extract the folder and open "Export_Sentinel_Artifacts.ps1" either in Visual Studio Code/PowerShell(Admin)

   **Note**  
   The script runs from the user's machine. You must allow PowerShell script execution. To do so, run the following command:
   
   ```PowerShell
   Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass  
   ```  

3. Run the script using the following command  
   ```  
   .\Export_Sentinel_Artifacts.ps1 -TenantID xxxx `
                        
   ```

# Questions ❓ / Issues 🙋‍♂️ / Feedback 🗨
Post [here](https://github.com/sreedharande/Microsoft-Sentinel-As-A-Code/issues).

Contributions are welcome! 👏
