# Shadow Dancer Music Video
![title](https://i.imgur.com/BuEJtTV.png)

[video link](https://youtu.be/FZyImKC0oLs)

Hours: 48.

A music video/lyric visualizer for the song ["Shadow Dancer" by Robin and the Goblins](https://www.youtube.com/watch?v=25Xaibsg15M).
The images were created with the Midjourney AI and edited using Davinci Resolve. 

I was inspired by for this project by the works of [Tree Jesus](https://www.youtube.com/watch?v=pIRKiCXT0gM) and [Ben Gillin](https://www.youtube.com/watch?v=Z5i-hL7eHHQ) as well as the movie [Loving Vincent](https://www.youtube.com/watch?v=CGzKnyhYDQI).

## Goals
* Dark romantic aesthetic
* Discernable storyline
* Absence of the common pitfalls of AI generated images, such as
  * overly messy or detailed backgrounds and textures
  * mangled body parts, especially hands, unless desired
* Illusion of stop motion animation 

## Ethical Considerations
Image generation AIs are being criticised for allowing users to imitate the style of living artists. Here's a comparison of an artwork by Madeline von Foerster and an imitation I created in Midjourney:

![OG](http://www.madelinevonfoerster.com/images/enlargements/Saartjie_Baartman.jpg)
![Fake](https://i.imgur.com/g46blbo.png)

Despite loosing by a landslide in comparison to the original artworks, it is easy to see how the technology endangers the futures of digital artists in particular.
For this project and in general, I only use image generation AIs for animations that wouldn't be possible (or financeable) through traditional means. 
Style-wise, I'll try to only imitate the styles of artists that have been dead for longer than 70 years, after which copyrights pass into public domain in the European Union. 

## Choice of Image AI

While Dall-E 2 provides more accurate results and Stable Diffusion excels at pinning down specific stylisations, there is something about Midjourney that gives it an almost analog quality:

![comparison](https://pbs.twimg.com/media/FanTVq0WAAAFGCq?format=jpg&name=large)
“Midjourney reminds me of a beautiful analog Moog synthesizer — it’s almost impossible to make it sound bad and you can do incredible things with it, but in exchange, its range is more limited. The artifacts it does are like analog distortion, very pleasing.”[source](https://petapixel.com/2022/08/22/ai-image-generators-compared-side-by-side-reveals-stark-differences/)

For the type the dark romantic painting style that I'm searching for, Midjourney proves to be the best choice. More importantly the raw image quality, Midjourney also allows for a workflow very suitable to my needs:
• Simultaneous image generation
• Unlimited number of images (paid version)
• Multiple upscaling algorithms (I achieved the best results by combining the regular upscale with a light upscale and finally a beta upscale, giving me 2k images)

For future projects it'd interesting to create my own models, but for this video I wanted to get started very quickly.

## Midjourney
After trying out multiple styles, I came to the conclusion that classicist and romantic painting styles produce the highest image quality. My main goal was to avoid the overly intricate and messy details that plague many Midjourney creations while preserving its analogue-ness, such as individual brush strokes.

I'm quite happy with the result:

![nice](https://i.imgur.com/c17D3Iu.jpg)

It's, of course, not authentic in any way, as Midjourney's tendency for stylized graphic novels faces is still very noticeable. No 18th century painter would paint like this:

![comic](https://i.imgur.com/UxrOMdE.jpg)

I don't necessarily mind it though, as it suits the poppy song, creates an interesting juxtaposition of styles and helps to keep the images coherent compared to other more wild models such as Stable Diffusion.
Speaking of coherence, I went for the style of Francisco de Goya in the end, as it allowed me to generate an infinite number of Timothee Chalamet lookalikes for my main character with the promt "young androgynous man".

Here are some first attempts at different styles that either proved too messy or too incoherent. For example, the next two images were supposed to be both in the style of ..., yet they turned out completely different:

![nice](https://i.imgur.com/xHn1KQ0.jpg)
![not nice](https://i.imgur.com/xOBQY07.jpg)
![uggo](https://i.imgur.com/V5P5eoB.jpg)
![uggo2](https://i.imgur.com/Q8xS7jv.png)

### Advanced prompting:

Outside of the --ar command to set and aspect ratio and the --no command to add negative weights, I don't use any of the more advanced commands and tricks available for Midjourney, as they lead the results away from my intended "Goya" style.
The --no command however doesn't fix everything, I couldn't get rid of the plate:

![yum](https://i.imgur.com/yWDrF3J.png)

I'm however pleasently surprised by how well Midjourney handles art history tropes such as the pieta or the danse macabre:

![pieta](https://i.imgur.com/ru6HdKE.png)
![danse](https://i.imgur.com/AQpi0Zg.png)

### Banned words:

When it comes to art history tropes, Midjourney does however not allow me to create the severely wounded St. Sebastian.
The lists of banned words includes exactly would to expect, but needless to say there is a workaround for everything.
Such is the omission of the word "blood" in contrast to the banned "bloody", which inspires Midjourney tremendously and leads to most of my more abstract images:

![suggestive](https://i.imgur.com/k0GuNJ7.png)
![another](https://i.imgur.com/YR9r9FS.jpg)


## Editing

DaVinci Resolve's multiple timelines are very useful in creating a non-destructive workflow, where I could easily edit individual shots without messing up the master timeline.
Each shot is comprised of four to seven variations of one image that cycle through in a four frames per second.

![davinci](https://i.imgur.com/qfCKBZe.png)

## Final Thoughts

I'm happy with the final result and the speed at which I could finish the project. Over the course of the video, I managed more and more to connect the individual scenes and started to think more artistically. 

For potential future projects, I'd like to utilize style transfer techniques such as Ebsynth or Warpfusion to create videos similar to [Sagans](https://www.youtube.com/watch?v=3ApMSKql23I).
