# The-Voice

## Table of Contents

-   [The-Voice](#the-voice)
    -   [Table of Contents](#table-of-contents)
    -   [Background](#background)
        -   [Demo Video](#demo-video)
        -   [Problem Statement](#problem-statement)
        -   [10. Reduced Inequalities](#10---reduced-inequalities)
    -   [Document](#document)
    -   [Implementation](#implementation)
        -   [Members](#members)
        -   [Responsibility](#responsibility)
        -   [Architecture](#architecture)
        -   [Google Products and Platforms](#google-products-and-platforms)
    -   [Reference](#reference)
    -   [Contacts](#contacts)

## Background

<img src="https://user-images.githubusercontent.com/60650372/230013718-8def5c1c-1ec2-4806-aa74-b2884b9e161b.png" height="100px" width="100px">

**"The Voice", is an AI-based application that uses conversational content to detect scam calls. Our goal is to protect seniors by analyzing call recordings using a deep-learning based model.**

### Demo Video

**Please turn on the caption!**

[![Video Label](https://img.youtube.com/vi/gxOZfgLVO70/0.jpg)](https://youtu.be/gxOZfgLVO70)

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

## [Document](https://abrasive-shift-c8c.notion.site/The-Voice-2ba7dc9ab10a48dfaa9eed7f4a63228b)

## Implementation

### Members

**_GDSC KAIST (Korea Advanced Institute of Science and Engineering)_**

Seungho Jang (hoosong0235@gmail.com) - Frontend

Kyungho Byoun(clearman001@gmail.com) - Team Lead, Backend

Taeil Kim(kti5589@gmail.com) - ML Model construction

Jongeun Park(abepje@gmail.com) - Data processing

### Responsibility

| Component | Stacks | Responsibility |
| --- | --- | --- |
| [Client](https://github.com/KAIST-Google-Solution-Challenge/frontend) | Flutter | User Interface |
| [Server](https://github.com/KAIST-Google-Solution-Challenge/backend) | Node.js, Google Compute Engine, Google Speech-to-Text | Pipeline to connect with services |
| [Model](https://github.com/KAIST-Google-Solution-Challenge/conversation_model) | Google Colab | Classify text input to probability of being fraudulent |
| [Data Preprocessing](https://github.com/KAIST-Google-Solution-Challenge/data_preprocess) | Python, Google Speech-to-Text | Gather voice phishing dataset |
| [Database]() | Firebase | Store Phone Scam Data |

### Architecture

<img src="https://user-images.githubusercontent.com/60650372/230013748-c7162e45-dda5-4b3a-8363-ba072e7c636c.png">

### Google Products and Platforms

<p align="middle">
  <img src="https://user-images.githubusercontent.com/60650372/230013769-e601b476-acb8-47bc-9c4e-4199f72df8f4.png" height="100px" width="100px">
  <img src="https://user-images.githubusercontent.com/60650372/230013809-0b02efe6-60d2-41c2-9c88-032522e7da11.png" height="100px" width="100px"> 
  <img src="https://user-images.githubusercontent.com/60650372/230013785-76542b81-b568-4f1c-82f6-d7e4cf01c221.png" height="100px" width="100px">
  <img src="https://user-images.githubusercontent.com/60650372/230013820-79f27a46-c874-4759-8634-156069be68f2.png" height="100px" width="100px">
  <img src="https://user-images.githubusercontent.com/60650372/230014161-5424f544-6e25-4ad2-8ea9-f2e9203a4782.png" heigµht="100px" width="100px">
</p>

## Reference

1. Milandu Keith Moussavou Boussougou, Sangyoon Jin, Daeho Chang, Dong-Joo Park, 2021, Korean Voice Phishing Text Classification Performance Analysis Using Machine Learning Techniques, ACK 2021
2. Milandu Keith Moussavou Boussougou, Dong-Joo Park, 2022, Exploiting Korean Language Model to Improve Korean Voice Phishing Detection, KIPS Trans. Softw. and Date Eng. Volume 11 Issue 10 / Pages.437-446

## Contacts

Kyungho Byoun : clearman001@gmail.com
