Command Line to Show Jpeg Information Demo
==========================================

```
brew install imagemagick
identify -verbose demo.jpg
```

Will output:

```
Image: demo.jpg
  Format: JPEG (Joint Photographic Experts Group JFIF format)
  Mime type: image/jpeg
  Class: DirectClass
  Geometry: 300x300+0+0
  Resolution: 300x300
  Print size: 1x1
  Units: PixelsPerInch
  Colorspace: sRGB
  Type: TrueColor
  Base type: Undefined
  Endianess: Undefined
  Depth: 8-bit
  Channel depth:
    Red: 8-bit
    Green: 8-bit
    Blue: 8-bit
  Channel statistics:
    Pixels: 90000
    Red:
      min: 0  (0)
      max: 186 (0.729412)
      mean: 46.1033 (0.180797)
      standard deviation: 24.9706 (0.0979238)
      kurtosis: 1.03545
      skewness: 0.730331
      entropy: 0.870931
    Green:
      min: 31  (0.121569)
      max: 254 (0.996078)
      mean: 170.287 (0.667794)
      standard deviation: 34.5637 (0.135544)
      kurtosis: 1.14538
      skewness: -0.438814
      entropy: 0.891141
    Blue:
      min: 36  (0.141176)
      max: 255 (1)
      mean: 181.775 (0.712844)
      standard deviation: 32.1501 (0.126079)
      kurtosis: 1.92092
      skewness: -0.743747
      entropy: 0.882341
  Image statistics:
    Overall:
      min: 0  (0)
      max: 255 (1)
      mean: 132.722 (0.520479)
      standard deviation: 30.5614 (0.119849)
      kurtosis: -1.23132
      skewness: -0.395858
      entropy: 0.881471
  Rendering intent: Perceptual
  Gamma: 0.454545
  Chromaticity:
    red primary: (0.64,0.33)
    green primary: (0.3,0.6)
    blue primary: (0.15,0.06)
    white point: (0.3127,0.329)
  Matte color: grey74
  Background color: white
  Border color: srgb(223,223,223)
  Transparent color: none
  Interlace: None
  Intensity: Undefined
  Compose: Over
  Page geometry: 300x300+0+0
  Dispose: Undefined
  Iterations: 0
  Compression: JPEG
  Quality: 97
  Orientation: TopLeft
  Properties:
    date:create: 2018-08-25T14:26:27+08:00
    date:modify: 2018-08-25T14:26:08+08:00
    exif:ColorSpace: 65535
    exif:DateTime: 2017:09:11 22:15:46
    exif:ExifImageLength: 300
    exif:ExifImageWidth: 300
    exif:ExifOffset: 236
    exif:Orientation: 1
    exif:ResolutionUnit: 2
    exif:Software: Adobe Photoshop CS5 (12.0x20100115 [20100115.m.998 2010/01/15:02:00:00 cutoff; m branch])  Windows
    exif:thumbnail:Compression: 6
    exif:thumbnail:JPEGInterchangeFormat: 374
    exif:thumbnail:JPEGInterchangeFormatLength: 4083
    exif:thumbnail:ResolutionUnit: 2
    exif:thumbnail:XResolution: 72/1
    exif:thumbnail:YResolution: 72/1
    exif:XResolution: 3000000/10000
    exif:YResolution: 3000000/10000
    jpeg:colorspace: 2
    jpeg:sampling-factor: 1x1,1x1,1x1
    signature: 45c36c633b8a332efc1bfa643b2e8f669544a93e2b66562f96a96b17847ff146
  Profiles:
    Profile-8bim: 6174 bytes
    Profile-exif: 4463 bytes
    Profile-iptc: 15 bytes
      City[1,90]: 0x00000000: 254700                                        -%
      unknown[2,0]: ��
    Profile-xmp: 3424 bytes
  Artifacts:
    verbose: true
  Tainted: False
  Filesize: 51085B
  Number pixels: 90000
  Pixels per second: 3MB
  User time: 0.010u
  Elapsed time: 0:01.029
  Version: ImageMagick 7.0.8-2 Q16 x86_64 2018-06-19 https://www.imagemagick.org
```

If you want to know the creation timestamp of the picture, it's:

```
exif:DateTime: 2017:09:11 22:15:46
```

Links
-----

- https://superuser.com/questions/275502/how-to-get-information-about-an-image-picture-from-the-linux-command-line
- https://www.sample-videos.com/download-sample-jpg-image.php