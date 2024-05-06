---
layout: default
title: "Teaching notes"
has_toc: true
nav_order: 1
---

# Teaching notes

{: .highlight }
The teaching notes include materials for the instructor and teaching assistants.

## Week 1: Introduction, topics, and groups

VC post:

> Sehr geehrte Studierende,
> 
> herzlich willkommen zum WI-Projekt der Juniorprofessur für Digital Work.
> 
> Sie finden alle administrativen Informationen sowie Unterlagen hier im VC-Kurs. Bitte beachten Sie, dass sämtliche schriftliche Kommunikation sowie alle Informationen hier im VC-Kurs erfolgt bzw. zur Verfügung gestellt wird.
> 
> Bei Fragen zur Veranstaltung können Sie sich gern an mich (gerit.wagner@uni-bamberg.de) wenden.
> 
> Ich wünsche Ihnen eine erfolgreiche Veranstaltung.
> 
> Mit besten Grüßen
> 
> Gerit Wagner

VC post (advertise the project in the lecture):

> Liebe Studierende,
> 
> ich hoffe, Sie hatten nach den Klausuren eine erholsame Zeit und sind wieder gut im Semester angekommen.
> 
> Im aktuellen Semester (sowie im kommenden Sommersemester) biete ich ein WI-Projekt an, bei dem wir mit Python, git und dem GitHub Open-Source Workflow arbeiten. Wenn Sie das WI-Projekt noch nicht belegt haben, können Sie gerne noch kurzfristig dazukommen. Mit git und GitHub sind Sie ja schon vertraut und die Einführung in Python findet nächste Woche statt (Dienstag, 24.10.2023, 08:00 – 12:00 Uhr (WE5/04.003), Donnerstag, 26.10.2023, 14:00 – 18:00 Uhr (WE5/02.020)). Schicken Sie mir bei Interesse gerne eine E-Mail.
> 
> Alles Gute für das WS 23/24!
> 
> Mit besten Grüßen
> 
> Gerit Wagner

## Week 2: Introduction to Git

**In preparation of the session**: check wheter the `rec_dict.patch` applies (`git diff > rec_dict.patch`)


VC post (24.04.24)

> Liebe Studierende,
> 
> wir möchten Sie daran erinnern, dass Sie bis Montag (29.4.) einen Kommentar in den Issue-Feeds hinterlassen.
>
> Ihr Interesse an den Teilthemen können Sie hier im Diskussionsfeeds signalisieren: https://github.com/CoLRev-Environment/colrev/milestone/8.
> 
> Ein einfaches “I would like to work on this issue 🙋” wäre ausreichend.
> 
> Bei Fragen können wir gerne weiterhelfen.
> 
> Mit besten Grüßen
> 
> Ihr Digital Work Team


## Week 3: Introduction to Python

Prepare the `tutorial_YYYY_MM` branch and update the commit-ids in the slides:

```
git branch tutorial_YYYY_MM
git switch tutorial_OLD
# get commit-ids (first and last)
git switch tutorial_YYYY_MM
git cherry-pick ab3715e85fb0219081ff60f6e4918953066bfe6a^..12c2d1730564b99fa11fbb618e92e2b67751e34c
# when the poetry.lock/pyproject.toml fail: checkout --ours poetry.lock/pyprojec.toml, poetry add bibtexparser
```

Keep a copy of branch (assign a `tutorial_backup` branch to the last commit)

Use the [teaching notes](../output/teaching_notes/03_python_1.html)

Create a list of topics and students (first/second choice) and facilitate issue discussions (students forming groups), e.g., with posts like this:

> Thank you, @pmao0907 and @MingxinJiang for offering to switch to #360 . This leaves a group of 3 with @CelinaSchwarz , @omanovb and @QuynhMaiNguyen 👍 Can you select a group lead, fork the repository and link your repository in this feed?

VC post (28.04.24)

