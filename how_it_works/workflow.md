# Overview

We decided to split the project implementation in phases. This will allow us to better focus our resources on more important issues, that should be solved in each phase.

# Foundation (Phase I)

## Overview

The first phase is where we define the foundations of the game. Roughly, this is where we describe the game we want to create.

Roughly, what we need to have ready on this phase is:

- Game name (tentative)
- Game genre
- Game principles
- Game objectives
  - Identification of target audience
  - Main platforms
- Base game concept: 
  - Base gameplay
  - Base storyline

As you can see, those are very fundamental and basic aspects of the game. And those have already been done for Hacker Experience 2.

Before proceeding, let's explain the word *base*. Having a *base* gameplay, or *base* storyline is intended to serve as template, or direction, for the next phases, where contributors will extend those concepts.

This is the reason we say HE2 will be a hacking game, even if we are unsure about how the final game design will be. We've shaped our basic concepts to match the one of a hacking game.

## Rationale

Phase I serves the main purpose of defining what the game is, and what it will be about. As long as the upcoming changes extend the concepts on the same basis, the final product will be shaped by these foundations.

# Concepts (Phase II)

## Overview

The Phase II aims to further expand the base gameplay and storyline defined on Phase I. By the end of Phase II, we are expected to have a set of *core* concepts.

- Core game concept
  - Core gameplay
  - Core storyline

Notice the subtle change from *base* to *core*. On Phase II, we firm game mechanics that make a good part of the game.

Core game mechanics include features we would like to see *still* on the first few releases of the game (within 3-6 months of publication). Game mechanics that are on the Roadmap, but would take too long to implement still can make as core, but it needs to be tagged as "Wishlist" or "Future".

## Rationale

With a predefined set of core concepts, we now have something to expect as the final version. Phase I shapes the way we want to follow, and Phase II paves it. 

That way, if by the end of Phase II we do not like the set of features we have, then we know very early that the final product probably will suck. 

The reverse is true: If we like the game described on Phase II, no matter how long it takes to finish the implementation, we know that the final product will be just as awesome - as long as executed properly.

**NOTE:** This is one of the most important phases, and the one we actively need your input. After all, this is the phase that shapes the entire gameplay, so this is the best time to share your ideas/suggestions.

Also note that, while most concepts are created during Phase II, *it is okay to suggest features after Phase II has been closed.* That's why Phase II and Phase III go on forever.

# Game Design (Phase III)

## Overview

The Phase III has the sole purpose of validating the concepts we've created on Phase I and II. This is the time our awesome Game Designers open their spreadsheets and do weird calculations.

During this phase (which takes very long) they work relentlessly on making sure there are no loopholes or disbalance on features.

By the way, *balance* is the key word during this phase. And it is not a tiny bit easy.

## Rationale

On Phase II we *described* the game we want, on lay terms. Of course we gave some thought when we were writing those concepts, but not with the ideal depth or context.

Now, on Phase III, we have the whole game described and we can analyze each feature in details.

Whenever a feature is rejected, or deemed impracticable, we go back to Phase II and check if its possible to rewrite this feature on a better way. 

Phase III happens concurrently with next phases.

# Technical Planning (Phase IV)

## Overview

On this phase, we choose the technology stack we are going to use. We take in consideration how many requests per second we plan to handle, and how we will be able to scale it out.

Another important thing done here is to define how many software will need to be built. Intuitively you might think one, but HE2 is a client-server software and therefore needs at least two different applications. In fact, since we expect to support Mobile (iOS, Android) and Terminal interfaces, we will need at least 5 different software.

This Phase is already completed for HE2, but a review would be nice.

## Rationale

This is a quick, but very important phase in which we decide the tools and services that best handle the game expected audience.

If the audience happens to be much bigger than expected, we need to have a way to scale out effortlessly. If it's much smaller than expected, it's ideal that we can shut down some services to save on resources.

The following Phases apply on each software outlined here.

# Software Planning (Phase V)

## Overview

This phase marks the beginning of the software. We study at better length what it is supposed to do, what to expect and how its interface should look (if applicable).

## Rationale

Really not much needs to be said here, I guess. Those who work with software knows exactly how this phase is.

It is a quick but necessary step to better account for potential breaking mistakes, and to make sure we are developing something we actually need.

However, given the nature of Phase VI, it's Okay to relax a bit on software planning. We expect to make constant planning through Phase VI.

# Evolutionary Prototyping (Phase VI)

## Overview

This is where the actual development takes place. This phase includes a loop of steps from building and evaluating a prototype until it is deemed acceptable by the end user. In the mean time, we get constant feedback from the community on ways to improve the software.

Usually, the non-technical user will only be able to give feedback on user experience and user interface, but we look forward for feedback on performance, security and overal quality of software as well.

This is an endless Phase if we see maintenance as part of prototyping.

## Rationale

Choosing evolutionary prototyping as lifecycle model was quite straightforward. It makes a lot of sense for open source software development.

- It allow developers to focus on specific areas of the application, instead of having to understand the application as a whole.
- It allow players to see how the game is shaping, give early feedback and potentially share new features.

Furthermore, we see software as a naturally evolving "beast".

We understand that it might take a while to loop (release) for the first time, since it involves the whole system working, building, testing and deploying itself, so we are OK with a delay to deliver the first cycle.

After the first cycle, however, we expect to naturally flow on the automatic deployment spectrum.


