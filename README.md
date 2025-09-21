# NIST CSF 2.0 Checklist

> **NIST Cybersecurity Framework Compliance to Mitigate Cyber Risk**

An interactive visual checklist for NIST Cybersecurity Framework (CSF) 2.0 compliance using an intuitive mind map interface.

## 🎯 Overview

This repository contains an interactive markmap visualization of the complete NIST CSF 2.0 framework, designed to help organizations systematically assess and implement cybersecurity controls to mitigate cyber risks.

## 📊 Framework Structure

```mermaid
graph TD
    A[NIST CSF 2.0<br/>Compliance Checklist] --> B[🏛️ Govern - GV]
    A --> C[🔍 Identify - ID]
    A --> D[🛡️ Protect - PR]
    A --> E[👁️ Detect - DE]
    A --> F[🚨 Respond - RS]
    A --> G[🔄 Recover - RC]
    
    %% Govern Function
    B --> B1[GV.OC<br/>Organizational Context]
    B --> B2[GV.RR<br/>Roles & Responsibilities]
    B --> B3[GV.RM<br/>Risk Management Strategy]
    B --> B4[GV.PO<br/>Policy]
    B --> B5[GV.OV<br/>Oversight]
    B --> B6[GV.SC<br/>Supply Chain Risk Mgmt]
    
    B1 --> B1a[GV.OC-01: Mission & Context]
    B1 --> B1b[GV.OC-02: Stakeholder Expectations]
    B1 --> B1c[GV.OC-03: Legal Requirements]
    B1 --> B1d[GV.OC-04: Critical Objectives]
    B1 --> B1e[GV.OC-05: External Dependencies]
    
    B2 --> B2a[GV.RR-01: Leadership Accountability]
    B2 --> B2b[GV.RR-02: Defined Roles]
    B2 --> B2c[GV.RR-03: Resource Allocation]
    B2 --> B2d[GV.RR-04: HR Integration]
    
    %% Identify Function
    C --> C1[ID.AM<br/>Asset Management]
    C --> C2[ID.RA<br/>Risk Assessment]
    C --> C3[ID.IM<br/>Improvement]
    
    C1 --> C1a[ID.AM-01: Physical Devices]
    C1 --> C1b[ID.AM-02: Software Platforms]
    C1 --> C1c[ID.AM-03: Data Flows]
    C1 --> C1d[ID.AM-04: External Systems]
    C1 --> C1e[ID.AM-05: Resource Priority]
    C1 --> C1f[ID.AM-06: Cybersecurity Roles]
    
    C2 --> C2a[ID.RA-01: Asset Vulnerabilities]
    C2 --> C2b[ID.RA-02: Threat Intelligence]
    C2 --> C2c[ID.RA-03: Threat Identification]
    C2 --> C2d[ID.RA-04: Business Impact]
    C2 --> C2e[ID.RA-05: Risk Determination]
    C2 --> C2f[ID.RA-06: Risk Responses]
    
    %% Protect Function
    D --> D1[PR.AA<br/>Identity & Access Control]
    D --> D2[PR.AT<br/>Awareness & Training]
    D --> D3[PR.DS<br/>Data Security]
    D --> D4[PR.IP<br/>Info Protection Processes]
    D --> D5[PR.PS<br/>Platform Security]
    D --> D6[PR.IR<br/>Infrastructure Resilience]
    D --> D7[PR.PT<br/>Protective Technology]
    
    D1 --> D1a[PR.AA-01: Identity Management]
    D1 --> D1b[PR.AA-02: Physical Access]
    D1 --> D1c[PR.AA-03: Remote Access]
    D1 --> D1d[PR.AA-04: Least Privilege]
    D1 --> D1e[PR.AA-05: Network Integrity]
    D1 --> D1f[PR.AA-06: Identity Proofing]
    D1 --> D1g[PR.AA-07: Authentication]
    
    D3 --> D3a[PR.DS-01: Data at Rest]
    D3 --> D3b[PR.DS-02: Data in Transit]
    D3 --> D3c[PR.DS-03: Asset Disposition]
    D3 --> D3d[PR.DS-04: Capacity Management]
    D3 --> D3e[PR.DS-05: Data Leak Protection]
    D3 --> D3f[PR.DS-06: Integrity Checking]
    D3 --> D3g[PR.DS-07: Dev/Test Separation]
    D3 --> D3h[PR.DS-08: Hardware Integrity]
    
    %% Detect Function
    E --> E1[DE.AE<br/>Anomalies & Events]
    E --> E2[DE.CM<br/>Continuous Monitoring]
    E --> E3[DE.DP<br/>Detection Processes]
    
    E1 --> E1a[DE.AE-01: Network Baseline]
    E1 --> E1b[DE.AE-02: Event Analysis]
    E1 --> E1c[DE.AE-03: Event Correlation]
    E1 --> E1d[DE.AE-04: Impact Determination]
    E1 --> E1e[DE.AE-05: Alert Thresholds]
    
    E2 --> E2a[DE.CM-01: Network Monitoring]
    E2 --> E2b[DE.CM-02: Physical Monitoring]
    E2 --> E2c[DE.CM-03: Personnel Monitoring]
    E2 --> E2d[DE.CM-04: Malicious Code Detection]
    E2 --> E2e[DE.CM-05: Mobile Code Detection]
    E2 --> E2f[DE.CM-06: External Provider Monitoring]
    E2 --> E2g[DE.CM-07: Unauthorized Monitoring]
    E2 --> E2h[DE.CM-08: Vulnerability Scanning]
    
    %% Respond Function
    F --> F1[RS.MA<br/>Incident Management]
    F --> F2[RS.CO<br/>Communications]
    F --> F3[RS.AN<br/>Analysis]
    F --> F4[RS.MI<br/>Mitigation]
    F --> F5[RS.IM<br/>Improvements]
    
    F1 --> F1a[RS.MA-01: Response Processes]
    F1 --> F1b[RS.MA-02: Response Plans]
    F1 --> F1c[RS.MA-03: Incident Categories]
    
    F2 --> F2a[RS.CO-01: Personnel Roles]
    F2 --> F2b[RS.CO-02: Incident Reporting]
    F2 --> F2c[RS.CO-03: Information Sharing]
    F2 --> F2d[RS.CO-04: Stakeholder Coordination]
    F2 --> F2e[RS.CO-05: External Sharing]
    
    F4 --> F4a[RS.MI-01: Incident Containment]
    F4 --> F4b[RS.MI-02: Incident Mitigation]
    F4 --> F4c[RS.MI-03: Vulnerability Mitigation]
    
    %% Recover Function
    G --> G1[RC.RP<br/>Recovery Planning]
    G --> G2[RC.IM<br/>Improvements]
    G --> G3[RC.CO<br/>Communications]
    
    G1 --> G1a[RC.RP-01: Recovery Execution]
    
    G2 --> G2a[RC.IM-01: Lessons Learned]
    G2 --> G2b[RC.IM-02: Strategy Updates]
    
    G3 --> G3a[RC.CO-01: Public Relations]
    G3 --> G3b[RC.CO-02: Reputation Repair]
    G3 --> G3c[RC.CO-03: Recovery Communications]
    
    %% Styling
    classDef governStyle fill:#e1f5fe,stroke:#01579b,stroke-width:2px,color:#000
    classDef identifyStyle fill:#f3e5f5,stroke:#4a148c,stroke-width:2px,color:#000
    classDef protectStyle fill:#e8f5e8,stroke:#1b5e20,stroke-width:2px,color:#000
    classDef detectStyle fill:#fff3e0,stroke:#e65100,stroke-width:2px,color:#000
    classDef respondStyle fill:#ffebee,stroke:#c62828,stroke-width:2px,color:#000
    classDef recoverStyle fill:#f1f8e9,stroke:#33691e,stroke-width:2px,color:#000
    classDef mainStyle fill:#fff9c4,stroke:#f57f17,stroke-width:3px,color:#000,font-weight:bold
    
    class A mainStyle
    class B,B1,B2,B3,B4,B5,B6,B1a,B1b,B1c,B1d,B1e,B2a,B2b,B2c,B2d governStyle
    class C,C1,C2,C3,C1a,C1b,C1c,C1d,C1e,C1f,C2a,C2b,C2c,C2d,C2e,C2f identifyStyle
    class D,D1,D2,D3,D4,D5,D6,D7,D1a,D1b,D1c,D1d,D1e,D1f,D1g,D3a,D3b,D3c,D3d,D3e,D3f,D3g,D3h protectStyle
    class E,E1,E2,E3,E1a,E1b,E1c,E1d,E1e,E2a,E2b,E2c,E2d,E2e,E2f,E2g,E2h detectStyle
    class F,F1,F2,F3,F4,F5,F1a,F1b,F1c,F2a,F2b,F2c,F2d,F2e,F4a,F4b,F4c respondStyle
    class G,G1,G2,G3,G1a,G2a,G2b,G3a,G3b,G3c recoverStyle
```

