## Taller de Desarrollo de Software INF3741
# Taller mecanico

![header](https://miro.medium.com/max/1400/1*Q-2-QYwLrePLja6Jacjhgw.png)

## Requirements

* Android Studio
* Git
* Contentful CLI (only for write access)
* Android build tools v 28+
* An Android phone 9.0 or up

Without any changes, this app is connected to a Contentful space with read-only access. To experience the full end-to-end Contentful experience, you need to connect the app to a Contentful space with read _and_ write access. This enables you to see how content editing in the Contentful web app works and how content changes propagate to this app.

## Common setup

Clone the repo and install the dependencies.

```bash
git clone https://github.com/danniel-me/Taller.git
```

Open Android Studio and create a new project from the just downloaded source.


## Steps for read-only access

Open `gradle.build` in Android Studio and run the app on an emulator or directly on a device.

## Steps for read and write access (recommended)

Step 1: Install the [Contentful CLI](https://www.npmjs.com/package/contentful-cli)

Step 2: Open `the-example-app.kotlin` in Android Studio and run the app on an emulator or device and take a look around the app.

<b>Enjoy exploring the app and feel free to leave <a href="https://github.com/danniel-me/Taller/issues/new">feedback</a>.</b>
