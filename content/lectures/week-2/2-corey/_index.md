+++
title = "Spectral Balance and Equalization"
outputs = ["Reveal"]
[reveal_hugo]
theme = "moon"
margin = 0.2
separator = "##"
+++

## Spectral Balance

> **Spectral balance** - an audio signal’s frequency content and the relative power of each frequency or frequency band across the audible range of frequencies, from 20 to 20,000 Hz.

{{% note %}}

**Show white noise vs pink noise in Reaper with ReaEQ.**

- Spectral balance refers to the distribution of power across different frequencies in an audio signal, crucial for sound quality in recording and production.
- Equalizers are the primary tools used by engineers to adjust spectral balance, allowing for the enhancement or suppression of specific frequencies.
- The spectral balance of an audio signal can be altered by various equipment, including microphones, preamplifiers, and vintage audio gear, each adding unique characteristics.
- Audio engineers must develop acute listening skills and understanding of frequency content to make informed decisions on equalization, akin to being human spectral analyzers.

{{%/ note %}}

---

## Tailoring Spectral Balance for Different Music Genres

- Variability of Spectral Balance Across Music Genres
- Listening Skills and Understanding of Equalization Parameters
- Monitoring and Analyzing Spectral Balance in Recording
- Limitations of Real-Time Spectral Analyzers

{{% note %}}

- The appropriate spectral balance differs across music genres, e.g., jazz vs. rock drumming, requiring genre-specific engineering approaches.
- Engineers must possess refined listening abilities to discern frequency content and understand equalization parameters like frequency, gain, and Q.
- Monitoring spectral balance involves assessing both individual and combined microphone signals throughout the recording process.
- Real-time spectral analyzers, while helpful for novices, have limitations. Professionals rely more on auditory perception due to the dynamic nature of music signals and the inadequacy of visual spectral analysis tools in capturing the essence of audio signals.

{{%/ note %}}

---

# Shaping Spectral balance

---

## Equalization

![](ion-boombox-top-289339532.jpg)

{{% note %}}

- Equalization, at a basic level, involves adjusting bass and treble, like with the tone controls on consumer sound systems. In recording, it's a more complex process.
- Besides equalizers, various tools and methods, both direct and indirect, are used to control the spectral balance of a recorded track.
- Equalizers are crucial for reducing certain frequencies that may mask others, as well as for enhancing specific frequency bands to bring out desired sound qualities.
- The use of equalization in recording and sound systems is both an art and a science. Engineers must have a keen ear to make precise adjustments in frequency, gain, and Q for optimal sound quality.

{{%/ note %}}

---
## Microphone Choice and Placement