## 📋 What's Included

### Interactive Markmap
- **File**: `nist-csf-2.0-checklist.html`
- **Description**: A fully interactive mind map that visualizes all NIST CSF 2.0 controls
- **Features**:
  - Expandable/collapsible nodes
  - Dark/light mode support
  - Full-screen interactive navigation
  - Zoom and pan capabilities

### Framework Coverage

The checklist covers all six core functions of NIST CSF 2.0:

#### 🏛️ **Govern (GV)** - Foundational Function
- **GV.OC**: Organizational Context
- **GV.RR**: Roles, Responsibilities, and Authorities
- **GV.RM**: Risk Management Strategy
- **GV.PO**: Policy
- **GV.OV**: Oversight
- **GV.SC**: Cybersecurity Supply Chain Risk Management

#### 🔍 **Identify (ID)**
- **ID.AM**: Asset Management
- **ID.RA**: Risk Assessment
- **ID.IM**: Improvement

#### 🛡️ **Protect (PR)**
- **PR.AA**: Identity Management, Authentication and Access Control
- **PR.AT**: Awareness and Training
- **PR.DS**: Data Security
- **PR.IP**: Information Protection Processes and Procedures
- **PR.PS**: Platform Security
- **PR.IR**: Technology Infrastructure Resilience
- **PR.PT**: Protective Technology

