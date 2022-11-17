---
layout: post
title:  "Highlights"
date:   2022-11-17 04:52:00
---


Here's me picking on a decked out guitar I put together.

<video src="https://user-images.githubusercontent.com/6301308/202567942-3a1086b3-eea1-48c6-a88f-7b19d3b8c279.mov" data-canonical-src="https://user-images.githubusercontent.com/6301308/202567942-3a1086b3-eea1-48c6-a88f-7b19d3b8c279.mov" controls="controls" class="d-block rounded-bottom-2 border-top width-fit" style="max-height:640px;">
</video>

It has a mesh of LEDs overlaying the fretboard.  I sent notes to it that I computed on my computer in realtime.
<video src="https://user-images.githubusercontent.com/6301308/202567957-3db9d9f2-660f-400c-8998-d4e54d3f0d09.mov" data-canonical-src="https://user-images.githubusercontent.com/6301308/202567957-3db9d9f2-660f-400c-8998-d4e54d3f0d09.mov" controls="controls" class="d-block rounded-bottom-2 border-top width-fit" style="max-height:640px;">
</video>

- Instead of having to keep looking at a piece of sheet music to understand where you are in a song, you could
- just send the bass notes of the chord progression over at the proper times, which is mostly what you need.  Then you can
- play your lines over the top of the rendered bass, and see a color corresponding to the solfege of the note in your line.
<video src="https://user-images.githubusercontent.com/6301308/202567991-a5eff804-f163-4f96-8644-1036c81fe85b.mov" data-canonical-src="https://user-images.githubusercontent.com/6301308/202567991-a5eff804-f163-4f96-8644-1036c81fe85b.mov" controls="controls" class="d-block rounded-bottom-2 border-top width-fit" style="max-height:640px;">
</video>

- Choosing notes on an instrument is really inhuman if you think about it, so I decided to write software to decode the tone you
- were singing with your voice, and use that in lieu of notes you played on your guitar.
<video src="https://user-images.githubusercontent.com/6301308/202568016-d87efb6e-6005-423f-94a5-2c043c591938.mov" data-canonical-src="https://user-images.githubusercontent.com/6301308/202568016-d87efb6e-6005-423f-94a5-2c043c591938.mov" controls="controls" class="d-block rounded-bottom-2 border-top width-fit" style="max-height:640px;">
</video>

- I have no idea what I was doing here but it sure looks complicated...
<video src="https://user-images.githubusercontent.com/6301308/202568030-a4ef6172-b2de-4f93-be8d-597b3d2817a4.mov" data-canonical-src="https://user-images.githubusercontent.com/6301308/202568030-a4ef6172-b2de-4f93-be8d-597b3d2817a4.mov" controls="controls" class="d-block rounded-bottom-2 border-top width-fit" style="max-height:640px;">
</video>

- Before I thought of using an LED mesh on a real guitar though, I decided to simulate a guitar interface on an iPad.  In my
- eyes, that was way more powerful, because I could arrange notes however I wanted and build any instrument imaginable... but 
- in reality it was kind of annoying having to play on a completely flat surface all the time.
<video src="https://user-images.githubusercontent.com/6301308/202568047-259ff329-21aa-4fdb-87b1-5171c3f3dd4a.mov" data-canonical-src="https://user-images.githubusercontent.com/6301308/202568047-259ff329-21aa-4fdb-87b1-5171c3f3dd4a.mov" controls="controls" class="d-block rounded-bottom-2 border-top width-fit" style="max-height:640px;">
</video>

- I love working backwards when solving problems, so I wanted to do the same thing when playing these musical games over songs.
- Slowing things down is also great, in order to give your brain time to process all this information.  I was under the impression
- that by practicing at higher speeds, playing at a regular tempo would be a piece of cake.
<video src="https://user-images.githubusercontent.com/6301308/202568068-f816ffd0-ef98-4ab4-8710-04bc711f32b8.mov" data-canonical-src="https://user-images.githubusercontent.com/6301308/202568068-f816ffd0-ef98-4ab4-8710-04bc711f32b8.mov" controls="controls" class="d-block rounded-bottom-2 border-top width-fit" style="max-height:640px;">
</video>

- I hate sheet music, and like real recordings, so I wanted to extract the information necessary to do this from things that sounded good.
<video src="https://user-images.githubusercontent.com/6301308/202568093-32c1e432-da24-463d-ba65-f95b4074e056.mov" data-canonical-src="https://user-images.githubusercontent.com/6301308/202568093-32c1e432-da24-463d-ba65-f95b4074e056.mov" controls="controls" class="d-block rounded-bottom-2 border-top width-fit" style="max-height:640px;">
</video>

- Key centers are important, but they can change frequently, especially in jazz, so I wanted a robust method to estimate them with software.
<video src="https://user-images.githubusercontent.com/6301308/202568104-65aa5675-169c-4f41-9e90-bd75bd0f77dc.mov" data-canonical-src="https://user-images.githubusercontent.com/6301308/202568104-65aa5675-169c-4f41-9e90-bd75bd0f77dc.mov" controls="controls" class="d-block rounded-bottom-2 border-top width-fit" style="max-height:640px;">
</video>

