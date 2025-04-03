# `imagefilterpy`

`imagefilter.py` application demonstrates how to implement a custom image filter (crosshair overlay) using Python API of [MRTech IFF SDK](https://mr-te.ch/iff-sdk).
It is located in `samples/07_filter_py` directory of IFF SDK package.
Application comes with example configuration file (`imagefilter.json`) demonstrating the following functionality:

* acquisition from XIMEA camera
* color pre-processing on GPU:
  * black level subtraction
  * histogram calculation
  * white balance
  * demosaicing
  * color correction
  * gamma
  * image format conversion
* automatic control of exposure time and white balance
* image export to the user code
* image import from the user code
* H.264 encoding
* RTSP streaming
* HTTP control interface
