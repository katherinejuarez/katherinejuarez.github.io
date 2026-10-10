---
layout: archive
title: "Research Projects"
permalink: /research/
author_profile: true
---

# Selected Research Projects

## Generative AI for Operationalizing Health Goals to Support Planning, Tracking, Reflecting, and Acting around Personal Health Data

We studied how generative AI (GAI) could support people across every stage of self-tracking for health, from deciding what to track to acting on what they learn. In sessions with 19 self-trackers, participants used ChatGPT or Copilot to ask questions about their own health data. We found that GAI showed promise for turning vague health goals into concrete tracking plans, but often gave generic responses that didn't make good use of the data participants shared.

**My role:** As second author, I helped conduct the study sessions, co-coded all 19 sessions and developed the codebook and themes with the first author, and contributed to writing the paper.

- [Engagements with Generative AI and Personal Health Informatics](https://dl.acm.org/doi/10.1145/3749503), IMWUT 2025


## Agency, Preference, and Cultural Influence of U.S.-Designed Technologies Among Latin American Users

Much of the technology used around the world is designed in the U.S. and carries values that not every user shares. Through 27 interviews conducted in Spanish with people in Costa Rica, El Salvador, México, and Panamá, we examined how Latin Americans experience U.S.-designed technologies and how these compare to local alternatives. Participants didn't see themselves as passive recipients of foreign values. They actively adapted technology to fit their own values and contexts, and preferred U.S.-designed tools for their reliability and usability.

**My role:** I led this project from start to finish. I shaped the research questions, drawing on decolonial computing and value sensitive design, and designed the interview protocol. I recruited participants across Central America and México, building trust with them through WhatsApp before each interview, and conducted the interviews in Spanish. I led the development of the codebook, coding of the interviews, and thematic analysis. I also translated participant quotes from Spanish to English. Throughout the project, I mentored undergraduate researcher [Elizabeth Castillo](https://www.linkedin.com/in/elizabeth-castillov/). I taught her how to conduct semi-structured interviews and carry out qualitative analysis, and she grew into a contributor across data collection and analysis.

## Designing to Record and Share Experiences of Menopause Across Generations

Menopause is often overlooked or treated as purely medical, and stigma, family dynamics, and loss mean many people go through it without learning from those who came before them. We conducted interviews and design sessions with 17 people who had experienced or were experiencing menopause, using design sketches to explore how they might record and pass down their experiences to future generations. Participants were especially drawn to personal storytelling and life-logging, which let them capture menopause as one part of their lives rather than a purely medical experience.

**My role:** As third author, I helped design the study protocol, conducted study sessions, and analyzed the data, including conducting and analyzing all sessions held in Spanish. I also contributed to writing the paper.

- [Menopause Legacies: Designing to Record and Share Experiences of Menopause Across Generations](https://doi.org/10.1145/3686975), CSCW 2024

## Identifying Process Behavior with Dynamic Analysis

Knowing how a running program behaves, such as whether it's reading files, doing heavy computation, or managing other processes, can help system administrators allocate resources and enforce policies. Analyzing a program's code before it runs shows what it could do, but not what it actually does. We developed a dynamic analysis approach that records the machine instructions a process executes and condenses them into compact instruction profiles for machine learning. In my honors thesis, I used these profiles to classify pairs of similar Linux utilities. Removing library instructions, grouping instructions into functional categories, and using short instruction sequences shrank the data while keeping classification accuracy between 98% and 100%. In follow-up work, we showed that clustering these profiles grouped utilities by their behavior, something static analysis couldn't do.

**My role:** I led this work as my undergraduate honors thesis, advised by Professor Errin W. Fulp. I extended an existing instruction-tracing tool and built a Python pipeline that generates instruction profiles from millions of executed instructions, reduces their dimensionality through instruction mapping and k-length sequence features, and classifies processes using support vector machines evaluated with 10-fold cross-validation. As second author on the follow-up paper presented at ISNCC 2020, I built the pipeline for its methodology, generating the execution profiles and evaluating how well Gaussian mixture model clustering matched the true behavior groups using silhouette scores and the Adjusted Rand Index.

- [Using Execution Profiles to Identify Process Behavior Classes](https://ieeexplore.ieee.org/document/9297303), ISNCC 2020
- Process Prediction Using Dynamic Analysis with Instruction Sequences, Honors Thesis, Wake Forest University, 2019