# The-Voice

## Table of Contents

- [The-Voice](#the-voice)
  - [Table of Contents](#table-of-contents)
  - [Background](#background)
    - [Demo Video](#demo-video)
    - [Problem Statement](#problem-statement)
    - [10. Reduced Inequalities](#10-reduced-inequalities)
  - [User Guide](#user-guide)
  - [Implementation](#implementation)
    - [Members](#members)
    - [Responsibility](#responsibility)
    - [Design](#design)
    - [Architecture](#architecture)
    - [Google Products and Platforms](#google-products-and-platforms)
  - [Reference](#reference)
  - [Contacts](#contacts)

## Background

![Thumbnail 2](https://github.com/KAIST-Google-Solution-Challenge/.github/assets/78964767/4aa36b8d-f0ab-42f0-96e7-aeac8c923701)

**"The Voice", is an AI-based application that uses conversational content to detect scam calls. Our goal is to protect seniors by analyzing call recordings using a deep-learning based model.**

### Demo Video

**Please turn on the caption!**

[![Video Label](https://img.youtube.com/vi/fXQEwMKBVvE/0.jpg)](https://youtu.be/fXQEwMKBVvE)

### Problem Statement

In Korea, there is a growing problem of phone scams that are specifically targeting elderly individuals who may not be knowledgeable about modern technology or fraudulent activities. The scams are becoming increasingly sophisticated, making it more challenging to identify them. Since seniors are less likely to recover financially and account for 56.8 percent of victims, these scams are more lethal than all other crimes to the elderly.

According to the Financial Supervisory Service, 56.8 percent of phone scams targeted individuals aged 60 and over in 2022. The primary reason for this discrimination is the disparity in information between seniors and younger people, caused by the elderly's lack of proficiency in using electronic devices and their reduced ability to efficiently process and respond to information.

Bridging this knowledge gap is especially an urgent issue for Korea. BBC has reported that people aged 60 and over will make up 20% of Korea’s population in 2025. As the population structure continues to shift rapidly, it’s crucial to prevent crimes that hinder the inclusion of seniors in the economy as well as society in advance.

Unfortunately, despite the majority of victims lacking the necessary information to respond to such crimes, the elderly are neglected and excluded from economics and society in indifference. Therefore, we firmly believe that a direct information mediator is essential to promote empowerment in their financial situation.

### 10. Reduced Inequalities

<img src="https://user-images.githubusercontent.com/60650372/230013727-0c381cb7-9cb0-4e2a-b700-fed6ae809ab1.png" height="100px" width="100px">

Our goal is to eliminate phone scams against elderly, in order to reduce information inequalities (SDG 10 - Reduced Inequalities) and promote seniors’ financial empowerment (Target 10.2).

One of our team members shared a personal experience of their grandmother falling victim to a scam call two years ago. The scammer pretended to be a prosecutor and required her to send money to a certain account. After that, she is so suspicious that she never uses internet banking again. Likewise, the increased vulnerability limits seniors from actively being involved in financial matters.

Unfortunately, there is no effective solution available to deal with this problem. The existing phishing prevention applications rely on pre-existing databases, which makes it difficult to detect new and diverse types of scams in advance. Furthermore, the follow-up measures are often too complex for elderly.

Our proposed solution, "The Voice", is an AI-based application that uses conversational content to detect scam calls. Our goal is to protect seniors by analyzing call recordings using a deep-learning based model. “The Voice” can detect a wide variety of phone scams and provide easy-to-understand alerts for elderly people.

Consequently, we expect “The Voice” can encourage seniors to become more involved in financial matters and promote their financial empowerment by reducing inequalities in information between seniors and others.

## [User Guide](https://github.com/KAIST-Google-Solution-Challenge/frontend/files/11524803/tutorial.pdf)

## Implementation

### Members

**_GDSC KAIST (Korea Advanced Institute of Science and Engineering)_**

Seungho Jang (hoosong0235@gmail.com) - Design & Frontend

Kyungho Byoun(clearman001@gmail.com) - Team Lead & Backend

Taeil Kim(kti5589@gmail.com) - Artificial Intelligence

Jongeun Park(abepje@gmail.com) - Data Preprocessing

### Responsibility

| Component | Stacks | Responsibility |
| --- | --- | --- |
| [Client](https://github.com/KAIST-Google-Solution-Challenge/frontend) | Android, Flutter | User Interface |
| [Server](https://github.com/KAIST-Google-Solution-Challenge/backend) | Node.js, Google Compute Engine, Google Speech-to-Text | Pipeline to connect with services |
| [Model](https://github.com/KAIST-Google-Solution-Challenge/conversation_model) | Google Colab | Classify text input to probability of being fraudulent |
| [Data Preprocessing](https://github.com/KAIST-Google-Solution-Challenge/data_preprocess) | Python, Google Speech-to-Text | Gather voice phishing dataset |
| [Database]() | Firebase | Store Phone Scam Data |

### Design

![The Voice 1 1 0](https://github.com/KAIST-Google-Solution-Challenge/.github/assets/78964767/40ebbc43-c747-42b8-bd4f-d4949d79a9d8)

### Architecture

![Architecture](https://github.com/KAIST-Google-Solution-Challenge/.github/assets/78964767/bc83eb2c-553d-4e70-ae5c-18d988f41fcb)

### Google Products and Platforms

<p align="middle">
  <img src="https://github.com/KAIST-Google-Solution-Challenge/.github/assets/78964767/86459451-4e70-4af1-8c75-4bf439c6ba0c" height="100px" width="100px">
  <img src="https://github.com/KAIST-Google-Solution-Challenge/.github/assets/78964767/4308fa44-ee8a-4056-9b1c-9660f5e88f08" height="100px" width="100px">
  <img src="https://github.com/KAIST-Google-Solution-Challenge/.github/assets/78964767/cba1bdce-7cc3-40c0-860d-7c83c49ab436" height="100px" width="100px">
  <img src="https://github.com/KAIST-Google-Solution-Challenge/.github/assets/78964767/3f4038fb-ae5e-4772-816c-11333395cdc7" height="100px" width="100px">
  <img src="https://github.com/KAIST-Google-Solution-Challenge/.github/assets/78964767/46b9e3cb-c0d8-4c01-b7a0-f676930360f0" height="100px" width="160px">
  <img src="https://github.com/KAIST-Google-Solution-Challenge/.github/assets/78964767/b7412070-e6b2-43b1-95b9-0b988c4c0d2c" height="100px" width="100px">
</p>

## Reference

1. Milandu Keith Moussavou Boussougou, Sangyoon Jin, Daeho Chang, Dong-Joo Park, 2021, Korean Voice Phishing Text Classification Performance Analysis Using Machine Learning Techniques, ACK 2021
2. Milandu Keith Moussavou Boussougou, Dong-Joo Park, 2022, Exploiting Korean Language Model to Improve Korean Voice Phishing Detection, KIPS Trans. Softw. and Date Eng. Volume 11 Issue 10 / Pages.437-446

## Contacts

Kyungho Byoun : clearman001@gmail.com
