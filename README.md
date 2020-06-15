Tizen Development: Signal App
=============================

I'm a long time fan of the Signal Private Messenger application, and a relatively new owner of the Samsung Galaxy Watch. I use the watch exclusively; without the phone. Unfortunately, there is not a native Tizen application to run on the watch, which means that I can no longer use Signal; this is completely unacceptable.

I am new to Tizen development, and I have not yet worked with the Signal Private Messenger SDK. Therefore, the goal of this research is to understand the requirements of a fully functional Tizen application, and to determine feasibility of creating a stand alone Signal Private Messenger application for the Samsung Galaxy Watch.

Ideation
--------

### BOM

1. Samsung Galaxy Watch
1. Samsung Series 9 - Linux - Ubuntu 18.04.4 LTS
1. Motorola Moto Z^2 Force _(in case a phone is required to sideload data)_

### Plan

1. Research
1. Install development tools locally _(to understand functionality/interaction)_
1. Create a blank Tizen application
1. Run application in the emulator
1. Sideload application to watch
1. Include Signal SDK to application
1. Create a minimal application capable of both sending and receiving messages
1. Assess additional work to implement a fully featured application
   - Research Android application functionality
   - Identify Tizen APIs required to support Signal features
   - Detail remaining work in this document
1. Setup development infrastructure
   - Create a containerized development environment
   - Select a unit-testing framework
   - Select a code-coverage utility
   - Select CI/CD software capable of running unit-tests and illustrating coverage results
1. Begin development of a robust Tizen application

Research
--------

### Web Searches

Journal
-------

**15 JUN 2020** - Set out vision for Tizen Signal Private Messenger application.
