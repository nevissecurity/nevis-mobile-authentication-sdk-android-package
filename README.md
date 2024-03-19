![Nevis Logo](https://www.nevis.net/hubfs/Nevis/images/logotype.svg)

# Nevis Mobile Authentication Client SDK

The Nevis Mobile Authentication Client SDK is a software development kit to develop native mobile applications, that are capable of carrying out FIDO UAF 1.1-based authentication in combination with a Nevis Mobile Authentication backend. The Nevis Mobile Authentication Client SDK is part of the Nevis Mobile Authentication solution, and it is designed to offer maximum flexibility. You can embed the Nevis Mobile Authentication Client SDK into existing native iOS and Android mobile applications to enhance them with Nevis Mobile Authentication capabilities, or use the SDK in a new mobile application written from scratch.

# Communication
 
- Check our [documentation](https://docs.nevis.net/mobilesdk/)
- Visit our [website](https://www.nevis.net/en/solution/authentication-cloud)
- Contact us on email: [sales@nevis.net](mailto:sales@nevis.net)

# Installation with Gradle

The Nevis Mobile Authentication Client SDK is published as a GitHub package in this repository. You have to specify this repository in the `build.gradle` of your application.

```
buildscript {
    repositories {
        maven {
            url "https://maven.pkg.github.com/nevissecurity/nevis-mobile-authentication-sdk-android-package"
            credentials {
               username = <GITHUB_USERNAME>
               password = <GITHUB_PERSONAL_ACCESS_TOKEN>
            }
        }
    }
}

```

> **Warning**
> Accessing GitHub packages requires you to have a GitHub account. You must provide a Personal Access Token, as described [here](https://docs.github.com/en/packages/working-with-a-github-packages-registry/working-with-the-gradle-registry#using-a-published-package).

Then you can use the Mobile Authentication SDK, by declaring as a dependency in your `build.gradle`:

```
dependencies {
    implementation "ch.nevis:nevis-mobile-authentication-sdk-android-debug:3.6.2.1525"
}

```

> **Warning**
> This repository only exposes the `debug` flavor. To use the `release` flavor contact us on [sales@nevis.net](mailto:sales@nevis.net).

For additional information, see the [Android Installation](https://docs.nevis.net/mobilesdk/guide/installation/android-installation) of the Nevis documentation.

# License

Nevis Mobile Authentication Client SDK is release under a commercial license. See [LICENSE](LICENSE) for details.

© 2023 made with ❤ by Nevis