#### 👁️ **Detect (DE)**
- **DE.AE**: Anomalies and Events
- **DE.CM**: Security Continuous Monitoring
- **DE.DP**: Detection Processes

#### 🚨 **Respond (RS)**
- **RS.MA**: Incident Management
- **RS.CO**: Communications
- **RS.AN**: Analysis
- **RS.MI**: Mitigation
- **RS.IM**: Improvements

#### 🔄 **Recover (RC)**
- **RC.RP**: Recovery Planning
- **RC.IM**: Improvements
- **RC.CO**: Communications

## 🚀 How to Use

### Method 1: Direct Browser Access
1. Download the `nist-csf-2.0-checklist.html` file
2. Open it in any modern web browser
3. Navigate through the interactive mind map
4. Click on nodes to expand/collapse sections
5. Use the toolbar in the bottom-right corner for additional features

### Method 2: GitHub Pages (if enabled)
1. Visit the GitHub Pages URL for this repository
2. Access the interactive checklist directly online

## 💡 Features

- **Interactive Navigation**: Click to expand/collapse framework sections
- **Visual Organization**: Hierarchical structure makes it easy to understand relationships
- **Comprehensive Coverage**: All 104 controls from NIST CSF 2.0
- **Mobile Responsive**: Works on desktop, tablet, and mobile devices
- **Dark Mode Support**: Automatically adapts to your system preferences
- **Zoom & Pan**: Navigate large framework sections with ease

## 🎨 Customization

The markmap visualization supports:
- Custom color schemes
- Adjustable font sizes
- Export capabilities (SVG, PNG)
- Print-friendly formatting

## 📚 About NIST CSF 2.0

The NIST Cybersecurity Framework 2.0 provides a policy framework of computer security guidance for how private sector organizations in the United States can assess and improve their ability to prevent, detect, and respond to cyber attacks.

### Key Improvements in Version 2.0:
- Enhanced **Govern** function as a foundational element
- Expanded supply chain risk management
- Improved integration with other frameworks
- Better alignment with current threat landscape

## 🤝 Contributing

Contributions are welcome! Please feel free to:
- Report issues with the visualization
- Suggest improvements to the framework mapping
- Submit updates for new NIST CSF versions
- Enhance the interactive features

## 📄 License

This project is open source and follows the terms specified in the LICENSE file.

## 📞 Support

For questions, issues, or suggestions:
1. Open an issue in this repository
2. Review the NIST CSF documentation
3. Check the markmap documentation for technical details

## 🔗 Useful Links

- [NIST Cybersecurity Framework 2.0 Official Documentation](https://www.nist.gov/cyberframework)
- [Markmap Documentation](https://markmap.js.org/)
- [NIST CSF Implementation Guidance](https://www.nist.gov/cyberframework/implementation-guidance)

---

**Created by**: Shubhendu  
**Framework Version**: NIST CSF 2.0  
**Last Updated**: September 2024  

*This tool is designed to assist with NIST CSF compliance assessment and should be used in conjunction with official NIST documentation and qualified cybersecurity professionals.*