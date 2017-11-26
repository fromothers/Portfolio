---
title: Create React App for Dart
description: Easily spin up React + Dart projects from the command line.
date: 2017-11-30
draft: true
images: ["http://www.leejamesrobinson.com/img/create-react-app/banner.png"]
categories:
  - code
---

![Command Line](/img/create-react-app/banner.png)


If there's one thing developers hate, it's spending time doing tasks that could be automated. Modern web development can be complex and setting up a new project takes longer than it should. With JavaScript, this usually entails installing a variety of packages to do things like: code linting, formatting, and testing. Wouldn't it be nice if all of this was included from the start? Enter [create-react-app](https://github.com/facebookincubator/create-react-app), a project created by Facebook to easily spin up new React applications.

Create React App has been around for awhile now and there's been a variety of spin offs to add more functionality on top, such as:

- [create-react-app-typescript](https://github.com/wmonk/create-react-app-typescript)
- [create-react-native-app](https://github.com/react-community/create-react-native-app/)
- [create-react-app-redux](https://github.com/notrab/create-react-app-redux)

I recently found myself spending a handful of time setting up new React projects in [Dart](https://www.dartlang.org). There's a high barrier of entry for these projects and not a lot of documentation or examples. I set out to create a tool that would function like Create React App for JavaScript but for Dart projects. Without further ado, let's take a look.

![Command Line](/img/create-react-app/example.gif)

If you've ever used Create React App for JavaScript, you'll feel right at home. In the example above, we gave the application a name for our new project and it created a directory with a barebones React app. We can jump into that directory and start the application by running:

```sh
cd my_app
pub serve
```

Then, we can open http://localhost:8080 to view it in the browser.

![Example Website](/img/create-react-app/website.png)

It's that simple. No complicated setup. No head scratching. Just a simple example project configured with the tooling you need.