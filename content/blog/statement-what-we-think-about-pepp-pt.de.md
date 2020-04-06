---
title: "Wie denken wir über PEPP-PT"
date: 2020-04-03T12:29:40+06:00
description : "PEPP-PT ist ein ähnliches Protokol wie STRICT, was ist unsere Meinung dazu?"
type: post
image: images/blog/thinker.jpg
author: ito Team
tags: ["review", "statement"]
---

Um unsere Situation zu verstehen, möchten wir zunächst kurz darstellen, wie sich die Dinge aus unserer Sicht entwickelt haben.

Wir waren nicht sehr verwundert, als das Projekt [**PEPP-PT**](https://www.pepp-pt.org/) [**P**an-**E**uropean **P**rivacy-**P**reserving **P**roximity **T**racing] vorgestellt wurde, denn bereits bei der Auszeichnung des #WirVsVirus Hackathons wurde kommuniziert, dass an einer Lösung von offizieller Seite gearbeitet wird. Uns ist klar, dass in gewisser Weise nicht voraussehbar war, wie weit die Teams hinsichtlich des Tracing-Themas an einem Wochenende voranschreiten können. Dennoch sind wir davon ausgegangen, dass spätestens, als sich herausstellte, dass eine Menge hoch qualifizierter Entwickler, Datenschutzverantwortliche und andere Experten an den Projekten beteiligt sind, ein gemeinsamer Diskurs entstehen würde. Unser Ziel dabei war es immer, eine Kooperation herzustellen, um keine Silos aufzubauen, die zu verschiedenen Lösungen führen würden. Die Bewältigung der Herausforderungen kann nur funktionieren, wenn die Akzeptanz in der Gesellschaft groß ist – und ein Konsens hinsichtlich eines Standards herrscht. Leider blieben unsere Bemühungen, Kontakt zum Robert-Koch-Institut sowie anderen Stellen, die am PEPP-PT Projekt mitwirken, unbeantwortet. Wir sind letztlich zu dem Ergebnis gekommen, dass nur ein gemeinsamer Standard, der länderübergreifend funktioniert und in verschiedene Apps übersetzt werden kann, funktioniert.

Da wir nur Zugang zu den bisher veröffentlichten [Dokumenten](https://404a7c52-a26b-421d-a6c6-96c63f2a159a.filesusr.com/ugd/159fc3_878909ad0691448695346b128c6c9302.pdf) haben, können wir auch nur dazu ein Statement verfassen.

Die Beschreibung des Protokolls ist sehr lückenhaft und daher nicht ohne Spekulationen möglich, weswegen wir hier eher aufzeigen möchten, wieso wir unseren bisherigen Weg weiter gehen werden.

Unser oberstes Ziel ist es, die Privatsphäre von jedem Nutzer zu schützen. Weil das besonders dann schwierig ist, wenn viele Daten anfallen können, wird Privacy Engineering benötigt. Je mehr Daten zur Verfügung stehen, desto einfacher wird es, diese zu einem großen Bild zusammenzufügen und einzelne Personen zu identifizieren. Daher müssen wir es vermeiden, die Daten der Kontakte einer Person zu veröffentlichen, sondern lediglich die zufälligen IDs der betroffenen Person selbst. In unserem Protokoll haben wir vorgesehen, dass der Datenabgleich auf den lokalen Geräten der Nutzer stattfindet. So, wie es bisher in den Medien und in den Projektpapieren des PEPP-PT Teams dargestellt wird, wird der Datenabgleich auf dem Server gemacht. Dies gilt es aus unserer Sicht zu vermeiden.

Der Grund dafür ist folgender: zwischen den PIDs einer einzelnen Person oder mehrerer Personen gibt es keine Korrelation, jedoch aber zwischen den Menschen, die man getroffen hat. Je mehr Menschen erkranken, desto mehr Kontaktdaten liegen dem Server vor – dadurch lassen sich personalisierte Ströme aufzeichnen.

Durch den hohen Schutz der Privatsphäre müssen wir verschiedene Kompromisse eingehen, weshalb unser Protokoll in der aktuellen Version sicher nicht perfekt ist. Durch die hohe Privatsphäre ist die Datenlast für die Prüfung, ob man infiziert ist oder nicht, höher als bei dem Ansatz von PEPP-PT. Wir haben schon verschiedene Möglichkeiten ausgearbeitet, um diese Datenlast zu minimieren, die jedoch immer eigene Kompromisse mit sich bringen. Aktuell geht es jedoch darum, möglichst zeitnah eine Lösung zur Hand zu haben um das Leben wieder in normale Bahnen zu lenken. Wir haben viele Ideen zur Optimierung des Protokolls. Deren Anonymisierung ist jedoch nicht ganz so einfach und benötigt daher mehr Zeit in der Entwicklung.

Wir wünschen uns eine simple, nachvollziehbar anonyme Lösung und arbeiten daher weiter an der Implementierung von [**STRICT**](https://github.com/ito-org/STRICT) [**s**imply **tr**ack **i**nfe**ct**ions] – in der Hoffnung, dass STRICT zu einem besseren Standard beiträgt.

