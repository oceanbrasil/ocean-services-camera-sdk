# Camera SDK

[![Latest Stable Version](https://img.shields.io/badge/version-1.2.3-green.svg)](http://developer.samsung.com/galaxy/camera)

__Restrictions__

- Devices with Android 5.0 Lollipop (API level 21) or above.

- The supported functions might change according to the hardware performance.

> __Note:__ Some features will be supported in Android 5.1 Lollipop (API level 22).

he Samsung Galaxy series camera has been leading the race on smartphone and tablet camera technology. It has introduced many enhanced features and technologies over time. However, these camera features were available only with the preloaded camera application. Through the Camera SDK, Samsung is providing easy to use APIs that lets you implement new features into your own application. It also lets you use state of the art functionalities, such as control-based hardware, convenient smart modes, various real-time filters, and fast processing of large size images, in developing enriched camera-based applications.

The newly developed, intuitive Camera SDK facilitates easy development even if you do not have prior knowledge about the camera. API documents, sample codes and programming guides are provided to assist and speed up app development.

Since basic camera functionalities are common across different vendor devices, there is no need to provide different implementations for each vendor/device.

![Camera SDK](http://developer.samsung.com/sd2_images/galaxy/content/sms_camera_01.jpg)


## Download

Add into gradle project level

``` Gradle
allprojects {
  repositories {
    ...
    maven { url "https://jitpack.io" }
  }
}
```

Add into app project level

``` Gradle
dependecies{
    compile 'com.github.oceanbrasil:samsung-services-accesory-sdk:1.2.3'
}
```

## Filter

Camera SDK Filter package supports following features:

- __Real-time preview effect__: Effects can be applied not only on a captured image but also on the real-time preview frames of the camera.
- __Still image and video recording with effects__: Effects can be applied on high-resolution images and full HD recoding of a moving object.
- __Post effect processing__: Post processing on various images, such as jpeg file, bitmap object.
- __Downloadable Filters__: Apart from preinstalled filters in the SDK, Galaxy device users can download the filters from Galaxy App stores and the application can load downloaded filters.

Following filters are included in SDK:

| Filter 1  | Filter 2  | Filter 3  |
|---|---|---|
| Negative      | Breeze                  | Vivid              |
| Soft          | Serene                  | Brightness         |
| Temperature   | Contrast                | Saturate           |
| Tint Control  | Highlights and Shadows  | Black and White    |
| Emboss        | Posterize               | Thermal Vision     |
| Ripple        | Mosaic                  | Beauty             |
| Vignette      | Vintage                 | Faded Color        |
| Greyscale     | Tint                    | Cartoon            |
| Moody         |                         |                    |

![Filter](http://developer.samsung.com/sd2_images/galaxy/content/sms_camera_04.jpg)

# Image

Image package provides features which work on a heterogeneous environment, thereby providing maximum benefits in terms of performance for the application developer.

This feature supports basic operations like load/save image in raw/jpeg and resizing to high performing algorithms like convolution, edge operations, histogram equalization and mathematical operations.

The following are the currently supported features:

- Large and various image data I/O interface
  - Large image handling : Bitmap object, jpeg file, raw file, etc.
  - Various image format : RGBA, NV21, YUYV, RGB888,JPEG
- Fast image processing algorithm that utilizes various hardware resources
- Edge operation, convolution, color space conversion, image transformation, etc.


![Image](http://developer.samsung.com/sd2_images/galaxy/content/sms_camera_05.jpg)

## LICENSE

Copyright © 2010 - 2017 SAMSUNG All rights reserved.

Portions of this page are reproduced from work created and shared by the Android Open Source Project and used according to terms described in the [Creative Commons 2.5](https://creativecommons.org/licenses/by/2.5/) Attribution License.
