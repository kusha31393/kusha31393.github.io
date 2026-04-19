---
layout: archive
title: "Projects, Activities & Service"
permalink: /projects/
author_profile: true
---

{% include base_path %}

## Major Datasets

### The MSP-Podcast Corpus
*Lead researcher — Multimodal Signal Processing Lab, UT Dallas*

To date the **largest naturalistic speech emotion dataset** in the world. I designed and implemented the entire pipeline — podcast mining, speaker diarization, cleaning, emotion retrieval via DNN frameworks (LSTMs for gender detection, etc.), and crowd-sourced annotation on Amazon Mechanical Turk. I managed the back-end (Microsoft Azure, PHP, SQL) and expert-annotator customer service. The corpus now contains **400+ hours of emotionally rich spontaneous speech** and over **a quarter-million annotated speaking turns**. Eight academic and commercial versions have been released.
[Corpus page →](https://www.lab-msp.com/MSP/MSP-Podcast.html)

### Microsoft Acoustic Echo Cancellation Dataset (ICASSP/Interspeech 2021 Challenge)
*Lead researcher — Microsoft IC3AI Team*

The **first large-scale AEC dataset**, built on an online subjective-test framework I designed around ITU-T P.808. The dataset comprises audio recordings from **2,500 real audio devices** across single-talk, double-talk with and without echo-path changes, and sweep signals for RT60 estimation. Released as the ICASSP 2021 (Toronto) and Interspeech 2021 (Brno) AEC Challenge.
[Challenge page →](https://www.microsoft.com/en-us/research/academic-program/acoustic-echo-cancellation-challenge-icassp-2021/)

## Professional Service

* **Invited reviewer — IEEE Transactions on Affective Computing (TAFFC)** · since 2020
* **Invited reviewer — IEEE/ACM Transactions on Audio, Speech, and Language Processing (TASLP)** · since 2020
* **Invited reviewer — ICASSP** · since 2020
* **Invited reviewer — Interspeech** · since 2020
* **Invited reviewer — IEEE Spoken Language Technology Workshop (SLT)** · since 2020
* **Invited reviewer — ACM Intl. Conf. on Affective Computing and Intelligent Interaction (ACII)** · since 2020

## Mentoring

* **Sony Interactive Entertainment** — Mentored 2 interns in the Future Technology Group, leading to **2 US patents** in expressive voice cloning for AAA games and uncertainty estimation for expressive speech synthesis.
* **Rice University** — Mentored 2 graduate students on ethics and bias in healthcare AI, producing **2 peer-reviewed publications** (ACII 2022; EMBC 2022).
* **The University of Texas at Dallas** — Mentored 2 undergraduates on speaker-ID-aware speech emotion recognition, conversational speech emotion recognition, and continuous emotional-trace annotation for conversational speech.

## Selected Research Directions (PhD)

* **Regularization of valence prediction** — showed that valence externalization in speech is speaker-dependent and needs different regularization than arousal/dominance (Interspeech 2018).
* **Reject-option SER** — first work in speech emotion recognition using Bayesian empirical risk minimization, probabilistic backpropagation, and Monte Carlo dropout to implement selective classification and regression (Interspeech 2019; ICASSP 2020; ACII 2021).
* **Knowledge distillation with latent emotional representations** — teacher/student transfer preserving predictive uncertainty via MC-dropout ensembling (Interspeech 2020).
* **DeepEmoCluster** — semi-supervised latent clustering on 500k+ unlabeled MSP-Podcast segments (ICASSP 2021; IEEE/ACM TASLP 2024).
* **Unsupervised personalization** — adapting SER models to target speakers by finding emotionally-close source speakers (IEEE TAFFC 2022).

## Redundancy-Augmented Regression (USC ISI)

With Prof. Greg Ver Steeg at USC ISI, I worked on **Linear Total Correlation Explanation (CorEx)** and the **Information Sieve** (ICML 2016) as approaches for regression over highly redundant features in high-dimensional spaces. Applied CorEx/Sieve via DNNs to a sparse matrix factorization problem with applications in compressed sensing. Achieved regression MSE < 5% on noisy datasets, opening directions for under-sampled regression where outliers act as training-time adversaries.
