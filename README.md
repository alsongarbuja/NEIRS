# NEIRS (Nepal Educational Institutes Ranking system)

NEIRS short for Nepal Educational Institutes Ranking system is an open source, independent entity created soley by me [Alson Garbuja](https://alsongarbuja.com.np) for the sole purpose of creating a system that can rank educational institutes from Nepal within Nepal.

> [!Warning]
>
> The project is conceptualized only and not a single line of code is written till now. I wanted to cover the difficult part of the project first which is to define the ranking system and its different mertics to standarize the ranking.

### Table of contents

- [Reason behind NEIRS](#reason-behind-neirs)
- [Introduction](#introduction)
- [Current ranking situtation for nepali institutes](#current-ranking-situation-for-nepali-eduacational-institute)
- [Ranking system](#ranking-system)
- [Tech stack](#tech-stack)
  - [Frontend](#frontend)
  - [Backend](#backend)
  - [UI/UX](#uiux)
  - [Testing](#testing)
  - [Security](#security)
  - [Production and Devops](#production-and-devops)
  - [Others](#others)
- [Contributions](#contribution)

## Reason behind NEIRS

> [!Warning]
>
> The back story is quite long, I got carried away writing it, so if you don't want to read all the reason behind why i started NEIRS, long story short: do not like the quality of education system in Nepal, came across youtube video about ministor sumana shrestha answering some questions from TU students probably, inspired by the statements of her "there is no competition and incentives for institutes to better their standards, need a independent entity to rank them" and here I am.

The education system in Nepal has been poor for the past decades or so. It is not suprising to why standards of education has gone below average in comparision to international education due to various reasons, one being the landlockness of Nepal.

But to see the standards being so low many young generations students simply walk right past the higher education opportunities in Nepal and choose international education in a heart beat. **(One of them being myself)** is sad.

I used to talk quite a lot about how the quality of education in Nepal is bad with my friends and a lot things should be done to improve it, though I didn't really understood in depth the huge economics behind education system and was not taking any actions either.

In 2024 Dec 10, I came across a [Youtube video by The untold](https://youtu.be/q5jGMqVW9qU?si=CRNUqsEUeTcdlZdU) channel with Ministor Sumana Shrestha. They gave her a mystery box which contained questions from probably students of TU on educational system of Nepal. Around [7:49](https://youtu.be/q5jGMqVW9qU?si=eXpaeK_JaYk_H6uW&t=469) into the video and she said

> "there is no incentives for universities and colleges to compete since there are no ranking of the institutes."

She also adds

> "there must be a separate entity that is not linked with any institutes and political parties who should be responsible for ranking them"

It hit me, while searching for universities to choose from for my higher education in abroad many friends and families said to look for universities that has higher ranking, it will be better for future. Most international universities and colleges have ranking of within the country, state as well as internationaly among them which lead to competition, ultimately to innovations and standards for quality education. But in case of Nepal, there is no ranking let alone competiton among them.

So being a geek and a good citizen of Nepal _(at least I view myself as one)_, I wanted to create a system where Institutes of Nepal can be ranked within themselves and provide future students with options to choose from and hopefully rise some competition among institutes for better education and quality of knowledge they provide.

## Introduction

NEIRS is an open source ranking system for all the educational institutes that are running in Nepal.

Education system of Nepal has been pretty bad and there is no denying the fact they have low quality standard. In order to create an incentive, a purpose _([look reason section for in depth answer to why](#reason-behind-neirs))_ for all the institutes to compete and improve thier quality in education, I am developing this open source project NEIRS.

At its core, it is a `ranking system` which will rank listed universities, colleges and private institutes based on different metrics ranging from teaching prespective to facilities and academic acheivements.

## Current ranking situation for Nepali Educational Institute

In the meantime I am developing this project there are no any official ranking system or process held for Nepali educational institutes. Although there are world rankings where only handfull _(at most 9 or 10)_ universities are listed and clearly they are way below other institutes worldwide, there is no any system that takes into every institutes of Nepal and rank them properly in context of Nepal.

Some world ranking systems where nepali institutes can be spotted are as follows:

- [Times higher education](https://www.timeshighereducation.com/)
- [Webometrics](https://webometrics.info/en)
- [UniRank](https://www.4icu.org/)

There are some articles and blogs written by few education related websites and projects regarding the ranking of Nepali institutes but they only showcase or use the ranking provide by the above mentioned systems or other resources.

E.g: [Edusanjal's blog post](https://edusanjal.com/blog/rankings-of-universities-operating-in-nepal-times-higher-education/)

But one thing I noticed looking into all those ranking system they are inconsistent. For example in the times higher education the **KU** is ranked top in Nepal while in webometric **TU** is ranked top among Nepali institutes. _(which can be due to different metrics they use to rank them)_

Another thing is only few universtities around 8 or 9 are listed in those systems **(expect for webometrics which suprisingly list over 30 institutes, kudos to them)**. It is due to fact that universities and colleges must be submitted to those systems and most likely nobody is doing that.

## Ranking system

The `Ranking system` core of the project, will be an algorithm that calculates the score for each institutes listed in the system using various metrics and data points.

As of now, while I am planning out the project these are some metrics to rank institutes:

1. **Teaching**: Score the teaching cabailities of the institutes.
2. **Facilities**: Score the facilities they provide to support their education like labs, internets, etc
3. **Ratios**: Score the facilities on the basis of ratios in different sectors like male to female student ratio, graduate to non graduate ratio, etc
4. **Capaicty**: Score the capacity like number of teachers per students, classes held per semester, etc
5. **Academic**: Score them based on the available courses and the performance of students in them.
6. **Popularity**: Score based on the popularity of the institution _(only minor impact overall)_

For data and surveys, here are some ideas:

- Google form survey
- Google ratings
- Usage of AI/ML for collecting resources of the insititutes

## Tech stack

For all the geeks and nerds out there who wants to contribute to the system or simply curious what I used to build the project here is a deep breakdown of technologies I have used.

#### Frontend

#### Backend

#### UI/UX

#### Testing

#### Security

#### Production and Devops

#### Others

## Contribution

> [!Warning]
>
> This is only a initial documenation for project and I am not actively looking for any contribution in this phase. Though you are more than welcome to mail me any suggestions and feedbacks. I just created a gist of every thing since I was so into documenting this project.

Any contribution is welcomed. It is an open source project and it can be better with all the help it can get.

There are multiple ways you can contribute:

#### Reporting

You can report or submit data about any institute you have been to or are currently a part of through the [Google form Survey](), or you can email me directly at: [magar33alson@gmail.com](mailto:magar33alson@gmail.com).

You can also suggest any institutes that are not listed in the system.

#### Code

You can fork the project, purpose any changes or fix any bugs or isssues and send a PR.
