---
title: Team
redirect_from:
  - /lab-members
  - /alums
  - /mascots
  - /staff
  - /trainees
---

# <i class="fas fa-users"></i>Team

Our lab is made up of a highly engaged and collaborative team of researchers.
We recognize that diverse teams do better research.
We foster an environment where team members are treated equally, and where we respect and admire our differences.
The team includes postdocs, students at all levels, staff, and our lab mascots.

{% capture html %}
{% include team-list.html role="pi" group="" %}
{% include team-list.html role="postdoc" group="" %}
{% include team-list.html role="phd" group="" %}
{% include team-list.html role="undergrad" group="" %}
{% include team-list.html role="programmer" group="" %}
{% include team-list.html role="mascot" group="" %}
{% endcapture %}

{% include centerer.html html=html %}

<!-- section break -->

We work with a wide range of outstanding groups from around the world, and we're always on the lookout for new and unique perspectives.
We want to push the frontier of data science and train the next generation of data scientists.

{%
  include big-link.html
  icon="fas fa-hands-helping"
  text="Join the Team"
  link="join"
%}{:.center}

<!-- section break -->

## Alumni

Gone but never forgotten.
These are past lab members who have moved on to the [Childhood Cancer Data Lab](https://www.alexslemonade.org/data-lab), other school programs, new jobs, or elsewhere.
They have all made lasting contributions to science and to our hearts. ❤️

{% capture html %}
{% include team-list.html role="pi" group="alum" mini="true" %}
{% include team-list.html role="postdoc" group="alum" mini="true" %}
{% include team-list.html role="phd" group="alum" mini="true" %}
{% include team-list.html role="undergrad" group="alum" mini="true" %}
{% include team-list.html role="programmer" group="alum" mini="true" %}
{% include team-list.html role="mascot" group="alum" mini="true" %}
{% endcapture %}

{% include centerer.html html=html %}

<!-- section break -->

## Funding

{:.center}
Our work is made possible by funding from several organizations.

{%
  include gallery.html
  flat="true"
  fit="false"

  image1="images/team/gordon-and-betty-moore-foundation.png"
  link1="https://www.moore.org/"
  tooltip1="Gordon and Betty Moore Foundation"

  image2="images/team/national-cancer-institute.png"
  link2="https://www.cancer.gov/"
  tooltip2="National Cancer Institute"

  image3="images/team/alex's-lemonade-stand-foundation-for-childhood-cancer.png"
  link3="https://www.alexslemonade.org/"
  tooltip3="Alex's Lemonade Stand Foundation for Childhood Cancer"

  image4="images/team/chan-zuckerberg-initiative.png"
  link4="https://chanzuckerberg.com/"
  tooltip4="Chan Zuckerberg Initiative"

  image5="images/team/cystic-fibrosis-foundation.png"
  link5="https://www.cff.org/"
  tooltip5="Cystic Fibrosis Foundation"

  image6="images/team/alfred-p-sloan-foundation.png"
  link6="https://sloan.org/"
  tooltip6="Alfred P. Sloan Foundation"

  image7="images/team/national-human-genome-research-institute.png"
  link7="https://www.genome.gov/"
  tooltip7="National Human Genome Research Institute"

  image8="images/team/national-heart-lung-and-blood-institute.png"
  link8="https://www.nhlbi.nih.gov/"
  tooltip8="National Heart, Lung, and Blood Institute"

  image9="images/team/national-institute-of-neurological-disorders-and-stroke.png"
  link9="https://www.ninds.nih.gov/"
  tooltip9="National Institute of Neurological Disorders and Stroke"
%}

<!-- section break -->

{%
  include figure.html
  image="images/team/group-photo-2.jpg"
  description="The Greene Lab in their natural Philadelphia habitat"
  width="100%"
%}
