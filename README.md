# Week 8 Quiz

### Part 1

I visited TeamLab's interactive installation *Forest and Spiral of Resonating Lamps* in 2019, which inspired me to create my assignment because we chose Wheels of Fortune, a work of Pointillism created by Pacita Abad to work with.

![14529.jpeg](assets/14529.jpeg)

![20939.jpeg](assets/20939.jpeg)

(Forest of Resonating Lamps - Shanghai, teamLab, 2016)

This artwork, in which lamps are seemingly scattered in a random manner, is composed of resonating light that changes based on the relationship between the people in the artwork space. It is a work that expresses the beauty of continuity.

When a person stands still close to a lamp, it shines brightly and emits a sound. The light spreads to the two closest lamps, which in turn similarly emit a sound, spreading their light to the lamps nearest to them. The light, now divided into two, will pass through all of the lamps in the room once, creating a single trajectory of light.

&nbsp;
### Part 2

I think the aspect of sound delivery and continuity in this work of art can be applied to my project. I want to implement live sound level input in my project to add animation effects. For example, when a user releases a shout, the sound level rises and one of the fortune wheels (representing the user) amplifies and transmits this energy to the surrounding fortune wheels (representing others). In my opinion, it can represent that one person's desire and pursuit of wealth will affect others, which should be in line with the intention expressed by this work of Pacita Abad.

![Pacita Abad Wheels of fortune.jpg](assets/Pacita_Abad_Wheels_of_fortune.jpg)

(Wheels of Fortune, Pacita Abad, 2000)

By inquiring the p5.js library, I think the **p5.AudioIn*** is helpful for my project. It enables the ability of my project to get Real-time audio from an input (i.e. user device’s microphone). And it can read the amplitude (volume level) of the audio input, creates the possibility of sound interaction with the artwork.

*For more information about p5.AudioIn, please go to: [https://p5js.org/reference/#/p5.AudioIn](https://p5js.org/reference/#/p5.AudioIn)