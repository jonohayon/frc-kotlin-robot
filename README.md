FRC Kotlin-based robot [WIP]
===

> A command-based robot template in Kotlin

:warning: *Warning - this hasn't been used yet on an actual robot yet, so it might not be working properly*

## What is this?
As the project's tagline says, this is a template for a command-based robot written in Kotlin. As simple as that.

## Why have you created this?
For two reasons:
1. I wanted to see whether that's possible
2. Semicolons (which are redundant in Kotlin) are ugly and unnecessary

## Is this being used on an actual robot?
As this is WIP and was created in 1am out of pure curiosity, not yet. But as soon as it will I'll update this project.
Also, we probably won't use it during the current season (2017) because teaching a new language will take time but maybe
in the next one.

## How does it work?
Since Kotlin and Java are interoperable and there's no need to do anything with WPILib, it's basically just the code of
the regular command based robot converted by hand to Kotlin.

### Running
First of all, you need to install the [IntelliJ FRC Plugin](https://gitlab.com/Javaru/frc-intellij-idea-plugin/), which
will make your life easier when running the robot software from IntelliJ and not from Eclipse. Then, simply clone this
repo and import the project into IntelliJ. After cloning the project change the X's all of the occurrences of `teamXXXX`
to match your team's number (thankfully, IntelliJ has a great refactor option just for this kind of things).

Then, follow the tutorial on their wiki to see how to run the Ant build and deploy the code to the robot.

## TODO
 - [x] Convert the template to Kotlin
 - [ ] Test on an actual robot
 - [ ] Add as a template to the FRC plugin