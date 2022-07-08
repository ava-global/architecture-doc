---
coverY: 0
---

# 🍄 iOS

## Architecture

### Application main architecture (Clean Swift)

![](../.gitbook/assets/clean-full-picture-2.png)

The Clean Swift architecture is derived from the Clean Architecture proposed by Uncle Bob. They share many common concepts such as the components, boundaries, and models.

### The VIP Cycle

The view controller, interactor, and presenter are the three main components of Clean Swift. They act as input and output to one another as shown in the following diagram.

![](../.gitbook/assets/vip-2.png)


### Card component architecture (MVVM)

![](../iOS/assets/mvvm.png)

## Dependency management

* Cartage
* Cocoapods
* Swift Package Manager
![](../iOS/assets/dependency.png)

## CI / CD

### Github Actions for **CI**

> GitHub Actions is a **continuous integration and continuous delivery** (CI/CD) platform that allows you to automate your build, test, and deployment pipeline. You can create workflows that build and test every pull request to your repository, or deploy merged pull requests to production.

### Fastlane Action for **CD**

> Automate your development and release process fastlane is an open source platform aimed at simplifying Android and iOS deployment. fastlane lets you automate every aspect of your development and release workflow.

### Build Pipeline

![](../iOS/assets/pipeline-categories.png)

### Pipeline State

![](../iOS/assets/pipeline-state.png)

### Pipeline 1: On push request (PR)

![](../iOS/assets/pipeline-pr.png)

### Pipeline 2: On push request (Merged)

![](../iOS/assets/pipeline-push.png)

### Release & Tags

* Changed Log / Features Note
* Tags (Versioning symmetric https://semver.org)

![](../iOS/assets/release-tag.png)

## Tests monitor: codecov

![](../iOS/assets/codecov.png)

* UI tests
* Code coverage (Xcode)

## Security
### Jailbreak detection
- IOSSecuritySuite
### SSL pinning
- public key pinning
### Data security
- [LV.1] General data (user default)
- [LV.2] Credential (keychain)
- [LV.3] Super credential (keychain + secure enclave)



![](../iOS/assets/enclave.png)

## Xcode Template

> XCode Templates is a tool for creating code snippets to give you a better starting point to achieve your goal. In this tutorial I will walk you through preparing a custom template for MVVM project architecture.

![](../iOS/assets/xcode-2.png) ![](../iOS/assets/xcode-1.png)

### Clean Architecture Template

#### Scene

* NameViewController.swift
* NamePresenter.swift
* NameInteractor.swift
* NameRouter.swift
* NameFacade.swift
* NameSceneModel.swift
* NameSceneWorker.swift
* Name.storybroad

#### View Component

* NameView.swift
* NameViewModel.swift


## Crash monitoring: Firebase Crashlytics

> Never miss a critical app crash with realtime alerts for new issues. Crashes are prioritized by impact on actual users so you know how to best fix bugs. Build Fast For Any Device. Customize Your App. Boost App Engagement. Accelerate Development. ![](../iOS/assets/firebase-crashlytics.png)

## Analytics: Mixpanel

> Mixpanel is a business analytics service company. It tracks user interactions with web and mobile applications and provides tools for targeted communication with them. Data collected is used to build custom reports and measure user engagement and retention.

![](../iOS/assets/mixpanel.png)

## App performance monitoring

> Firebase Performance Monitoring, a real time app performance monitoring tool, helps you keep a close eye on your app as you roll out new features or make configuration changes. Performance Monitoring also gives you control over your performance data with a customizable dashboard that makes it easy to focus on your most important metrics.

![](../iOS/assets/firebase-performance.png)

**Keep your app fast and responsive**

> Gain insight into how your app performs from your users' point of view with a breakdown of trace and network data into dimensions like app version, country, device, and network type.

![](https://firebase.google.com/images/products/performance/performance-1.jpg)

**Capture health and performance of network requests**

![](https://firebase.google.com/images/products/performance/performance-2.png)

> Stay on top of your app's dependencies, network latencies, and errors affecting your users with automated monitoring of HTTP/S requests. You can also customize URL patterns to closely monitor response times, success rates, and payload sizes of your critical requests.

**Reduce troubleshooting and resolution time**

![](https://firebase.google.com/images/products/performance/performance-3.jpg)

Understand the context in which performance issues take place and more easily address them using custom traces. You can also make use of automated traces, such as app startup time.

## Design Language

* Colors
* Typography
  * Font
  * Weight
  * Style
* UI Components
  * UI Element
* Line
* Spacer
* Theme
* Lanuage
* Asset
  * Filename
    * Snake case

## Etc.

* Post Man (API Live Document)
* Project Branch
  * main
  * develop
* Enviroment
  * Develop
  * Production
