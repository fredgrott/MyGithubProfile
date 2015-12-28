GWS, the GrottWorkShop System
=============================

I hold in my hand, two things, some computer paper made by a paper mill called Georgia-Pacific and
a ball-point pen. Both made by combining raw material and natural processes with human management.

They are of 100% quality due to the beliefs and science that we can know and have knowledge of a
system and use that knowledge to fine-tune that system where natural processes and human intervention
mix. Like high quality manufactured goods, the GWS system starts with a theory of knowledge of systems.

C.I. Lewis, the philosopher, came up with a theory of knowledge of systems that basically data can
be studied and analyzed to develop an understanding of how system or group of systems works.
The GrottWorkShop system has this philosophical basis.

# Core of the GWS System

* Continuous Integration Building

  I combine a well developed and tested set of gradle build scripts with a set of android best practices
  in project structure along with some customized tools and libraries so that I get daily builds of any
  project I work on and can break-down any project into weekly milestones.

  Testing is also part of this build system in that either I am fully junit testing or testing components
  by building a sample application or some other form of testing the components before i rely upon using
  them in some project.

* Manual Compiler/Android Build Tools Error and Warning Decision Process

  We have come a long way as far as computer application building technology but still some of the process
  still requires manual decisions. The manual decision process of the GWS System relies upon how the
  IDE shows errors and warnings of the Android Application build tools and than I make a decision
  on whether code must change based upon java and android application development best practices.

  This is important as some errors and warnings are there to indicate the full system will not fully compile
  the application and other warnings might indicate that a developer decision increases bad performance of the
  application, running things on the wrong thread, etc.

  A mark of quality java developer is a reduction of these errors and warnings that show up in the IDE to
  no ERRORS and 1 to 5 warnings. In other words either a green check in the IDe or a little yellow warning
  box.

  Because the under-lying technology of the Android Device hardware and the Android OS itself changes,
  I am always updating my Android Java Best Practices to update to the changing Android Device environment.
  An example is how I write concurrent Java code to handle two or more CPUs in the device. But, there are
  other areas it impacts as well, for example now due to the power of the minimum Android Device we can
  in fact use enums and slightly relax the rule on not using getter and setters.

* Art Of Debugging

  My style of debugging is different, in that because I am breaking things down to the smallest component
  to test the effort of debugging is somewhat easier as it serves to remove the amount of noise I see
  when I debug so that I than see only what is important error in my debugging process.


* Process and Tool Usage to Fit the Problem

  Not every developer problem can be solved with every process and tool. I first do a system-analysis type
  analysis of what the problem represents as challenges and than choose the processes and tools that are
  most-likely for me to reach some short-term and and long-term goals of that project development.

  This also extends to determining if the proposed Android Application Development will reach the
  short-term and long-term goals of the firm requesting the development of the Android Application.
  For example, creating an Android Application does not always dramatically increase the amount of users
  using a service and if the firm system and process has barriers to viral-ability than adding an Android
  Application to accessing the service will not reach the firm's goals.

* A Set of Well Maintained And Developed Libraries

  Everyone that is non-tech likes going to a hack-a-thon and getting to see an application magically
  develop right before their eyes seemingly in 24 to 48 hours.  What really is at-work-here is that the
  developers who have participated in the hack-a-thon have developed a system of preparation whereas they
  build all the GUI and other components of every imagine-able application.

  The Android Applications that do well in the mobile application stores have a common set of UI components
  that have been customized and or created anew in addition to the UI and application components found in
  the Android SDK and or NDK.

  Thus, I have developed my own set of UI and Application component libraries for Android Java Application
  development based upon analyzing popular Android Applications in the Google Play Store.  These same
  libraries are integrated into my development process as well so that I can in a realistic manner prevent
  such things like user information leakage in logging statements, etc.

  THE IMPORTANT THING TO YOU is that this means I can fast prototype Android Applications. For example, if one
  needs a fast Android Application Prototype to validate a market concept than I can possibly complete
  that in some weeks instead of the normal iPhone development of 6 months to get a polished mobile application.
  Thus the user while helping test the market concept still is experiencing a polished application and thus
  you do not loose the user retention by having the user use the application prototype.



That is the core part of the GWS System. And now the rest of the Android, Java, and Software Engineering
Best Practices, Processes, and development technology get combined on top of this core such as:

* Annotation Processing Tool Development

  At times I need in android application development to re-establish the boundaries of the scope of android
  application structures so that I can keep the amount that I have to instrumented-test to a minimum.
  I create annotation processing tools that combined with some coding libraries allows me to do this.

* Aspect Code Generation Development

  At other times solving the same set of problems of re-establishing the boundaries of the scope of android
  application structures so that I can keep the amount of instrumented-testing that I have to complete
  to a minimum requires a heavier solution such as code generation. i sue aspect code generation
  for that purpose.

* Custom Lint Rule Development

  In java application development developers use a tool called PMD to catch the type of java development
  errors that people who use human languages my say are grammatical in nature. In Android Application
  development we use a tool called the AndroidLint tool instead.

  Google develops the core set of Android Lint Rules, but at times I custom create my own set of additional
  Android Lint Rules that are specific to some of my android application development processes as it
  reduces the amount of coding errors and thus saves time in debugging, etc.

* Custom UI and Android Application Components

  I create and customize new View and Widget UI components along with other Android Application components
  that can be combined in modular ways similar to how you might have built houses and cars out of Legos
  when you were a child.

* Agile Software Engineering Methods ToolBox

  I use the term tool-box as there are benefits and cons to using each tool in this tool box and thus
  I am dynamically choosing which set of tools in are most apt to be correctly useful to solving the
  software creation process at-hand.


That in a-nut-shell is the full GrottWorkShop System of Android Application development.