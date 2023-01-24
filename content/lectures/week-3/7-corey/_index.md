+++
title = "Analysis of sound"
outputs = ["Reveal"]
[reveal_hugo]
theme = "moon"
margin = 0.2
separator = "##"
+++

# Analysis of sound

{{% note %}}
We will use these subjective methods of sound analysis to work on our sound journals through the semester. These will get more detailed and specific over the course of the semester. These will culminate in a paper on one recording and a presentation on that paper.

> What makes sound recordings (records) different from live performance or even live band recordings?

{{%/ note %}}

---

## Further info about recordings

- [AllMusic | Record Reviews, Streaming Songs, Genres & Bands](https://www.allmusic.com/)
- [Discogs - Music Database and Marketplace](https://www.discogs.com/)

{{% note %}}

> For each recording that seems interesting from a sound quality and production point of view, make a note of the production personnel credits, including producer, recording engineer, mixing engineer, and mastering engineer.

Knowing who helped create the recording can aid in the analysis of it. Look at sites like allmusic.com for information on a specific recording.

{{%/ note %}}

---

## Analysis of sound from Electroacoustic sources

- sound quality
- technical fidelity
- sonic characteristics

{{% note %}}
Through the analysis process it is possible to learn to identify what aspects of their recordings make them particularly successful from a timbral, spatial, and dynamic point of view.

The **sound quality, technical fidelity, and sonic characteristics** of a recording have a significant impact on how clearly the musical meaning and intentions of a recording are communicated to listeners. Components of a stereo image can be deconstructed to learn more about the use of reverberation and delays, panning, layering and balancing, dynamics processing, and equalization.

Sound mixing at it's most basic level involves gain or level variation over time. This can be done either to the entire frequency spectrum, or a small subset. An analysis can cover how the recording used this emphasis or deemphasis of frequencies to enhance musical meaning.

> At a much deeper level in the analysis of a recording, an engineer who is more advanced in critical listening skills can begin to make guesses about specific models of equipment used during recording and mixing, based on the timbres and amplitude envelopes of components in a sound image.

{{%/ note %}}

---

Analysis characteristics

- [European Broadcasting Union Technical Document 3286](https://tech.ebu.ch/docs/tech/tech3286.pdf) titled “Assessment Methods for the Subjective Evaluation of the Quality of Sound Programme Material— Music”:
  - Overall bandwidth
  - Spectral balance
  - Auditory image
  - Spatial impression, reverberation, and time-based effects Dynamic range, changes in level or gain, artifacts from dynamics processing (compressors/expanders)
  - Noise and distortion
  - Balance of elements within a mix

---

## Overall Bandwidth

- the frequency content and how far it extends to the lowest and highest frequencies of the audio spectrum
- Does the recording go from 20 Hz to 20 kHz?
- Consider the overtones, not just fundamentals

{{% note %}}
FM radio extends only up to about 15kHz and the bandwidth of standard telephone communication ranges from about 300 to 3000 Hz. A record- ing may be limited by its recording medium, a sound system can be limited by its electronic components, and a digital signal may be down-sampled to a narrower bandwidth to save data transmission. The effect of narrowing a bandwidth can be heard through the use of high- and low- pass filters.

In making a judgment about high frequency extension, the highest overtones present in recording need to be considered. **The highest fundamental pitches in music do not go much above about 4000 Hz, but overtones from cymbals and brass instruments easily reach 20,000 Hz.** An engineer’s choice of recording equipment or filters may intentionally reduce the bandwidth of a sound, which differentiates the bandwidth of the acoustic and recorded sound of an instrument.

> Demo this in Reaper

{{%/ note %}}

---

## Spectral Balance

- the relative level of frequency bands across the entire audio spectrum
- balance of high to low frequencies
  - or resonances/anti-resonances
- Can be measured with an fast Fourier transform (FFT)

---

## Possible questions

- Are there specific frequency bands that are more prominent or deficient than others?
- Can we identify resonances by their approximate frequency in Hertz?
- Are there specific musical notes that are more prominent than others?

{{% note %}}

Frequency resonances in recordings can occur because of the deliberate use of equalization, microphone placement around an instrument being recorded, or specific characteristics of an instrument, such as the tuning of a drumhead. The location and angle of orientation of a microphone will have a significant effect on the spectral balance of the recorded sound produced by an instrument. Because musical instruments typically have sound radiation patterns that vary with frequency, a microphone position relative to an instrument is critical in this regard.

{{%/ note %}}

---

## Auditory Image

- “a mental model of the external world which is constructed by the listener from auditory information (p. 198).” Woszcyzk (1993)
- **stereo image** - forms the auditory impression of sounds located between speakers
- Does the recording use the full stereo image?
- Does the recording use conventions of panning or break them?
- Check with a "correlation meter"

{{% note %}}
In the study of music production and mixing techniques, a number of conventions in panning sounds within the ste- reo image are found among various genres of music. For instance, pop and rock generally emphasize the central part of the stereo image, because kick drum, snare drum, bass, and vocals are typically panned to the center. Guitar and keyboard parts are sometimes panned to the side, but overall there is significant energy originating from the center.

{{%/ note %}}

---

## Spatial impression, reverberation, and time-based effects

- Apparent room size:
  - How big is the room?
  - Is there more than one type of reverberation present in a recording?
  - Is the reverberation real or artificial?
  - What is the approximate reverberation time?
  - Are there any echoes or long delays in the reverberation and early reflections?
- Depth perspective: Are sounds placed up front clearly distinguished from those in the background?

{{% note %}}
The spatial impression of a recording is critical for conveying emotion and drama in music. Reverberation and echo help set the scene in which a musical performance or theatrical action takes place. Listeners can be transported mentally to the space in which music exists through the strong influence of early reflections and reverberation that envelops music in a sound recording.

Show some examples of different spaces in Reaper using \* [OpenAIR – Open Air Library](https://www.openairlib.net/)
{{%/ note %}}

---

- What is the spectral balance of the reverberation?
- What is the direct/reverberant ratio?
- Are there any strong echoes or delays?
- Is there any apparent time-based effect such as chorus or flanging?

---

## Concert Hall Acoustics

<iframe width="560" height="315" src="https://www.youtube.com/embed/mDCJLbz61fU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

{{% note %}}
Classical music recordings can give listeners the opportunity to familiarize themselves with reverberation from a real acoustic space. Often orchestras and artists with higher recording budgets will record in concert halls and churches with acoustics that are deemed to be very conducive to music performance. The depth and sense of space that can be created with appropriate pickup of a real acoustic space are generally difficult to mimic with artificial reverberation.
{{%/ note %}}

---

## Dynamic range, changes in level

- Some styles have drastic dynamic ranges and changes in level
  - classical music even has names for ranges such as pianissimo, forte, etc
  - pop and rock music has more subtle dynamic level changes that we can see on a meter
- listen for changes in level of individual instruments and of an overall stereo mix.

{{% note %}}
Demo this with automation curves in Reaper.

Also show LUFS view in Reaper.
{{%/ note %}}

---

## Dynamics in classical music

<iframe width="560" height="315" src="https://www.youtube.com/embed/nkx_42h1ngI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

---

## Noise and distortion

- 50 or 60Hz buzz or hum,
- low-frequency thumps from a microphone or stand being bumped,
- external noises such as car horns or airplanes,
- clicks and pops from inaccurate digital synchronization, and
- drop- outs (very short periods of silence) resulting from defective recording media.

---

## Hum examples

<iframe width="560" height="315" src="https://www.youtube.com/embed/pMtn-loUrg8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

---

## Balance of elements within a mix

- Think about questions such as the following:
  - Are the amplitude levels of the instruments balanced appropriately for the style of music?
  - Is there an instrument that is too loud or another that is too quiet?

---

- Some of these subfeatures might include the following:
  - Specific features of each component, musical voice, or instrument such as the temporal nature or spatial location of amplitude envelope components (e.g., attack, decay, sustain, and release)
  - Definition and clarity of elements within a sound image
  - Width and spatial extent of individual elements

{{% note %}}
Show an example from the Riff Raff mix of different ways of balancing components in a mix.
{{%/ note %}}
