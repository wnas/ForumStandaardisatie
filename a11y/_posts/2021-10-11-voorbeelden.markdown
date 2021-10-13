---
layout: post
title:  "Voorbeelden"
date:   2021-10-11 13:24:14 +0200
categories: voorbeelden
---
# Voorbeelden

## Afkortingen

Afkortingen worden vaak gebruikt, in print is het normaal om deze eerst uit te schrijven zodat ze duidelijk zijn. In html kun je gebruikt maken van een `abbr` tag. Luister naar deze twee voorbeelden met een screenreader.

A11Y

<abbr title="accessibility">A11y</abbr>

In de code hebben we het zo geschreven:

```
<abbr title="accessibility">A11y</abbr>
```

Je zou verwachten dat een screenreader in plaats van **A11y** de titel uitspreekt, [onderzoek](https://www.powermapper.com/tests/screen-readers/labelling/acronym-abbr-title/) wijst echter uit dat dit niet zo is.

Jammer genoeg is het dus ook in HTML beter om het eerst uit te schrijven, dan de afkorting er tussen haakjes achter te zetten en dan te vertrouwen op het geheugen van je gebruiker.

Beter is het nog om helemaal geen afkortingen te gebruiken aangezien je dan altijd mensen buiten sluit. Niet iedereen kent alle lingo!
