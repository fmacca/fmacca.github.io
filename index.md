---
layout: default
title: Home
---

# Hi, I'm {{ site.title }}

{{ site.description }}

Welcome to my CV!
[Download my CV](attached_files/Francesco_Maccarini_CV_Short_Web.pdf)

## About Me

I am a highly motivated and detail-oriented professional with {{ site.experience_years }} years of experience. I specialize in {{ site.skills }}.

## Experience

{% include experience.html %}

## Skills

{% include skills.html %}

## Projects

{% include projects.html %}

## Publications

- [Dinh-Viet-Toan Le, Mathieu Giraud, Florence Levé, Francesco Maccarini. A Corpus Describing Orchestral Texture in First Movements of Classical and Early-Romantic Symphonies. Digital Libraries for Musicology (DLfM 2022), 2022, Prague, Czech Republic. pp.22-35. ⟨hal-03663112⟩](https://dl.acm.org/doi/abs/10.1145/3543882.3543884)

## Contact

Let's connect! You can reach out to me through the following channels:

- Email: {{ site.email }}
- Phone: {{ site.phone }}
- LinkedIn: [{{ site.social_links[0].title }}]({{ site.social_links[0].url }})
- GitHub: [{{ site.social_links[1].title }}]({{ site.social_links[1].url }})

Thank you for visiting my CV. I look forward to hearing from you!
