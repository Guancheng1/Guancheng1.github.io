---
title: "Mutual TLS in Practice: A Deep Dive into Certificate Configurations and Privacy Issues"
collection: publications
category: manuscripts
permalink: /publication/Mutual_TLS
excerpt: 'Our research investigates the security of mutual Transport Layer Security (mTLS) certificates using over 1.2 billion TLS connection logs collected from a large campus network over 23 months. While previous studies have primarily focused on server certificates, our work explores the lesser-studied area of analyzing both client and server certificates in mTLS connections. Through the joint analysis of connection data and certificate properties, we uncovered critical security concerns arising from the use of untrusted or misconfigured certificates, as well as from certificates being shared between servers and clients. Furthermore, we present the first in-depth study on the wide range of information included in CommonName (CN) and Subject Alternative Name (SAN) fields, revealing potential sensitive information leakage.'
date: 2024-11-04 
venue: "ACM Internet Measurement Conference, 2024 (IMC ’24)"
slidesurl: 'https://github.com/mutual-tls-study/mutual-tls-study-code'
paperurl: 'https://dl.acm.org/doi/10.1145/3646547.3688415'
citation: "Hongying Dong, Yizhe Zhang, Hyeonmin Lee, Kevin Du, Guancheng Tu, and Yixin Sun. Mutual TLS in Practice: A Deep Dive into Certificate Configurations and Privacy Issues. In Proceedings of the ACM Internet Measurement Conference, 2024 (IMC ’24)."
---
