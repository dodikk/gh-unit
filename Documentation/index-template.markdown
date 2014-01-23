## Installing GHUnit

- [iOS](appledoc_include/guide_install_ios_7.html)
- [Mac OS X](appledoc_include/guide_install_macosx_4.html)

See [Installing in Xcode 4](appledoc_include/guide_install_ios_4.html) or [Installing in Xcode 3](appledoc_include/guide_install_old.html) for help installing in older projects.

## Using GHUnit

- [Tests & Examples](appledoc_include/guide_testing.html): Creating a test, asynchronous test, using asserts
- [Command Line](appledoc_include/guide_command_line.html): Running from the command line, using a Makefile, env variables
- [Continuous Integration](appledoc_include/guide_ci.html): Setting up Jenkins for continuous integration

<div style="float:left;margin:30px 10px 10px 20px" markdown="1">
<img src="appledoc_include/images/GHUnit-IPhone-0.5.8.png"/>
</div>

<div markdown="1">
<img src="appledoc_include/images/GHUnit-0.5.8.png"/>
</div>

## Reference

[Source documentation](../index.html)

## Other

To build the framework for iOS, run `make` from within the `Project-iOS` directory. The framework is in `Project-iOS/build/Framework/`.

To build the framework for Mac OS X, run `make` from within the `Project-MacOSX` directory. The framework is in `Project-iOS/build/Release/`.

GHUnit was inspired by and uses parts of GTM (google-toolbox-for-mac) code, mostly from [UnitTesting](http://code.google.com/p/google-toolbox-for-mac/source/browse/trunk/UnitTesting/)
