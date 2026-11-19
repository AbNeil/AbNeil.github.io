---
layout: page
permalink: /blog/
title: Blog
nav: true
nav_order: 1
_styles: |
  .post-header {
    display: none;
  }
  .blog-article {
    max-width: 760px;
    margin: 1.5rem auto 3rem;
    line-height: 1.75;
  }
  .blog-article h1 {
    font-size: 2rem;
    line-height: 1.25;
    font-weight: 600;
    margin-bottom: 0.4rem;
  }
  .blog-article h2 {
    font-size: 1.3rem;
    font-weight: 600;
    margin-top: 2rem;
    margin-bottom: 0.8rem;
  }
  .blog-subtitle {
    font-size: 1.15rem;
    margin-bottom: 0.5rem;
  }
  .blog-byline {
    font-size: 0.9rem;
    color: var(--global-text-color-light);
    margin-bottom: 2rem;
  }
---

<div class="blog-article" markdown="1">

# The Boy Who Memorised Everything

<p class="blog-subtitle"><em>Rethinking LLM hallucinations</em></p>

<p class="blog-byline">19 November 2026 · Abdul Wahid (@Neeil)</p>

## The boy at the back of the class

Let me tell you about a boy. You probably went to school with him. Some of you, if we're being honest, *were* him.

He sits near the back of a classroom where everyone else seems to be doing exceptionally well. They answer questions without blinking. They understand things he can only nod along to. And every day, he feels the gap a little more.

So he makes a plan. If he can't understand everything, he will *memorise* everything. Every answer, every phrase the teacher likes, every possible question he might be asked. He studies late into the night, not to learn, but to never be caught out again.

And for a while, it works beautifully.

Give this boy a stage and he lights up. He talks, he explains, he performs. He uses the right words in the right order, and people are impressed. For the first time, he isn't the one at the back. He's the one at the front.

Then one day, someone in the audience raises a hand and asks a question he didn't prepare for.

There is a pause. You can almost hear the clock on the wall.

The boy has a choice. He can say the four most frightening words a performer knows: *“I don't know that.”* Or he can keep talking.

He keeps talking.

He pulls together fragments of things he half-remembers, joins them with confidence, and builds a story. It sounds right. It has the rhythm of truth. It is, unfortunately, almost entirely made up. And because the room is still nodding, he goes further, adding details to cover the gaps in the details he just invented.

I've been a computer scientist long enough to recognise this boy. Not from my school days (although, no comment), but from my screen. Because for a few years, this boy was the most talked-about piece of software on the planet.

We called what he did **hallucination**.

## A word borrowed in a hurry

Here's something that has always bothered me. “Hallucination” is a dramatic word. It sounds clinical, even a little mystical, as if the machine slipped into a fever dream and saw things that weren't there.

But nobody sat down and carefully defined it for language models. The word drifted in from older corners of the field. Computer vision researchers used it around the turn of the millennium for systems that “imagined” detail in blurry images, and it was meant as a *good* thing back then. Later, machine translation researchers picked it up for systems that produced fluent sentences with no connection to the source text. By the time chatbots arrived, the word was simply lying around, and we grabbed it.

The trouble is that a borrowed word carries borrowed assumptions. Calling it a hallucination makes it sound like a strange glitch in perception, something spooky and hard to explain. I don't think it was either of those things. I think it was much more ordinary, and much more human.

I think it was the boy at the back of the class.

## Memorising the answers, missing the subject

Early large language models were trained to do one thing extraordinarily well: predict the next word. Feed them a mountain of text and they learn what tends to follow what. Not *why*. Just *what*.

That is exactly the boy's strategy. He knows what a good answer sounds like. He knows which words appear near which other words, which phrases teachers reward, how a confident explanation is shaped. What he never built was the foundation underneath: the context of a topic, its history, the evidence behind it, how it connects to everything else, and what you can sensibly conclude from it.

When I first started thinking about this, my instinct was to say the models simply hadn't been trained enough. Give the boy more time in the library and he'll be fine. But I've changed my mind. Bigger models, trained on far more data, still made things up. The boy didn't need more hours of memorising. He needed a different kind of learning.

