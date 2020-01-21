+++
title = "Writing Messy Code"
# publish date
date = 2020-01-20T15:48:58-05:00
# whether or not the post is a draft
draft = false
#  Short description of the document (limit to 150 characters)
# This content *may* be used as a part of search engine results.
description = 'Writing messy code in the pursuit of perfection.'
+++

As part of my goal to write more messy code this year I've been writing small programs on the weekend with a one hour timer next to me. The idea is to give myself a small amount of time to output as much as possible without getting bogged down in the details.

The motivation for the exercise comes from a parable I found on [stratchery](https://stratechery.com/2015/buzzfeed-important-news-organization-world/) about a ceramics teacher who grades on two scales *quantity* and *quality*.

> The ceramics teacher announced on opening day that he was dividing the
> class into two groups. All those on the left side of the studio, he said,
> would be graded solely on the quantity of work they produced, all those on
> the right solely on its quality.
>
> His procedure was simple: on the final day of class he would bring in his
> bathroom scales and weigh the work of the “quantity” group: fifty pound of
> pots rated an “A”, forty pounds a “B”, and so on. Those being graded on
> “quality”, however, needed to produce only one pot – albeit a perfect one –
> to get an “A”.
>
> Well, came grading time and a curious fact emerged: the works of highest
> quality were all produced by the group being graded for quantity. It seems
> that while the “quantity” group was busily churning out piles of work – and
> learning from their mistakes – the “quality” group had sat theorizing about
> perfection, and in the end had little more to show for their efforts than
> grandiose theories and a pile of dead clay.[^c]

Programmers are always trying to strike a balance between writing features quickly, and writing features with good design principles and solid abstractions. The best programmers can do both, but for most people there is a tradeoff. 

When I first started computer science I spent lots of time on [CheckIO](https://checkio.org/) finding ways to write code which was fast and short. CheckIO has categories for speed, clarity, and length and I was always interested in *high speed* and *brevity*. In those early days my programs were only 10-20 lines long. I could spend 30 minutes obsessing over a short algorithm and have 6 toy programs done in an afternoon.

About six months after I started exploring computer science I was granted the opportunity to work in [Andy van Dam's](https://en.wikipedia.org/wiki/Andries_van_Dam) [graphics lab](http://ptc.cs.brown.edu/#/). I was placed on a codebase with ten other students. The codebase was in C# and probably had around 30K lines of code when I joined. It was by far the most complicated piece of code I had come across.

Having learned how to code in python I became enamored with C#'s type system, classes, and object oriented programming. On the weekends I read about software design patterns like MVC, MVVC, Abstract Factories, and Singletons. I pirated a copy of [the Gang of Four Design Patterns](https://www.amazon.com/Design-Patterns-Object-Oriented-Addison-Wesley-Professional-ebook/dp/B000SEIBB8) and read it on the plane.

As I spent more time working with real world data I began to write `assert` statements everywhere. By implementing design patterns in the code base I was able to keep things [loosely coupled](https://en.wikipedia.org/wiki/Loose_coupling) and [DRY](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself).

Although I became great at writing structured and extensible code I lost the ability to write code quickly. Nowadays I don't have as much time for pleasure programming. My life is busy, my attention span is short. If I want to implement something for fun I need it to be done in a weekend, preferably in less than an afternoon.

I'm now trying to write code without paying as much attention to design patterns and optimizations. I'm trying to build things that work. Over the past two weekends I built a song exploration site in react and an asynchronous api scraper in python. The scraper was written in an hour, The song exploration site was written in a couple of 2-3 hour chunks over the course of the weekend.

Both programs have small issues that I could fix but they exist now and I'm free to move on and enjoy other things.

Happy Hacking

<!-- [^tc]: [Thinking Concurrently](https://www.linuxjournal.com/content/thinking-concurrently) -->

[^c]: [Why Buzzfeed is the Most Importand News Organization in the World](https://stratechery.com/2015/buzzfeed-important-news-organization-world/)