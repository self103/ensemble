# Ensemble

##In order to begin, follow [instructions](https://swift.org/getting-started/) to download XCode and install Swift

1. Download [XCode](https://itunes.apple.com/app/xcode/id497799835) through the App Store 

2. Run the package installer, which will install an Xcode toolchain into <code>/Library/Developer/Toolchains/</code>

3. An Xcode toolchain (<code>.xctoolchain</code>) includes a copy of the compiler, lldb, and other related tools needed to provide a cohesive development experience for working in a specific version of Swift 

4. Open Xcode’s <code>Preferences</code>, navigate to <code>Components > Toolchains</code>, and select the installed Swift toolchain 5. Xcode uses the selected toolchain for building Swift code, debugging, and even code completion and syntax coloring. You’ll see a new toolchain indicator in Xcode’s toolbar when Xcode is using a Swift toolchain. Select the Xcode toolchain to go back to Xcode’s built-in tools 6. Selecting a Swift toolchain affects the Xcode IDE only. To use the Swift toolchain with command-line tools, use <code>xcrun --toolchain swift</code> and <code>xcodebuild -toolchain swift</code>, or add the Swift toolchain to your path as follows:

    <code>$ export PATH=/Library/Developer/Toolchains/swift-latest.xctoolchain/usr/bin:"${PATH}"</code>

##For first time **Swift** Developers
1. You can find a [brief intro](https://developer.apple.com/library/prerelease/content/documentation/Swift/Conceptual/Swift_Programming_Language/GuidedTour.html#//apple_ref/doc/uid/TP40014097-CH2-ID1) to the language to begin to understand basic syntax, etc
