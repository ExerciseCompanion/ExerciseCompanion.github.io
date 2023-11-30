---
id: home
title: Exercise Companion Application
sidebar_label: Home
---

# Exercise Companion Application
## Motivation
The motivaton of this application is to improve the overall fitness of the population through gamification.  In modern times, there are many people who remain sedentary.  This can be detrimental to long term health.  By build a relationship with the virtual pet/ companion, we hope that this is enough motivation for the user to go and exercise.

## Goals
The goal is to encourage people to excercise or walk around.  In this inital implementation, a step counter will be used to determine the fitness metrics.

## Usage

Login Page                 | Login Failed
:-------------------------|:-------------------------
![Login](https://raw.githubusercontent.com/ExerciseCompanion/exercisecompanion.github.io/main/assets/release/login.png) | ![LoginFailed](https://raw.githubusercontent.com/ExerciseCompanion/exercisecompanion.github.io/main/assets/release/loginfailed.png)
Login page where a user can login | Demonstration of failed login

Home Page                  |  Home Page Swiped Up
:-------------------------|:-------------------------
![Home](https://raw.githubusercontent.com/ExerciseCompanion/exercisecompanion.github.io/main/assets/release/home.png) | ![Statistics](https://raw.githubusercontent.com/ExerciseCompanion/exercisecompanion.github.io/main/assets/release/homeup.png)
Home page where the virtual pet exists with Step counter metrics readily available near the bottom pull up tab. The navigation bar is adorned with: tasks, wardrobe, home, pets, and shop. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Swipe up to see specific data metrics. The Experience and Health bars are percentages of the current pet's statistics.  A temporal representation of steps taken each month is given in a graph form.  The settings button is found at the bottom.

Settings                   |  Settings Changed
:-------------------------|:-------------------------
![Settings](https://raw.githubusercontent.com/ExerciseCompanion/exercisecompanion.github.io/main/assets/release/settings.png) | ![SettingsDark](https://raw.githubusercontent.com/ExerciseCompanion/exercisecompanion.github.io/main/assets/release/settingsdark.png)
View of settings page | Dark mode applied

Task                       | Task Claimed
:-------------------------|:-------------------------
![Task](https://raw.githubusercontent.com/ExerciseCompanion/exercisecompanion.github.io/main/assets/release/task.png) | ![TaskClaimed](https://raw.githubusercontent.com/ExerciseCompanion/exercisecompanion.github.io/main/assets/release/taskclaimed.png)
View of tasks page with three distinct states: in progress, claimable, and claimed.  Ideally, new tasks are added daily  | User may depress the claimed button to receive a sum of in game currency denoted in the top right &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

Shop                       | Shop Purchase Failed      | Shop Purchase Success | Shop Purchase Success Hat Added
:-------------------------|:-------------------------|:-------------------------|:-------------------------
![Shop](https://raw.githubusercontent.com/ExerciseCompanion/exercisecompanion.github.io/main/assets/release/shop.png) | ![ShopFailed](https://raw.githubusercontent.com/ExerciseCompanion/exercisecompanion.github.io/main/assets/release/shopbuyfail.png) | ![ShopPass](https://raw.githubusercontent.com/ExerciseCompanion/exercisecompanion.github.io/main/assets/release/shopbuypass.png) | ![CustomizationAllHat](https://raw.githubusercontent.com/ExerciseCompanion/exercisecompanion.github.io/main/assets/release/customizeallhat.png)
A shop page view with listed items avalible for purchase &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | In the event of insufficent funds, a transaction is denied &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | If the user has enough currency, the transaction passes and the item purchased is removed from the shop &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Upon a successful purchase, the hat is added to the inventory &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;


Customization             |  Customization (Black Hat) | Customization (Red Hat) | Pet (Red Hat)
:-------------------------|:-------------------------|:-------------------------|:-------------------------
![Customization](https://raw.githubusercontent.com/ExerciseCompanion/exercisecompanion.github.io/main/assets/release/customize.png) | ![CustomizationRedHat](https://raw.githubusercontent.com/ExerciseCompanion/exercisecompanion.github.io/main/assets/release/customizeredhat.png) | ![CustomizationBlackHat](https://raw.githubusercontent.com/ExerciseCompanion/exercisecompanion.github.io/main/assets/release/customizeblackhat.png) | ![PetRedHat](https://raw.githubusercontent.com/ExerciseCompanion/exercisecompanion.github.io/main/assets/release/pethat.png)
The container isolating the hats is scrollable, and allows the user to select a hat for their virual pet &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | This is a demonstration of a black top hat applied to the virtual pet &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | This is a demonstration of a red cap applied to the virtual pet &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | This is a demonstration of the red cap being applied to the pet selection screen &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

Pet                      |  Pet (Change Selection)
:-------------------------|:-------------------------
![Pet](https://raw.githubusercontent.com/ExerciseCompanion/exercisecompanion.github.io/main/assets/release/pet.png) | ![Pet](https://raw.githubusercontent.com/ExerciseCompanion/exercisecompanion.github.io/main/assets/release/petchange.png) 
This page is where the user can select their pet via the select button.  The discolouration in the gradiance indicates both the pets health and experience | This is a demonstration of another pet being selected, this change propogrates to the home screen and customization screen &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

## Installation (Run)
Repo: [https://github.com/ExerciseCompanion/app/tree/main](https://github.com/ExerciseCompanion/app/tree/main)
```bash
git clone https://github.com/ExerciseCompanion/app.git
cd exercise_companion
flutter run
```

## Build
```bash
flutter build apk --release
```

## Usability Evaluation
[View Evaluation](https://exercisecompanion.github.io/evaluation.html)

## Releases
### Latest
- [v1.0](https://github.com/ExerciseCompanion/exercisecompanion.github.io/releases/tag/v1.0)
  - [Android APK Download](https://github.com/ExerciseCompanion/exercisecompanion.github.io/releases/download/v1.0/exercise-companion-app-release.apk)
### All Releases
-  [Releases](https://github.com/ExerciseCompanion/exercisecompanion.github.io/releases/)

## Develpment Status
[https://github.com/orgs/ExerciseCompanion/projects/1](https://github.com/orgs/ExerciseCompanion/projects/1/views/1)

## About Me
Hi, my name is Christopher Lee. I am in my first semester of ICS graduate school in University of Hawaiʻi at Mānoa.  I enjoy traveling abroad and sightseeing.
