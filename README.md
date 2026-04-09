ImageVault: A Decentralized Blockchain-based Image Management Platform

Paper ID: ICAIS-80  
Presenter: Karan Kumar Das

OVERVIEW:

Traditional cloud storage systems rely on centralized servers, creating privacy risks, data breaches, and reduced user control. Users struggle to maintain ownership, transparency, and fine-grained access control over sensitive images and digital assets.
ImageVault addresses these limitations using decentralized blockchain infrastructure combined with IPFS distributed storage. The platform enables encrypted image storage, immutable access tracking, and secure owner-controlled permission management.

GOAL: Deliver a scalable, privacy-preserving image storage solution ensuring transparency, security, and complete user data ownership.

EXISTING APPROACHES & LIMITATIONS:

| Approach | Limitations |

| Google Drive, Dropbox, AWS | Centralized → privacy risks, third-party control, limited transparency |
| Traditional encryption | Keys managed by service providers → reduced user ownership |
| IPFS alone | No native access control or identity verification |
| Blockchain-only storage | Storing large files on-chain is economically inefficient |
| Hybrid blockchain–IPFS | Complex key management and usability challenges |



PROPOSED METHODOLOGY:

- Client-side encryption – Images are encrypted before leaving the user device, never stored in plain form.
- IPFS storage – Decentralized, content-addressed storage with integrity verification.
- Ethereum smart contracts – Manage ownership, access requests, approvals, and immutable audit logging.
- Public-key cryptography – Decryption keys delivered only to authorized requesters.
- Modular architecture – Angular frontend + Web3 wallet + Node.js encryption services + decentralized storage.

PERFORMANCE RESULTS:

| Metric | Result |

| Smart contract execution | < 3 seconds |
| IPFS retrieval | < 2 seconds |
| On-chain storage overhead | Minimal |

COMPARISON WITH EXISTING METHODS:

- Centralized storage → lacks transparency and user-controlled privacy.
- Blockchain-only storage → secure but inefficient and costly.
- ImageVault → balances security, scalability, and transparency.

CONCLUSION:

 ImageVault integrates blockchain, IPFS, and client-side encryption to enable secure, decentralized, and privacy-preserving image storage. Achieved smart contract execution under 3 seconds, IPFS retrieval under 2 seconds, and minimal on-chain storage overhead. The platform ensures transparent access control, immutable auditability, and user-owned data management. Demonstrates practical feasibility for real-world privacy-sensitive applications.

FUTURE WORK:

- Deploy on public blockchain networks and evaluate performance under real-world network conditions and larger user workloads.
- Develop mobile applications and improve user experience for non-technical users.

REFERENCES:

1. Doan, T. V., Psaras, Y., Ott, J., & Bajpai, V. (2022). Toward decentralized cloud storage with IPFS: Opportunities, challenges, and future considerations. *IEEE Internet Computing*, 26(6), 7–15. https://doi.org/10.1109/mic.2022.3209804

2. Cong, X., Feng, L., & Zi, L. (2024). Research on IPFS image copyright protection method based on Blockchain. *Computers, Materials & Continua*, 81(1), 663–684. https://doi.org/10.32604/cmc.2024.054372

3. Jabarulla, M. Y., & Lee, H.-N. (2020). Blockchain-based distributed patient-centric Image Management System. *Applied Sciences*, 11(1), 196. https://doi.org/10.3390/app11010196

4. Singh, M. K., Pippal, S. K., & Sharma, V. (2025). A Blockchain-IPFS Framework for Secure, Scalable, and Interoperable Healthcare Data Management. *SN Computer Science*, 6(5). https://doi.org/10.1007/s42979-025-03936-z

5. Patil, N. P. (2025). Secure file sharing using blockchain and IPFS with smart contract-based access control. *Journal of Information Systems Engineering and Management*, 10(16s), 184–194. https://doi.org/10.52783/jisem.v10i16s.2588

6. Li, Z., Joseph, K. L., Yu, J., & Gasevic, D. (2022). Blockchain-based solutions for education credentialing system: Comparison and implications for future development. *2022 IEEE International Conference on Blockchain*, 79–86. https://doi.org/10.1109/blockchain55522.2022.00021

7. Armbrust, M., et al. (2010). A view of cloud computing. *Communications of the ACM*, 53(4), 50–58. https://doi.org/10.1145/1721654.1721672

8. Mell, P. M., & Grance, T. (2011). The NIST Definition of Cloud Computing. https://doi.org/10.6028/nist.sp.800-145

9. Zyskind, G., Nathan, O., & Pentland, A. (2015). Decentralizing privacy: Using blockchain to protect personal data. *2015 IEEE Security and Privacy Workshops*, 180–184. https://doi.org/10.1109/spw.2015.27

10. Shafagh, H., Burkhalter, L., Hithnawi, A., & Duquennoy, S. (2017). Towards blockchain-based auditable storage and sharing of IoT Data. *Proceedings of the 2017 on Cloud Computing Security Workshop*, 45–50. https://doi.org/10.1145/3140649.3140656

## Presented at ICAIS-2025


