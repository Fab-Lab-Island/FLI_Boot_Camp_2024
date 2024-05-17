# Ondsel/FreeCAD

Náið í Ondsel teikniforritið hér:
[Windows](https://github.com/Ondsel-Development/FreeCAD/releases/download/2024.2.0/Ondsel_ES-2024.2.0.37191-Windows-x86_64-installer.exe), [Intel Mac](https://github.com/Ondsel-Development/FreeCAD/releases/download/2024.2.0/Ondsel_ES_2024.2.0.37191-macOS-intel-x86_64.dmg), [Apple Silicon](https://github.com/Ondsel-Development/FreeCAD/releases/download/2024.2.0/Ondsel_ES_2024.2.0.37191-macOS-apple-silicon-arm64.dmg), [Linux](https://github.com/Ondsel-Development/FreeCAD/releases/download/2024.2.0/Ondsel_ES_2024.2.0.37191-Linux-x86_64.AppImage).

## Mín reynsla

[Ég skipti um skoðun á frjálsum teiknihugbúnaði](https://fabacademy.org/2023/labs/isafjordur/students/svavar-konradsson/assignments/week02.html#on-free-and-open-source-engineering-software) þegar ég tók þátt í Fab Academy. Áður notaði ég [Inventor](https://teamspark.is/is/vehicles/old) og [SolidWorks](https://rafnar.com/), sem kosta hundruð þúsunda króna á ári, og leit ekki við neinu öðru. Autodesk bauð mér tvisvar til útlanda; á [stúdentaráðstefnu á Spáni](https://www.youtube.com/watch?v=RZ0dcDp1KXI) og á [Autodesk University í Las Vegas](https://adsknews.autodesk.com/en/stories/autodesk-university-2013-opening-keynote-urges-attendees-to-go-outside/). Ég ætti að vera þeirra helsti talsmaður!

Og ég var það. Þessi forrit eru frábær. En að útvega leyfi og halda því er ekki skemmtilegt. Ég hef svo oft verið að teikna hluti og gera burðarþolsgreiningar og þegar ég vil skoða skrárnar aftur seinna þá er hugbúnaðarleyfið mitt runnið út. Hér eru tvær greinar frá Ondsel teyminu sem ég tengi hart við:

[Autodesk is teaching students hard life-lessons about vendor lock-in](https://ondsel.com/blog/hard-lessons/)

[Autodesk continues to enshittify Fusion 360 with a 27% price increase](https://ondsel.com/blog/autodesk-enshittifies-fusion-360/)

Þegar fyrsti tíminn í Fab Lab áfanganum var að hefjast í MÍ í janúar, þá sagði Fusion mér að leyfið mitt væri útrunnið. Það er vel hægt að finna út úr því, en ég var orðinn ansi leiður á að standa í leyfisveseni fyrir mig og nemendur mína, svo að ég skipti snarlega yfir í FreeCAD. Það tók nemendurna álíka langan tíma að ná í FreeCAD á allar tölvurnar og það tekur að fá Fusion leyfi. Og Doddi gat alveg lært á FreeCAD líka þegar hann kom frá [Nordic Bootcamp](https://nordicfablabs.org/bootcamp-2024-finland/). Að teikna í FreeCAD var svolítið stirt til að byrja með, en þau komust öll í gegnum myndband frá Neil og eitt af Youtube myndböndunum hér fyrir neðan. Sum notuðu FreeCAD til að teikna lokaverkefnin sín. Í kennslukönnuninni sagði einn nemandinn "Ekki fokking Freecad." Ég skil. Það eru ýmsir hnökrar á forritinu (og kennararnir voru að læra á það á sama tíma og nemendurnir).

Svo kom Ondsel, sem er þægilegri útgáfa af FreeCAD.

## Hvers vegna Ondsel/FreeCAD?

<iframe width="560" height="315" src="https://www.youtube.com/embed/udIBhVIy5MI?si=g7LZe4lDToAry7O2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

- Mun öflugra teikniforrit en flestir gera sér grein fyrir, byggt á góðum grunni. Hægt er að teikna (nánast) allt í Ondsel, vinna með mesh, útbúa toolpaths, gera burðarþolsgreiningar, gera smíðateikningar, forrita teikningarnar í Python og fleira.
- Frjáls hugbúnaður er hluti af menningu Fab Lab smiðja.
- Frjáls hugbúnaður er frábær vegna þess að leyfið rennur ekki út. Þú hefur alltaf aðgang að forritinu og teikningunum þínum. 
- Gestir þínir í Fab Lab þurfa ekki að búa til t.d. Fusion reikning til að teikna einfaldan hlut og búa til. 
- Svo er hægt að ná í forritið og halda áfram að teikna heima. 
- Allir geta skoðað kóðann á bak við teikniforritið og geta breytt og bætt að vild. Margir hafa lagt af mörkum verkfæri í FreeCAD og byggt upp virkni sem er ekki til annars staðar. 
- Hægt er að komast hratt af stað með 
[örstuttu myndböndunum úr Fab Academy](http://academy.cba.mit.edu/classes/computer_design/index.html).
- [Pieter Hijma](https://fabacademy.org/2023/labs/waag/students/pieter-hijma/), sem tók Fab Academy í fyrra, er hluti af Ondsel teyminu. Við getum kvartað beint við hann á [Mattermost](https://chat.academany.org/). Það gladdi Ondsel teymið að við værum strax byrjaðir að nota það í kennslu. Og Doddi bjó til meme:


### Hvers vegna Ondsel frekar en FreeCAD

- Ondsel hjálpar manni að byrja teikninguna á réttan hátt ([opna Part Design workbench, búa til Body og síðan búa til Sketch](https://youtu.be/U2_x2RqJb7Q?si=dOPH_YwSSwkCY-nB))
- Þægilegri litir og skipulag
- Stillt á Blender mús, sem er þægilegri en sú sem er default í FreeCAD (Að vísu getur verið þægilegra að hafa músina stillta á CAD þegar maður er að vinna í tvívíðri skissu)
- Mun þægilegri málsetningar í 2D skissum
- Búið að bæta við [midpoint constraint](https://youtube.com/shorts/1ZFCw8LydxA?si=zVfEt8pCvrdBNxmn), mjög mikilvægt
- Construction geometry er strikalínur, eins og þær eiga að vera
- Mæliverkfærið í 3D
- Ondsel assembly workbench

## Hvers vegna gæti verið gott að hinkra með að skipta yfir í Ondsel/FreeCAD?

- Vinnuflæðið er [innblásið af CATIA](https://ondsel.com/blog/catia-suffers-from-the-same-problems/) og er aðeins öðruvísi en CAD forritin sem flestir eru vanir. - Suma fídusa vantar. 
- Viðmótið getur verið svolítið stirt.
- Það eru villur í forritinu hér og þar.
- [Topological naming problem](https://youtu.be/6p2vqEEmWq4?si=2rqe8Ff-KkaQpWYM) er stærsta og versta villan (er að mestu leyst, en á eftir að fara í gegnum prófanir)

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

### Hvernig teiknar maður hluti í CAD forriti?

Fyrst er stutt sýnidæmi fyrir byrjendur í CAD teikningu. CAD teikning snýst að miklu leyti um að finna hvernig er hægt að skipta hlutnum upp í einföld form sem er hægt að búa til með tvívíðum skissum:

<iframe width="560" height="315" src="https://www.youtube.com/embed/tRNc6AhG7b8?si=0H9XlU1VFLdlvdsu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

Til þess að geta bjargað sér í CAD teikningu er í raun nóg að læra að gera tvívíðar teikningar með málsetningum og skorðum:

<iframe width="560" height="315" src="https://www.youtube.com/embed/gbNg3mzm84s?si=QRbz4QEDg4He6aLf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

Síðan notar maður Pad, Pocket, Revolve, Loft eða Sweep til að búa til þrívíðan hlut úr skissunni.

Til að staðsetja skissurnar í þrívíðu rými er gott að búa fyrst til [nýtt plan](https://youtu.be/nGI1_1QTdyg?si=HeSK9EhkHwQgJuN9) til að skissa á. [Hér](https://youtu.be/j6C53zTszx0?si=5iCFKoaCD162Lpsm) er líka þægileg aðferð til að færa til skissur.

### Hlutir til að passa sig á

- Í öllum CAD forritum þarf að passa upp á að [tvívíða skissan sé lokuð](https://youtu.be/w7_jCxxN1OY?si=ixnz_cEuqz7DVGvh) áður en henni er breytt í 3D hlut. Þ.e. að línur séu tengdar saman og skarist ekki. Þetta er oftast vandamálið þegar það er virkar ekki að búa til þrívíðan hlut úr tvívíðu skissunni þinni. 

Ondsel/FreeCAD hefur nokkrar sérviskur sem fá fólk til að gefast upp og fara aftur í Fusion. En ef þið vitið af þeim þá getið þið klórað ykkur fram úr hlutunum:

- Þú *verður* að vera með rétt Body valið til þess að Ondsel leyfi þér að gera Pad, Pocket, Revolve, o.s.frv. En það er til leið [framhjá því](https://youtu.be/ylAMGQ8HV0w?si=8nSflnThgODHTINf).
- Síðan er mikilvægt að vita að það er bara hægt að hafa einn prófíl í hverri skissu. Það er takmarkandi en líka góð venja í CAD teikningu. Og það er hægt að nota [master skissu](https://youtu.be/k6lMaQiIlKo?si=NBaXXGe8sX_AslgZ) til að stýra öllum hinum skissunum. 

### Góð ráð

Ýttu á bilstöngina til að fela og sýna hluti.

### Myndbönd úr Fab Academy

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
- [fillet chamfer](http://academy.cba.mit.edu/classes/computer_design/filletchamfer.mp4)
- [offset](http://academy.cba.mit.edu/classes/computer_design/offset.mp4)
- [links hierarchy](http://academy.cba.mit.edu/classes/computer_design/links.mp4)
- [construction](http://academy.cba.mit.edu/classes/computer_design/construction.mp4) (construction línur sjást betur í Ondsel)
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

Teiknaðu LEGO kubb (ég mæli með þessu, það kennir að gera pattern og að [taka þrívíða geómetríu inn í tvívíða skissu](https://youtu.be/x7_KgeLOcKY?si=4JxT2ygyOHgnEzZz)):
<iframe width="560" height="315" src="https://www.youtube.com/embed/Pse7tcafcRM?si=R8vi9MA4of8P_L_i" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen=""></iframe>

Notaðu ljósmynd til að teikna eftir (það er sérlega gott að nota 2D skanna, því að þá færðu myndina í réttri stærð):
<iframe width="560" height="315" src="https://www.youtube.com/embed/xQcDoAhmoa8?si=SI9mLM5bWnZu9pea" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen=""></iframe>

Svona er hægt að nota Rotate skipunina til að búa til hringlaga hlut út frá 2D skissu:
<iframe width="560" height="315" src="https://www.youtube.com/embed/5YK1vZuNgaQ?si=h9NMSvJpJbk-XAA4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen=""></iframe>

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

Teiknaðu skeið (mæli með):
<iframe width="560" height="315" src="https://www.youtube.com/embed/m6JLox1A7KY?si=7X9e9p3myP-_X19B" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

Surface continuity:
<iframe width="560" height="315" src="https://www.youtube.com/embed/5sXfs_0y8O4?si=RpV8ZWNvVQMz424y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

Flóknari form:
<iframe width="560" height="315" src="https://www.youtube.com/embed/19klYkKqvFo?si=OljXwl5FSGg3ps3u" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen=""></iframe>