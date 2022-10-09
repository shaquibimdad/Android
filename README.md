# Daemon OS

This is a project to create a daemon OS for Android. It is based on the [AOSP] project. It is a fork of the [HavocOS] project.

## Currently Work in Progress

## Building

To build, you need to initialize the build environment first. To do so, run the following command:

    . build/envsetup.sh

Then, to build for a specific device, run the following command:

    lunch daemon_<devicecodename>-userdebug

For example, to build for the Pixel 3 XL, run the following command:

    lunch daemon_crosshatch-userdebug

Then, to start the build, run the following command:

    mka bacon

## Contributing

If you want to contribute to this project, you can do so by forking this repository and sending a pull request. Please make sure that your code is properly formatted and that it follows the [AOSP] coding style.

## License

This project is licensed under the [Apache License 2.0].

[aosp]: https://source.android.com/

[HavocOS]:

[apache license 2.0]: https://www.apache.org/licenses/LICENSE-2.0

## Credits

- [HavocOS] for the base
- [LineageOS] for the base
- [AOSP] for the base
- [PixelExperience] for the base
- [DirtyUnicorns] for the base
- [AICP] for the base
- [AOSiP] for the base
- [AOSPA] for the base
- [AOSCP] for the base
- [AOKP] for the base
- [AOSPExtended] for the base
- [AOSPA] for the base
