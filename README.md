# Expo Android Build Failure: Dependency Resolution Error

This repository demonstrates a common error encountered when building Android APKs with the Expo CLI. The issue manifests as a vague error message related to dependency resolution, typically during the Gradle build process. This is often caused by version mismatches between dependencies declared in `package.json` and those accessible in the Android build system.

**Problem:** The primary challenge is the lack of specific error details. The error messages are not very informative, making it difficult to pinpoint the root cause.  The solution involves thorough dependency analysis and verification of Android SDK components.

**Solution:** The proposed solution focuses on identifying the conflicting dependencies and ensuring all required Android SDK components are correctly installed and configured.  This involves checking `package.json` dependencies, Gradle files, and Android Studio settings.

This repository provides example code and clear steps to reproduce and resolve the issue.  The `bug.js` file showcases a project with the issue, while `bugSolution.js` demonstrates the solution.
