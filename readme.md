------------------------------------------------------------------------

### Blee-LCNT:

### An Emacs-Centered Content Production and Self-Publication Framework

### 

<table data-border="0">
<tbody>
<tr class="odd">
<td>Document Number:</td>
<td>PLPC-180068   <a
href="/content/generated/doc.free/bystar/PLPC/180068/current/PLPC-180068.bib">[
.bib ]</a></td>
</tr>
<tr class="even">
<td>Version:</td>
<td>0.1</td>
</tr>
<tr class="odd">
<td>Dated:</td>
<td>December 6, 2025</td>
</tr>
<tr class="even">
<td>Group:</td>
<td>facilities</td>
</tr>
<tr class="odd">
<td>Primary URL:</td>
<td><a
href="https://emacsconf.org/2025/talks/blee-lcnt">https://emacsconf.org/2025/talks/blee-lcnt</a></td>
</tr>
<tr class="even">
<td>Federated Publications:</td>
<td><a href="http://bytopic/PLPC/180068">ByTopic</a> -- <a
href="http://bycontent/PLPC/180068">ByContent</a></td>
</tr>
<tr class="odd">
<td>AccessPage Revision:</td>
<td>This AccessPage was produced on December 05, 2025 at 12:05 PST
(-0800)</td>
</tr>
<tr class="even">
<td>Author(s):</td>
<td><a href="emacs@mohsen.1.banan.byname.net">Mohsen Banan --- محسن
بنان</a></td>
</tr>
</tbody>
</table>

AVAILABLE FORMATS  

-   [PDF](./pdf/c-180068-0.1-blee-lcnt_EmacsConf25-pres.pdf):
    -- -- Provides the document in Portable Document Format.
-   [HTML](./html/c-180068-blee-lcnt_EmacsConf25-pres-reveal-html/index.html):
    -- -- Displays the document as a web page.

AVAILABLE OTHER FORMS  

-   [Youtube](https://www.youtube.com/watch?v=RNnrKUbMlsY&t=1112s):
    -- -- .
-   [presArtEnFa.pdf](./pdf/c-180068-0.1-blee-lcnt_EmacsConf25-presArt-8.5x11.pdf):
    -- -- .
-   [presArtEnFa-html](./html/c-180068-blee-lcnt_EmacsConf25-presArt-html-html):
    -- -- .

SHORT DESCRIPTION  

In a sense this is yet another talk about how you can use Emacs to produce fancy presentations like this or write complex books and self-publish them. But our approach is fundamentally different.

Many talks at previous Emacs Conferences have described how Emacs and org-mode can be extended to facilitate content production by adding more to Emacs. Our approach is that of putting a smaller Emacs at the core of something bigger. That something bigger is an autonomy oriented digital ecosystem called "ByStar" which is uniformly built with a layer on top of Debian called BISOS (ByStar Internet Services OS).

At Emacs Conf-2024 the title of my talk was "About Blee" – https://emacsconf.org/2024/talks/blee. Blee (ByStar Libre-Halaal Emacs Environment) is that smaller Emacs packaging that positions Emacs at the core of BISOS and ByStar. BISOS and Blee are intertwined and ByStar is about autonomy oriented unified platforms for developing and delivering both internet services and software-service continuums.

This talk is about Content Production and Self-Publication capabilities of Blee and BISOS.

Blee-LCNT is LaTeX centric. The original text is always in COMEEGA-LaTeX – LaTeX augmented by Org-Mode. This is the inverse direction of exporting LaTeX from Org-Mode. For typesetting, the LaTeX syntax is far more powerful than org-mode. And with COMEEGA-LaTeX, you can also benefit from all that org-mode offers. The scope of Blee-LCNT is all types of content from presentations to videos to books to name-tags and business cards.

LaTeX to HTML translation is done with HeVeA. For presentation/screen-casting, the original text is then augmented in layers by images, audio voice-overs, screen captures, videos and captions. The Beamer LaTeX file is then processed by both LaTeX and HeVeA. LaTeX produced slides are then absorbed in html by HeVeA as images. HeVeA output is destined to be dispensed by Reveal.js. The video is then just a screen capture of the autoplay of reveal file. Viewing presentations in their original Reveal form makes for an even richer experience.

All of this involves a whole lot of integration and scripting. But all of that has been done and you can get it all in one shot by just running one script.

To get started with BISOS, Blee, and ByStar, visit https://github.com/bxgenesis/start. From a vanilla Debian 13 installation ("Fresh-Debian"), you can bootstrap BISOS and Blee (with Emacs-30) in one step by running the raw-bisos.sh script. It produces "Raw-BISOS" which includes "Raw-Blee".

You can then add the LaTeX sources for your content as ByStar Portable Objects (BPO) to BISOS and process your content with Blee-LCNT.

All of this and more has been documented in a book that was produced by Blee-LCNT itself. The title of that book is:

Nature of Polyexistentials: Basis for Abolishment of the Western Intellectual Property Rights Regime And Introduction of the Libre-Halaal ByStar Digital Ecosystem

On Line US Edition: https://github.com/bxplpc/120033 – Download:
https://raw.github.com/bxplpc/120033/main/pdf/c-120033-1_05-book-8.5x11-col-emb-pub.pdf

On Line International Edition: https://github.com/bxplpc/120074 –
Download: https://raw.github.com/bxplpc/120074/main/pdf/c-120074-1_05-book-a4-col-emb-pub.pdf DOI: https://doi.org/10.5281/zenodo.8003846

US Edition Book Prints At Amazon: https://www.amazon.com/dp/1960957015
International Edition Book Prints in Iran:
https://jangal.com/fa/product/252689/nature-of-polyexistentials

I welcome your thoughts and feedback, especially if you experiment with Blee, BISOS, ByStar, and the model and the concept of Libre-Halaal Polyexistentials.

------------------------------------------------------------------------

FULL INLINE DOCUMENT

  
