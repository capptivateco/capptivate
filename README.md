# Capptivate.co

Capptivate.co captured fleeting transitions between app screens and delightful animated UI elements that we might otherwise have lost forever as apps and operating systems evolved. It preserved integral and tricky to communicate aspects of app design, sparked new ideas, and functioned as a kinetic pattern library for designers and developers working on iOS apps. The project was inspired by [pttrns.com](https://pttrns.com) by Robin Raszka and [Mobile Patterns](http://www.mobile-patterns.com) by Mari Shelby.

**You have probably already realized the bad news:**

Capptivate.co redirects to this GitHub repository and the iOS app is no longer available in the App Store.

**Here is some good news:**

I’ve uploaded the videos, screenshots, and metadata from the site to this Github repository, so that anyone who relied on Capptivate.co for inspiration can still access the materials.

Thanks so much to everyone who visited Capptivate.co, it’s all yours now. I can’t wait to see what you do with it!

Alli


## About this Repository

Included here are all of the videos and screenshots from the Capptivate.co posts, as well as the metadata associated with each post.

Please open an issue if you have any questions.

### Animations

The `animations/` directory contains a folder for each animation that was posted to Capptivate.co.

Each animation includes two files:
* screenshot.png - A static cover image for each video/post
* video.mov - Screen recording of the animation pattern

### Metadata

The root directory of this repository includes a json representation of all the animation metadata:

```json
{
  "appStoreID": "592453480",
  "title": "City Guides",
  "animation_name": "NatGeoTest",
  "categories": ["Arc", "Ease", "Intro", "Loading", "Orbit", "Perspective"],
  "tags": ["loading", "national geographic", "perspective"]
}
```

| Property       | Description                                     |
| -------------- | ----------------------------------------------- |
| appStoreID     | iTunes Store App ID (when available).           |
| title          | Title of the original post.                     |
| animation_name | Folder name of the animation in `animations/`.  |
| categories     | Categories in which the animation was included. |
| tags           | Tags associated with the animation.             |

## License

![CC-BY-SA-4.0](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)

The contents of this project are made available under the [CC-BY-SA-4.0 license](https://creativecommons.org/licenses/by-sa/4.0/).

Please include a link to this repository if you decide to use or adapt any of the contents of this project.
