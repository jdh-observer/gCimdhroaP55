---
jupyter:
  jupytext:
    formats: ipynb,md
    text_representation:
      extension: .md
      format_name: markdown
      format_version: '1.3'
      jupytext_version: 1.19.5
  kernelspec:
    display_name: Python 3 (ipykernel)
    language: python
    name: python3
---

<!-- #region editable=true slideshow={"slide_type": ""} tags=["title"] -->
# Queen of the Winds: Rethinking the Armada Portrait. A Video Essay
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} tags=["contributor"] -->
 ### Isabel Davis [![orcid](https://orcid.org/sites/default/files/images/orcid_16x16.png)](https://orcid.org/ORCID_ID) 
Natural History Museum, London
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} tags=["copyright"] -->
[![cc-by-nc-nd](https://licensebuttons.net/l/by-nc-nd/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc-nd/4.0/) 
© Isabel Davis. Published by De Gruyter in cooperation with the University of Luxembourg Centre for Contemporary and Digital History. This is an Open Access article distributed under the terms of the [Creative Commons Attribution License CC-BY-NC-ND](https://creativecommons.org/licenses/by-nc-nd/4.0/)

<!-- #endregion -->

```python editable=true slideshow={"slide_type": ""} tags=["cover", "anchor-cover-*"]
from IPython.display import display, Image
#caption_text = "Detail from Armada Portrait (c. 1588); National Maritime Museum, London, ID number ZBA7719."
display(Image("./media/Cover image.jpg"))
```

<!-- #region editable=true slideshow={"slide_type": ""} tags=["keywords"] -->
Armada Portrait, Portolan Charts, Cartography, Geometry, Wind, Video Essay
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} tags=["abstract"] -->
This article presents a video essay that re-examines the composition of the Armada portrait of Queen Elizabeth I (*c*. 1588). While the painting has been extensively interpreted, the video essay demonstrates that its composition is structured by the geometries of contemporary sea charts or ‘portolan’ maps, a relationship not previously identified. Through close visual comparison, the video essay reveals how cartographic forms underpin the organisation of the image, intensifying the painting’s engagement with wind and maritime power in the context of the defeat of the Spanish Armada. By making these geometries visible, the essay offers a new interpretation of the portrait as an articulation of imagined mastery over the forces of the wind in ways which anticipate later maritime fuel innovation.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} tags=["Subtitle"] -->
## Introduction
<!-- #endregion -->

<!-- #region citation-manager={"citations": {"2fnvq": [{"id": "1998823/UG8GNB5V", "source": "zotero"}], "c8gl9": [{"id": "1998823/HRJ6GQ6I", "source": "zotero"}], "cpd8u": [{"id": "1998823/ZIK8NWJT", "source": "zotero"}], "iaxdd": [{"id": "1998823/H8H9RH4I", "source": "zotero"}], "ovixz": [{"id": "1998823/4KFKNASA", "source": "zotero"}], "qxhq3": [{"id": "1998823/JPE8ILHV", "source": "zotero"}], "ue6zg": [{"id": "1998823/6FZDR7AD", "source": "zotero"}]}} editable=true slideshow={"slide_type": ""} tags=["Introduction-*"] -->
The famous [Armada Portrait](#figure-ArmadaPortrait-*) (*c*. 1588) of Elizabeth I exists in three similar versions.. This article and its embedded video essay focus on the one which now hangs in Queen’s House, part of the collection of the Royal Museums, Greenwich (<cite id="2fnvq"><a href="#zotero%7C1998823%2FUG8GNB5V">(<i>Armada Portrait of Elizabeth I</i>, 1588)</a></cite>). As one of the most iconic portraits of Tudor queen, Elizabeth I (1533-1603), the painting has been extensively decoded in prior art historical and museum-led interpretation (<cite id="ovixz"><a href="#zotero%7C1998823%2F4KFKNASA">(Montrose, 1986)</a></cite>, 314-317; <cite id="qxhq3"><a href="#zotero%7C1998823%2FJPE8ILHV">(Belsey &#38; Belsey, 1990)</a></cite>, 11-18; <cite id="cpd8u"><a href="#zotero%7C1998823%2FZIK8NWJT">(Strong, 1987)</a></cite>, 131-133; <cite id="ue6zg"><a href="#zotero%7C1998823%2F6FZDR7AD">(Brookes, 2006)</a></cite>, 238-250; <cite id="c8gl9"><a href="#zotero%7C1998823%2FHRJ6GQ6I">(Riding &#38; Blyth, 2020)</a></cite>) and <cite id="iaxdd"><a href="#zotero%7C1998823%2FH8H9RH4I">(<i>Symbolism in Portraits of Elizabeth I</i>, n.d.)</a></cite>. What has not been previously discussed is that the painting’s compositional logic is borrowed from so-called ‘portolan’ maps or sea charts. This essay uses the visual possibilities of digital film editing to explore the painting’s relationship to contemporary cartographic geometries, finding that relationship to emphasize an interest in the wind and mastery of it.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} tags=["Subtitle"] -->
## Queen of the Winds: Rethinking the Armada Portrait, a Video Essay
<!-- #endregion -->

```python editable=true slideshow={"slide_type": ""} tags=["video-ArmadaPortrait-*"]
from IPython.display import VimeoVideo

metadata={
    "jdh": {
        "module": "object",
        "object": {
            "type":"image",
            "source": [
                "Video essay on the Armada Portrait"
            ]
        }
    }
}

# Vimeo
display(VimeoVideo('1200692089','100%','347'), metadata=metadata)
```

<!-- #region editable=true slideshow={"slide_type": ""} tags=["Subtitle"] -->
## The Armada Portrait in Scholarly Context
<!-- #endregion -->

```python citation-manager={"citations": {"582wn": [{"id": "1998823/TZZ97CQC", "source": "zotero"}]}} editable=true slideshow={"slide_type": ""} tags=["figure-ArmadaPortrait-*"]
from IPython.display import display, Image
metadata={
    "jdh": {
        "module": "object",
        "object": {
            "type":"image",
            "source": [
                "Armada Portrait (c. 1588); National Maritime Museum, London, ID number ZBA7719."
            ]
        }
    }
}
display(Image("./media/Armada portrait.jpg"), metadata=metadata)
```

<!-- #region editable=true slideshow={"slide_type": ""} -->
In my video essay I haven’t included direct references to the rich history of interpretation that surrounds the Armada portrait. I therefore present a short survey here.
<!-- #endregion -->

<!-- #region citation-manager={"citations": {"1f2ab": [{"id": "1998823/6J3JPJDJ", "source": "zotero"}], "2svvp": [{"id": "1998823/4KFKNASA", "source": "zotero"}], "7bg4h": [{"id": "1998823/6FZDR7AD", "source": "zotero"}], "skprb": [{"id": "1998823/XJH7W8B2", "source": "zotero"}]}} editable=true slideshow={"slide_type": ""} -->
Two connected priorities emerge from prior scholarly attention to the Armada portrait: gendered symbolism and imperialist ambitions. Ornaments on the queen’s dress, especially the abundance of pearls and the distinctive ‘virgin-knot’ bow positioned low on the image and Elizabeth’s body, have been interpreted as expressions of strategic virginal symbolism (<cite id="2svvp"><a href="#zotero%7C1998823%2F4KFKNASA">(Montrose, 1986)</a></cite>, 315). The carved mermaid on Elizabeth’s left-hand side has also been understood as a statement on feminine sexuality and power, both as a possible comparison and a contrast to the queen herself (e.g. <cite id="7bg4h"><a href="#zotero%7C1998823%2F6FZDR7AD">(Brookes, 2006)</a></cite>, 239-243). The painting has been central in scholarly assessments of Elizabeth’s ‘cult of virginity’, wielded as political propaganda (<cite id="skprb"><a href="#zotero%7C1998823%2FXJH7W8B2">(King, 1990)</a></cite>, 30-31, but see, for a counter position, <cite id="1f2ab"><a href="#zotero%7C1998823%2F6J3JPJDJ">(Doran, 2003)</a></cite>, 171-172).
<!-- #endregion -->

<!-- #region citation-manager={"citations": {"4wxag": [{"id": "1998823/ZIK8NWJT", "source": "zotero"}], "d9kpr": [{"id": "1998823/TSEIJ7SX", "source": "zotero"}], "g28ne": [{"id": "1998823/TZZ97CQC", "source": "zotero"}]}} editable=true slideshow={"slide_type": ""} -->
The portrait’s imperial desires are clearly articulated in the crown – a closed type symbolically associated with the Holy Roman Empire – and the globe on Elizabeth’s right-hand side (<cite id="4wxag"><a href="#zotero%7C1998823%2FZIK8NWJT">(Strong, 1987)</a></cite>, 132; <cite id="d9kpr"><a href="#zotero%7C1998823%2FTSEIJ7SX">(Wells-Cole, 2012)</a></cite>, 836). Depictions of the Spanish and English navies through the windows in the top corners of the image evoke the immediate maritime rivalry with Spain in Europe, while the globe, oriented to show the Americas, projects that rivalry transatlantically. By positioning Elizabeth’s hand over the American map, the painting signals Elizabeth’s intention to reach for New World territory beyond what had already been seized in Newfoundland and at Roanoke (<cite id="g28ne"><a href="#zotero%7C1998823%2FTZZ97CQC">(Hower, 2020)</a></cite>, chapter six).
<!-- #endregion -->

<!-- #region citation-manager={"citations": {"2jv2k": [{"id": "1998823/6FZDR7AD", "source": "zotero"}], "6xafs": [{"id": "1998823/6FZDR7AD", "source": "zotero"}], "dkhxc": [{"id": "1998823/JPE8ILHV", "source": "zotero"}], "uo2u9": [{"id": "1998823/4KFKNASA", "source": "zotero"}]}} editable=true slideshow={"slide_type": ""} -->
Several scholars have connected the painting’s sexual and colonial dynamics (<cite id="uo2u9"><a href="#zotero%7C1998823%2F4KFKNASA">(Montrose, 1986)</a></cite>, 314-317; <cite id="dkhxc"><a href="#zotero%7C1998823%2FJPE8ILHV">(Belsey &#38; Belsey, 1990)</a></cite>, 12-14; <cite id="6xafs"><a href="#zotero%7C1998823%2F6FZDR7AD">(Brookes, 2006)</a></cite>, 244). Kristen Brookes, for example, has argued for a cartographic identification of the queen’s body with America, suggesting that in the gesture of her right hand, Elizabeth is caressing and laying claim to a body that is simultaneously her own and another’s. The queen is portrayed, Brookes argues, ‘as perpetually virginal and pregnant with imperial potential’ (<cite id="2jv2k"><a href="#zotero%7C1998823%2F6FZDR7AD">(Brookes, 2006)</a></cite>, 251). In this reading, Queen Elizabeth swells to become and/or contain the globe, despite being also chastely inviolable, as symbolized by the pearly aesthetics that others have so fully described.
<!-- #endregion -->

<!-- #region citation-manager={"citations": {"884ct": [{"id": "1998823/JPE8ILHV", "source": "zotero"}], "d2pxs": [{"id": "1998823/35CF6KKX", "source": "zotero"}]}} editable=true slideshow={"slide_type": ""} -->
The video essay I present here embroiders on these discussions through a visual exploration of the painting’s geometry which I suggest directly quotes contemporary sea charts or portolan maps. I use one particular portolan chart, from Trinity College Library Cambridge, which is a close contemporary witness, albeit from the opposing side of the Anglo-Spanish conflict (<cite id="d2pxs"><a href="#zotero%7C1998823%2F35CF6KKX">(Martinez, 1584)</a></cite>). This observation of the connectedness of painting and maritime maps builds on prior recognition that the portrait’s composition is governed by a complex of circles and semi-circles (<cite id="884ct"><a href="#zotero%7C1998823%2FJPE8ILHV">(Belsey &#38; Belsey, 1990)</a></cite>, 17). Noting that the painting’s geometrical logic is borrowed from maritime map technologies reveals that these circles are also networked with connecting lines. On portolan charts these lines are known as ‘rhumb lines’ and they lace together circular compasses, or wind-roses. Rhumb lines mark out the routes mariners can take over open seas by picking up particular winds. Aeolian symbolism - understandings of how winds shaped and propelled things and might themselves be directed and deployed - informs the painting's imperial ambitions.
<!-- #endregion -->

<!-- #region citation-manager={"citations": {"mk81c": [{"id": "1998823/883MTWPD", "source": "zotero"}]}} editable=true slideshow={"slide_type": ""} -->
This connection between painting and cartography is an observation I have made before in an argument about how the childlessness of England’s Tudor queens was culturally understood and politically managed (<cite id="mk81c"><a href="#zotero%7C1998823%2F883MTWPD">(Davis, 2025)</a></cite>, 133-137). Here I isolate the point about the painting’s citation of map technologies from the thematic discussion of childlessness which I previously explored. The medium of film, moreover, more fully shows the association between painting and sea charts and can more vividly explore its implications. My central claim is that the painting’s citation of portolan geometries adds greater force to the theme of the wind, which had always been an acknowledged subject because of the portrait’s celebration of the defeat of the Armada, partially wrecked by storms. In my video essay, I finish my discussion of the Armada portrait by looking at the queen’s ostrich feather fan: a literal wind generator that adds to the painting’s colonial ambitions by dreaming of private control of the wind, even in ways that anticipate modern independence from wind as a propulsion system at sea.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} tags=["Subtitle"] -->
## The Video Essay as a Digital History Methodology
<!-- #endregion -->

<!-- #region citation-manager={"citations": {"trz61": [{"id": "1998823/V9EPPFX9", "source": "zotero"}]}} editable=true slideshow={"slide_type": ""} tags=["hermeneutics"] -->
The video essay as a research practice emerged from screen media studies. It is understood both as a means of dissemination and a research methodology, generating fresh insight modally. Other visual fields of study – especially art practice, movement studies and art history – are developing the possibilities of the form, enabled by the cheapening of software tools (I used free versions of Davinci Resolve and Audacity), and the wider availability of sound, image, and video files with creative commons licences. Proponents of the audiovisual essay have explored how it aligns research object and finding, constituting ‘performative research’, to use a phrase from film scholar Catherine Grant (<cite id="trz61"><a href="#zotero%7C1998823%2FV9EPPFX9">(Grant, 2016)</a></cite>, 255-256). That alignment generates findings which looking/watching, analysing and writing alone cannot. But exactly how formal alignment creates knowledge is different for each individual example. In what follows I explore the new insights that digital video editing practice brings to the Armada portrait.
<!-- #endregion -->

<!-- #region citation-manager={"citations": {"bp4yu": [{"id": "1998823/V9EPPFX9", "source": "zotero"}]}} editable=true slideshow={"slide_type": ""} tags=["hermeneutics"] -->
Grant describes how research might be ‘translated’ from a piece of writing into a digital film output or, alternatively and perhaps preferably, research might be conducted exclusively digitally (<cite id="bp4yu"><a href="#zotero%7C1998823%2FV9EPPFX9">(Grant, 2016)</a></cite>, 255). Having previously written about the Armada portrait’s quotation of portolan maps, I am thus translating in the way that Grant describes. Moreover, the Armada portrait itself isn’t a film and so another kind of translation was necessary in my case: to present a still object in moving images. Translation is never a transparent window, however; rather, it generates new interpretive observations and, in the case here, foregrounds questions of movement and time in the durational process of composition.
<!-- #endregion -->

<!-- #region citation-manager={"citations": {"us69r": [{"id": "1998823/FFSQZDJN", "source": "zotero"}]}} editable=true slideshow={"slide_type": ""} tags=["hermeneutics"] -->
The value and suitability of digital video editing for historical research lies in its diachronic and synchronic logics. Video editing software requires analysis to be plotted on a ‘timeline’, emphasizing temporality (see discussion below), while also enabling the co-location of things from different times, places or collections, even into the same frame, as synchronous layers. This second capacity – to bring together materials from physically separate repositories – makes video essaying particularly suited to collections-based research. New digital collections, such as the Medea-Chart database of historical nautical maps which I use here, give digital access to otherwise geographically dispersed materials (<cite id="us69r"><a href="#zotero%7C1998823%2FFFSQZDJN">(Project MEDEA-CHART &#38; Gaspar et al., 2023)</a></cite>). Furthermore, audiovisual forms are especially apt because collection objects need to be understood visually and materially as well as in more abstracted analytical terms. Where objects are housed in museums, film offers a particular opportunity for engaging audiences with their histories in readily updatable forms, whether in gallery or in associated web-based content.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} tags=["hermeneutics"] -->
Because I worked with still images rather than live-action film, I create movement in my video essay by travelling around, into and out of those images, using the Davinci Resolve transform tools, zoom and position. Making still images move, however, creates challenges. Practical fixes have to compensate for the loss of the motion blur that the human eye produces in the perception of real-world motion, and which live-action filming simulates. The brain’s ability to read and predict movement instinctively co-operates with filmed motion, anticipating the effects of inertia, for example, where objects begin slowly, speed up, and then slow to a stop. Moving in and out of a painting or travelling over a physical map, then, requires an increase in the number of frames per second and the application of simulated motion blur and easing to remove the judder effect that synthetic movement generates. Iterative trial and error on the optical effects of motion across still image files created the majority of the labour in the making of this video essay. This process brought a counter perspective on the artist's challenge of representing movement in the eventually static medium of paint.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} tags=["Subtitle"] -->
## The Armada Portrait: Stasis, Movement and Maps
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
The Armada portrait makes a study of the contrast between change and constancy, between movement and stasis. The clearest point of kinetic energy is seen through the window on the right of the painting, where Spanish galleons are tossed and sunk in turbulent waves (as in the [cover image](#anchor-cover-*) above). My video essay begins in those rough seas, centring not only the Armada fleet but also the storm in which it scuppered. I use footage of scudding clouds and turbulent seas, sourced from Open Planet, to keep the topic of wind energy visually at the fore through the rest of the video.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
The tranquil sea surrounding the English navy seen through the left-hand window contrasts with the energy on view through its right-hand twin. The windows look out, indeed, onto different moments in time. Events separated by months are presented synchronically, as if the same sea could be calm or choppy in discrete localised zones. In another contrast to the turbulence overcoming the Spanish fleet, the central figure of the queen is still and solid. Art historians, Catherine and Andrew Belsey highlight the painting’s ‘non-illusionistic’ character, seen in its restrained use of depth perspective, a feature, I suggest, which also amplifies the stillness of the foregrounded interior. Belsey and Belsey add:
<!-- #endregion -->

<!-- #region citation-manager={"citations": {"jixg4": [{"id": "1998823/JPE8ILHV", "source": "zotero"}]}} editable=true slideshow={"slide_type": ""} tags=["quotation-*"] -->
> in place of illusion the picture offers a complex composition of circles and semi-circles, and this contributes to the impression that we are presented with a figure abstracted from any kind of immediacy or materiality (<cite id="jixg4"><a href="#zotero%7C1998823%2FJPE8ILHV">(Belsey &#38; Belsey, 1990)</a></cite>, 17-18).
<!-- #endregion -->

<!-- #region citation-manager={"citations": {"9bh1w": [{"id": "1998823/736HBRFD", "source": "zotero"}]}} editable=true slideshow={"slide_type": ""} -->
I extend Belsey and Belsey’s observation by connecting the circles they identify here with the compasses of portolan maps. I make this connection in the video essay by directly superimposing maritime chart elements over the portrait, adjusting their opacity so that coincident geometries become visible. I argue, too, that different kinds of spheres were understood in early modern reckonings to be shaped by wind energy; puffed cheeks, full sails, pregnant or morbidly distended bodies, and even the earth itself were all formed by pneumatic inflation. A renaissance drawing guide, for example, explains that the personified ‘winds must be drawn with puffed and blowne cheekes’ (<cite id="9bh1w"><a href="#zotero%7C1998823%2F736HBRFD">(Peacham, 1612)</a></cite>, 131). As inflating air escapes, it produces the directional forces depicted as rhumb lines or as gusts from wind heads at the edges of maps. In the Armada portrait, rhumb lines and air puffs are respectively invoked by the lines round and over shapes, and individual feather barbs in the queen’s headdress. Habits of drawing the winds shape the painting’s meaning.
<!-- #endregion -->

<!-- #region citation-manager={"citations": {"nxcuf": [{"id": "1998823/QQSMIZGP", "source": "zotero"}], "v2vkl": [{"id": "1998823/DIBQDKGC", "source": "zotero"}]}} editable=true slideshow={"slide_type": ""} tags=["hermeneutics"] -->

In digital video editing, the durational character of drawing, and so of compositional plotting is simulated by a structuring timeline. My video essay takes advantage of this via a stop-motion animation of the construction of a universal network chart or ‘mariners’ chart’, for which I follow the instructions in a late sixteenth-century navigational treatise (<cite id="nxcuf"><a href="#zotero%7C1998823%2FQQSMIZGP">(Blundeville, 1594/1638)</a></cite>). The authenticity of those instructions is corroborated by the close physical analysis of portolan charts conducted by historian of cartography, Tony Campbell (<cite id="v2vkl"><a href="#zotero%7C1998823%2FDIBQDKGC">(Campbell et al., 1987)</a></cite>, 391). He has identified scrapes in the vellum of such maps which mark ‘hidden’ or ‘secret circles’ determining the outer reach of the rhumb lines that radiate from a central point. The drawing process underscores the interdependency of circles and lines in the graphic translation of early modern ideas about the wind onto maps. Campbell's analysis of medieval and renaissance sea charts has also shown that the outlines of coasts and other geographical elements were drafted subsequently to the compasses and rhumb lines. The universal idea of the wind, then, precedes the specificity of toponymy in sixteenth-century sea map making, establishing it as a foundational and structuring logic.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
Video essaying, then, brings the hyperlocal time of the draughtsman into view even as the painting projects a grand colonial future that is yet to be realised. The imperial dreams of Eurpoean monarchs were practically achieved by the technics of mapping, drafted map by map, rhumb line by rhumb line. Expansive political visions, made numinous by the power symbolism of the crown, the pure aesthetics of pearls and the suggestion of divine agency in the weather, are underpinned by the *ars practica* of cartography. The practice of digital editing offers a process through which the imaginative power of these material and technical arts can be explored and invoked.
<!-- #endregion -->

<!-- #region citation-manager={"citations": {"34xr5": [{"id": "1998823/JPE8ILHV", "source": "zotero"}]}} editable=true slideshow={"slide_type": ""} -->
Belsey and Belsey’s sense in 1990 that the ‘remarkable geometry of the ‘Armada’ portrait’ had ‘received rather less attention’ than other aspects of the painting, is still somewhat true decades years on (<cite id="34xr5"><a href="#zotero%7C1998823%2FJPE8ILHV">(Belsey &#38; Belsey, 1990)</a></cite>, 16-17). Most discussions of the portrait consider the context of the Anglo-Spanish war and the politics of queenship, reading the painting’s many arresting elements – pearls, crown, globe, mermaid – without special interest in the structuring design. I have argued here that the painting is grounded in contemporary meteorological, and specifically Aeolian thought and practice, as it was graphically articulated in the navigational technology of the portolan chart. In unpicking the painting’s composition using digital video editing methods I have sought less to illustrate than to ‘perform’ the portrait’s sense that imperial ambition might be realised, rather than purely represented by maritime cartographic tools.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} tags=["Acknowledgements-*", "Subtitle"] -->
## Acknowledgements
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
With thanks to: Anna Burel, John Gibbs, Mara Oliva, Mark Perrott, and the community that gathered at the Minghella Studios, University of Reading, for the Video Essay Summer School in 2025 and the work in progress workshop in January 2026.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
## Film assets
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
### Images

Armada Portrait of Elizabeth I, *c*. 1588, Queen’s House, 
National Maritime Museum, London, ID number ZBA7719.
Source: rmg.co.uk.

Texts and Illustrations Relating to Medicine (*c*. 1250-1310), 
Oxford Bodleian MS Ashmole 399. 
Source: Digital Bodleian.

Commemorative Armada Coin,
British Museum, London, ID number M.6898.
Source: britishmuseum.org.

Blundevile, M., *A New and Necessary Treatise of Navigation*, 1597. 
Source: Archive.org.

Botticelli, Sandro, *Birth of Venus*, *c*. 1485, 
Uffizi Gallery, Florence, Italy. 
Source: Wikimedia.

Carew, Richard, *The Herrings Tayle*, 1598. 
Source: Archive.org. 

Gutiérrez II, Diego, *Printed Map of America*, 1562. 
Library of Congress. G3290 1562 .G7. 
Source: Medea-Chart Database. 

Martines, Joan, *Portolan Map of the Mediterranean*, 1584. 
Trinity College Library, Cambridge, MS. R.4.50. 
Source: Medea-Chart Database.

Münster, Sebastian, *Typus Orbis Universalis*, 1572. 
Source: David Rumsey Map Collection.

### Video: 

Kiln, International Shipping Movement and Routes, 2012.
Source: Shipmap.org.

Silverback Films, *Turbulent Coastal Waves*, 2024, ID number 59993192. 
Source: OpenPlanet.org.

Yoho Media, *Clouds as a Rainstorm Builds, Kenya*, 2014, ID number 55645620. 
Source: OpenPlanet.org.


### Music: 

Dream-Protocol, *Fatigue (Moody ambient cello)*, 2022.
Source: Pixabay.

Rockot, *Amalgam*, 2024. 
Source: Pixabay.

SamuelFJohanns, *Sinister Akroterion*,  2023.
Source: Pixabay.

### Sound Effects:

Dragon-Studio, *Light Switch*, 2025.  
Source: Pixabay.

MilanWulf, *Foot Switch*, 2023. 
Source: Pixabay.

Reitherman, Bruce, *Surf - medium close-up waves breaking on rocks, from a stormy sea*, 1988, ID: NHU05066068.
Source: BBC Sound Effects Library.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} tags=["Bibliography-*", "hidden"] -->
## Bibliography
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} tags=["hidden"] -->
<!-- BIBLIOGRAPHY START -->
<div class="csl-bib-body">
  <div class="csl-entry"><i id="zotero|1998823/UG8GNB5V"></i><i>Armada Portrait of Elizabeth I</i>. (1588). [Oil on oak]. <a href="https://www.rmg.co.uk/collections/objects/rmgc-object-1096108">https://www.rmg.co.uk/collections/objects/rmgc-object-1096108</a></div>
  <div class="csl-entry"><i id="zotero|1998823/JPE8ILHV"></i>Belsey, C., &#38; Belsey, A. (1990). Icons of Divinity: Portraits of Elizabeth I. In N. Llewellyn &#38; L. Gent (Eds.), <i>Renaissance Bodies: The Human Figure in English Culture c.1540–1660</i> (pp. 11–35). Reaktion.</div>
  <div class="csl-entry"><i id="zotero|1998823/QQSMIZGP"></i>Blundeville, T. (1638). A New and Necessary Treatise of Navigation. In <i>His Exercises: Contayning Eight Treatises</i> (pp. 645–745). Richard Bishop. <a href="https://archive.org/details/bim_early-english-books-1475-1640_m-blundeuile-his-exerci_blundeville-thomas_1638">https://archive.org/details/bim_early-english-books-1475-1640_m-blundeuile-his-exerci_blundeville-thomas_1638</a> (Original work published 1594)</div>
  <div class="csl-entry"><i id="zotero|1998823/6FZDR7AD"></i>Brookes, K. G. (2006). A Feminine “Writing that conquers”: Elizabethan Encounters with the New World. <i>Criticism</i>, <i>48</i>(2), 227–262. <a href="https://doi.org/23127293">https://doi.org/23127293</a></div>
  <div class="csl-entry"><i id="zotero|1998823/DIBQDKGC"></i>Campbell, T., Harley, J. B., &#38; Woodward, D. (1987). Portolan Charts from the Late Thirteenth Century to 1500. In <i>History of Cartography Volume One. Cartography in Prehistoric, Ancient, and Medieval Europe and the Mediterranean: One</i> (Six, pp. 371–463). University of Chicago Press. <a href="https://press.uchicago.edu/books/HOC/HOC_V1/Volume1.html">https://press.uchicago.edu/books/HOC/HOC_V1/Volume1.html</a></div>
  <div class="csl-entry"><i id="zotero|1998823/883MTWPD"></i>Davis, I. (with Burel, A.). (2025). <i>Conceiving Histories: Trying for Pregnancy, Past and Present</i>. MIT Press.</div>
  <div class="csl-entry"><i id="zotero|1998823/6J3JPJDJ"></i>Doran, S. (2003). Virginity, Divinity and Power: The Portraits of Elizabeth I. In S. Doran &#38; T. S. Freeman (Eds.), <i>The Myth of Elizabeth</i> (pp. 171–199). Palgrave Macmillan.</div>
  <div class="csl-entry"><i id="zotero|1998823/V9EPPFX9"></i>Grant, C. (2016). the Audiovisual Essay as Performative Research. <i>NECSUS. European Journal of Media Studies</i>, <i>5</i>(2), 255–265. <a href="https://doi.org/10.25969/mediarep/3370">https://doi.org/10.25969/mediarep/3370</a></div>
  <div class="csl-entry"><i id="zotero|1998823/TZZ97CQC"></i>Hower, J. S. (2020). <i>Tudor Empire: The Making of Early Modern Britain and the British Atlantic World, 1485-1603</i>. Palgrave Macmillan.</div>
  <div class="csl-entry"><i id="zotero|1998823/XJH7W8B2"></i>King, J. N. (1990). Queen Elizabeth I: Representations of the Virgin Queen. <i>Renaissance Quarterly</i>, <i>43</i>(1), 30–74. <a href="https://doi.org/2861792">https://doi.org/2861792</a></div>
  <div class="csl-entry"><i id="zotero|1998823/35CF6KKX"></i>Martinez, J. (1584). <i>Chart of the Mediterranean and Black Sea</i> [Portolan Chart]. Trinity College Library, Cambridge. <a href="https://medea.fc.ul.pt/view/chart/943">https://medea.fc.ul.pt/view/chart/943</a></div>
  <div class="csl-entry"><i id="zotero|1998823/4KFKNASA"></i>Montrose, L. (1986). The Elizabethan Subject and the Spenserian Text. In P. Parker &#38; D. Qunit (Eds.), <i>Literary Theory/Renaissance Texts</i> (pp. 303–340). Johns Hopkins Press.</div>
  <div class="csl-entry"><i id="zotero|1998823/736HBRFD"></i>Peacham, H. (1612). <i>The Gentleman’s Exercise</i>. John Browne. <a href="https://hdl.loc.gov/loc.rbc/Rosenwald.1464">https://hdl.loc.gov/loc.rbc/Rosenwald.1464</a></div>
  <div class="csl-entry"><i id="zotero|1998823/FFSQZDJN"></i>Project MEDEA-CHART, &#38; Gaspar et al., J. A. (2023). <i>Medea-Chart Database</i> (Version v1.50.2) [Dataset]. <a href="https://medea.fc.ul.pt/main">https://medea.fc.ul.pt/main</a></div>
  <div class="csl-entry"><i id="zotero|1998823/HRJ6GQ6I"></i>Riding, C., &#38; Blyth, R. (2020). <i>The Armada Portrait</i>. Royal Museums Greenwich.</div>
  <div class="csl-entry"><i id="zotero|1998823/ZIK8NWJT"></i>Strong, R. (1987). <i>Gloriana: The Portraits of Queen Elizabeth I</i>. Thames and Hudson.</div>
  <div class="csl-entry"><i id="zotero|1998823/H8H9RH4I"></i><i>Symbolism in Portraits of Elizabeth I</i>. (n.d.). [Educational article]. Royal Museums Greenwich. Retrieved May 29, 2026, from <a href="https://www.rmg.co.uk/stories/art-culture/symbolism-portraits-queen-elizabeth-i">https://www.rmg.co.uk/stories/art-culture/symbolism-portraits-queen-elizabeth-i</a></div>
  <div class="csl-entry"><i id="zotero|1998823/TSEIJ7SX"></i>Wells-Cole, A. (2012). Scissors-and-Paste in Two Paintings of Elizabeth I. <i>Burlington Magazine</i>, <i>154</i>(1317), 834–838. <a href="https://doi.org/41812902">https://doi.org/41812902</a></div>
</div>
<!-- BIBLIOGRAPHY END -->
<!-- #endregion -->
