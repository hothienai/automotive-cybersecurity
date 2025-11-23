Term Definitions and Abbreviations
=====================================================

Introduction
------------

This document provides comprehensive definitions of terms and abbreviations used in the ``Automotive CyberSecurity`` domain. Understanding this terminology is essential for anyone working with automotive cybersecurity implementations, from developers and engineers to product managers, security researchers, and certification specialists.

This guide covers multiple aspects of automotive cybersecurity including:

- Vehicle architecture and networks
- Security standards and regulations
- Threat modeling and risk assessment
- Cryptographic concepts
- Attack vectors and vulnerabilities
- Secure development practices

Vehicle Architecture and Network Terms
---------------------------------------

``Electronic Control Unit (ECU)``
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    - A microcontroller-based device that controls one or more electrical systems in a vehicle (e.g., engine control, braking, infotainment).

``Controller Area Network (CAN)``
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    - A robust vehicle bus standard allowing microcontrollers and devices to communicate without a host computer, widely used for in-vehicle networking.

``CAN Bus``
~~~~~~~~~~~
    - The physical network implementation using the CAN protocol, connecting ECUs throughout the vehicle.

``FlexRay``
~~~~~~~~~~~
    - A deterministic, fault-tolerant automotive network protocol designed for high-speed, safety-critical applications.

``Local Interconnect Network (LIN)``
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    - A low-cost serial network protocol for distributed electronic systems in vehicles, typically for non-critical applications.

``Media Oriented Systems Transport (MOST)``
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    - A multimedia network technology for automotive applications, supporting audio, video, and data transmission.

``Automotive Ethernet``
~~~~~~~~~~~~~~~~~~~~~~~
    - High-bandwidth Ethernet networking technology adapted for automotive use, supporting advanced features like ADAS and autonomous driving.

``Gateway ECU``
~~~~~~~~~~~~~~~
    - A central ECU that connects different vehicle networks (CAN, LIN, FlexRay, Ethernet) and controls communication between them.

``Telematics Control Unit (TCU)``
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    - An embedded system providing wireless connectivity for vehicle tracking, diagnostics, and remote services.

``On-Board Diagnostics (OBD)``
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    - Vehicle self-diagnostic and reporting capability, with OBD-II being the standard interface for accessing diagnostic information.

``Domain Controller``
~~~~~~~~~~~~~~~~~~~~~
    - High-performance computing units consolidating functions from multiple ECUs into centralized domains (e.g., powertrain, chassis, ADAS).

Security Standards and Regulations
-----------------------------------

``ISO/SAE 21434``
~~~~~~~~~~~~~~~~~
    - International standard for road vehicle cybersecurity engineering, covering the entire vehicle lifecycle from concept to decommissioning.

``UN R155``
~~~~~~~~~~~
    - United Nations regulation mandating cybersecurity management systems for vehicle manufacturers.

``UN R156``
~~~~~~~~~~~
    - United Nations regulation for software update management systems in vehicles.

``AUTOSAR (AUTomotive Open System ARchitecture)``
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    - A worldwide development partnership of vehicle manufacturers and suppliers for standardized automotive software architecture.

``AUTOSAR Adaptive Platform``
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    - AUTOSAR architecture for high-performance computing platforms, supporting dynamic applications and modern software paradigms.

``AUTOSAR Classic Platform``
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    - Traditional AUTOSAR architecture for deeply embedded ECUs with real-time constraints and safety requirements.

``SAE J3061``
~~~~~~~~~~~~~
    - SAE guidebook for cybersecurity for cyber-physical vehicle systems.

``NIST Cybersecurity Framework``
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    - Framework providing guidelines for managing cybersecurity risks, increasingly applied to automotive systems.

``Common Criteria (CC)``
~~~~~~~~~~~~~~~~~~~~~~~~
    - International standard (ISO/IEC 15408) for computer security certification.

Threat Modeling and Risk Assessment
------------------------------------

``TARA (Threat Analysis and Risk Assessment)``
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    - Systematic approach to identify, analyze, and assess cybersecurity threats and vulnerabilities in automotive systems.

``Attack Tree``
~~~~~~~~~~~~~~~
    - Hierarchical diagram representing potential attack paths, showing how an attacker might achieve specific goals.

``Attack Surface``
~~~~~~~~~~~~~~~~~~
    - The sum of all possible points where an unauthorized user could attempt to enter or extract data from a system.

``Threat Actor``
~~~~~~~~~~~~~~~~
    - An entity (individual, group, or organization) capable of carrying out a cybersecurity threat.

``Vulnerability``
~~~~~~~~~~~~~~~~~
    - A weakness in a system that can be exploited by a threat actor to perform unauthorized actions.

``Exploit``
~~~~~~~~~~~
    - A piece of software, data, or sequence of commands that takes advantage of a vulnerability to cause unintended behavior.

``STRIDE Model``
~~~~~~~~~~~~~~~~
    - Threat modeling framework categorizing threats into: Spoofing, Tampering, Repudiation, Information Disclosure, Denial of Service, Elevation of Privilege.

