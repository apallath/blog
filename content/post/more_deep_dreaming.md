---
title: "More Deep Dreaming"
date: 2021-05-28
hero: /blog/images/fireworks_dream_hero.jpg
excerpt: Watching dreams evolve into hallucinations.
authors:
    - Akash Pallath
---

In my [last post](/blog/post/deep_dreaming), I shared some cool images that I made with Deep Dream.
This time, I updated the loss functions in my code, made some changes,
and generated deep dreams by iteratively running the Deep Dream algorithm
on images. I also made some videos showing the evolution of dreams (into 'hallucinations'). Here's what I got:

![College Hall](penn_dream_iter0.jpg)
*Another deep dream of College Hall at the University of Pennsylvania. Original image from Penn's public Flickr feed.*

{{< video "penn_evolution.mp4" "my-5" "1">}}

*Hallucination*

![Osaka](osaka_dream.jpg)
*Another deep dream of Dotonbori, Osaka, Japan at night.*

![Nomi](nomi_dream.jpg)
![Nomi2](nomi2_dream.jpg)
*Deep dreams of views of the countryside in Nomi-shi, Ishikawa, Japan.*

![NewYear](fireworks_dream_iter0.jpg)
*Deep dream of New Years' fireworks over the Delaware river between Philadelphia, PA and Camden, NJ.*

{{< video "fireworks_evolution.mp4" "my-5" "2">}}

*Hallucination*

Finally, my favorite:

{{< video "solvated_ubq_evolution.mp4" "my-5" "3">}}

*Evolution of a deep dream of a VMD snapshot of solvated ubiquitin.*

Check out the [code](https://github.com/apallath/generative_art) I used to make these images and movies on Github.
