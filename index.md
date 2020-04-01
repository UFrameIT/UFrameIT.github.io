## Detangling Knowledge Management from Game Design in Serious Games

UFrameIT is a framework for building serious games by combining the exploration of virtual worlds with logic-based knowledge management. 

The UFrameIT project initiated by the [KWARC Research Group](https://kwarc.info) at [FAU Erlangen-Nürnberg](https://fau.de). 

More information is also available at the [KWARC project page](https://kwarc.info/systems/frameit) and within our [publications](https://kwarc.github.io/bibs/frameit/).

#### The [Jacobs University](https://jacobs-university.de) Phase

The idea behind UFrameIT (using MMT pushouts for scroll application) was already formulated in a [paper in 2012](http://kwarc.info/kohlhase/submit/activeex-2012.pdf).
A very first version was implemented in [a 2013 bachelor thesis](https://gl.kwarc.info/supervision/BSc-archive/-/blob/master/2013/rachev_daniel/project/thesis/thesis.pdf).
In 2015/6, Denis Rochau gave a complete implementation based on the [Unreal Engine](https://www.unrealengine.com) ([Bachelor's Thesis](https://gl.kwarc.info/supervision/BSc-archive/blob/master/2016/rochau_denis.pdf); [CICM Work-in-Progress Paper](http://ceur-ws.org/Vol-1785/W50.pdf),  [demo video](https://gl.kwarc.info/FrameIT/CICM16-WiP/-/blob/master/Screen%2005-12-2016%2020-17-23.avi)).

#### UFrameIT at [FAU Erlangen-Nürnberg](https:.//fau.de)

After a long period, where students got frustrated with the complexities of the unreal engine and its documentation, a group for FAU students got together in late 2019 to restart the project using the [Unity game engine](https://unity.com) as a basis. The UFrameIT framework is the result of this effort. 

#### The Framework
In the FrameIT method, we use [MMT](https://kwarc.info/projects/mmt) theory graphs to represent the background knowledge
and [MMT](https://kwarc.info/projects/mmt) pushouts to compute the application of knowledge in concrete situations, whereas we use Unity to create the virtual world.

Accordingly, the [repository](https://github.com/UFrameIT) splits the framework implementation into two parts: the [Unity part](https://github.com/UFrameIT/UFrameIT) and the [server](https://github.com/UFrameIT/mmt-server), which acts as an interface to the [MMT system](https://github.com/UniFormal/MMT) and thus the [formalized knowledge](https://gl.mathhub.info/FrameIT).



#### Demo Video

<iframe width="560" height="315" src="https://www.youtube.com/embed/98D2PYgflPw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

#### The 2016 Version

<video src="https://github.com/UFrameIT/UFrameIT.github.io/blob/master/FrameITVideoOld.mp4?raw=true" width="320" height="200" controls preload></video>



#### Try it out yourself

1. Get the latest [Release](https://github.com/UFrameIT/UFrameIT/releases).
2. Download and extract the ZIP file.
3. Open the Build folder and start FrameWorld1.exe

#### [The FrameIT Team](people.md)


#### Support or Contact

Feel free to raise an issue at our [UFrameIT/UFrameIT repository](https://github.com/UFrameIT/UFrameIT/issues).
