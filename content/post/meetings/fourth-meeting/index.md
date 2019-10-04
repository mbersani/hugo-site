---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Fourth Meeting (2019/04/02)"
subtitle: "Minutes"
summary: ""
authors: []
tags: []
categories: [Meetings]
date: 2019-04-02
lastmod: 2019-04-02
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
#projects: []
---

As we are all over the world, for some the (skype) meeting took place on April
2nd and for some on April 3rd. Present at this meeting: Rustan Leino (US,
Seattle), Catherine Dubois (France, Paris), Pierluigi Sanpietro (Italy,
Milano), Luigia Petre (Finland, Turku), Kenji Taguchi (Japan, Kyoto), Graeme
Smith (New Zealand).

Bernd Fisher stepped down the committee as he became head of his department at
Stellenbosch University, in South Africa.

We had two points to discuss at this meeting:

 1. The FMTea19 workshop webpage and call for papers (CfP), to be released soon
 2. The course repository – future changes

## Point 1
There were no suggestions for the webpage update, except to include the
tutorial programme as  soon as we can. The tutorial program is quite stable at
this point, having the following main structure:

  Time        | Talk
  ----------- | --------------------------------------------------------------------
  9-10        | Carroll Morgan (invited talk)
  10-10.45    | Tony Hoare (foundations talk)
  10.45-11.15 | Break                        
  11.15-12    | Holger Hermanns (tutorial on teaching concurrency with pseuCo.com) https://depend.cs.uni-saarland.de/~hermanns/, https://pseuco.com/#/landing 
  12-12:45    | Bas Luttik (tutorial on online teaching Logic and Set Theory) https://www.win.tue.nl/~luttik/index.shtml 


Regarding the first paragraph of the CfP, Rustan suggested it is abit too
gloomy, at least from the industry’s point of view. Graeme argued that the
situation is however far from pink in universities. So Rustan wrote a new
beginning of the CfP proposal, which at least I like very much. 

### Old version:

> “Teaching Formal Methods is an important aspect of the Formal Methods world, as
> it invests in the future of Formal Methods (FM). However, in many universities
> around the world, Formal Methods courses have decreased in number and/or
> content, have been transformed into (smaller) postgraduate courses, or have
> been kept only as self-study courses for truly motivated students. Even in
> universities where the courses have remained intact in the curriculum, the
> attendance and motivation of the students is sometimes challenging. This
> happens at the same time as the need for Formal Methods has in fact increased
> proportionally with the ubiquity of software and microchips in all aspects of
> our lives. 
> We need to find ways to teach Formal Methods to the next generation, but we
> obviously need to adapt our teaching to the 21st century’s students. We will
> explore these ideas in FMTea19, a combined workshop and tutorial associated
> with the 3rd World Congress on Formal Methods, FM2019.”

### New proposal:

> “Formal Methods provide software engineering with tools and techniques for
> rigorously reasoning about the correctness of systems. While in recent years
> formal methods are increasingly being used in industry, university curricula
> are not adapting at the same pace. Some existing formal methods classes
> interest and challenge students, whereas others fail to ignite student
> motivation. We need to find ways to teach formal methods to the next
> generation, and doing so will require us to adapt our teaching to 21st century
> students.
> FMTea19 is a combined workshop and tutorial at the 3rd World Congress on Formal
> Methods, FM2019. Its aim is to share experiences of teaching formal methods
> that have gone well, or that failed in surprising ways, as well as to develop
> ways to reboot the presence of formal methods in curricula.”
> 


## Point 2
About the course repository, the opinions were unanimous that we should choose
the format proposed by Alexandra and Joao. They have revived a 10-year old
database of formal methods courses (117 courses) and discovered that only 20
are still alive:

 - Old database: https://jff.github.io/fme-teaching/courses_all/  
 - Only 20 courses out of 117 are still active: https://jff.github.io/fme-teaching/courses_live/     

They have also re-written our current repository in their format: https://jff.github.io/fme-teaching/ 

The proposal is to move to this new format, but to find a way to add the
university, country and teaching year. We should also find a way of
re-organizing the topics, as right now every course has its own topics
basically. And we should be able to search based on everything (teacher,
country, etc). If possible :-)

Graeme observed that, when clicking on the course taught by Jeff Sanders
(Application Oriented Program Semantics), this leads to an alphabetical list of
courses at Oxford. This course seems to have disappeared. The same with Domain
theory. I have clicked on other Oxford courses and it’s the same: Lambda
Calculus leads to the same alphabetical list of courses, and when searching for
the course, I found that it’s not A. Ker who teaches it anymore, but somebody
else who uses the lecture notes of A. Ker. The webpage for  “Formal Methods for
Software Engineering” is also gone. So maybe we should check them once more.
Finally, we should implement a way of checking annually if courses are still
alive. Maybe collect all contacts in a group email, or something in that
direction.


