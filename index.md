## Overview

UFrameIT is a framework for building serious games by combining the exploration of virtual
worlds with logic-based knowledge management (... [details](#the-uframeit-framework),
[publications](https://kwarc.github.io/bibs/frameit/), [news](#recent-news-see-all))

The [UFrameIT project](https://kwarc.info/systems/frameit) was initiated by the [KWARC Research Group](https://kwarc.info) at
[FAU Erlangen-Nürnberg](https://fau.de) (... [history](#history), [team](#frameit-team), [news](#recent-news-see-all)). 

<iframe width="560" height="315" src="https://www.youtube.com/embed/98D2PYgflPw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

[... more videos](#demo-videos)

## Try it out yourself

You can find built executables here: [UFrameIT releases](https://github.com/UFrameIT/UFrameIT/releases).

Currently, we only have a distributable package for Windows. Other operating systems are already supported under the hood, but are still awaiting packaging.

## The UFrameIT Framework

In the FrameIT method, we use [MMT](https://kwarc.info/projects/mmt) theory graphs to represent the background knowledge
and [MMT](https://kwarc.info/projects/mmt) pushouts to compute the application of knowledge in concrete situations, whereas we use Unity to create the virtual world.

Accordingly, the [UFrameIT group on GitHub](https://github.com/UFrameIT) splits the framework implementation into two parts: the [Unity part](https://github.com/UFrameIT/UFrameIT) and the [server](https://github.com/UFrameIT/mmt-server), which acts as an interface to the [MMT system](https://github.com/UniFormal/MMT) and thus the [formalized knowledge](https://gl.mathhub.info/FrameIT).

## FrameIT Team

### Current Members
* [Prof. Dr. Michael Kohlhase](https://kwarc.info/people/mkohlhase/) (lead; enjoys the demos) 
* [Richard Marcus](https://kwarc.info/people/rmarcus/) (Unity framework in [UFrameIT][UFrameIT])
* [Navid Roux](https://kwarc.info/people/nroux/) ([mmt-server][mmt-server] and MMT formalizations)
* John Schihada (Unity gadgets in [UFrameIT][UFrameIT], [mmt-server][mmt-server])

### Former Members 
* Benjamin Bösl ([mmt-server][mmt-server], MMT formalizations of [FrameWorld v1][FrameWorld]) 
* Denis Rochau (first Unreal-based FrameIT implementation) 

### Advisors
* [Dennis Müller](https://kwarc.info/people/dmueller/) ([MMT][MMT] and Formalization Guru)
* [Prof. Dr.-Ing. Marc Stamminger](https://www.lgdv.tf.fau.de/person/marc-stamminger/)
  (Graphics/Virtual Worlds)

[FrameWorld]: https://gl.mathhub.info/FrameIT/frameworld
[MMT]: https://uniformal.github.io/
[mmt-server]: https://github.com/UFrameIT/mmt-server
[UFrameIT]: https://github.com/UFrameIT/UFrameIT

## History

#### The [Jacobs University](https://jacobs-university.de) Phase

The idea behind UFrameIT (using MMT pushouts for scroll application) was already formulated in a [paper in 2012](http://kwarc.info/kohlhase/submit/activeex-2012.pdf).
A very first version was implemented in [a 2013 bachelor thesis](https://gl.kwarc.info/supervision/BSc-archive/-/blob/master/2013/rachev_daniel/project/thesis/thesis.pdf).
In 2015/6, Denis Rochau gave a complete implementation based on the [Unreal Engine](https://www.unrealengine.com) ([Bachelor's Thesis](https://gl.kwarc.info/supervision/BSc-archive/blob/master/2016/rochau_denis.pdf); [CICM Work-in-Progress Paper](http://ceur-ws.org/Vol-1785/W50.pdf), [demo video](https://gl.kwarc.info/FrameIT/CICM16-WiP/-/blob/master/Screen%2005-12-2016%2020-17-23.avi)).

#### UFrameIT at [FAU Erlangen-Nürnberg](https://fau.de)

After a long period, where students got frustrated with the complexities of the unreal engine and its documentation, a group for FAU students got together in late 2019 to restart the project using the [Unity game engine](https://unity.com) as a basis. The UFrameIT framework is the result of this effort. 

## Demo Videos

### Most Recent
<iframe width="560" height="315" src="https://www.youtube.com/embed/98D2PYgflPw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### The 2016 Version
<iframe width="560" height="315" src="https://www.youtube.com/embed/GWuySbzJUwQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Support and Contact

To contact a human: reach out to [Michael Kohlhase](https://kwarc.info/kohlhase).

Feel free to raise an issue at our
[UFrameIT/UFrameIT repository](https://github.com/UFrameIT/UFrameIT/issues) or a question
on our [MatterMost FrameIT channel](https://mattermost.kwarc.info/kwarc/channels/frameit).

## Recent News ([see all](/news/))
 
<ul class="collection">
    {% for post in site.posts limit:5 %}
        {% include post_link.html post=post %}
    {% endfor %}
</ul>
