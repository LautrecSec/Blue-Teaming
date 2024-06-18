# Incident Response (IR) and Windows Forensics Playbook

## Table of Contents
1. [Introduction](#introduction)
2. [Incident Response Steps](#incident-response-steps)
    - [Preparation](#preparation)
    - [Identification](#identification)
    - [Containment](#containment)
    - [Eradication](#eradication)
    - [Recovery](#recovery)
    - [Lessons Learned](#lessons-learned)
3. [Windows Forensics](#windows-forensics)
    - [Tools](#tools)
    - [Key Artifacts](#key-artifacts)
    - [Analysis Steps](#analysis-steps)
4. [Documentation](#documentation)

## Introduction
This playbook is designed to guide blue team members through the essential steps of incident response and Windows forensics. It provides a structured approach to handle security incidents, ensuring thorough and effective resolution.

## Incident Response Steps

### Preparation
- **Develop Policies and Procedures**: Ensure incident response policies are in place and regularly updated.
- **Training and Awareness**: Conduct regular training for all team members.
- **Tools and Resources**: Ensure all necessary tools and resources are readily available.

### Identification
- **Detection**: Use monitoring tools to detect potential incidents.
- **Analysis**: Verify and analyze the indicators of compromise (IOCs).
- **Documentation**: Record all findings and actions taken.

### Containment
- **Short-term Containment**: Implement immediate measures to contain the incident.
- **Long-term Containment**: Develop a strategy for more sustainable containment.

### Eradication
- **Identify Root Cause**: Determine the root cause of the incident.
- **Remove Threat**: Eliminate the root cause and all traces of the threat.

### Recovery
- **System Restoration**: Restore affected systems to normal operation.
- **Validation**: Ensure systems are secure and fully functional.

### Lessons Learned
- **Post-Incident Review**: Conduct a thorough review of the incident and response.
- **Documentation**: Update policies and procedures based on lessons learned.

## Windows Forensics

### Tools
- **Sysinternals Suite**: A collection of utilities for system monitoring, including Process Explorer, Autoruns, and more.
- **Volatility**: A powerful memory forensics framework.
- **Wireshark**: A network protocol analyzer.
- **FTK Imager**: A forensic imaging tool.
- **Autopsy**: A digital forensics platform.

### Key Artifacts
- **Event Logs**: Windows Event Logs (System, Application, Security).
- **Registry Hives**: Critical registry hives such as SYSTEM, SAM, and SOFTWARE.
- **Prefetch Files**: Used to speed up the startup of applications.
- **Browser History**: Internet Explorer, Chrome, Firefox history and cache files.
- **Scheduled Tasks**: Tasks that are scheduled to run automatically.

### Analysis Steps
1. **Initial Triage**: Perform an initial assessment to understand the scope of the incident.
2. **Collect Volatile Data**: Gather information from RAM, running processes, network connections.
3. **Acquire Disk Images**: Create forensic images of affected systems.
4. **Analyze Logs and Artifacts**: Review event logs, registry entries, and other artifacts.
5. **Identify Malicious Activity**: Look for signs of compromise such as unusual processes, unauthorized access, and data exfiltration.
6. **Report Findings**: Document all findings and create a detailed report.

## Documentation
- **Incident Report Template**: Standardized format for documenting incidents.
- **Evidence Collection Log**: Track all evidence collected during the investigation.
- **Chain of Custody Form**: Ensure integrity of collected evidence.
- **Post-Incident Review Form**: Template for conducting lessons learned reviews.