> Liebe Studierende,
> 
> zur Vorbereitung unserer Session am Dienstag möchten wir Sie kurz erinnern, dass Sie eine eingerichtete Programmierumgebung benötigen. Wie auf den letzten Slides aus der ersten Session beschrieben, sollten Git, Python und ColRev installiert sein. Der Befehl "colrev init --example" sollte ohne Fehler ausgeführt werden. Es wäre gut, wenn Sie dies auf Ihrem Arbeitsgrät, auf GitHub Codespaces oder einem CIP-Pool Rechner ausprobieren.
>
> Bei Fragen helfen wir gerne weiter. Um Probleme bei der Einrichtung der Programmierumgebung zu unterstützen, bieten wir zudem am "Tag" (Datum) eine offene Session von ... bis ... Uhr an. Kommen Sie bei Bedarf gerne im Büro (WE5/01.081) vorbei!
> 
> Wenn Sie sich im Vorfeld noch mit der Python-Syntax vertraut machen möchten, finden Sie hier ein gutes Tutorial: https://www.learnpython.org/. Der "Learn the Basics" Teil bietet einen guten und interaktiven Überblick.
> 
> Wir freue uns auf die kommende Session mit Ihnen!
> 
> Beste Grüße & ein schönes Wochenende
> 
> Ihr Digital Work Team

## Week 4: Group work (no session)

Reminder for merge: 08.05. (linking to resources)

Distribute the [survey](../assets/Interim_Project_Assessment_Survey.docx) via VC, asking students to upload it (upload box).

VC post (10.05.24)

> Liebe Studierende,
>
> zur Vorbereitung der Best Practice Session würden wir Sie bitten, die Umfrage die im VC gepostet wurde herunterzuladen und auszufüllen.
>
> Nachdem Sie die Umfrage ausgefüllt haben, bitten wir Sie diese bis zum 12.5 auszufüllen und im PDF Format hochzuladen.
>
> Somit können wir die Session noch an mögliche Problem von Ihnen anpassen.
>
> Wir freuen uns auf die nächste Session mit Ihnen am 15. Mai!
>
> Beste Grüße und eine erfolgreiche Woche
>
> Ihr Digital Work Team
> 

## Week 5: Best practice session

TBD: Make cheatsheets ([git](../teaching_notes/cheatsheet_git.md), [python](../teaching_notes/cheatsheet_python.md), [colrev package development](../teaching_notes/cheatsheet_colrev.md)) available?

## Week 7

VC post (27.05.24)

> Liebe Studierende,
>
> wir möchten Sie nochmals auf das Angebot der Hacking Sessions verweisen.
>
> Diese können Sie einfach unter diesem Link buchen.
>
> Beste Grüße und weiterhin Viel Erfolg beim Projekt
>
> Ihr Digital Work Team


## Week 11

VC post (23.06.24)

> Liebe Studierende,
>
> wir möchten Sie nochmals an die Abgabe am 26. Juni hinweisen.
>
> Beste Grüße und weiterhin Viel Erfolg beim Projekt
>
> Ihr Digital Work Team

## Week 12: Code review session

<!-- 
Liebe Studierende,

die Scheine liegen abholbereit im Sekretariat (WE5/01.029) bei Frau Gehringer. Sie können Montag/Mittwoch/Donnerstag zwischen 10 und 13 Uhr bzw. Dienstag zwischen 11 und 13 Uhr abgeholt werden. Die Scheine können bei Herrn Kipphan (WE5/01.078) eingebracht werden (Montag 13-15 Uhr, Mittwoch 9.30-11.30 und 13-15 Uhr).

Die ersten Pull-Requests sind gemerged. Sie können gerne einen Blick auf meine abschließenden Änderungen werfen. Sprechen Sie mich bei Interesse an der Nutzung oder Weiterentwicklung von CoLRev, z.B. im Rahmen einer Abschlussarbeit, gerne an!

Die Evaluation sollten Sie ebenfalls erhalten haben - ich würde mich freuen, wenn Sie sich die Zeit nehmen und mir ein Feedback zur Veranstaltung geben.

Mit den besten Wünschen für eine erfolgreiche Klausurenzeit und eine erholsame vorlesungsfreie Zeit,

Gerit Wagner
-->
