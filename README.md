# Viro Platform
Viro Media is a platform for developers to rapidly build augmented reality (AR) and virtual reality (VR) experiences. Developers write in React Native, and Viro runs their code natively across all mobile VR (including Google Daydream, Samsung Gear VR, and Google Cardboard for iOS and Android) and AR (iOS ARKit) platforms. [More info here](http://docs.viromedia.com/).

This project contains various sample Viro projects.

[Sign up](https://viromedia.com/signup) for an API key. The platform is free to use with no limits on distribution.

To report bugs/issues with Viro platform, please file new issues on this repository.

## Instructions for running sample projects using Testbed app:

1. Follow directions on our [Quick start guide](http://docs.viromedia.com/v1.0.0/docs/quick-start) to setup dependencies for trying these sample projects with the Viro Media App.
2. Clone the repo into your workspace with git: `git clone https://github.com/viromedia/viro.git`.
3. Edit index.ios.js or index.android.js, depending on your test device, and replace "API_KEY_HERE" with the key emailed to you with signup.
4. Run `npm install` from the root of this project.
5. Run `npm start` from the root of this project.
6. Open the Viro Media App, slide out the left panel and select "Enter Testbed".
7. Type the entire ngrok URL output (xxxxxx.ngrok.io) at the top of the terminal into the text field and hit 'GO'
8. You should now be in the application! Enjoy!

## Changing Between Samples

1. Open the index.ios.js or index.android in a text editor
2. Modify line 39: `scene: scenes['360 Photo Tour'],` to a scene defined in the `scenes` dictionary on line 23.
3. Reload/restart the application.

## More information

Check out our [website](http://www.viromedia.com/).

Look at our [documentation](http://docs.viromedia.com/).

## Sample Code Overview

### [Hello World](https://github.com/viromedia/viro/tree/master/js/HelloWorld)
![ScreenShot](js/HelloWorld/hello_world.jpg)
A scene with a 360 photo that displays "Hello World".
### [360 Photo Tour](https://github.com/viromedia/viro/tree/master/js/360PhotoTour)
![ScreenShot](js/360PhotoTour/photo_tour.jpg)
360 photo tour example that shows you how to display a 360 photo with clickable hot spots.
### [Human Body](https://github.com/viromedia/viro/tree/master/js/HumanBody)
![ScreenShot](js/HumanBody/heart.jpg)
This example showcases 3d objects. Orbit around a 3d Heart to see it from different angles!
### [VR MediaPlayer](https://github.com/viromedia/viro/tree/master/js/ViroMediaPlayer)
![ScreenShot](js/ViroMediaPlayer/theater.jpg)
Learn how to display and play 2d and 360 video with interactive play controls that can play, pause and stop.
### [Product Showcase](https://github.com/viromedia/viro/tree/master/js/ProductShowcase)
![ScreenShot](js/ProductShowcase/product_showcase.jpg)
A demonstration on how to do an interactive shopping app for TV's. Uses flexbox for UI and 3d objects with animations.
### [AR Sample](https://github.com/viromedia/viro/tree/master/js/ARSample)
![ScreenShot](js/ARSample/ar_sample.jpg)
A scene with objects, text and animation displayed on ARKit planes detected in the scene.




