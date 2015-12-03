GWS, the GrottWorkShop system
=============================

I hold in my hand, two things, some computer paper made by a paper mill called Georgia-Pacific and
a ball-point pen. Both made by combining raw material and natural processes with human management.

They are of 100% quality due to the beliefs and science that we can know and have knowledge of a
system and use that knowledge to fine-tune that system where natural processes and human intervention
mix. Like high quality manufactured goods, the GWS system starts with a theory of knowledge of systems.

C.I. Lewis, the philosopher, came up with a theory of knowledge of systems that basically data can
be studied and analyzed to develop an understanding of how system or group of systems works.
The GrottWorkShop system has this philosophical basis.

Because the GWS system manages a set of development processes producing code, the quality of code matters.
One of the things that new developers do not realize is that the maintenance of code quality even with
modern IDE's is still a manual affair. Thus, I have this manual habit of reducing errors and warnings
in the IDE when I have java class open to either the desirable green flag with zero warnings and
zero errors or a yellow flag with only 5 to 3 warnings.

Adn those errors and warnings come from two places, the java compiler and the Android Lint Check tool.
Due to that fact I keep my Lint options file to a minimum so that I get the full amount of Android Lint
warnings and thus I am forced in my manual code quality process to research those Lint warnings and
reduce them through improvements in code quality.

The other thing that affects code quality is the affect code organization has on what can be tested
and improved through testing. Through code organization you want to be able to unit test the
User-Interface units through instrumented testing on the device or emulator and be able to
plain jvm unit test what is not the user-interface which should by your code organization be only
Plain-Old-Java-Objects.

Thus I use Inversion-of-Control, MVVMB, MVPB, and other OOP compound patterns to organize the
application code into distinct layers of control.

At the core of this GWS System is a gradle set of build scripts that allows me to daily and weekly
build the application-in-progress. This gradle build system incorporates some debug tools such as a
layout transversal tool to measure layout rendering times which I then use to decide on whether or
not to build a custom view-group to improve those layout transversal rendering times.
The GWS gradle build scripts also incorporate some design debug tools so that I can focus on particular
visual aspects of the user-interface and fine-tune them.

And of course there is the manual process of breaking down one-week and two-week sprints into
manageable feature units so that I get a working prototype milestone at the end of the sprint every
time without fail. Because I have both cleaned up back-ported user-Interface libraries and have
developed utility libraries for every layer of concern in the application, I thus know how every
component will fit and thus its easy to see how to break down a complex android application into
manageable one-to-two-week-sprints.

Lastly, I fully believe that one should have some hours devoted to the non-coding work of getting
feed-back from stake-holders and or alpha prototype users of the android application. Those are the
mini-meetings that matter in developing an android application. I find that if I reduce my commute
to work from being forced to work on-site with 2 to 3 hours both way commutes to a situation where
I remotely completed the android application code as that 15 hours saved on commuting than can be
applied to those all-important mini-meetings with stake-holders and the application users as that
feed-back is as valuable as the feed-back generated from unit testing.

And that is the GWS Best Practices and the GWS System I use.
