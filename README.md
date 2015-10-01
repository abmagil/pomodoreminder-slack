# pomodoreminder-slack
Send reminders for the end of a pomodoro

## Pomodoro
The [pomodoro technique](https://en.wikipedia.org/wiki/Pomodoro_Technique) has been highly successful (at least for me) at
improving focus and time-on-task. The technique calls for an uninterrupted block
of time (25 minutes) spent on a singular task, with no interruptions. This is
followed by a 5 minute break. This 30-minute block is a "pomodoro" and every 4th
pomodoro, a longer break of 15 minutes replaces the 5 minute break.

## Problem
For me, I find that I have lots of thoughts related to, but not part of, the
task at hand. For instance, while working on a functionality, I may recognize an
opportunity for a refactoring that would be out of scope for the work I am doing
but very valuable for the project at hand. In the traditional pomodoro technique
I would lose these task-adjacents because I forget them by the end of the
pomodoro.

## Solution!
Slack has an exceptionally useful "reminder" function which will remind you
(via Slackbot at the given time). This works perfectly for letting me push an
idea out of band during a pomodoro, then return to it at during the break. Of 
course, I need to have Slack open to set up reminders and Slack is a giant
distraction when open, so...what to do?

My solution is a small app, living on the desktop, which exists just to shoot
properly-formed reminders to Slack's hook infrastructure. Since Slack isn't
open, I don't get distracted. Since the reminders live in Slack (where I expect
them), I don't lose the task.

The goal is to be as minimal as possible and ever-present, so that I can quickly
remind future-me what to do, without compromising right-now-me's flow.

__________
*PomodoReminder is built proudly with [Shoes](http://shoesrb.com/)*