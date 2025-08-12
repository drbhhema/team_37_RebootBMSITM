# team_37_RebootBMSITM
Blockchain Examination Security System
The proposed Blockchain-Enabled Examination Security System (BEESS) aims to digitize and secure the examination system from answer script submission, to evaluation and result publication. It leverages blockchain's core properties—immutability, decentralization, and transparency—to address issues such as tampering and unauthorized access, all while being scalable and user-friendly for universities.
Objectives:
1.	To digitize the answer paper submission and evaluation process.
2.	To ensure transparency, security and traceability using blockchain.
3.	To eliminate tampering, loss or manipulation of marks and scripts.
4.	To facilitate real-time updates and notifications to stakeholders.

Architecture Diagram
1.	Collection and Segregation of Answer Scripts
o	Physical bundles of answer scripts are collected from examination halls.
o	Scripts are sorted branch-wise, scheme-wise and course-wise to streamline processing.
2.	Masking and Coding
o	The USN (University Seat Number) is masked to ensure anonymity.
o	A unique blockchain-based code is assigned to each script for secure tracking.
3.	Scanning
o	Answer scripts are scanned at high resolution.
o	Digital copies are generated in a standardized format (PDF).
4.	Blockchain-Based Storage
o	Digital answer scripts are encrypted (AES-256).
o	Encrypted files are uploaded to blockchain-integrated decentralized storage (e.g., IPFS).
o	The hash of each script is stored on the blockchain ledger for tamper-proof verification.
5.	Evaluator Allocation
o	Smart contracts automatically allocate scripts to evaluators based on subject expertise and workload balancing.
6.	Secure Evaluation & Moderation
o	Evaluators access scripts via a secure, role-based portal.
o	Marks are submitted directly through the system.
o	Moderation workflows ensure consistency and fairness.
7.	Tabulation of Marks
o	The system automatically aggregates marks from all evaluators.
o	Discrepancies flagged by smart contracts are routed for re-check.
8.	Result Generation & Publication
o	Final results are auto-generated after tabulation.
o	Results are published securely through the blockchain ledger, ensuring authenticity.
9.	Immutable Audit Logging
o	Every evaluation activity (script view, mark entry, moderation) is recorded as a blockchain transaction.
o	The audit trail is immutable and verifiable at any point.
10.	Authority Verification
o	COE (Controller of Examinations) and authorized officials can instantly verify the complete evaluation history through blockchain queries.

Team Members: 
1. Dr. HanumanthaRaju M C
2. Dr. Prakash G L
3. Dr. Archana K
4. Dr. Jojy Joseph Idicula

Team Leader: Dr. HemaMalini B H

