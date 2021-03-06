# CaptureReplayTesting

Capture/replay testing is an intuitive form of software testing that is in vogue in the areas of web development and mobile development. It is a relatively old form of testing that originally comes from the realm of embedded software. There it had the goal of allowing to test embedded software in realistic circumstances, albeit not on the embedded device itself (because the processing power of the embedded device was not sufficiently capable for example).

Modern capture/replay testing is all about functional testing, often at the level of the Graphical User Interface. Known tools in the area are Selenium IDE (web), Robotium or Espresso (Android) and Appium (iOS). The idea of the aforementioned tools is twofold. 

1. It allows to easily script a test at the user interface level, i.e., fill in this value in field X and then press button "OK.
2. It even allows to automate step 1, by recording user actions, thus generating the script, that can be replayed over and over (hence the name capture/replay).

This assignment is about exactly this. The explanation below will be about Espresso, but if you feel adventurous, you can obviously also try to do this for Robotium, Appium or Selenium IDE. 

The minimal steps that you will need to take are:
1. Install Android Studio (see: https://developer.android.com/studio/index.html)
2. Download the Robotium example package for Android Studio (see: https://github.com/RobotiumTech/robotium/wiki/Downloads)
3. Unzip the example package and import the project into Android Studio.
4. In Android Studio define a virtual device and activate it (Android Studio --> Tools --> Android --> AVD Manager)
5. Now you can start recording your Espresso tests. For that go to the menu Run --> Record Espresso Test
6. Play out a scenario in the Android emulator that is started. Play around with defining assertions.
7. Once you have captured what you want, save the test.
8. Now you can replay the test.

As stated, these are the minimal steps! Be more adventurous and find other projects, find projects for other platforms (e.g., web, iOS, ...)!

Finally, put everything into context and read the following paper:
1. Laurent Christophe, Reinout Stevens, Coen De Roover, Wolfgang De Meuter: Prevalence and Maintenance of Automated Functional Tests for Web Applications. ICSME 2014: 141-150

Specifically, think about the following questions:
1. Why should you use capture replay testing?
2. Who should use it?
3. Why shouldn't you use it.
4. What is the relation between unit/integration testing and this form of testing?
5. What is to be preferred? Is something to be preferred? Why?