``DREAD Model``
~~~~~~~~~~~~~~~
    - Risk assessment model rating threats based on: Damage, Reproducibility, Exploitability, Affected users, Discoverability.

``CVSS (Common Vulnerability Scoring System)``
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    - Industry standard for assessing the severity of computer system security vulnerabilities.

``CAL (Cybersecurity Assurance Level)``
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    - Risk-based approach in ISO/SAE 21434 defining the rigor of cybersecurity activities based on risk assessment.

``Impact Rating``
~~~~~~~~~~~~~~~~~
    - Assessment of potential consequences if a cybersecurity threat is realized (e.g., severe, major, moderate, negligible).

``Attack Feasibility Rating``
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    - Assessment of how difficult it would be for an attacker to successfully exploit a vulnerability.

Attack Vectors and Vulnerabilities
-----------------------------------

``Man-in-the-Middle (MitM) Attack``
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    - Attack where the attacker secretly intercepts and possibly alters communications between two parties.

``Replay Attack``
~~~~~~~~~~~~~~~~~
    - Attack where valid data transmission is maliciously repeated or delayed.

``Relay Attack``
~~~~~~~~~~~~~~~~
    - Attack extending the range of wireless communications to gain unauthorized access (common in keyless entry systems).

``Fuzzing``
~~~~~~~~~~~
    - Automated testing technique providing invalid, unexpected, or random data as inputs to discover vulnerabilities.

``CAN Bus Injection``
~~~~~~~~~~~~~~~~~~~~~
    - Attack where malicious messages are injected into the CAN bus to manipulate vehicle behavior.

``Remote Code Execution (RCE)``
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    - Vulnerability allowing an attacker to execute arbitrary code on a target system remotely.

``Denial of Service (DoS)``
~~~~~~~~~~~~~~~~~~~~~~~~~~~
    - Attack making a system or network resource unavailable by overwhelming it with traffic or exploiting vulnerabilities.

``Side-Channel Attack``
~~~~~~~~~~~~~~~~~~~~~~~
    - Attack based on information gained from physical implementation (timing, power consumption, electromagnetic leaks).

``Zero-Day Vulnerability``
~~~~~~~~~~~~~~~~~~~~~~~~~~
    - Previously unknown vulnerability that has no patch or fix available.

``Backdoor``
~~~~~~~~~~~~
    - Hidden method of bypassing normal authentication or encryption in a system.

``Social Engineering``
~~~~~~~~~~~~~~~~~~~~~~
    - Psychological manipulation of people to divulge confidential information or perform actions compromising security.

Secure Development and Testing
-------------------------------

``Secure Software Development Lifecycle (SSDLC)``
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    - Development process integrating security considerations at every phase of the software lifecycle.

``Penetration Testing``
~~~~~~~~~~~~~~~~~~~~~~~
    - Authorized simulated cyberattack on a system to evaluate security and identify vulnerabilities.

``Security by Design``
~~~~~~~~~~~~~~~~~~~~~~
    - Approach where security is considered from the initial design phase rather than added later.

``Defense in Depth``
~~~~~~~~~~~~~~~~~~~~
    - Layered security strategy using multiple security measures to protect assets.

``Least Privilege Principle``
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    - Security concept where users/processes are granted only minimum access rights needed to perform their functions.

``Security Requirements``
~~~~~~~~~~~~~~~~~~~~~~~~~
    - Specifications defining security properties and capabilities a system must have.

``Secure Boot``
~~~~~~~~~~~~~~~
    - Security mechanism ensuring only authenticated software can execute during system startup.

``Code Signing``
~~~~~~~~~~~~~~~~
    - Cryptographic method to verify the authenticity and integrity of software code.

``Whitebox Testing``
~~~~~~~~~~~~~~~~~~~~
    - Security testing with full knowledge of internal system structure and implementation.

``Blackbox Testing``
~~~~~~~~~~~~~~~~~~~~
    - Security testing without knowledge of internal system workings, simulating external attacker perspective.

``Static Application Security Testing (SAST)``
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    - Analysis of source code for security vulnerabilities without executing the program.

``Dynamic Application Security Testing (DAST)``
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    - Testing of running applications to find security vulnerabilities.

Advanced Vehicle Technologies
------------------------------

``Advanced Driver Assistance Systems (ADAS)``
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    - Electronic systems helping drivers in driving and parking, including features like adaptive cruise control, lane keeping.

``Vehicle-to-Everything (V2X)``
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    - Communication between a vehicle and other entities including infrastructure, pedestrians, and other vehicles.

``Vehicle-to-Vehicle (V2V)``
~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    - Direct wireless communication between vehicles to share information about speed, position, and direction.

``Vehicle-to-Infrastructure (V2I)``
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    - Communication between vehicles and roadside infrastructure like traffic lights and road signs.

``Cooperative Intelligent Transport Systems (C-ITS)``
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    - Systems enabling vehicles, infrastructure, and other road users to share information for improved safety and efficiency.

``Software-Defined Vehicle (SDV)``
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    - Vehicle where features and functions are primarily defined and controlled by software rather than hardware.

Abbreviations
-------------

