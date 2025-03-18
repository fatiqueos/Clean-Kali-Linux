# Kali Cleanup Script  

## Description  

This Bash script is designed to remove various cybersecurity tools pre-installed on **Kali Linux**. It iterates through a predefined list of tools and uninstalls them from the system. Afterward, it runs the `autoremove` command to clean up unnecessary dependencies, ensuring a streamlined and lightweight system.  

## Usage Instructions  

### 1. Download or Copy the Script  
Ensure you have the script saved on your system.  

### 2. Open Terminal and Navigate to the Script Directory  
Use the `cd` command to move to the directory where the script is located.  

### 3. Make the Script Executable  
Run the following command to grant execution permissions:  

```bash
chmod +x kali_cleanup.sh
```

### 4. Run the Script  
Execute the script using the command:  

```bash
./kali_cleanup.sh
```

Once executed, the script will begin removing the listed cybersecurity tools and perform system cleanup using `autoremove`.  

## ⚠️ Important Notice  

- This script **permanently** removes cybersecurity tools from Kali Linux.  
- Ensure you **do not need** these tools before running the script.  
- Use it with caution, as reinstallation may require additional setup.  

## License  

This script is open-source and can be modified as needed. Use at your own risk.  
