---
title: "Mutual TLS in Practice: A Deep Dive into Certificate Configurations and Privacy Issues"
#collection: publications
#category: conferences
permalink: /publication/Mutual_TLS
excerpt: 'In this research, we investigated the prevalence and characteristics of mutual TLS connections, including the associated services and patterns of certificate usage. Specifically, by analyzing TLS connection logs collected from a large campus network over 23 months, we identified over 2.2 million unique server certificates and over 3.4 million unique client certificates used in over 1.2 billion mutual TLS connections. Using this data, we examined security concerns, non-standard behaviors in certificate sharing, and the privacy implications of sensitive information found in mutual TLS certificates.'
#date: 2024-11-04 
venue: "ACM Internet Measurement Conference, 2024 (IMC ’24)"
slidesurl: 'https://github.com/mutual-tls-study/mutual-tls-study-code'
paperurl: 'https://dl.acm.org/doi/10.1145/3646547.3688415'
citation: "Hongying Dong, Yizhe Zhang, Hyeonmin Lee, Kevin Du, Guancheng Tu, and Yixin Sun. Mutual TLS in Practice: A Deep Dive into Certificate Configurations and Privacy Issues. In Proceedings of the ACM Internet Measurement Conference, 2024 (IMC ’24)."
---
My primary contribution to this research was in addressing the challenge of TLS interception, a significant factor that biases certificate analysis. TLS interception occurs when encrypted traffic is decrypted and re-encrypted by an intermediary, resulting in altered certificate issuers. I developed python codebase to identify and exclude such interception certificates from our dataset. By filtering out certificates whose issuer was absent from major trust stores, cross-referencing these with Certificate Transparency logs, and manually investigating discrepancies, we eliminated 871,993 certificates (8.4%) from the dataset. This process ensured that our analysis was not skewed by artificially altered certificates. This contribution was vital in improving the accuracy of our results and ensuring that our security findings reflect real-world scenarios.