.. list-table::
   :header-rows: 1
   :widths: 20 80

   * - Abbreviation
     - Full Form
   * - ADAS
     - Advanced Driver Assistance Systems
   * - AES
     - Advanced Encryption Standard
   * - API
     - Application Programming Interface
   * - APDU
     - Application Protocol Data Unit
   * - AUTOSAR
     - AUTomotive Open System ARchitecture
   * - BLE
     - Bluetooth Low Energy
   * - CA
     - Certificate Authority
   * - CAL
     - Cybersecurity Assurance Level
   * - CAN
     - Controller Area Network
   * - CC
     - Common Criteria
   * - C-ITS
     - Cooperative Intelligent Transport Systems
   * - CVE
     - Common Vulnerabilities and Exposures
   * - CVSS
     - Common Vulnerability Scoring System
   * - DAST
     - Dynamic Application Security Testing
   * - DDoS
     - Distributed Denial of Service
   * - DoS
     - Denial of Service
   * - DREAD
     - Damage, Reproducibility, Exploitability, Affected users, Discoverability
   * - E2EE
     - End-to-End Encryption
   * - ECC
     - Elliptic Curve Cryptography
   * - ECDSA
     - Elliptic Curve Digital Signature Algorithm
   * - ECU
     - Electronic Control Unit
   * - eSE
     - Embedded Secure Element
   * - FIPS
     - Federal Information Processing Standards
   * - HMAC
     - Hash-based Message Authentication Code
   * - HSM
     - Hardware Security Module
   * - IDS
     - Intrusion Detection System
   * - IEEE
     - Institute of Electrical and Electronics Engineers
   * - IPS
     - Intrusion Prevention System
   * - ISO
     - International Organization for Standardization
   * - KMS
     - Key Management System
   * - LIN
     - Local Interconnect Network
   * - MAC
     - Message Authentication Code (or Media Access Control)
   * - MitM
     - Man-in-the-Middle
   * - MOST
     - Media Oriented Systems Transport
   * - NFC
     - Near Field Communication
   * - NIST
     - National Institute of Standards and Technology
   * - OBD
     - On-Board Diagnostics
   * - OEM
     - Original Equipment Manufacturer
   * - OTA
     - Over-The-Air
   * - PEPS
     - Passive Entry Passive Start
   * - PKI
     - Public Key Infrastructure
   * - RCE
     - Remote Code Execution
   * - RFC
     - Request for Comments
   * - RKE
     - Remote Keyless Entry
   * - SAE
     - Society of Automotive Engineers
   * - SAST
     - Static Application Security Testing
   * - SDK
     - Software Development Kit
   * - SDV
     - Software-Defined Vehicle
   * - SE
     - Secure Element
   * - SSDLC
     - Secure Software Development Lifecycle
   * - STRIDE
     - Spoofing, Tampering, Repudiation, Information Disclosure, Denial of Service, Elevation of Privilege
   * - TARA
     - Threat Analysis and Risk Assessment
   * - TCU
     - Telematics Control Unit
   * - TLS
     - Transport Layer Security
   * - TPM
     - Trusted Platform Module
   * - TSP
     - Trust Service Provider
   * - UICC
     - Universal Integrated Circuit Card
   * - UN R155
     - United Nations Regulation No. 155 (Cybersecurity)
   * - UN R156
     - United Nations Regulation No. 156 (Software Updates)
   * - UWB
     - Ultra-Wideband
   * - UUID
     - Universally Unique Identifier
   * - V2I
     - Vehicle-to-Infrastructure
   * - V2V
     - Vehicle-to-Vehicle
   * - V2X
     - Vehicle-to-Everything
   * - VPN
     - Virtual Private Network

Usage Notes
-----------

- Terms may have slightly different meanings in different contexts; refer to the specific standards and specifications for precise definitions
- Some abbreviations are used differently in other industries; this document focuses on automotive cybersecurity contexts
- New terms and abbreviations are regularly added as the technology evolves
- For ISO/SAE 21434 compliance, use standardized terminology from the official specification
- Security ratings and assessment methods may vary by region and regulatory framework

Related Resources
-----------------

**Standards and Regulations:**

- ``ISO/SAE 21434``: Road vehicles — Cybersecurity engineering
- ``UN R155``: Uniform provisions concerning cyber security and cyber security management system
- ``UN R156``: Uniform provisions concerning software update and software updates management system
- ``SAE J3061``: Cybersecurity Guidebook for Cyber-Physical Vehicle Systems
- ``ISO 26262``: Road vehicles — Functional safety
- ``ISO/IEC 15408``: Common Criteria for Information Technology Security Evaluation

**Technical Specifications:**

- ``AUTOSAR Specifications``: Standardized automotive software architecture
- ``NIST Cybersecurity Framework``: Risk management framework

**Industry Resources:**

- ``OWASP Automotive Security``: Open-source automotive security testing guidance
- ``CVE Database``: Common Vulnerabilities and Exposures
- ``MITRE ATT&CK``: Adversarial tactics and techniques knowledge base
- ``RFC 2119``: Key words for requirement levels in technical specifications
