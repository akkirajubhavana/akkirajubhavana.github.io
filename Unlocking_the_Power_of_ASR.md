---
layout: post
title: "Transcribing Talk: Exploring the World of Automatic Speech Recognition"
subtitle: A Beginner’s Guide to Automatic Speech Recognition!
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [asr]
comments: true
mathjax: true
author: Bhavana Akkiraju
---
![](/assets/img/1.gif)


When I embarked on my journey to learn **Automatic Speech Recognition** (ASR) from scratch, I found myself lost in a sea of resources, unsure of where to begin and what topics to cover in order to truly excel in this field. Determined to make sense of it all, I decided to compile all the information I gathered, hoping that it would serve as a guiding light for fellow beginners like myself, helping them navigate the complex world of ASR terminology and essential subjects.

Coming to the main discussion!

Now, let's dive headfirst into our main topic: **A***utomatic* **S***peech* **R***ecognition* (**ASR**). In its simplest form, *ASR is the remarkable process of transforming spoken words into written text.* Through the power of ASR technology, spoken language can be effortlessly transcribed into written form.

But before we delve deeper into the intricacies of ASR, let’s take a moment to understand the fundamental aspects that come to mind when we think of speech recognition. First and foremost, we must grasp the concept of speech itself.

Speech, in its essence, is the audible expression of our thoughts and emotions, a meaningful sound produced by us humans.

> But what lies beneath the surface?
>
> How is speech generated?
>
> Which organs are responsible for this miraculous act?
>
> And can we even fathom the mathematical analogies behind this phenomenon

These are the questions we will explore and comprehend.

# **Generation of Speech :**

How is sound produced in a human body? In our body, the lungs, vocal tract, vocal folds, and glottis are responsible for producing the sound.

In more straightforward terms, speech production refers to the process of using our vocal apparatus to create sounds for communication. This process involves several steps.

* First, air is expelled from the lungs, initiating speech.
* Then, in the larynx, the vocal folds can vibrate to produce voiced sounds or remain open for voiceless sounds.
* The air then travels through either the oral or nasal cavity, depending on the position of the velum or soft palate.
* Finally, in the mouth, we use our articulators, such as the lips, tongue, and teeth, to shape the airflow and create different speech sounds.
* In essence, speech production is how we generate and shape sounds to effectively communicate with others.

![](/assets/img/2.png)

Imagine you are a singer getting ready to perform on stage. You take a deep breath, filling your lungs with air, like a pump getting ready to release energy. As you start singing, your vocal cords vibrate and create a beautiful melody, much like the strings of a musical instrument. Simultaneously, your vocal tract shapes and refines the sound, allowing you to project your voice with clarity and precision. Through the coordinated efforts of the lungs, vocal cords, and vocal tract, you bring your speech or singing to life, captivating your audience with the power of your voice.

* Lungs - provide the air supply necessary for speech production.
* Vocal cords - produce phonation, the generation of sounds.
* Vocal tract - Shape and refine the produced sounds.

# **Mathematical Analogy of the Speech Production System**

Picture two different worlds of understanding. In the computer realm, when you start a program, you deal with three key elements: the stuff you put in (input), the powerful brain that does the work (processing unit), and the result you get out (output). Now, in the world of electronics, there’s this captivating idea of systems. They’re like magic makers. They can ask you for information (input), blend it into their world, and create something amazing as if they were wizards with a wand (output).

![](/assets/img/3.png)


Let’s draw a parallel between our way of speaking and the system mentioned. Imagine our voice as a symphony: the initial push from our lungs serves as the opening note—that's our input. The vocal tract, like a dynamic musical instrument, modulates and shapes the sounds over time, just like the system. And finally, the speech or sound that emerges is our grand musical performance, the output.

  ![](/assets/img/4.png)
  

* Vocal Tract: It’s like a shape-shifter during speech, not staying the same.
* Excitation Source: Divided into “voiced,” which is like a rhythmic beat, and “unvoiced,” resembling noisy chaos.
* Output: Speech is a bit like music, with some repeating patterns but not always the same tune.

In the world of signals and systems, the output is the product of the input signal and the system’s influence, represented as y(t) = H[x(t)].

![](/assets/img/5.png)

**y(t) = H[x(t)]**

Similarly,

> *Speech signal is the convolved output of the Excitation source and the vocal tract system*

*Of course! Think of it as if we’ve built a roadmap, where each answer is a signpost guiding us to a clearer understanding of those initial questions.*
