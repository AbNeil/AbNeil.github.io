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
  .blog-article { scroll-margin-top: 90px; }
  .blog-index { max-width: 760px; margin: 1.5rem auto; padding-bottom: 1rem; border-bottom: 1px solid var(--global-divider-color); }
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

<div class="blog-index" markdown="1">

**Latest articles**

- [We Built Them in Our Image, Then Demanded They Be Better](#we-built-them-in-our-image-post) · 20 November 2026
- [The Boy Who Memorised Everything](#the-boy-who-memorised-everything-post) · 19 November 2026

</div>

<div id="we-built-them-in-our-image-post" class="blog-article" markdown="1">

# We Built Them in Our Image, Then Demanded They Be Better

<p class="blog-byline">20 November 2026 · Abdul Wahid (@Neeil)</p>

## The new intern 💼

Every office has had one. The new intern.

On day one, nobody really knows what they're good at, so they get the jobs nobody else wants. Fix the printer. Sort the spreadsheet from 2019. Take the meeting notes nobody will read. Answer the phone when it's *that* client.

And here's the funny part. We give the intern the most boring, most thankless work in the building, and then we expect them to do it perfectly. One typo in the notes and suddenly it's a story at lunch. “Did you see what the intern did?”

Meanwhile, the senior manager has sent the wrong attachment to the whole company three times this month. Nobody tells that story at lunch. That's just Dave having a busy week.

I've been thinking about the intern a lot lately, because I think we've hired a new one. It's not a person this time. It's the AI.

In my last post, [*The Boy Who Memorised Everything*](#the-boy-who-memorised-everything-post), I wrote about why early language models made things up. This time I want to turn the camera around and look at the people in the room. Us.

## One mistake and you're out ⚖️

This isn't just a feeling. Researchers have actually measured it.

In 2015, three researchers at the Wharton School published a study with a title that says it all: [*Algorithm Aversion: People Erroneously Avoid Algorithms after Seeing Them Err*](https://faculty.wharton.upenn.edu/wp-content/uploads/2016/11/20-Dietvorst-Simmons-Massey-2015.pdf). They let people watch either a human or a computer make predictions, then asked them which one they'd rather bet on.

The result? People lost faith in the computer much faster than in the human after seeing both make the *same* mistake. Even people who had just watched the computer beat the human still walked away from it.

Think about that for a second. The machine was better. Everyone could see it was better. But it slipped once, and that was it. The human slipped too, and got a pat on the back and a “we all have off days.”

That's the intern and Dave all over again.

We say “to err is human” like it's a gentle excuse. What we don't say out loud is the second half: *and only human*. Everyone else has to be perfect.

## An old habit with a new face

Here's the part I've been chewing on, and I want to be careful with it.

Humans have a long habit of deciding that someone or something is “less than” us. Once we've decided that, a pattern follows. We hand them the work we don't want to do. We watch them closely. And we judge them harder than we judge ourselves.

History has far too many examples of this done to people, and the harm was real and terrible. I am not saying a chatbot is in the same position as a human being who was treated that way. It isn't. Software doesn't suffer. People did.

But I do think the *instinct* is the same one, and it's worth noticing when it shows up again. Put something below you. Give it the jobs you'd never take. Then hold it to a standard you'd never meet.

If you've ever been the intern, you know exactly how that feels. And if that instinct can show up so easily with a machine, it's a good reminder to check where else it's quietly showing up in our own lives, with real people.

## Scared of it and expecting miracles

Now here's what makes me laugh, a little nervously.

On Monday, we're scared that AI is going to take all our jobs. On Tuesday, it gets a date wrong and we say it's useless. On Wednesday, we're scared again.

Pick one, people.

It's like being terrified that the new intern will take your job, while also complaining they can't work the coffee machine. Both can't be the whole story.

I think the fear and the demand for perfection come from the same place. If the machine has to be perfect to be useful, then every mistake it makes is proof that we're still needed. Every wrong answer is a small sigh of relief. “See? It's not that clever.”

I understand that feeling. I'm a computer scientist and I still feel it sometimes. But it's a strange way to measure anything. We're imperfect too, gloriously so. We forget names, we misread emails, we confidently give directions to places we've never been. (That last one might just be me.)

So we're judging the machine by a test we would fail ourselves.

## Room to be wrong 🤝

So what's the answer? It isn't to stop expecting good work from AI. The intern should still learn to fix the printer.

The answer is to build the same kind of safety net we already build for people. We don't trust a single person to get everything right, so we have second opinions, checklists, reviews and a colleague who says “hang on, are you sure?” Good teams work because they *expect* mistakes and plan for them, not because nobody ever makes one.

We can treat AI the same way. Check its work. Give it ways to say “I'm not sure.” Use it for what it's good at, and keep a human nearby for what it isn't. That's not lowering the bar. That's how every good team has always worked.

In my last post, I said the boy at the back of the class needed permission to say “I don't know.” I think the rest of us need permission too. Permission to share the work with something imperfect, without needing it to fail to feel safe, and without needing it to be perfect to feel impressed.

We built these machines in our own image, mistakes and all. Maybe the fairest thing we can do is judge them the way we'd like to be judged.

Gently. Honestly. And with a second pair of eyes.

Now if you'll excuse me, I need to go apologise to the printer. 🖨️

</div>

<hr>

<div id="the-boy-who-memorised-everything-post" class="blog-article" markdown="1">

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

Which raises an uncomfortable question about who set those rules in the first place, but [that’s a story for another post](#we-built-them-in-our-image-post).

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
