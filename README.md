# Task-3 Perform a Basic Vulnerability Scan on Your PC

## Tool Options

### Nessus

A widely used commercial vulnerability scanner developed by Tenable. It identifies security issues like misconfigurations, missing patches, and known vulnerabilities across networks, systems, and applications.

**OpenVAS:** A free, open-source alternative to Nessus for network vulnerability scanning.

## Objective Steps

After skipping the installation steps

### 1. Selecting Scan Type

A dashboard is presented after logging into the Nessus web interface, where we can choose our desired Scan Templete.

Here, we will select the `Basic Network Scan` option under the `Vulnerabilities section`.

![image](https://raw.githubusercontent.com/lakshaytondwal/task-3/refs/heads/main/img/1.png)

### 2. Configuring The scan

After selecting the Scan Templete, we can configure the required information related to the scan, such as targets, scan intensity, scan type, and ports.

![image](https://raw.githubusercontent.com/lakshaytondwal/task-3/refs/heads/main/img/2.png)

### 3. Initiating The Scan

Once all scan configurations are set — including targets, scan intensity, and port options — we can initiate the scan by clicking the "Save" button followed by the "Launch" option. Nessus will begin scanning the specified systems for vulnerabilities. The progress can be monitored in real time through the dashboard. Depending on the scope and depth of the scan, this process may take several minutes to complete.

![image](https://raw.githubusercontent.com/lakshaytondwal/task-3/refs/heads/main/img/3.png)

### 4. Observation

After the scan is complete, the results can be viewed by clicking on the completed scan entry in the dashboard. Nessus provides a detailed report showing discovered vulnerabilities, their severity levels (e.g., Critical, High, Medium, Low), affected hosts, and possible remediation steps. You can filter findings, explore affected ports and services, and export the report for documentation or further analysis.

**Selecting Host**
In this case, only a single host is attached, which has been intentionally left vulnerable for this practice, so we will select it.

![image](https://raw.githubusercontent.com/lakshaytondwal/task-3/refs/heads/main/img/4.png)

Here, we can see all the vulnerabilities that Nessus has found so far. However, it's important to note that Nessus and similar tools may produce false negatives, so manual verification and additional testing are necessary to ensure comprehensive coverage.

![image](https://raw.githubusercontent.com/lakshaytondwal/task-3/refs/heads/main/img/5.png)

If we select a particular vulnerability, Nessus provides all the necessary information about it, including possible mitigation steps, along with other sources as references.

![image](https://raw.githubusercontent.com/lakshaytondwal/task-3/refs/heads/main/img/6.png)

---
