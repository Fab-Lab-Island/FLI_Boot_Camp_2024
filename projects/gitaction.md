# Git Action

## Hvað eru Github Actions?

[_Github Actions_](https://docs.github.com/en/actions) er sjálfvirkar aðgerðir sem gera notendum kleift að keyra verkefni, prófanir eða aðrar aðgerðir tengd þeim. 

## Ondsel/FreeCAD og Github Actions

Eftir kynningu Svavars á Ondsel langaði mig að bæta smá sjálfvirkni við Ondsel verkefni. 

Ég bjó til [verkefni hér](https://github.com/arnib13/ondselverkefni) til prufu. Það sem við viljum að gerist er að þegar breyttu módeli er ýtt yfir á vefþjóninn, fer aðgerð í gang sem býr til / uppfærir `.STL` skrá í `model`
 möppunni. Til 

Í `model` möppunni er `test.FCStd` Ondsel/FreeCAD skráin. 

Í `.github/workflows/` er skránni `freecad-to-stl.yml` komið fyrir. 

Sú skrá inniheldur upplýsingar á `YAML` formi.

FreeCAD býður upp á forritanlegt viðmót, þ.e.a.s. við getum stýrt FreeCAD frá skipanalínunni. Það er **mjög** hentugt þegar kemur að því að sjálfvirknivæða aðgerðir. 

Árni fór yfir hvernig git action er notað og sýndi okkur dæmi hvernig það er hægt að nota github og freecad/[ondsel](ondsel.md) saman.

[Hlekur á sýni síðu](https://github.com/arnib13/ondselverkefni)

[Docker](https://www.docker.com/)

