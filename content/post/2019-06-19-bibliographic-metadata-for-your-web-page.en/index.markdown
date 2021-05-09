---
title: Bibliographic Metadata for your web page
author: Peter Baumgartner
date: '2019-06-19'
lastmod: ~
categories:
  - app
  - bibliography
  - open-science
tags:
  - zotero
summary: 'With _Web 2.0_, we see a radical change in scholarly communication.
  This transition period poses problems for the researcher as the challenges have
  multiplied. On the one hand, there is a growing need to be present on different
  web channels  (blog, twitter, youtube, and much more). On the other hand, the more
  traditional ways of publications in high ranked peer review channels are still prevalent.
  I present in this post a workaround to fulfill both requirements at a certain level:
  Embed bibliographic metadata in your web pages so that they can be cited and count
  as a web publication.'
slug: bibliographic-metadata-for-your-web-page
bibliography: ["../../../static/media/references.bib"]
disable_comments: no
draft: no
---

With *Web 2.0*, we see a radical change in scholarly communication. On the one hand, there is a growing need for researchers to be present on different web channels (blog, twitter, youtube, and much more). On the other hand, the more traditional ways of publications in high ranked peer review channels are still prevalent. It is difficult for researchers to meet this twofold challenge at the same time: After all the day has only 24 hours!

## Double bind for ECRs

<figure>

[<img src="images/Logo-Euraxess-min.jpg" alt="EUROAXESS log" class="border shadow"/>](https://euraxess.ec.europa.eu/)

<figcaption>
<h4>

**Figure 1:** EURAXESS - Researchers in Motion is a unique pan-European initiative delivering information and support services to professional researchers.

</h4>
</figcaption>
</figure>

Especially for young researchers (so-called Early Career Researchers, or ECRs[^1] is this situation alarming and even existence-threatening. The find themselves in a double-bind: Should they more invest in traditional ways of career planning, or is it more promising to expand and foster their internet presence? I do not have a clear solution for myself. I think a transition period, the most secure strategy is to follow both paths.

> ECRs have both the most to gain and the most to lose from being at the forefront of changes to scholarly communications (Eve 2014; St. Louis 2015).

## COinS and Zotero

<figure>

[<img src="images/zotero-logo-long.png" alt="Logo Zotero" class="border shadow"/>](https://www.zotero.org/)

<figcaption>
<h4>

**Figure 2:** Zotero is a free, easy-to-use tool to help you collect, organize, cite, and share research.

</h4>
</figcaption>
</figure>

The only way I can think of to meet both challenges is to maximize the efficiency of *all* career moves. One of my aims with this blog on *Open Science Education* is to talk about technology supported new ways for research and publication to fulfill both requirements.

[<img src="images/zotero-logo-round-min.jpeg" alt="Logo Zotoro" class="floatright"/>](https://www.zotero.org/)With the following lines, I will show you how you can help your blog readers or website visitors to cite your posts and pages correctly and in way that they could count as a kind of publication.

My suggestion is

1.  to use the free research tool [Zotero](https://www.zotero.org/)
2.  to produce a specific HTML code (COinS = Context Objects in Spans) and
3.  inject this code into your web page.

[COinS](https://en.wikipedia.org/wiki/COinS) is a [microformat standard to embed bibliographic metadata](https://www.univie.ac.at/elib/index.php?title=COinS_Microfromat_Bibliographic_Metadata_for_Embedding_in_HTML) for Embedding in HTML. COinS include as HTML code all the information necessary to cite a publication correctly. It works for every type of publication (books, papers, web pages).

<figure>

[<img src="images/zotero-startpage-min.png" alt="Zotero Start Page" class="border shadow"/>](https://www.zotero.org/)

<figcaption>
<h4>

**Figure 3:** Zotero is designed to store, manage, and cite bibliographic references, such as books and articles. It is available for Mac, Windows, and Linux.

</h4>
</figcaption>
</figure>

There are [several possibilities to generate COinS](https://en.wikipedia.org/wiki/COinS#Client_tools), but I will focus on Zotero. I am not going into further details here, but [I have prepared a tutorial](%60r%20blogdown::shortcode(%22ref%22,%20%222019-06-19-how-to-produce-coins.md%22)%60) with images from all the necessary steps to produce, embed, and download [COinS](https://www.questia.com/magazine/1G1-161981672/coins-what-it-stands-for-context-objects-in-spans).

<div class="notices tip">

Visit my tutorial on [How to produce bibliographic metadata for your web page?](%60r%20blogdown::shortcode(%22ref%22,%20%222019-06-19-how-to-produce-coins.md%22)%60)

</div>

## References

<div id="refs" class="references csl-bib-body hanging-indent">

<div id="ref-eve_open_2014" class="csl-entry">

Eve, Martin Paul. 2014. *Open Access and the Humanities: Contexts, Controversies and the Future*. Cambridge: Cambridge University Press. <https://doi.org/10.1017/CBO9781316161012>.

</div>

<div id="ref-st._louis_open_2015" class="csl-entry">

St. Louis, Scott R. 2015. “Open Access and the Humanities: An Interview with Dr. Martin Paul Eve (Right to Research Coalition).” *The Right to Research Coalition Access to Research Is a Student Right*. <http://www.righttoresearch.org/blog/open-access-and-the-humanities-an-interview-with-d.shtml>.

</div>

</div>

[^1]: There are different definitions for ECRs around, varying how many years after a Ph.D. are included. The period starts from [4 years](https://blog.jobs.ac.uk/all-things-research/phd-ecr/) and goes to in some institutions to [10 years](https://blog.soton.ac.uk/athenaswan/ecrs/what-is-an-ecr/). A more detailed description of different research profile descriptors has the European Research Commission ([EURAXESS](https://euraxess.ec.europa.eu/europe/career-development/training-researchers/research-profiles-descriptors))
