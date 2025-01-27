+++
title = "Analysis of Sound"
outputs = ["Reveal"]
[reveal_hugo]
theme = "moon"
margin = 0.2
separator = "##"
+++

# Analysis of sound

---

## Sound Quality and Music Production

- Key Elements:
  - Timbral Characteristics
  - Spatial Dimensions
  - Dynamic Properties

{{% note %}}

- Recorded sound has specific qualities that make it unique, focusing on timbral, spatial, and dynamic aspects.
- While live performances offer immediacy, recorded music provides a different experience, characterized by clarity and a crafted sense of space, though it may convey a more distant perspective due to reverberation.
- Recording engineers and producers play a pivotal role in shaping the listening experience by adjusting levels and processing, guiding listeners through the musical journey.
- Analyzing a diverse range of recordings across various genres and noting the production choices and personnel involved enriches an engineer's understanding and informs their approach to sound quality and mix balance.

{{%/ note %}}

---

## Research Tools for Recording Analysis

- [AllMusic | Record Reviews, Streaming Songs, Genres & Bands](https://www.allmusic.com/)
  - Comprehensive reviews
  - Detailed credits
  - Production information
- [Discogs - Music Database and Marketplace](https://www.discogs.com/)
  - Technical personnel credits
  - Release information
  - Production history

{{% note %}}

> For each recording that seems interesting from a sound quality and production point of view, make a note of the production personnel credits, including producer, recording engineer, mixing engineer, and mastering engineer.

Knowing who helped create the recording can aid in the analysis of it. Look at sites like allmusic.com for information on a specific recording.

{{%/ note %}}

---

## Analysis of Sound from Electroacoustic Sources

- Analyze Sonic Signatures of artist, producer & engineer styles
- Sound Quality Impact
- Master Mix Elements
  - Learn stereo imaging basics
  - Study reverb, panning & EQ
  - Develop equipment recognition



{{% note %}}

- Analyzing recordings critically helps in understanding the unique sonic signatures of artists, producers, or engineers, particularly in terms of timbre, space, and dynamics.
- The clarity of sound quality, technical fidelity, and sonic characteristics of a recording significantly influence how listeners perceive the musical intent and meaning.
- Learning the components of a stereo image, such as reverberation, panning, and equalization, enhances understanding of sound mixing and its foundational element: control of sound level or amplitude.
- Advanced critical listening involves not only deconstructing the overall mix but also delving into the specific details of each sound source, even predicting the models of equipment used, based on the sound's characteristics.

{{%/ note %}}

---

> [European Broadcasting Union Technical Document 3286](https://tech.ebu.ch/docs/tech/tech3286.pdf) titled “Assessment Methods for the Subjective Evaluation of the Quality of Sound Programme Material—Music”

---

## Understanding Bandwidth

- Audio Frequency Range:
  - Full Spectrum: 20 Hz - 20 kHz
  - Musical Content:
    - Fundamentals (up to 4 kHz)
    - Overtones (up to 20 kHz)
- Bandwidth Factors:
  - Recording medium
  - System components
  - Digital compression
  - Filtering effects


{{% note %}}

- Overall bandwidth refers to the range of frequencies a recording encompasses, typically from the lowest bass at 20 Hz to the highest treble at 20 kHz. Analyzing this reveals the fullness and richness of a recording.
- The bandwidth can be limited by factors such as the recording medium, sound system components, or purposeful down-sampling in digital formats to save on data transmission, each impacting the audio quality uniquely.
- The effects of narrowed bandwidth are perceptible and can be analyzed through the use of high-pass and low-pass filters, which cut off frequencies beyond certain thresholds.
- In evaluating high-frequency extension, it's crucial to consider the presence of overtones, especially since musical fundamentals generally don't exceed 4,000 Hz, yet overtones from instruments like cymbals and brass can reach up to 20,000 Hz, significantly contributing to the richness and texture of the sound.

{{%/ note %}}

---

## Spectral Balance

- Energy Distribution Across Frequencies
  - Balance between frequency bands
  - Identify resonances/antiresonances
  - Critical for pleasing sound
- Analysis Methods
  - FFT power spectrum visualization
  - Subjective critical listening
  - Musical context evaluation
- Key Influencing Factors
  - EQ decisions
  - Mic technique
  - Instrument physics
  - Room acoustics

{{% note %}}

- Spectral balance refers to the distribution of sound energy across different frequency bands, crucial for achieving a harmonious and pleasing sound. It's not just about the balance between high and low frequencies but also about identifying specific frequency resonances and antiresonances.
- The power spectrum of an audio signal, often visualized through the fast Fourier transform (FFT), is a common tool for analyzing spectral balance, showcasing the frequency content and relative amplitudes of frequency bands.
- Subjective analysis involves holistic listening to identify prominent or deficient frequency bands, resonances, and specific musical notes, considering the broader context and nuanced elements of the recording.
- The spectral balance is influenced by various factors, including equalization, microphone placement and orientation, sound radiation patterns of musical instruments, and the acoustic characteristics of the recording space, all of which can introduce or amplify specific frequencies, shaping the final sound.

{{%/ note %}}

---

## Possible questions for spectral balance

- Are there specific frequency bands that are more prominent or deficient than others?
- Can we identify resonances by their approximate frequency in Hertz?
- Are there specific musical notes that are more prominent than others?

{{% note %}}
* **Frequency Band Balance**
  - Helps identify if specific ranges are overpowering or too weak in the mix
  - Low-end (20-250 Hz) can cause boominess if excessive
  - High frequencies (6-20 kHz) contribute to clarity and air - deficiency makes mix sound dull

* **Resonance Identification**
  - Resonances are unnatural frequency peaks that need to be controlled
  - Common problem areas include 200 Hz (mud in vocals) and 2-3 kHz (harshness)
  - Precise frequency identification allows for targeted EQ notching
  - Can often be heard as a "ringing" or sustained tone in the mix

* **Musical Note Prominence**
  - Relates to both tonal balance and technical mixing issues
  - Example: Low E bass note at 41.2 Hz overwhelming the mix
  - Helps identify both musical arrangement issues and technical frequency problems
  - Understanding musical notes' frequency relationships aids in more musical EQ decisions
{{%/ note %}}

---

## The Auditory Image & Stereo Field

- Creating Spatial Perception:
  - Mental representation from audio cues
  - Phantom image creation
  - Interchannel time/amplitude control
- Production Conventions:
  - Center: vocals, bass, kick
  - Sides: instruments for width
  - Depth through processing
- Analysis Elements:
  - Image width & stability
  - Source placement
  - Spatial distribution

{{% note %}}

- The auditory image is a listener's mental representation of the external world based on auditory input, allowing localization of sound sources even when they are phantom images created between actual loudspeakers.
- The stereo image is crafted by manipulating interchannel amplitude and time differences, creating an illusion of sound source locations between two loudspeakers. This process doesn't mimic natural hearing due to the phantom image effect.
- Conventions in music production, like those in pop and rock, utilize the stereo image in specific ways, often emphasizing the center for critical elements like vocals and bass, with other instruments panned to create balance and depth.
- Analyzing a stereo image involves assessing its width, the placement and stability of sound sources, and the spatial distribution of these sources, all contributing to the clarity, balance, and overall impact of the recording.

{{%/ note %}}

---

## Possible questions for auditory image

- How wide or monophonic is the image?
- What are the locations and widths of individual sound sources in a recording?
- Are their locations stable and definite or ambiguous? 
- How easily can the locations of sound sources be pinpointed within a stereo image?
- Does the sound image appear to have the correct and appropriate spatial distribution of sound sources?

{{% note %}}

* **Width Assessment (How wide or monophonic is the image?)**
  - Helps determine if the mix is using the full stereo spectrum effectively
  - Guides decisions about panning, stereo widening, and mono compatibility
  - Critical for ensuring the mix translates well across different playback systems
  - Too narrow can sound boring; too wide can sound unnatural

* **Sound Source Location and Width**
  - Determines how much space each instrument or sound occupies
  - Helps prevent overcrowding in specific areas of the stereo field
  - Guides decisions about how wide stereo elements like keyboards or backing vocals should be
  - Important for creating depth and dimension in the mix

* **Location Stability and Definition**
  - Addresses whether elements are firmly placed or moving around unnaturally
  - Helps identify phase issues that might cause unstable imaging
  - Guides decisions about modulation effects (chorus, flangers) that might destabilize positioning
  - Critical for maintaining a professional, polished sound

* **Location Precision (Pinpointing)**
  - Relates to how clearly defined each element's position is
  - Helps identify masking issues where sounds blur together
  - Important for clarity and separation in dense mixes
  - Guides decisions about EQ and spatial processing

* **Spatial Distribution Appropriateness**
  - Ensures the mix matches genre expectations and artistic intent
  - Guides decisions about front-to-back depth using reverb and delay
  - Helps create a natural, believable sound stage
  - Important for maintaining musical context and authenticity
{{%/ note %}}

---

## Creating Spatial Impression

- Understanding Space in Audio:
  - Emotional & Scene Setting
    - Reverberation impact
    - Echo characteristics
    - Intimate to expansive range
- Analysis Components:
  - Room characteristics
  - Depth perception
  - Direct vs. reflected sound


> Key Focus:
Natural vs. Artificial Space
Foreground/Background Balance

{{% note %}}

- Spatial impression in a recording is pivotal for evoking emotions and setting the scene, with reverberation and echoes playing key roles in creating a sense of space, whether intimate or expansive.
- Analyzing the spatial impression involves assessing apparent room size, depth perspective, and the characteristics of reverberation, including its realness, duration, and spectral balance.
- Depth perspective analysis focuses on how well the recording differentiates between foreground and background sounds, the balance of direct sound to reverberation, and the presence of specific time-based effects like chorus or flanging.
- The authenticity of spatial effects is notable; real acoustic spaces provide a depth and realism that is challenging to replicate with artificial reverberation, especially when the original recording is in an acoustically dead space.

{{%/ note %}}

---

## Questions for spatial impression

- Apparent room size:
  - How big is the room?
  - Is there more than one type of reverberation present in a recording?
  - Is the reverberation real or artificial?
  - What is the approximate reverberation time?
  - Are there any echoes or long delays in the reverberation and early reflections?
- Depth perspective: Are sounds placed up front clearly distinguished from those in the background?

{{% note %}}

* **Room Size Assessment**
  - Helps determine the appropriate reverb settings to create a convincing space
  - Guides decisions about pre-delay and reverb time
  - Critical for maintaining consistent spatial impression across the mix
  - Different genres often have expected room size characteristics (intimate for folk, large for orchestral)

* **Multiple Reverb Analysis**
  - Helps identify when different spaces are needed for different elements
  - Guides decisions about using multiple reverb plugins or sends
  - Important for creating depth and separation between instruments
  - Common practice to use different reverbs for drums, vocals, and instruments

* **Real vs. Artificial Reverb Detection**
  - Helps in matching additional reverb to existing room sound in recordings
  - Guides decisions about whether to preserve natural room sound or replace it
  - Important for maintaining authenticity in acoustic recordings
  - Influences choices between convolution and algorithmic reverbs

* **Reverberation Time Considerations**
  - Determines how long the reverb tail should last
  - Guides tempo-synchronized reverb decisions
  - Critical for maintaining clarity vs. creating atmosphere
  - Helps prevent mud buildup from too-long decay times

* **Echo and Early Reflection Analysis**
  - Identifies potential problems with flutter echoes or unwanted reflections
  - Guides decisions about early reflection patterns in artificial reverb
  - Important for creating realistic space simulation
  - Helps in controlling definition vs. diffusion

* **Depth Perspective Management**
  - Crucial for creating front-to-back dimensionality in the mix
  - Guides decisions about reverb send levels and EQ
  - Important for maintaining clarity of foreground elements
  - Helps create hierarchical importance in the mix through spatial placement

Show some examples of different spaces in Reaper using \* [OpenAIR – Open Air Library](https://www.openairlib.net/)
{{%/ note %}}

---

## Questions for spatial impression

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

##  Understanding Dynamic Range

- Dynamic Range Elements:
  - Amplitude spectrum (soft to loud)
  - Microdynamics - subtle variations
  - Genre-specific expectations
- Technical Analysis:
  - Level meter monitoring
  - Compression effects
  - LUFS measurement
  - Peak vs. perceived loudness
- Production Impact:
  - Manual gain control
  - Automation techniques

{{% note %}}

- Dynamic range, representing the span between the softest and loudest parts of a recording, varies significantly across musical genres and is essential for conveying the emotional depth and intensity of a piece.
- Microdynamics, or the subtle fluctuations in sound level, can be observed and analyzed using level meters, revealing how compression and other production choices influence the sound and its perceived loudness.
- The dynamic range of a recording affects its perceived loudness, with recordings having smaller amplitude fluctuations sounding louder to the human ear than those with larger fluctuations, even if peak amplitudes are equal.
- Attention to dynamic level changes, whether through manual gain adjustments or automated processes like compression, is crucial as they can underscore musical intentions, enhance the listening experience, or, if not managed well, detract from the musical impact by making quieter sections inaudible.
- Demo with automation and LUFS in Reaper to show how dynamic range can be controlled.

{{%/ note %}}

---

## Dynamics in classical music

<iframe width="560" height="315" src="https://www.youtube.com/embed/nkx_42h1ngI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

---

## Managing Noise & Distortion
  
- Sources of Audio Degradation:
  - Electrical interference, Physical disturbances, Digital sync issues, Signal overload/clipping
- Artistic Considerations:
  - Intentional vs. unwanted noise
  - Creative distortion effects
  - Stylistic choices
- Quality Control:
  - Level management
  - Noise reduction
  - Distortion prevention
  - Artistic integrity
  
{{% note %}}

- Noise in recordings can stem from a variety of sources, including electrical interference, physical disturbances, external sounds, and issues with digital synchronization or recording media, often detracting from the audio quality if not managed properly.
- While the general goal in production is to minimize unintentional noise, certain styles or artistic choices may embrace specific noise elements to create a desired effect or atmosphere in the recording.
- Recognizing and addressing clipping, a form of distortion that occurs when a signal exceeds an equipment's maximum capacity, is crucial to maintain the integrity of the sound. It's important to adjust levels appropriately to avoid or minimize this issue.
- Differentiating between artistic distortion, intentionally used as a creative effect, and unintentional distortion, which typically degrades the sound quality, is essential in the analysis and production process.

{{%/ note %}}

---

## Hum examples

<iframe width="560" height="315" src="https://www.youtube.com/embed/pMtn-loUrg8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

---

## Mix Balance Analysis

- Balance Elements:
  - Level relationships shape impact
  - Style-specific requirements
  - Individual component clarity
- Analysis Skills:
  - Overall mix assessment
  - Temporal/spatial features
  - Artifact detection
  - Quality control

{{% note %}}

- The balance of elements within a mix profoundly affects the musical meaning, impact, and listener focus, with each component's amplitude influencing the perception of the whole mix and its individual elements.
- Critical analysis involves assessing whether the amplitude levels of instruments are harmoniously balanced for the music's style and identifying any elements that may be overly dominant or subdued.
- Beyond the overall mix, the analysis can extend to specific subfeatures such as the temporal and spatial characteristics of each musical voice or instrument, including aspects like amplitude envelope components, definition, clarity, and spatial extent.
- A trained listener's ability to discern subtle audio features and artifacts, which may go unnoticed by untrained ears, is crucial, especially in contexts like perceptual encoder algorithm development where identifying and addressing encoding shortcomings is essential.

{{%/ note %}}

---