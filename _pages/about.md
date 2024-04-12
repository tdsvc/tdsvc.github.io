---
layout: about
title: Home
permalink: /
subtitle: Short-duration speaker verification in two different configurations

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >

news: false # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page
---

Following the success of two previous [Short-duration Speaker Verification Challenges](https://sdsvc.github.io/), this challenge aims to focus researchers' attention on the relevance of recent training strategies, such as self-supervised learning, in the context of text-dependent speaker verification (TdSV). The challenge evaluates the TdSV task in the following two practical scenarios:

**Track 1:** Conventional TdSV Using Predefined Passphrases
Participants are tasked with training a speaker encoder model using a significantly large training dataset sourced from a predefined phrase pool consisting of 10 phrases. Speaker models are created using three repetitions of a specific passphrase from the phrase pool. Speakers are then verified using an utterance containing the passphrase.

**Track 2:** TdSV Using User-defined Passphrases
Participants are required to train a speaker encoder model using a large text-independent training dataset in addition to the training data sourced from a predefined phrase pool consisting of 6 phrases. Speaker models are created using three repetitions of a user-defined passphrase (not included in the phrase pool), along with some free-text utterances. Speakers are verified using an utterance containing the user-defined passphrase.
