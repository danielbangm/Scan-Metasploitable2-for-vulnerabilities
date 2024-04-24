<p align="center">
<img src="https://shorturl.at/cjxy2" />
</p>

<h1>OpenVAS: Scanning Metasploitable2 </h1>

The goal of this lab is to Scan Metasploitable2 using OpenVAS Greenbone Security Manager.  

<h2>Objectives</h2>

-  Learning how to perform a Scan with OpenVAS
-  Getting more familiar with Greenbone Security Manager.
-  Gain a better understanding of all parts of OpenVAS (How to start and stop the OpenVAS process).

<h2>Environments and Technologies Used</h2>

- Virtual Machine
- Kali Linux VM
- OpenVAS
- VMWare Workstation
- Greenbone Security Manager website

<h2>Operating Systems Used</h2>

- Linux

<h2>List of Prerequisites</h2>

- You need to download VMWare Workstation and have a computer of at least 8GB of RAM

<h2>Scanning Steps</h2>

-  Step 1: What is OpenVAS: Greenbone Security Manager?

OpenVAS (Open Vulnerability Assessment System, originally known as GNessUs) is the scanner component of Greenbone Vulnerability Manager (GVM), a software framework of several services and tools offering vulnerability scanning and vulnerability management. The Greenbone Security Manager (GSM) is an appliance for the vulnerability management of IT infrastructures, available as physical or virtual models. It assists companies and agencies with automated and integrated vulnerability assessment and management. Its task is to discover vulnerabilities and security gaps before a potential attacker does.

-  Step 2: Scanning a System OpenVAS

For this exercise, I will scan our Metasploitable2-Linux System. First go back to Metasploitable2 and grab the IP address by typing <b>ifconfig</b> and write it down.

![image](https://github.com/danielbangm/Scan-Metasploitable2-for-vulnerabilities/assets/22795502/8fc4d7c1-9ee7-4c48-aeaa-e302bc4af42e)

Now let's configure a new task as follow: Select Scans > Tasks in the menu bar. Start the wizard by moving the mouse over and clicking Task Wizard. Enter the IP address or host name of the target system in the input box. This will be the Metasploitable IP Address.

![image](https://github.com/danielbangm/Scan-Metasploitable2-for-vulnerabilities/assets/22795502/be5dae71-32a4-4feb-8da3-95512bb7021c)

⦁	Click Start Scan → The task wizard performs the following steps automatically: Creating a new scan target on the GSM, Creating a new scan task on the GSM, Starting the scan task immediately, Displaying the page Tasks.
After the task is started, the progress can be monitored 

![image](https://github.com/danielbangm/Scan-Metasploitable2-for-vulnerabilities/assets/22795502/07372618-df08-4017-b870-94b50bba3c8b)

Now that the scan has started……We wait……This may take a while, it’s not quick. Just start the scan, and take a break….
If you are curious if anything has been detected during the scan, you can click on the “1” under Reports

![image](https://github.com/danielbangm/Scan-Metasploitable2-for-vulnerabilities/assets/22795502/d65d19eb-0f70-42b8-a16c-b257077d47fd)


In the next section, I am going to analyze the scan



<p align="center">
<img src="https://shorturl.at/foEHX" />
</p>