Because here's the uncomfortable part. Memorisation works brilliantly inside the boundaries of what you memorised. It's the edges that get you. Ask the boy something one step outside his script and he has nothing to stand on, only the *shape* of an answer. So he fills that shape with whatever fits.

And a well-shaped answer filled with whatever fits is, more or less, the definition of a hallucination.

## The pressure to impress

There's a second half to the boy's story that matters even more than the memorising. *Why* does he keep talking when he's stuck?

Because the room rewards him for it. Silence feels like failure. “I don't know” feels like being sent back to the last row. A confident wrong answer at least has a chance of being right, or of nobody noticing.

It turns out the machines were raised in the same kind of classroom. In 2025, a group of researchers at OpenAI published a paper with the refreshingly blunt title [*Why Language Models Hallucinate*](https://openai.com/index/why-language-models-hallucinate/). Their argument was that training and evaluation reward guessing over admitting uncertainty. Most benchmarks score a model on how many answers it gets right. A guess might land; “I don't know” is a guaranteed zero.

They even used the same metaphor I had been carrying around: the model as a student facing a hard exam, guessing because guessing improves the score.

I'll admit I laughed when I read that. Not because it was funny, but because it was so painfully familiar. We built machines, put them in a classroom, graded them only on getting answers right, and then acted surprised when they learned to bluff.

We didn't build a liar. We built a very good test-taker.

## Where the story breaks

Every good analogy has a crack in it, and I'd be bluffing myself if I didn't show you this one.

The boy *knows* he's stuck. That moment of panic, the clock ticking, the decision to keep going: that's him choosing to cover up. There is intent there, and probably a little guilt on the walk home.

The early models had no such moment. No panic, no choice, no walk home. They didn't know they were stuck, because they didn't know anything in the way the boy does. The next word simply came out, as smoothly as the last one.

There's a better word for this, and it comes from neuroscience: **confabulation**. Some patients with certain kinds of memory damage will fill the gaps in their memory with invented stories, and they aren't lying. They genuinely believe what they're saying. The story feels true from the inside because there is nothing inside to tell them otherwise.

Now let me indulge the science fiction fan in me for a moment.

Imagine a ship's computer, a few hundred years from now, guiding a crew through deep space. The navigator asks for the safest route past an uncharted moon. The computer has never seen this moon. It has seen a thousand moons *like* it. So, in a calm and reassuring voice, it describes a route, with coordinates, timings and a little joke about the view.

It isn't lying. It isn't malfunctioning. It's doing exactly what it was built to do: produce the most plausible-sounding answer. Nobody ever taught it that “I have never seen this moon” was an acceptable reply.

That's not a horror story about evil machines. In some ways it's sadder than that. It's a story about a machine that was never allowed to say it was lost.

## What the boy needed all along

So what would have saved the boy?

Not more memorising. He'd already done more of that than anyone. He needed two things that no amount of late-night cramming could give him.

The first was **understanding**: the slow, unglamorous work of learning where ideas come from, how they connect, and what they actually imply. That's the difference between knowing the words of an answer and knowing the answer. For machines, this looks like grounding: tying what they say to real sources, real evidence and real reasoning, rather than to the rhythm of language alone.

The second was **permission**. Permission to raise his own hand and say, “I don't know, but here's how I'd find out.” A classroom that treats that sentence as a sign of strength rather than failure. For machines, that means building tests and training that stop punishing honest uncertainty, and stop rewarding the lucky bluff.

I find something quietly hopeful in this. The problem we called hallucination was never really a ghost in the machine. It was a mirror. We trained these systems the way we too often train people: to perform, to impress, to always have an answer ready. And they learned that lesson perfectly.

Maybe the next lesson is one we could all stand to relearn.

The smartest person in the room isn't the one with an answer for everything. It's the one brave enough to say, “I'm not sure,” and curious enough to find out.

The boy at the back of the class would have done just fine, if anyone had told him that.

</div>
