---
title: "What we think about PEPP-PT"
date: 2020-04-03T12:29:40+06:00
description : "PEPP-PT is a protocol similar to STRICT, what is our assessment?"
type: post
image: images/blog/thinker.jpg
author: ito Team
tags: ["review", "statement"]
---

## English

In order to understand our situation, we would first like to briefly describe how things evolved from our perspective.

We were not very surprised when the project [**PEPP-PT**](https://www.pepp-pt.org/) [**P**an-**E**uropean **P**rivacy-**P**reserving **P**roximity **T**racing] publicly launched, since it had been announced that some relevant institutions were working on a solution during the #WeVsVirus results ceremony. While we understand that it was unforeseeable how much progress the hackathon teams would make towards a tracing solution in one weekend, we did assume that once it became clear how many highly qualified developers, data protection officers and other experts were involved, a common discourse would emerge. Our goal has always been to establish cooperation and to prevent silos that would lead to different solutions. Overcoming these challenges can only work if there is a high level of acceptance in society - and by extension a consensus on a standard. Unfortunately, our efforts to establish contact with the Robert Koch Institute and other agencies involved in the PEPP-PT project remained unanswered. We concluded and share the opinion that only a common standard that works across countries and can be implemented by different apps can succeed.

Since we only have access to the [documents](https://404a7c52-a26b-421d-a6c6-96c63f2a159a.filesusr.com/ugd/159fc3_878909ad0691448695346b128c6c9302.pdf) published so far, we can only write a statement about these.

The description of the protocol PEPP-PT published contains some gaps and it is therefore not possible to evaluate it without speculation, we would rather proceed by explaining why we will continue to work on our solution.

Our primary goal is to protect the privacy of every user. Because this is especially difficult when a lot of data might be generated, privacy engineering is needed. The more data is available, the easier it is to combine it into one big picture and identify individual persons. Therefore we have to avoid publishing the data of a person’s contacts, and instead publish only the random IDs of the person concerned. In our protocol, data matching occurs on the users’ local devices, thereby decentralising the data. As far as we have been able to deduce from media reports and the published project documentation of the PEPP-PT team, the data reconciliation is done on the server. From our point of view this should be avoided.

The reason for this is the following: there is no correlation between the PIDs of a single person or several people, but there is a correlation between the people you have met. The more people are ill, the more contact data is available to the server - this allows personal and individual contact flows to be recorded.

The high level of privacy protection we are seeking to achieve means we have to make various compromises, which is why our protocol in its current form is certainly not perfect. Due to the high privacy, the data size required for checking whether a user has been in contact with someone who is infected or not is higher than with the PEPP-PT approach. We have already worked out different ways to minimize this data load, but they always bring their own trade-offs. Currently, however, the aim is to have a solution at hand as soon as possible to get life back on track. We have many ideas for optimizing the protocol. However, maintaining user anonymity is not an easy task and takes time and careful implementation.

We want a simple, comprehensible and anonymous solution and therefore continue to work on the implementation of [**STRICT**](https://github.com/ito-org/STRICT) [**s**imply **tr**ack **i**nfe**ct**ions] - in the hope that STRICT leads to a better standard for everyone.

----

## Deutsch 
Um unsere Situation zu verstehen, möchten wir zunächst kurz darstellen, wie sich die Dinge aus unserer Sicht entwickelt haben.

Wir waren nicht sehr verwundert, als das Projekt [**PEPP-PT**](https://www.pepp-pt.org/) [**P**an-**E**uropean **P**rivacy-**P**reserving **P**roximity **T**racing] vorgestellt wurde, denn bereits bei der Auszeichnung des #WirVsVirus Hackathons wurde kommuniziert, dass an einer Lösung von offizieller Seite gearbeitet wird. Uns ist klar, dass in gewisser Weise nicht voraussehbar war, wie weit die Teams hinsichtlich des Tracing-Themas an einem Wochenende voranschreiten können. Dennoch sind wir davon ausgegangen, dass spätestens, als sich herausstellte, dass eine Menge hoch qualifizierter Entwickler, Datenschutzverantwortliche und andere Experten an den Projekten beteiligt sind, ein gemeinsamer Diskurs entstehen würde. Unser Ziel dabei war es immer, eine Kooperation herzustellen, um keine Silos aufzubauen, die zu verschiedenen Lösungen führen würden. Die Bewältigung der Herausforderungen kann nur funktionieren, wenn die Akzeptanz in der Gesellschaft groß ist – und ein Konsens hinsichtlich eines Standards herrscht. Leider blieben unsere Bemühungen, Kontakt zum Robert-Koch-Institut sowie anderen Stellen, die am PEPP-PT Projekt mitwirken, unbeantwortet. Wir sind letztlich zu dem Ergebnis gekommen, dass nur ein gemeinsamer Standard, der länderübergreifend funktioniert und in verschiedene Apps übersetzt werden kann, funktioniert.

Da wir nur Zugang zu den bisher veröffentlichten [Dokumenten](https://404a7c52-a26b-421d-a6c6-96c63f2a159a.filesusr.com/ugd/159fc3_878909ad0691448695346b128c6c9302.pdf) haben, können wir auch nur dazu ein Statement verfassen.

Die Beschreibung des Protokolls ist sehr lückenhaft und daher nicht ohne Spekulationen möglich, weswegen wir hier eher aufzeigen möchten, wieso wir unseren bisherigen Weg weiter gehen werden.

Unser oberstes Ziel ist es, die Privatsphäre von jedem Nutzer zu schützen. Weil das besonders dann schwierig ist, wenn viele Daten anfallen können, wird Privacy Engineering benötigt. Je mehr Daten zur Verfügung stehen, desto einfacher wird es, diese zu einem großen Bild zusammenzufügen und einzelne Personen zu identifizieren. Daher müssen wir es vermeiden, die Daten der Kontakte einer Person zu veröffentlichen, sondern lediglich die zufälligen IDs der betroffenen Person selbst. In unserem Protokoll haben wir vorgesehen, dass der Datenabgleich auf den lokalen Geräten der Nutzer stattfindet. So, wie es bisher in den Medien und in den Projektpapieren des PEPP-PT Teams dargestellt wird, wird der Datenabgleich auf dem Server gemacht. Dies gilt es aus unserer Sicht zu vermeiden.

Der Grund dafür ist folgender: zwischen den PIDs einer einzelnen Person oder mehrerer Personen gibt es keine Korrelation, jedoch aber zwischen den Menschen, die man getroffen hat. Je mehr Menschen erkranken, desto mehr Kontaktdaten liegen dem Server vor – dadurch lassen sich personalisierte Ströme aufzeichnen.

Durch den hohen Schutz der Privatsphäre müssen wir verschiedene Kompromisse eingehen, weshalb unser Protokoll in der aktuellen Version sicher nicht perfekt ist. Durch die hohe Privatsphäre ist die Datenlast für die Prüfung, ob man infiziert ist oder nicht, höher als bei dem Ansatz von PEPP-PT. Wir haben schon verschiedene Möglichkeiten ausgearbeitet, um diese Datenlast zu minimieren, die jedoch immer eigene Kompromisse mit sich bringen. Aktuell geht es jedoch darum, möglichst zeitnah eine Lösung zur Hand zu haben um das Leben wieder in normale Bahnen zu lenken. Wir haben viele Ideen zur Optimierung des Protokolls. Deren Anonymisierung ist jedoch nicht ganz so einfach und benötigt daher mehr Zeit in der Entwicklung.

Wir wünschen uns eine simple, nachvollziehbar anonyme Lösung und arbeiten daher weiter an der Implementierung von [**STRICT**](https://github.com/ito-org/STRICT) [**s**imply **tr**ack **i**nfe**ct**ions] – in der Hoffnung, dass STRICT zu einem besseren Standard beiträgt.

