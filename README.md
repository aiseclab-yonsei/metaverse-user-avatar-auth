# Continuous Authentication for Secure and Seamless User-Avatar Integration in Multi-Device Metaverses

**📄 Accepted to IEEE Internet of Things Journal (2025)**  
**👩‍💻 Authors: Eunbi Hwang, Yoonsik Kim, Taekyoung Kwon**

This repository contains the official implementation and documentation of our research on continuous authentication in multi-device metaverse environments.  
We propose a framework that ensures **secure and seamless integration between users and their avatars**, even as users switch between devices such as smartphones and HMDs.

## 📝 Abstract

The metaverse connects the virtual and real worlds, enabling users to interact as avatars across multiple devices, including smartphones, HMDs, and other devices. While multi-device access enhances convenience, it also expands attack surfaces, increasing security risks. Continuous authentication is crucial, but traditional methods like fuzzy extractors struggle with dynamic data, making reliable identification difficult. Moreover, conventional authentication focuses on user-side verification, failing to detect avatar manipulation attacks like avatar hijacking.
This paper proposes a continuous authentication system that integrates user and avatar behavior data in multi-device environments. A transformer-based embedding model processes data on edge devices and securely transmits it via JSON Web Tokens (JWT). The authentication model binds user and avatar data in real-time to compute confidence scores and detect avatar manipulation. We implemented a VRSpace-based metaverse on NGINX and conducted simulations using open datasets—HMOG, Liebers, and BOXRR—to evaluate authentication accuracy and continuity. The `Smartphone+HMD_{6DOF}+Avt_{act}+Window_{(20)}` model achieved an average FAR of 0.0034%, an EER of 0.3386%, and an ADR of up to 97.67% for avatar manipulation detection.
Based on our work, industry-driven research is expected to explore real-world applications, further validating our approach in evolving multi-device metaverse ecosystems.
