# Claude Sonnet 5.5 - Graphics Showreel
Hi everyone! This is me testing Claude's ability to create graphics. I used **Sonnet 5.5** with Effort set to **High** for a balance between output quality and usage limits.

## Idea
The idea came from these two videos by [Last School](https://www.youtube.com/@Last-school) on YouTube:

- [Claude AI-യുടെ ഈ എഡിറ്റിംഗ് മാജിക് കണ്ടോ? 🔥 | Best AI Video Editing Tool 2026 Malayalam](https://www.youtube.com/watch?v=SR8yK_8D63Y)
- [Edit Full Videos in 1 Prompt! 🔥 Secret AI Video Editing Trick (Malayalam)](https://www.youtube.com/watch?v=v7-Qi9FgT74)

So, I decided to try out this using my limited amount of Claude usage credits 😭 The result I got was in `.html` format. I have uploaded it to this repository and hosted using GitHub Pages.

### Prompt
`make a dynamic 15-second motion graphics video that shows what an incredible motion designer you are, like it's your showreel for a résumé. go all out.`

Yes, this is the prompt, rest of the work was done by Sonnet 5.5. I got it from [here](https://prompt-motion.com/shneural-2abdfa).

## How was the ouput?
Honestly, this is my first time using Claude to generate a _video_. I have used Google's video generation models quite a lot. **But, this is different.**

## How's this different from video generation models?
Here's what Claude says about this:

_Video generation models (Sora, Veo, and similar) are diffusion-based. They synthesize pixels frame by frame from learned visual patterns, so they can produce photorealistic footage, people and natural scenes without anyone specifying the geometry._

_What I made is procedural motion graphics. I wrote code that describes every frame as a function of time: positions, easing curves, colours and 3D projection math. The browser renders it deterministically, so the result is exactly reproducible, resolution-independent, and scrubbable. Editing is precise: change one number and the timing shifts._

_The trade-offs:_

_Code-driven: crisp type, shapes and data-style animation, with exact control.
Generative models: realistic footage and organic textures, but less precision and consistency, and no editable structure._

_They solve different problems. Motion design suits code; cinematic realism suits generative video._

## Links
- [Prompt Motion](https://prompt-motion.com/)
- [Results](https://code-beaker.github.io/claude-graphics/)
