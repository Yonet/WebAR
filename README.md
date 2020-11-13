# Web Augmented Reality

Getting Started with Augmented Reality Demo.

* Slides:[bit.ly/WebARSlides](https://bit.ly/WebARSlides)
* Workshop Video:

[![Workshop Video](http://img.youtube.com/vi/trQYd-HVoBg/0.jpg)](http://www.youtube.com/watch?v=trQYd-HVoBg)

## Models

 - "[Church of St. Sofia](https://poly.google.com/view/13hUrQbMlAt)" by [CyArk Info](https://poly.google.com/user/4U4FhbhDQdR)

 

![Church of St. Sofia](images/ChurchofStSophia.gif)

 - "[Thomas Jeferson Memorial](https://poly.google.com/view/3uHfaa5Kmki)"  by [CyArk Info](https://poly.google.com/user/4U4FhbhDQdR)

 

![Thomas Jeferson Memorial](images/ThomasJeffersonMemorialUSA.gif)

## Technology

* [three.js](https://threejs.org/): 3D library.
* [WebXR Device API](https://developer.mozilla.org/en-US/docs/Web/API/WebXR_Device_API): is a group of standards which are used together to support rendering 3D scenes to hardware designed for presenting virtual worlds (virtual reality, or VR), or for adding graphical imagery to the real world, (augmented reality, or AR). 
* [glTF](https://www.khronos.org/gltf/): 3D File format.
* [Poly API](https://developers.google.com/poly)
* [NodeJS](https://nodejs.org/en/)
* [Visual Studio Code](https://code.visualstudio.com/?WT.mc_id=spatial-0000-ayyonet)

## Running Locally

1. Download NodeJS: https://nodejs.org/en/
2. Install dependencies

Open your terminal and navigate to folder for this project and type

``` 
npm install
```

2. Get [Poly API](https://developers.google.com/poly/develop/api) key and add create a config.js as in config.example.js. Add your API key to apiKey string value.

``` js
var config = {
    apiKey: "Your Poly API key here!"
}
export {
    config
};
```

3. Start the server

``` 
npm start
```

4. Navigate to [http://localhost:4200/](http://localhost:4200/)

## Debugging on the mobile browser

[![How to debug WebXR on Chrome Dev Tools Tutorial](http://img.youtube.com/vi/r-wSk24Wmpk/0.jpg)](https://www.youtube.com/watch?v=r-wSk24Wmpk)

1. Enable [Developer mode](https://developer.android.com/studio/debug/dev-options) on your mobile device.

2. Download [Chrome Canary](https://www.google.com/chrome/canary/) or [Edge Canary](https://www.microsoftedgeinsider.com/en-us/download). Checkout [CanIUse.com](https://caniuse.com/#feat=webxr) for other browsers that support [WebXR Device API](https://developer.mozilla.org/en-US/docs/Web/API/WebXR_Device_API).

3. Go to chrome://inspect/#devices and click on port forwarding. Add localhost:4200.

![Inspect Devices](images/portForwarding.png)

![Port Forwarding](images/portForwardingEnabled.png)

## Other Resources

* [Mixed Reality Resources](http://bit.ly/MixedRealityResources)
* [Windows Mixed Reality Development](https://docs.microsoft.com/windows/mixed-reality/?WT.mc_id=spatial-0000-ayyonet)
* [WebXR APIs](https://developer.mozilla.org/en-US/docs/Web/API/WebXR_Device_API)
* [ImmersiveWeb.dev](https://immersiveweb.dev/)
