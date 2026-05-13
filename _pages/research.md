---
title: "NRDG - Research"
layout: textlay
excerpt: "NRDG -- Research"
sitemap: false
permalink: /research/
---

# Research

Our work is devoted to advancing understanding of the brain through data-driven
discovery, focusing on the role of brain networks in a range of behaviors and
on how these networks change across the lifespan, through experience, and in
neurological and psychiatric diseases.

Our approach stems from a conviction that scientific progress requires not only
isolated discoveries but also integrative infrastructure and supportive
community practices enabling knowledge to be shared, verified, and built upon.
We take a highly collaborative approach, working with researchers across
complementary domains to translate advances in artificial intelligence and
machine learning into impactful insights about the brain.

Our commitment to transparent and reproducible science means that all of our
research outputs – from data and software, through publications and educational
materials – are openly available. This ensures that publicly funded research
benefits the broadest possible audience while maintaining potential for
clinical and commercial translation.

## Human Connectomics

Networks of brain regions and their joint activity give rise to coordinated
information processing and to the complex adaptive behavior that characterizes
human cognition. The proper function of brain networks is also crucial to
neurological, cognitive, and psychiatric health. Therefore, a better
understanding of brain networks is a major goal of contemporary neuroscience.
Diffusion MRI (dMRI) is the only currently available method to measure and
delineate white matter connections *in vivo* in a non-invasive matter.

We focus on a dMRI analysis approach known as ``tractometry''. This approach
uses dMRI measurements to assess the physical properties of long-range brain
connections within every individual. We develop and maintain cutting edge
methods to perform tractometry and we have established an integrative ecosystem
of software that implements all of the steps of tractometry: post-processing of
dMRI data, delineation of major white matter pathways, and modeling of the
tissue properties within them.

### Tools and publications:

{% for publi in site.data.publist %}
  {% if publi.connectomics == 1 %}

  {{ publi.title }} <br />
    <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
  {% endif %}

{% endfor %}


## Developing interpretable AI methods for neuroimaging

To make progress in addressing the range of disorders and conditions that
affect the aging human brain, including neurodegenerative disorders, it is
vital that we capitalize on the rapid advances that are happening in artificial
intelligence and machine learning. However, it is also crucial that we develop
tools that are transparent and amenable to interpretation.

### Tools and publications:

{% for publi in site.data.publist %}
  {% if publi.ai == 1 %}

  {{ publi.title }} <br />
    <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
  {% endif %}

{% endfor %}

## Building open-source infrastructure for reproducible neuroscience

We are embedded in a network of

### Tools and publications:

{% for publi in site.data.publist %}
  {% if publi.open == 1 %}

  {{ publi.title }} <br />
    <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
  {% endif %}

{% endfor %}



<!-- This is how/where to put in images>
<!--![]({{ site.url }}{{ site.baseurl }}/images/respic/layers_real.jpg){: style="width: 300px; float: right; border: 10px"}-->
