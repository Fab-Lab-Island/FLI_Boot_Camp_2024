# Ondsel/FreeCAD vinnustofa

Náið í Ondsel hér:
[Windows](https://github.com/Ondsel-Development/FreeCAD/releases/download/2024.2.0/Ondsel_ES-2024.2.0.37191-Windows-x86_64-installer.exe), [Intel Mac](https://github.com/Ondsel-Development/FreeCAD/releases/download/2024.2.0/Ondsel_ES_2024.2.0.37191-macOS-intel-x86_64.dmg), [Apple Silicon](https://github.com/Ondsel-Development/FreeCAD/releases/download/2024.2.0/Ondsel_ES_2024.2.0.37191-macOS-apple-silicon-arm64.dmg), [Linux](https://github.com/Ondsel-Development/FreeCAD/releases/download/2024.2.0/Ondsel_ES_2024.2.0.37191-Linux-x86_64.AppImage).

Næsti hluti er samantekt af fyrirlestri Leo McElroy sem heitir [CAD in 1 Hour](https://fab.cba.mit.edu/classes/865.24/topics/design-tools/):

### Tegundir af CAD forritum

[![Flokkun á CAD forritum](https://fab.cba.mit.edu/classes/865.24/topics/design-tools/assets/cad-landscape.png)](https://fab.cba.mit.edu/classes/865.24/topics/design-tools/)*Mynd frá [Leo McElroy](https://fab.cba.mit.edu/classes/865.21/people/leo-mcelroy/#/about)*

### Saga tölvuvæddrar hönnunar (CAD)

Tvennt þarf til að búa til "solid modeling" CAD forrit: 

1. Geometry kernel (formkjarni)
1. Constraint solver (skorðuforrit)

#### Geometry kernel
Geometry kernel, sem mætti íslenska sem formkjarna, er forrit sem býr til þrívíð yfirborð sem eru tengd saman í lokaðan hlut ([B-Rep](https://fab.cba.mit.edu/classes/865.24/topics/design-tools/#brep) solid body).

Þrír menn bjuggu alla helstu formkjarna (geometry kernels) á markaðinum:

[![Höfundar formkjarna (geometry kernels)](https://fab.cba.mit.edu/classes/865.24/topics/design-tools/assets/cad-tree.png)](https://fab.cba.mit.edu/classes/865.24/topics/design-tools/#cad-history)*Mynd frá [Leo McElroy](https://fab.cba.mit.edu/classes/865.21/people/leo-mcelroy/#/about)*

[OpenCascade](https://www.opencascade.com/), sem FreeCAD er byggt á, er eini frjálsi formkjarninn. Hann er mikilvægur af þeim sökum.

#### Constraint solver
Constraint solver, sem mætti kannski íslenska sem skorðuforrit, er forrit sem leysir skorður og málsetningar í tvívíðum línuteikningum.

[D-Cubed](https://plm.sw.siemens.com/en-US/plm-components/d-cubed/) constraint solverinn er á bak við öll helstu CAD forritin á markaðinum: Siemens NX, Autodesk Inventor og Fusion, SolidWorks og fleiri. Það er undarlegt.

Aðeins tvö slík forrit eru frjáls ([FreeCAD planegcs](https://github.com/FreeCAD/FreeCAD/tree/main/src/Mod/Sketcher/App/planegcs) og [Solvespace](https://fab.cba.mit.edu/classes/865.24/topics/design-tools/papers/sketchflat.pdf)). Þau halda til haga tækni sem er okkur mikilvæg.

## Sýnikennsla

Veljið ykkur eitt af eftirfarandi myndböndum til að fara eftir. Klárið fyrir lok bootcampsins. Ég kíki aftur á ykkur í myndsímtali og get hjálpað ykkur í gegnum screen share i Discord.

<p style="text-align: left;"><br></p>
<h4 style="text-align: left;">Notaðu ljósmynd til að teikna eftir</h4>
<iframe width="560" height="315" src="https://www.youtube.com/embed/xQcDoAhmoa8?si=SI9mLM5bWnZu9pea" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen=""></iframe>
<p style="text-align: left;"><br></p>
<h4 style="text-align: left;"><span style="font-size: 1.54rem;">Rotate</span><br></h4>
<p dir="ltr" style="text-align: left;">Svona er hægt að nota Rotate skipunina til að búa til hringlaga hlut út frá 2D skissu:</p>
<iframe width="560" height="315" src="https://www.youtube.com/embed/5YK1vZuNgaQ?si=h9NMSvJpJbk-XAA4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen=""></iframe>
<p>Það þarf alltaf að passa upp á að skissan sé lokuð áður en henni er breytt í 3D hlut. Þ.e. að línur séu tengdar saman og skarist ekki.</p>
<p><br></p>
<h4>Blómavasi</h4>
<iframe width="560" height="315" src="https://www.youtube.com/embed/8V4zmIoYuOA?si=xq81sv6iiGuzzDUQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen=""></iframe>
<p><br>
</p>
<h4>Dolla með skrúfuðu loki</h4>
<iframe width="560" height="315" src="https://www.youtube.com/embed/LdE22iHt8Bo?si=yEJiRSxQ6-9vEUhf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen=""></iframe>
<p><br></p>
<h4>Límbandshaldari</h4>
<p><br></p>
<iframe width="560" height="315" src="https://www.youtube.com/embed/SVnPg5QfnR8?si=BQtKZomxrhJPkA3b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen=""></iframe>
<p><br></p>
<h4>Símastandur</h4>
<iframe width="560" height="315" src="https://www.youtube.com/embed/n4FIhoLKGKc?si=rWeT3RD-n4ihPw6P" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen=""></iframe>
<p></p>
<p><br></p>
<h4>Símahulstur</h4>
<iframe width="560" height="315" src="https://www.youtube.com/embed/1bmBwGDe2Is?si=I-bto8krsXz0Q77Z" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen=""></iframe>
<p><br>
</p>
<h4>Box með loki og lömum</h4>
<p></p>
<iframe width="560" height="315" src="https://www.youtube.com/embed/JmWt8XP_Eds?si=kGvvYfYek-GLWRp0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen=""></iframe>
<p><br></p>
<h4>Fleiri hlutir með lömum</h4>
<p><iframe width="560" height="315" src="https://www.youtube.com/embed/-eq4e5w2oMI?si=KHl_GXluEBNHzZH0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen=""></iframe></p>
<h4>Loft</h4>
<p>Loft hentar t.d. til að búa til hlut sem tengir saman rör sem eru mismunandi í laginu.</p>
<iframe width="560" height="315" src="https://www.youtube.com/embed/uDZ_xZ1LJ1c?si=7rZUavPAudILeTBD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen=""></iframe>
<p><br></p>
<h4>Flóknari form</h4>
<iframe width="560" height="315" src="https://www.youtube.com/embed/19klYkKqvFo?si=OljXwl5FSGg3ps3u" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen=""></iframe>
<p></p>