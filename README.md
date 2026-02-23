# Card Transaction Complaint Management System – Process Analysis & UML Modeling

## Business Context
The system manages complaints submitted by bank clients regarding card transactions. Its purpose is to provide fast and accurate processing of complaints, support the customer service team in analyzing potentially unauthorized or erroneous transactions, and minimize fraud risk.
Business Context:

## Scope of Analysis:
* Business process modeling in BPMN
* UML diagrams: Use Case, Class, Sequence
* Functional and non-functional requirements analysis
* Integration with Fraud Detection Engine and Card Processing System

## Primary Roles in the System:
* **Client** – submits complaints
* **Support** – verifies complaints and makes decisions
* **Complaint Management System** – core process automation
* **Fraud Detection Engine** – independent system for risk analysis

## Selected Functional Requirements:
1. Collect complaint data from clients, including transaction ID, date, amount, and reason.
2. Perform automated fraud analysis and flag high-risk transactions.
3. Notify support team and set complaint priority based on risk and workflow rules.
4. Enable cancellation or rejection of transactions based on support decisions.

## Selected Non-Functional Requirements:
* Ensure first response to the client within 24 hours.
* Maintain complete audit logs of all actions and decisions.
*Provide system resilience via asynchronous processing to handle high complaint volumes.

## Key Diagrams to Include:
1. **Use Case Diagram** – shows actors and primary system use cases 
    ![Use Case Diagram](diagrams/use-case.png)
2. **Class Diagram** – illustrates system objects, relationships, and inheritance 
    ![Class Diagram](diagrams/class-diagram.png)
3. **Sequence Diagram** – demonstrates the flow of actions from complaint submission to resolution 
    ![Sequence Diagram](diagrams/sequence-diagram.png)
4. **BPMN Diagram** – full end-to-end process including the “Client Contact” subprocess and asynchronous fraud analysis 
    ![BPMN Diagram](diagrams/bpmn-diagram.png)

