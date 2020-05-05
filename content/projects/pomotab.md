+++
aliases = ["PomoTab"]
date = 2020-04-18T20:22:00Z
description = "A Pomodoro Timer in each new tab."
github = "https://github.com/andyjgao/PomoTab"
images = ["/images/PomoTab.png"]
link = "https://chrome.google.com/webstore/detail/pomotab/dbpkgeidmoofficdjjpikfachonamakh"
tags = ["Chrome Extension", "React"]
title = "PomoTab"
view = "View Extension"

+++
**Tech Stack:** ReactJS (Hooks), MaterialUI

**Duration:** 1 Day

PomoTab is a Chrome Extension rendering a minimalist Pomodoro timer in each new tab. The app is designed based on a philosophy of minimalism + function. Every component serves a purpose.

**Features:**

* PomoTab when you open a new tab
* 25 Minute Study Timer + 5 Minute Break
* Start/Pause + Reset Button
* Focus Box
* Light Mode / Dark Mode

**Future Features:**

* Customization of Study/Break timer
* Customization of Alarm Sound
* Pomodoro Completion Counter

## Problem

I built this Chrome Extension after not being able to find an extension that offered a simple Pomodoro Timer _without feature bloat_. Almost every extension I installed was riddled with additional functions and did not serve my use-case of a simple, minimal Pomodoro Timer.

## Goal

Build a minimalist Pomodoro Timer. It must have only the necessary features and be easy to use/access.

## Ideation

Low-Fidelity Mock Up

![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fandyjgao%2FiFRceHGp-y?alt=media&token=9428cda7-3ecf-4c2c-85d9-53a2e80a8ef2)

## Roadblocks

The primary roadblock I ran into was trying to use **React Hooks** with the **setInterval()** JavaScript function. React is built off of the declarative programming paradigm while the setInterval() API is imperative. These conflicting models caused a lot of unintended behavior for me -- resulting in the timer skipping seconds randomly. I found [this article](https://overreacted.io/making-setinterval-declarative-with-react-hooks/ "url: https://overreacted.io/making-setinterval-declarative-with-react-hooks/") very helpful in solving my issue.

## End Result

After a few hours of coffee induced grinding, I ended up with the following result:

![](https://i.imgur.com/sipyQpU.gif)

I was pretty happy with the result. And I learned a good amount about **React Hooks and Chrome Extensions.**

If you want PomoTab for your own Chrome Browser, [add the extension here](https://chrome.google.com/webstore/detail/pomotab/dbpkgeidmoofficdjjpikfachonamakh "url: https://chrome.google.com/webstore/detail/pomotab/dbpkgeidmoofficdjjpikfachonamakh").