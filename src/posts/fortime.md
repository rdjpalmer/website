---
layout: post
title: "For Time"
date: 2020-04-13
slug: "/fortime"
description: >-
  Fullscreen, retro sci-fi video game style countdown clock.
---

## TL;DR

Here's <a href="https://www.fortime.co" target="_blank" rel="noopener noreferrer">For Time</a>. A sci-fi retro countdown timer meant for full screening.

<figure>
  <img src="images/fortime.jpg" alt="For Time displayed on a TV" />
</figure>

## Back story

I've been missing the adrenaline caused by <a href="http://www.theyardpeckham.com/#textboxupye0si" target="_blank" rel="noopener noreferrer">Gareth</a> setting the countdown clock for the imminent workout. The impending doom caused by the beeps, the final warning before having to sweat your heart out for the next ten minutes.

Me & Lyd have been trying to keep ourselves healthy since the UK went into lockdown by doing circuits around our living room (so many press-ups <span role="img" aria-label="sob">😭</span>), but one thing that was missing was the clock staring you in the face saying "you're not even half way through yet, keep going!"

I'm sure you're thinking—as did I—that you can use your phone. Or Google would return _exactly the right thing_. You'd be correct on both. But neither are very fun, and none of them are nice enough that you _want_ to be looking at them at all.

I thought I'd give it a go, and build my own. A classic Software Engineer thing to do. But here we go:

<a href="https://www.fortime.co" target="_blank" rel="noopener noreferrer">For Time</a>. A sci-fi retro countdown timer meant for full screening.

## Details, details

"For time" is an expression used in the CrossFit world for a work out against the clock.

For Time (the website this post is about) turned out to be more art than engineering. It's the first time in awhile I've just let things happen. I was not consciously designing For Time in this aesthetic. It was pure chance I started to make the time display in neon, which led me to make it Tron-esk.

For the inspiration that started it all off, you'll find a couple of Codepens below.

For Time is open source <a href="https://github.com/rdjpalmer/fortime" target="_blank" rel="noopener noreferrer">on GitHub</a>, with a concepts directory with some early experimentation with the neon effect in the last codepen.

Important to note that Firefox has a hard time rendering the floor animation via canvas. Safari seemingly is unsure about when to use the blend mode on the gradient (it works for me, but not for my house mate) and at some resolutions (mostly if you have your screen set to a _scaled_ resolution) the frame rate drops quite a bit. Considering this is an experiment more than anything else, I think it's okay. You should've seen the performance before I switched it to canvas <span role="img" aria-label="wink">😉</span>.

It's made with <a href="https://svelte.dev/" target="_blank"  rel="noopener noreferrer">Svelte</a>, after I thought it was about time I tried something different to (<a href="https://preactjs.com/" target="_blank" rel="noopener noreferrer">p</a>)<a href="https://reactjs.org/" target="_blank" rel="noopener noreferrer">react</a>. From my very brief foray into Svelte, I can only report back good things.

<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

## Codepens

<div class="codepen-container">
  <p class="codepen" data-height="400" data-theme-id="light" data-default-tab="result" data-user="al-ro" data-slug-hash="BaaBage" data-pen-title="NEON LOVE">
    <span>See the Pen <a href="https://codepen.io/al-ro/pen/BaaBage">
    NEON LOVE</a> by al-ro (<a href="https://codepen.io/al-ro">@al-ro</a>)
    on <a href="https://codepen.io">CodePen</a>.</span>
  </p>
</div>

<div class="codepen-container">
  <p class="codepen" data-height="400" data-theme-id="light" data-default-tab="result" data-user="giana" data-slug-hash="qmKNeE" data-pen-title="CSS-only shimmering neon text">
    <span>See the Pen <a href="https://codepen.io/giana/pen/qmKNeE">
    CSS-only shimmering neon text</a> by Giana (<a href="https://codepen.io/giana">@giana</a>)
    on <a href="https://codepen.io">CodePen</a>.</span>
  </p>
</div>