- [Charm Studio microphone list](https://docs.google.com/presentation/d/130uChoUPV370sMNJEc02n41QXdygYUO5zVqAWKoa900/present#slide=id.g10e552eff57_0_0) - see frequency response patterns.
- Compare [mic placement](https://cambridge-mt.com/rs2/lmp/) with a different instrument.

{{% note %}}

- Different microphone types and models significantly influence the spectral balance of recorded sound, akin to filters in photography.
- Engineers choose microphones for their unique frequency responses, considering the specific sound source and recording environment.
- Microphone placement is crucial; its orientation and location relative to the sound source can dramatically alter the spectral balance. This includes the consideration of sound radiation patterns and the ratio of direct to reverberant sound.
- The proximity effect in directional microphones, especially evident in low frequencies, is another critical factor. Engineers must understand and skillfully use this phenomenon to enhance or control low-frequency response in recordings.

{{%/ note %}}

---

## Indirect Factors Affecting Spectral Balance

![](signal-path.png)

{{% note %}}

- Monitors and loudspeakers are critical in shaping how audio is perceived, as they translate electrical signals into acoustical energy. Their quality and characteristics can significantly affect the spectral balance.
- Room acoustics play a substantial role in sound quality. The size, shape, and materials of a studio room can alter the way sound waves propagate and are perceived, influencing the spectral balance.
- The perceived spectral balance can vary with different sound levels. Louder sounds can make certain frequencies more prominent, altering the perceived balance. Understanding this relationship is crucial for engineers to achieve a consistent spectral balance.

{{%/ note %}}

---

## Role of Monitors and Loudspeakers in Audio Perception

- Function of Monitors in Audio Engineering
- Influence of Monitor and Loudspeaker Frequency Response
- Techniques for Accurate Spectral Balance Assessment
- Adjustments and Real-Time Analysis in Loudspeaker Response

{{% note %}}

- Monitors and loudspeakers act as crucial tools for audio engineers, providing the auditory window to recorded sounds.
- The unique frequency response of each monitor and loudspeaker model can indirectly influence the engineer's perception of the audio signal's spectral balance.
- Engineers often use multiple monitors and headphones to gain a comprehensive understanding of the true spectral balance of a recording.
- Adjustments to loudspeaker response, including built-in filters and equalization, play a significant role in shaping the final sound. Real-time analyzers can assist in understanding a loudspeaker's frequency response in a specific room, but this response is influenced by room acoustics as well as the loudspeaker's characteristics.

{{%/ note %}}

---

## Control Room and Listening Room Acoustics

- Impact of Room Dimensions and Acoustics
- ITU Recommendations for Listening Environments - [PDF](https://www.itu.int/dms_pubrec/itu-r/rec/bs/R-REC-BS.1116-3-201502-I!!PDF-E.pdf)
- Role of Room Modes in Audio Perception
- Techniques for Assessing and Compensating Acoustic Influence

{{% note %}}

- The physical and acoustical properties of control and listening rooms significantly affect the sound heard during audio monitoring.
- ITU-R BS.1116 provides guidelines for creating acoustically neutral rooms, but completely reflection-free environments are not always ideal for realistic sound reproduction.
- Room modes, particularly in the low-frequency range, are influenced by room dimensions and can create uneven frequency responses at different locations in the room.
- Engineers utilize various techniques, like listening from different positions and using multiple speaker sets, to understand and mitigate the room's acoustic impact on the spectral balance. Listening in adjacent rooms or through different monitoring systems helps in achieving a mix that "translates" well across various sound systems, ensuring consistency and quality in diverse listening environments.

{{%/ note %}}

---

## Sound Levels and Their Effect on Spectral Balance

- Relationship Between Sound Levels and Perception
- Influence of Equal-Loudness Contours
- Adjusting Mixes at Different Sound Levels
- Finding the Optimal Spectral Balance Across Varying Levels

{{% note %}}

- Sound level significantly influences how we perceive the spectral balance of audio.
- The Fletcher-Munson equal-loudness contours demonstrate that human hearing sensitivity varies across frequencies and changes with sound level. This implies that the same audio can sound different at varying volumes.
- Mixing at high sound levels can lead to a skewed perception of low and high frequencies. Conversely, at lower levels, these frequencies might seem underrepresented.
- Audio engineers should monitor and adjust mixes at various sound levels to achieve a balance that remains consistent and pleasing across a range of listening conditions. This approach helps compensate for the varying sensitivity of the human ear to different frequencies at different volumes.

> Test - play a song very loud and then very soft. What do you notice?

{{%/ note %}}

---

## Types of Filters and Equalizers

- Differentiating Filters and Equalizers
- Types of Filters: High-Pass, Low-Pass, Band-Pass
- Graphic Equalizers and Their Function
- Parametric Equalizers for Precise Control

{{% note %}}

- Filters and equalizers, though related, serve distinct functions in shaping spectral balance. Filters typically remove frequencies, while equalizers adjust (boost or attenuate) them.
- Common filter types include high-pass (removing low frequencies), low-pass (removing high frequencies), and band-pass (allowing a specific range while removing others).
- Graphic equalizers provide a visual approach to adjusting frequencies, usually with fixed bands, allowing for broad control over the spectral balance.
- Parametric equalizers offer more precise control, enabling adjustments of specific frequency bands, levels of boost or cut, and bandwidth (Q factor), for detailed shaping of audio signals.

{{%/ note %}}

---


Filters: Low-Pass and High-Pass

![](high-low-filter.png)

{{% note %}}

- High-pass filters remove frequencies below a set cut-off point, commonly used to eliminate low-frequency noise or rumble in recordings. The key is setting the cut-off frequency appropriately to avoid losing important low-end content.
- Low-pass filters, conversely, cut out frequencies above a certain threshold, useful for reducing high-frequency noise or harshness in a sound.
- Some filters allow adjustment of the slope, determining how rapidly frequencies are attenuated beyond the cut-off point. This feature enables more control over how abruptly the filtered frequencies are reduced.

{{%/ note %}}

---

## Graphic Equalizers

![](graphical-eq.jpg)

{{% note %}}

- Graphic equalizers provide control over specific frequency bands, typically aligned with ISO standard octave frequencies like 31.5 Hz to 16,000 Hz.
- They often come with various frequency resolution options, such as 1/3rd octave or 1/12th octave bands, allowing more detailed control over the spectral balance.
- The bandwidth or Q of each band in a graphic equalizer is usually fixed, predetermined by the manufacturer, which sets the range of influence each adjustment has on the frequencies.
- The name "graphic equalizer" is derived from its interface, where vertical sliders create a visual representation of the equalization curve, mapping low to high frequencies from left to right. This visual aspect aids in understanding and adjusting the spectral balance.

{{%/ note %}}

---

##  Parametric Equalizers

- Definition and Capabilities of Parametric Equalizers
- Control Over Center Frequency, Q, and Gain
- Q Factor and Bandwidth Relationship
- Variations and Limitations in Parametric Equalizer Design

{{% note %}}

- Parametric equalizers, introduced by George Massenburg, offer finely tunable control over three key parameters: center frequency, Q (quality factor), and the level of boost or cut.
- The Q factor, which inversely relates to the bandwidth of the equalization curve, is calculated using the formula Q = Fc/bandwidth, where Fc is the center frequency.
- Despite the ideal of complete control, many parametric equalizers in practice have limitations. For example, Q may only be adjustable to preset values, and the center frequency selection might be restricted to specific choices.
- Some designs link Q to the amount of gain, where minimal adjustments yield broader bandwidths, and maximum adjustments result in narrower bandwidths. These constraints can impact the flexibility and precision with which an engineer can shape the audio's spectral balance.

{{%/ note %}}

---

## Shelving Equalizers

![](shelving.png)


{{% note %}}

- Shelving equalizers are often mistaken for high-pass and low-pass filters, but they differ in function. While filters remove frequencies, shelving equalizers can either boost or attenuate them.
- A low-shelf equalizer affects frequencies below a certain point, and a high-shelf equalizer impacts frequencies above it, applying a uniform boost or cut across these ranges.
- In consumer audio, such as home or car sound systems, shelving equalizers are commonly used for basic tone control through 'bass' and 'treble' settings.
- In professional recording studios, shelving filters are frequently part of parametric equalizers, offering options for adjusting the extreme low and high ends of the frequency spectrum. They provide a versatile tool for fine-tuning the overall spectral balance of a recording.

{{%/ note %}}

---

## Getting Started with Practice

[WebTET](https://webtet.net/apcl/#/about)

{{% note %}}

- Effective practice involves regular, focused sessions, ideally daily or several times a week. Shorter sessions (10-15 minutes initially, gradually increasing up to 45-60 minutes) are recommended to avoid fatigue and maximize learning efficiency. Even brief daily practices can be more beneficial than infrequent, prolonged sessions.
- The software provides randomly generated equalization settings within user-defined limitations, offering a practical and interactive way to sharpen listening and technical skills in equalization.

{{%/ note %}}

---

## Practice Types in WebTET

- Matching Mode for Equalization Duplication
- Matching Memory Mode for Sound Memorization
- Return to Flat Mode for Equalization Reversal
- Absolute Identification Mode for Advanced Skill Development

{{% note %}}

- **Matching Mode**: The objective is to replicate the equalization applied by the software, allowing comparison between the original and user's adjustments.
- **Matching Memory Mode**: Similar to Matching, but with the added challenge of relying on memory, as the original setting becomes unavailable after any adjustments are made.
- **Return to Flat Mode**: This mode involves reversing the software's equalization to bring the audio back to its original spectral balance, requiring opposite adjustments to the applied changes.
- **Absolute Identification Mode**: The most challenging mode, where the goal is to identify the equalization settings applied by the software without any reference. This mode tests and improves the user's ability to discern subtle audio changes.

{{%/ note %}}

---

## Frequency Resolution 

- Options for Frequency Resolution in Ear Training
- Difference Between Octave and Third-Octave Frequencies
- Strategy for Identifying Frequencies
- Progression from Octave to Third-Octave Training

{{% note %}}

- "WebTET" offers two frequency resolution options: 1 octave and 1/3rd octave.
- **1 Octave**: Easier, with 9 possible frequencies. Ideal for beginners to familiarize with basic frequency recognition.
- **1/3rd Octave**: More challenging, encompassing 25 frequencies, including all octave frequencies plus additional frequencies between each octave pair.
- A key strategy for mastering third-octave frequencies is to initially anchor to the nearest octave frequency. Once familiar with the nine octave frequencies, users can then progress to identifying the more nuanced third-octave frequencies.
- Example: For 1000 Hz and 2000 Hz octave frequencies, the adjacent third-octave frequencies would be 2500 Hz (upper neighbor), 1600 Hz (lower neighbor) for 2000 Hz, and 1250 Hz (upper neighbor), 800 Hz (lower neighbor) for 1000 Hz. This approach helps in building a strong foundational understanding of frequency ranges.

{{%/ note %}}

---

![](iso-freq.png)

---

## Managing Frequency Range 

- Setting Frequency Range Limits
- Starting with Midrange Frequencies
- Expanding Frequency Range Gradually
- Challenges with Low-Frequency Identification

{{% note %}}

- In "TETPracticeEQ", users can limit the frequency range for practice, starting from a full range of 63 Hz to 16,000 Hz down to as narrow as three octaves.
- Beginners are advised to start with a limited midrange, such as 500 to 2000 Hz, mastering these frequencies before expanding the range.
- As proficiency improves, users can gradually include more octaves, eventually working up to the full frequency range.
- Identifying low frequencies (63 Hz to 250 Hz) can be particularly challenging due to factors like inconsistent levels in music recordings, limitations of sound reproduction systems, and room acoustics. Using headphones can mitigate issues caused by room acoustics, though their frequency response should be considered. For the best results, especially in low frequencies, selecting high-quality headphones with a flat response is crucial.

{{%/ note %}}

---

## Working with the EQ Practice Module

- Initial Setup and Listening to Octave Frequencies
- Auditioning a Sound File and Identifying Instrumental Effects
- Recognizing Frequency-Specific Effects on Different Recordings

{{% note %}}

- Upon opening the EQ practice module, select pink noise and adjust the volume. Explore each octave frequency to understand its sound. Remember, the gain jumps to 12dB by default for each new frequency.
- When loading a sound file, notice how different frequencies affect various instruments. For example, 125 Hz might enhance a snare drum, while 8kHz could highlight cymbal harmonics.
- Each recording reacts differently to the same frequency adjustments, emphasizing the need for a unique approach to each mix. What works for one recording may not suit another.

{{%/ note %}}

---


## Vowel method

- 250 Hz = [u] as in boot
- 500 Hz = [o] as in tow
- 1000 Hz = [a] as in father
- 2000 Hz = [e] as in bet
- 4000 Hz = [i] as in beet

{{% note %}}

- Researchers have found that associating vowel sounds with octave frequencies aids in identifying them due to formant frequencies. This technique is rooted in studies by Letowski, Miskiewicz, Opolko, Woszczyk, Quesnel, and Slawson.
- Key vowel sounds and their corresponding frequencies: 250 Hz is like [u] in "boot," 500 Hz as [o] in "tow," 1000 Hz like [a] in "father," 2000 Hz as [e] in "bet," and 4000 Hz resembles [i] in "beet."
- By associating a sound with a vowel, learners can more easily remember and identify specific frequencies. This method is beneficial for auditory memory and frequency recognition.

{{%/ note %}}

---

## Recommended recordings

- Anderson, Arild. (2004). “Straight” from The Triangle. ECM Records. (jazz piano trio)
- Blanchard, Terence. (2001). “On the Sunny Side of the Street” from Let’s Get Lost. Sony. (jazz with vocals)
- Earth, Wind & Fire. (1998). “September” from Greatest Hits. Sony. (R&B pop)
- Hellendaal, Pieter. (1991). “Concerto II—Presto” from 6 Concerti Grossi. Perf. The European Community Baroque Orchestra. Channel Classics. (Baroque orchestra)

---

- Le Concert des Nations. (2002). “Marche pour la céré- monie” from Soundtrack from the film Tous les matins du monde. Alia Vox Spain. (Baroque orchestra)
- Randall, Jon. (2005). Walking Among the Living. Epic/ Sony BMG Music Entertainment. (roots music/bluegrass)
- Steely Dan. (2000). “Gaslighting Abbie” from Two Against Nature. Giant Records. (pop)
  The Police. (1983). “Every Breath You Take” from Syn- chronicity. A&M Records. (rock)
