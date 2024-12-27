# SOC-Automation-Project
The goal of this Project is to fully integrated SOAR solution incorporating Wazuh &amp; TheHive for case management. 


Invoke-WebRequest -Uri https://packages.wazuh.com/4.x/windows/wazuh-agent-4.9.2-1.msi -OutFile $env:tmp\wazuh-agent; msiexec.exe /i $env:tmp\wazuh-agent /q WAZUH_MANAGER='142.93.33.92' WAZUH_AGENT_NAME='MyAgent' 