- I didn't want to loop over measures, I wanted to loop over meaningful things like phrases, verses, choruses, ... so I used a model
- that could help me achieve that.
<video src="https://user-images.githubusercontent.com/6301308/202568125-8e916b7c-6394-4d31-8d7a-6fa249467f5e.mov" data-canonical-src="https://user-images.githubusercontent.com/6301308/202568125-8e916b7c-6394-4d31-8d7a-6fa249467f5e.mov" controls="controls" class="d-block rounded-bottom-2 border-top width-fit" style="max-height:640px;">
</video>

- Of course, not all songs keep the same tempo throughout, but I still wanted to automatically produce a "sheet music like"
- representation of them.
<video src="https://user-images.githubusercontent.com/6301308/202568141-d26db088-8013-4332-9b59-0cf8a8bf0551.mov" data-canonical-src="https://user-images.githubusercontent.com/6301308/202568141-d26db088-8013-4332-9b59-0cf8a8bf0551.mov" controls="controls" class="d-block rounded-bottom-2 border-top width-fit" style="max-height:640px;">
</video>

- I was reallly a perfectionist about rhythm - I wanted to be able to loop over a phrase 100 times, and get into
- a trance-like state, so I didn't want any abrupt things going on musically.
<video src="https://user-images.githubusercontent.com/6301308/202568157-f0309ce6-b5a2-45bd-8de5-3081d7f71773.mov" data-canonical-src="https://user-images.githubusercontent.com/6301308/202568157-f0309ce6-b5a2-45bd-8de5-3081d7f71773.mov" controls="controls" class="d-block rounded-bottom-2 border-top width-fit" style="max-height:640px;">
</video>


- This one didn't end up being too useful, but it was kind of cool... I converted a vocal signal into a Hertz timeseries
- and fed it into a synthesizer
<video src="https://user-images.githubusercontent.com/6301308/202568174-a3233659-aa18-4edf-b108-94e0006e54fa.mov" data-canonical-src="https://user-images.githubusercontent.com/6301308/202568174-a3233659-aa18-4edf-b108-94e0006e54fa.mov" controls="controls" class="d-block rounded-bottom-2 border-top width-fit" style="max-height:640px;">
</video>

- Here we see that the software representation of the automatically transcribed song could be rendered to sheet music,
- producing a jazz "lead sheet"-like artifact.
<video src="https://user-images.githubusercontent.com/6301308/202568190-f66bd058-a586-4c95-b5ad-88458af53a7a.mov" data-canonical-src="https://user-images.githubusercontent.com/6301308/202568190-f66bd058-a586-4c95-b5ad-88458af53a7a.mov" controls="controls" class="d-block rounded-bottom-2 border-top width-fit" style="max-height:640px;">
</video>

- If we view the brain as a machine-learning model, could we create a machine-learning platform with software
- that could optimize the performance of certain musical tasks?
<video src="https://user-images.githubusercontent.com/6301308/202568205-e56e5f31-45ba-4477-9a7f-922de86a42dd.mov" data-canonical-src="https://user-images.githubusercontent.com/6301308/202568205-e56e5f31-45ba-4477-9a7f-922de86a42dd.mov" controls="controls" class="d-block rounded-bottom-2 border-top width-fit" style="max-height:640px;">
</video>

- timeseries classification
<video src="https://user-images.githubusercontent.com/6301308/202568225-3bfc8742-3cd7-42c5-9bb7-75b27a8e9acb.mov" data-canonical-src="https://user-images.githubusercontent.com/6301308/202568225-3bfc8742-3cd7-42c5-9bb7-75b27a8e9acb.mov" controls="controls" class="d-block rounded-bottom-2 border-top width-fit" style="max-height:640px;">
</video>

- timeseries prediction
<video src="https://user-images.githubusercontent.com/6301308/202568245-4347309f-3a62-45be-aa35-d023fe6b3d54.mov" data-canonical-src="https://user-images.githubusercontent.com/6301308/202568245-4347309f-3a62-45be-aa35-d023fe6b3d54.mov" controls="controls" class="d-block rounded-bottom-2 border-top width-fit" style="max-height:640px;">
</video>

- parsing
<video src="https://user-images.githubusercontent.com/6301308/202568256-fff6f3fc-ed73-44ae-a8de-70415db1eb37.mov" data-canonical-src="https://user-images.githubusercontent.com/6301308/202568256-fff6f3fc-ed73-44ae-a8de-70415db1eb37.mov" controls="controls" class="d-block rounded-bottom-2 border-top width-fit" style="max-height:640px;">
</video>

- deriving
<video src="https://user-images.githubusercontent.com/6301308/202568270-67fd74e8-6f96-45ee-92c3-913771fd1fa5.mov" data-canonical-src="https://user-images.githubusercontent.com/6301308/202568270-67fd74e8-6f96-45ee-92c3-913771fd1fa5.mov" controls="controls" class="d-block rounded-bottom-2 border-top width-fit" style="max-height:640px;">
</video>




