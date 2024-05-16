# Ondsel/FreeCAD

Náið í Ondsel hér:
[Windows](https://github.com/Ondsel-Development/FreeCAD/releases/download/2024.2.0/Ondsel_ES-2024.2.0.37191-Windows-x86_64-installer.exe), [Intel Mac](https://github.com/Ondsel-Development/FreeCAD/releases/download/2024.2.0/Ondsel_ES_2024.2.0.37191-macOS-intel-x86_64.dmg), [Apple Silicon](https://github.com/Ondsel-Development/FreeCAD/releases/download/2024.2.0/Ondsel_ES_2024.2.0.37191-macOS-apple-silicon-arm64.dmg), [Linux](https://github.com/Ondsel-Development/FreeCAD/releases/download/2024.2.0/Ondsel_ES_2024.2.0.37191-Linux-x86_64.AppImage).

## Hvers vegna Ondsel/FreeCAD?

Ondsel er þægilegri útgáfa af frjálsa teikniforritinu FreeCAD. Þessi forrit þróast hratt um þessar mundir. Núverandi FreeCAD útgáfa er 0.22 og nú fer að styttast í útgáfu 1.0!

- Frjáls hugbúnaður er frábær vegna þess að leyfið rennur ekki út. Þú hefur alltaf aðgang að forritinu og teikningunum þínum. 
- Gestir þínir í Fab Lab þurfa ekki að búa til t.d. Fusion reikning til að teikna einfaldan hlut og þrívíddarprenta. 
- Svo er hægt að ná í forritið og halda áfram að teikna heima. 
- Allir geta skoðað kóðann á bak við teikniforritið og geta breytt og bætt að vild. Margir hafa lagt af mörgum verkfæri í FreeCAD og byggt upp afar öflugt forrit. - Hægt er að komast hratt af stað með 
[örstuttu myndböndunum úr Fab Academy](http://academy.cba.mit.edu/classes/computer_design/index.html).

### Hvers vegna Ondsel frekar en FreeCAD

- Þægilegri litir og skipulag
- Mun þægilegri málsetningar í 2D skissum
- Construction geometry er strikalínur, eins og þær eiga að vera
- Mæliverkfærið í 3D
- Ondsel assembly workbench

## Hvers vegna ekki Ondsel/FreeCAD?

Vinnuflæðið er innblásið af CATIA og er aðeins öðruvísi en CAD forritin sem flestir eru vanir. Suma fídusa vantar og viðmótið getur verið svolítið stirt. Það eru líka villur í forritinu hér og þar.

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

Aðeins tvö slík forrit eru frjáls ([FreeCAD planegcs](https://github.com/FreeCAD/FreeCAD/tree/main/src/Mod/Sketcher/App/planegcs) og [Solvespace](https://fab.cba.mit.edu/classes/865.24/topics/design-tools/papers/sketchflat.pdf)). Þau halda til haga tækni sem er mikilvæg fyrir flesta hluti sem eru settir í framleiðslu.

## Sýnikennsla

### Fab Academy myndbönd

Veljið ykkur eitt af eftirfarandi myndböndum til að fara eftir í Ondsel.

- [constraints](http://academy.cba.mit.edu/classes/computer_design/2Dconstraints.mp4) (hjartað í CAD)
- [workbenches](http://academy.cba.mit.edu/classes/computer_design/workbenches.mp4) (hvað er í boði í Ondsel/FreeCAD)
- [snaps](http://academy.cba.mit.edu/classes/computer_design/snaps.mp4)
- [coordinates containers](http://academy.cba.mit.edu/classes/computer_design/coordinates.mp4)
- [extrude](http://academy.cba.mit.edu/classes/computer_design/extrude.mp4)
- [revolve](http://academy.cba.mit.edu/classes/computer_design/revolve.mp4)
- [loft](http://academy.cba.mit.edu/classes/computer_design/loft.mp4)
- [sweep](http://academy.cba.mit.edu/classes/computer_design/sweep.mp4)
- [constructive solid geometry (CSG)](http://academy.cba.mit.edu/classes/computer_design/CSG.mp4)
- [symmetry](http://academy.cba.mit.edu/classes/computer_design/symmetry.mp4)
- [pad pocket](http://academy.cba.mit.edu/classes/computer_design/pocket.mp4) (mikilvægast!)
- [fillet chamfer](http://academy.cba.mit.edu/classes/computer_design/filletchamfer.mp4)
- [offset](http://academy.cba.mit.edu/classes/computer_design/offset.mp4)
- [links hierarchy](http://academy.cba.mit.edu/classes/computer_design/links.mp4)
- [construction](http://academy.cba.mit.edu/classes/computer_design/construction.mp4)
- [projection, section](http://academy.cba.mit.edu/classes/computer_design/section.mp4)
- [alignment](http://academy.cba.mit.edu/classes/computer_design/alignment.mp4)
- [assemblies](http://academy.cba.mit.edu/classes/computer_design/assemblies.mp4) (Assembly3 workbench í FreeCAD (Ondsel er þægilegra))
- [measurement](http://academy.cba.mit.edu/classes/computer_design/measurement.mp4) (hvernig maður mælir í FreeCAD (mun betra í Ondsel))
- [folding](http://academy.cba.mit.edu/classes/computer_design/fold.mp4)
- [parametric](http://academy.cba.mit.edu/classes/computer_design/parametric.mp4) (ég notaði þetta [hér](https://fab.cba.mit.edu/classes/865.24/people/svavar/components/images/cable_carrier/parametric_cable_carrier.mp4))
- [programming](http://academy.cba.mit.edu/classes/computer_design/console.mp4)
- [algorithmic](http://academy.cba.mit.edu/classes/computer_design/algorithmic.mp4)
- [drawing](http://academy.cba.mit.edu/classes/computer_design/drawing.mp4)
- [render](http://academy.cba.mit.edu/classes/computer_design/render.mp4)
- [animation](http://academy.cba.mit.edu/classes/computer_design/animation.mp4)

### Youtube myndbönd

Þegar fyrirlestrinum lýkur skuluð þið velja eitt af eftirfarandi myndböndum til að fara eftir. Klárið fyrir lok bootcampsins. Ég kíki aftur á ykkur í myndsímtali og get hjálpað ykkur í gegnum screen share i Discord. ATH: Ondsel er svo nýtt að það er betra að skrifa FreeCAD í staðinn þegar þið eruð að gúgla hluti.

Teiknaðu LEGO kubb (ég mæli með þessu):
<iframe width="560" height="315" src="https://www.youtube.com/embed/Pse7tcafcRM?si=R8vi9MA4of8P_L_i" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen=""></iframe>

Notaðu ljósmynd til að teikna eftir:
<iframe width="560" height="315" src="https://www.youtube.com/embed/xQcDoAhmoa8?si=SI9mLM5bWnZu9pea" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen=""></iframe>

Svona er hægt að nota Rotate skipunina til að búa til hringlaga hlut út frá 2D skissu:
<iframe width="560" height="315" src="https://www.youtube.com/embed/5YK1vZuNgaQ?si=h9NMSvJpJbk-XAA4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen=""></iframe>

Það þarf alltaf að passa upp á að skissan sé lokuð áður en henni er breytt í 3D hlut. Þ.e. að línur séu tengdar saman og skarist ekki.

Blómavasi:
<iframe width="560" height="315" src="https://www.youtube.com/embed/8V4zmIoYuOA?si=xq81sv6iiGuzzDUQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen=""></iframe>

Dolla með skrúfuðu loki:
<iframe width="560" height="315" src="https://www.youtube.com/embed/LdE22iHt8Bo?si=yEJiRSxQ6-9vEUhf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen=""></iframe>

Límbandshaldari:
<iframe width="560" height="315" src="https://www.youtube.com/embed/SVnPg5QfnR8?si=BQtKZomxrhJPkA3b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen=""></iframe>

Símastandur:
<iframe width="560" height="315" src="https://www.youtube.com/embed/n4FIhoLKGKc?si=rWeT3RD-n4ihPw6P" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen=""></iframe>

Símahulstur:
<iframe width="560" height="315" src="https://www.youtube.com/embed/1bmBwGDe2Is?si=I-bto8krsXz0Q77Z" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen=""></iframe>

Box með loki og lömum:
<iframe width="560" height="315" src="https://www.youtube.com/embed/JmWt8XP_Eds?si=kGvvYfYek-GLWRp0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen=""></iframe>

Fleiri hlutir með lömum:
<p><iframe width="560" height="315" src="https://www.youtube.com/embed/-eq4e5w2oMI?si=KHl_GXluEBNHzZH0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen=""></iframe>

Loft hentar t.d. til að búa til hlut sem tengir saman rör sem eru mismunandi í laginu:
<iframe width="560" height="315" src="https://www.youtube.com/embed/uDZ_xZ1LJ1c?si=7rZUavPAudILeTBD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen=""></iframe>

Flóknari form:
<iframe width="560" height="315" src="https://www.youtube.com/embed/19klYkKqvFo?si=OljXwl5FSGg3ps3u" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen=""></iframe>