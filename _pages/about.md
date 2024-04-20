---
layout: about
title: Home
permalink: /
subtitle: Short-duration speaker verification in two different configurations

profile:
  align: right
  image: tdsvc_poster.jpg
  image_circular: false # crops the image to make it circular
  more_info: >

news: false # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page
---

Following the success of two previous [Short-duration Speaker Verification Challenges](https://sdsvc.github.io/), this challenge aims to focus researchers' attention on the relevance of recent training strategies, such as self-supervised learning, in the context of text-dependent speaker verification (TdSV). The challenge evaluates the TdSV task in the following two practical scenarios:

**Task 1: Conventional TdSV Using Predefined Passphrases**

Participants are tasked with training a speaker encoder model using a significantly large training dataset sourced from a predefined phrase pool consisting of 10 phrases. Speaker models are created using three repetitions of a specific passphrase from the phrase pool. Speakers are then verified using an utterance containing the passphrase.

**Task 2: TdSV Using User-defined Passphrases**

Participants are required to train a speaker encoder model using a large text-independent training dataset. Additionally, there are utterances from a predefined pool of 6 phrases for each in-domain training speaker. Speaker models are created using three repetitions of a user-defined passphrase (not included in the phrase pool), along with some free-text utterances. Speakers are verified using an utterance containing the user-defined passphrase.

---

#### Challenge Prizes
	
There will be three cash prizes for each task. Winners will be selected based on the results of the evaluation dataset and other qualitative factors. In addition to the cash prize, each winner will receive a certificate for their achievement. The cash prizes for each task are as follows:

- Rank 1: **2000** USD
- Rank 2: **1000** USD
- Rank 3: **500** USD

---

#### Challenge Dataset

The evaluation dataset of the challenge is drawn from the new versions of the multi-purpose DeepMine dataset[1]. The dataset has three parts and among them, Parts 1 and 3 are used in this challenge.

[1] H. Zeinali, L. Burget, J. Cernocky, "A multi-purpose and large scale speech corpus in Persian and English for speaker and speech recognition:  the DeepMine database", in:  Proc. ASRU 2019 The 2019 IEEE Automatic Speech Recognition and Understanding Workshop, 2019.

---

#### Challenge Evaluation Plan

The full challenge evaluation plan version 1.0 can be found at [this link](https://tdsvc.github.io/assets/pdf/TdSV_Challenge_2024_Evaluation_Plan.pdf) and the high-quality challenge poster is available through [this link](https://tdsvc.github.io/assets/img/tdsvc_poster.jpg). If you have any more questions regarding the challenge you can contact organizers via [tdsvc.2024\[at\]gmail.com](mailto:tdsvc.2024\[at\]gmail.com).

---

#### Planned Evaluation Schedule

<table border="0">
 <tr>
    <td>
    Apr 10, 2024
    </td>
    <td>
    Release of Evaluation Plan
    </td>
 </tr>
 <tr>
    <td>
    Apr 10, 2024
    </td>
    <td>
    Release of Train, Dev, and Eval Sets
    </td>
 </tr>
 <tr>
    <td>
    Apr 20, 2024
    </td>
    <td>
    Evaluation Platform Open
    </td>
 </tr>
 <tr>
    <td>
    Jun 10, 2024
    </td>
    <td>
    Challenge Deadline
    </td>
 </tr>
 <tr>
    <td>
    Jun 17, 2024
    </td>
    <td>
    System Description Deadline
    </td>
 </tr>
 <tr>
    <td>
    Jun 20, 2024
    </td>
    <td>
    SLT Paper Submission Deadline
    </td>
 </tr>
 <tr>
    <td>
    Dec 02, 2024 &nbsp;&nbsp;&nbsp;&nbsp;
    </td>
    <td>
    TdSV Challenge 2024 Special Session at SLT
    </td>
 </tr>
 <tr><td> &nbsp; </td></tr>
</table>


---

### Sponsors

<table border="0" width="95%">
 <tr>
    <td>
	<a href="https://aut.ac.ir/en/">Amirkabir University of Technology (Tehran Polytechnic) </a> &nbsp;&nbsp;&nbsp;&nbsp;
    </td>
    <td>
	<a href="https://aut.ac.ir/en/"><img align="right" width="125" height="auto" src="https://tdsvc.github.io/assets/img/aut_logo.png"></a>
    </td>
 </tr>
 <tr>
    <td>
	<a href="https://deepmine.ir/">Sharif DeepMine Ltd.</a>
    </td>
    <td>
	<a href="https://deepmine.ir/"><img align="right" width="120" height="auto" src="https://tdsvc.github.io/assets/img/deepmine.png"></a>
    </td>
 </tr>
</table>
