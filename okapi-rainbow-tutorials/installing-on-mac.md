# Okapi on a Mac

### Okapi

Okapi is a cross-platform and open source toolset designed to aid in the translation/localization process.

### Installing Okapi on a Mac

#### 1. Prerequisites
First, you'll need to download and install the prerequisites:
   1. Homebrew
   - Follow the installation instructions on [the Homebrew site](https://brew.sh/)
   2. Java 11
   - The cleanest, and simplest, way I've found to get this installed is by `brew` installing `temurin11`. The terminal command I used to accomplish this is below.
   ```
      brew install --cask temurin@11
   ```
   - To verify the Java installation, run `java -version` after `temurin11` is installed. You should get something like the response below:
   ```
   openjdk version "11.0.29" 2025-10-21
   OpenJDK Runtime Environment Temurin-11.0.29+7 (build 11.0.29+7)
   OpenJDK 64-Bit Server VM Temurin-11.0.29+7 (build 11.0.29+7, mixed mode)
   ```
   3. Okapi
   - Download the Okapi [version](https://okapiframework.org/wiki/index.php/Distributions) of the Main Release for your macOS version. (I installed the ZIP archive version for reference.)
   - Note, if you have an M1 chip, you'll want to get one versions with `aarch64` in the name.

#### 2. Opening Okapi
TBC
