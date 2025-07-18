<!--
Licensed to the Apache Software Foundation (ASF) under one
or more contributor license agreements.  See the NOTICE file
distributed with this work for additional information
regarding copyright ownership.  The ASF licenses this file
to you under the Apache License, Version 2.0 (the
"License"); you may not use this file except in compliance
with the License.  You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing,
software distributed under the License is distributed on an
"AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
KIND, either express or implied.  See the License for the
specific language governing permissions and limitations
under the License.
-->

# Getting Help

So something didn't work as you expected it to?
You think that *Maven is broken*.
What should you do?

Here's a list of actions that you can take:

## You did check the documentation, didn't you?

Apart from the central Maven site, each of our plugins has a website.
Go to the [plugins page](../plugins/index.html) and follow the link to the plugin you are having problems with.

## Try the latest version of Maven or the plugin in question

Before you start intensive investigations on your problem, you should try to update Maven and/or the plugins
in question to the latest stable release.
After all, the issue you encounter might have been fixed already.
To find out what is the latest stable release version, consult [Maven's download section](../download.html)
and the [plugins page](../plugins/index.html).

## Search the user-list archives

Someone else might have experienced the same problem as you before.
A list of mail-archives can be found on [mailing list index page](https://maven.apache.org/mailing-lists.html).
Please search one of them before going any further.

## Ask on the user list

Our community is very helpful, just ask it the right way.
See the references section, at the end of this page, for info on how to do that.
Subscribe to  the [users list](https://maven.apache.org/mailing-lists.html) and describe your problem there.
Don't expect to get an answer right away.
Sometimes it takes a couple of days.

## Submit an issue

If it turns out that there is indeed something wrong with Maven or one of the plugins, you should report it to the issue management system.
All projects (Apache Maven core, Apache Maven plugins, subcomponents) have been migrated to use GitHub issues.

You don't need to create an issue only to ask us something - in such case please first ask on [users list](https://maven.apache.org/mailing-lists.html).

## Where?

If the problem is in one of the plugins, check the site of that plugin to get the correct link.
Each plugin has its own GitHub repository, so using the correct link is important.
Click on *Project Information* and then *Source Code Management*.
On that page you will find the correct link.

If the problem is in Maven itself you can find the appropriate link to GitHub repository on the [scm](/scm.html) page.

## How?

Just describing the problem is not enough.
It takes a developer a lot of time to make a usable POM to even attempt to assess the problem.
Issues that states problems without something usable to try out will be closed as incomplete.

Please attach a working POM, or a set of POMs, that we can download and run.
We appreciate reports, but if you don't have something usable for us, it's incredibly hard for us to manage the issues.
A POM goes a long way to helping us resolve problems.

Create a POM that can be used to verify that it is a bug.
If your pom uses plugins, make sure that you have specified the version for each and every plugin.
If you don't, then we might not be using the same version as you are when we test it.

What we like best are patches that fixes the problem.
If you want to create a patch for an issue please read the [Maven Developer Guide](../guides/development/guide-maven-development.html) first.

If you have been able to figure out the changes needed for your problem or enhancement request, you can directly create a Pull Request against the GitHub repository.

## References

* [Eric Steven Raymond - How To Ask Questions The Smart Way](http://www.catb.org/~esr/faqs/smart-questions.html) (Note: HTTP only!)
* [Blog: Open Source Strategies - How to Get Support from Open Source Mailing Lists](http://opensourcestrategies.blogspot.com/2005/09/how-to-get-support-from-open-source.html) (Note: HTTP only!)

