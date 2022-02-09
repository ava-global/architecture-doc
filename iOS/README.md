# iOS

## Architecture

### Main architecture (Clean Swift)
xxxxxx
![](<./assets/clean-full-picture.png>)


#### Component architecture (MVVM)
xxxx
![](<./assets/mvvm.png>)

## CI / CD
### Github Action for CI
### Fatlane Action for CD
### Build Pipeline
![](<./assets/pipeline-categories.png>)

### Pipeline State
![](<./assets/pipeline-state.png>)

### Pipeline 1
- On push request (PR)
![](<./assets/pipeline-pr.png>)

### Pipeline 2
- On push request (Merged)
![](<./assets/pipeline-push.png>)

### Release & Tags
- Changed Log / Features Note
- Tags (Versioning symmetric https://semver.org)
    <img src="./assets/release-tag.png" > 

            
## Dependency management
- Cartage
- Cocoapods
- Swift Package Manager

![](<./assets/dependency.png>)

## Tests
- Test monitor (codecov)
![](<./assets/codecov.png>)

- UI tests
- Code coverage (Xcode)

## Crash monitoring
- Firebase Crashlytics    
![](<./assets/firebase-crashlytics.png>)

## Analytics
- Mixpanel
    ![](<./assets/mixpanel.png>)

## App performance monitoring
    ![](<./assets/firebase-performance.png>)

## Security
<img src="./assets/enclave.png" height="350px;" > 

## Xcode Template
![](<./assets/xcode-2.png>)
![](<./assets/xcode-1.png>)

### Clean Architecture Template

#### Scene
- NameViewController.swift
- NamePresenter.swift
- NameInteractor.swift
- NameRouter.swift
- NameFacade.swift
- NameSceneModel.swift
- NameSceneWorker.swift
- Name.storybroad
#### View Component
- NameView.swift
- NameViewModel.swift


## Design Language

- Colors
- Typography 
    - Font
    - Weight
    - Style
- UI Components
    - UI Element
- Line 
- Spacer
- Theme
- Lanuage
- Asset
    - Filename
        - Snake case

## Etc.

- Post Man (API Live Document)
- Project Branch
    - main 
    - develop
- Enviroment
    - Develop
    - Production 
