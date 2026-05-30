# ELHT Neonatal Infusion Calculator (iOS Wrapper)

## Overview
This project wraps the ELHT Neonatal Infusion Calculator PWA inside a native iOS application using SwiftUI and WKWebView.

The calculator itself remains HTML/JavaScript-based while being delivered through a standard iOS app container.

## Contents
- ELHT_Neonatal_Calculator.html
- ELHTNeonatalApp.swift
- ContentView.swift

## Requirements
- macOS
- Xcode 15 or later
- Apple ID (for personal device deployment)
- Apple Developer Account (required for App Store distribution)

## Build Instructions

### 1. Create an Xcode Project
1. Open Xcode.
2. Select **Create New Project**.
3. Choose **iOS → App**.
4. Product Name: `ELHTNeonatal`
5. Interface: `SwiftUI`
6. Language: `Swift`

### 2. Add the Files
Replace the generated Swift files with:
- ELHTNeonatalApp.swift
- ContentView.swift

Add:
- ELHT_Neonatal_Calculator.html

Ensure the HTML file is included in:
**Build Phases → Copy Bundle Resources**

### 3. Run on Device
1. Connect an iPhone.
2. Select your device in Xcode.
3. Press Run.
4. Trust the developer certificate if prompted on the device.

## App Store Preparation
Before submission:
- Replace placeholder icons with production assets.
- Add a launch screen.
- Remove prototype warnings if clinically approved.
- Complete governance, validation, and pharmacy sign-off.
- Perform clinical safety testing.

## Important Notice
This calculator contains a prototype warning and should not be used for clinical decision-making until fully validated and approved under local governance procedures.

## Source
Based on the ELHT Neonatal Standard Infusion Calculator PWA.
