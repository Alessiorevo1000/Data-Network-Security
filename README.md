The goal of this course was to propose an invection based on the latest cutting-edge technology in the networking field.
My proposal has been an Analyzer based on AI 
[Click here to check out the paper](https://github.com/Alessiorevo1000/Data-Network-Security/blob/main/Data_and_Network_Security_report.pdf)


# Data and Network Security Project

## Project Overview

This project focuses on the development of a **Network Analyzer** tailored for **Named Data Networking (NDN)**, an innovative paradigm in network architecture under the concept of **Information-Centric Networking (ICN)**. The proposed solution enhances the security of NDN by introducing proactive monitoring and control mechanisms at the network's border routers.

The analyzer integrates two main approaches:  

1. **Signature-Based Detection**: Blocks malicious requests by matching them against a local database of prohibited patterns.  
2. **AI-Enhanced Reputation Assessment**: Evaluates and adapts consumer behavior to detect and mitigate anomalous activity.  

## Objectives

- **Enhance NDN Security**:  
  Protect the network by addressing privacy and security challenges inherent in NDN.  
- **Real-Time Monitoring**:  
  Deploy a hybrid detection mechanism for immediate intervention against threats.  
- **Consumer Reputation Management**:  
  Introduce a dynamic reputation system to track and manage consumer behavior.

## Features

1. **Signature-Based Detection**:  
   - Utilizes a local database to block requests with blacklisted patterns.  
   - Efficient for known threats with minimal computational overhead.  

2. **AI-Based Reputation Analysis**:  
   - Adapts dynamically to consumer behavior using machine learning.  
   - Maintains and adjusts a **Reputation Score** for each consumer.  

3. **Reputation-Driven Actions**:  
   - High reputation: Normal network operations.  
   - Low reputation: Block malicious consumers.  
   - Medium reputation: Flag suspicious activity for manual review by a Security Operations Center (SOC).  

4. **Data and Trust Management**:  
   - Tracks consumer activity, interfaces, and request patterns.  
   - Dynamically updates reputation based on activity trends.  

5. **Operational Flow**:  
   - Incoming requests pass through signature-based filtering.  
   - Remaining requests are evaluated by the AI model for abnormal patterns.  
   - Reputation scores determine subsequent actions.

## Simulation Results

- **Two Phases**:  
  1. **Learning Phase**: Builds initial models for consumers, reducing false positives.  
  2. **Adaptive Security Phase**: Dynamically adjusts reputation and flags abnormal requests.  

- **Key Observations**:  
  - **Consumer A** demonstrated normal behavior, maintaining a high reputation.  
  - **Consumer B** exhibited suspicious activity, triggering alerts and eventual blocking.  

## Advantages and Challenges

### Advantages:
- Adaptive learning through AI.  
- Decentralized decision-making at border routers.  
- Improved timeliness in threat mitigation.  

### Challenges:
- Higher hardware requirements for AI-based processing.  
- Vulnerability to content naming forgery.  
- Need for compliance with data privacy regulations.

## Conclusion and Future Work

This project demonstrates a robust approach to securing NDN networks by combining traditional and AI-powered techniques. Future enhancements include improving AI accuracy, optimizing hardware costs, and expanding the system's scalability for broader applications.

## References

The implementation is grounded in recent advancements in ICN and AI-powered Intrusion Prevention Systems (IPS), with references from notable works in the field. For details, see the references section in the full report.
