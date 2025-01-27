Guerilla
========

Guerilla is a distributed build/test server specialized for iOS and Android.

An instance of Guerilla manages jobs and provides a UI to view job results. A job consists of tasks. Examples of tasks are check out project from Github, build a project using Gradle, execute XCTests, and retrieve method count from an APK. Guerilla provides some core tasks and also gives the user the ability to write custom tasks that may be specific to a certain project. With Guerilla, it is easy to run scheduled, automated tests on real devices. Guerilla can also generate reports based on data points that are outputted from job results. This will show a user how their project is changing over time (APK size over time). Reports can also be generated to show things like memory and network usage during a single run. Guerilla can easily be scaled by configuring and adding new workers. It is a flexible platform that aims to help automate hard-to-automate tasks.

### Wiki

* [Installing Guerilla](wiki/Installing.md)
* [iOS Configuration](wiki/iOS.md)
* [Android Configuration](wiki/Android.md)
* [Configuring Guerilla](wiki/Configure.md)
* [Launching Guerilla](wiki/Launching.md)
* [Setting up Jobs](wiki/Jobs.md)
* [Guerilla Tasks](wiki/Tasks.md)
* [Custom Tasks](wiki/CustomTasks.md)
* [Guerilla on VMs](wiki/VM.md)
* [FAQs](wiki/FAQs.md)

### License

Code licensed under the MIT License. See LICENSE file for terms.