---
title: Publications
nav:
  order: 1
  tooltip: Published works
---

# {% include icon.html icon="fa-solid fa-microscope" %}Publications

To dive into some of our main research topics, hit the buttons below! (Page update may take a few seconds)
<br>

{%
  include button.html
  icon="fa-solid fa-brain"
  text="basal ganglia"
  link="?search=tag:basal ganglia"
%}

{%
  include button.html
  icon="fa-solid fa-circle-nodes"
  text="network theory"
  link="?search=tag:network theory"
%}



{% include section.html %}

{%
  include button.html
  icon="fa-brands fa-google"
  text="Google Scholar"
  link="https://scholar.google.co.uk/citations?hl=en&user=AKR7P-4AAAAJ&view_op=list_works&sortby=pubdate"
%}

{%
  include button.html
  icon="fa-solid fa-book-open"
  text="Pre-prints"  link="https://www.biorxiv.org/search/author1%3AMark%2BHumphries%2B%20text_abstract_title%3AManchester%2BNottingham%20text_abstract_title_flags%3Amatch-any%20numresults%3A10%20sort%3Arelevance-rank%20format_result%3Astandard"
%}

{% include section.html %}

## All

{% include search-box.html %}

{% include search-info.html %}

{% include list.html data="citations" component="citation" style="rich" %}