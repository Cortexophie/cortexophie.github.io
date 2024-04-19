---
title: Temporal Limitations of the Standard Leaky Integrate and Fire Model
authors:
- Liya Merzon
- Tatiana Malevich
- Georgiy Zhulikov
- Sofia Krasovskaya
- W. Joseph MacInnes
date: '2020-01-01'
publishDate: '2024-04-19T12:33:30.808150Z'
publication_types:
- article-journal
publication: '*Brain Sciences*'
doi: 10.3390/brainsci10010016
abstract: Itti and Koch&rsquo;s Saliency Model has been used extensively to simulate
  fixation selection in a variety of tasks from visual search to simple reaction times.
  Although the Saliency Model has been tested for its spatial prediction of fixations
  in visual salience, it has not been well tested for their temporal accuracy. Visual
  tasks, like search, invariably result in a positively skewed distribution of saccadic
  reaction times over large numbers of samples, yet we show that the leaky integrate
  and fire (LIF) neuronal model included in the classic implementation of the model
  tends to produce a distribution shifted to shorter fixations (in comparison with
  human data). Further, while parameter optimization using a genetic algorithm and
  Nelder&ndash;Mead method does improve the fit of the resulting distribution, it
  is still unable to match temporal distributions of human responses in a visual task.
  Analysis of times for individual images reveal that the LIF algorithm produces initial
  fixation durations that are fixed instead of a sample from a distribution (as in
  the human case). Only by aggregating responses over many input images do they result
  in a distribution, although the form of this distribution still depends on the input
  images used to create it and not on internal model variability.
tags:
- leaky integrate and fire model
- saccade generation
- salience model
- visual search
links:
- name: URL
  url: https://www.mdpi.com/2076-3425/10/1/16
---
