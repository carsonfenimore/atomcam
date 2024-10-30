# atomcam
Atomcam is an open source security camera. The software running on atomcam is called atomrust (https://github.com/carsonfenimore/atomrust).  This page contains the physical platform.  As of the writing of this document not all the needed documentation has been updated.  We hope to publish the model files, assembly instructions, and configuration soon.

# Case
The following case is available for printing. Recommend using PETG or ABS. Coming soon.

# Electronics
The camera consists of the following components:
  - pi zero 2w: $15 (https://www.raspberrypi.com/products/raspberry-pi-zero-2-w/)
  - 850nm LED: $0.4 (https://www.amazon.com/gp/product/B01BVGU1R8/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)
  - 5v regulator: $2 https://www.amazon.com/gp/product/B0B779ZYN1/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&th=1
  - Camera:
    - High quality option: arducam IMX327 (B0425) + csi cable + 140deg V lens + motorized m12 mount ($50)
    - Afforable option: $23 https://www.amazon.com/Arducam-Day-Night-Raspberry-Automatic-Switching/dp/B07X1VGQSL?th=1
   
The affordable option, plus other components, runs the total cost to be under $50.  There is a sony IMX 462 option that may work.

# Physical Installation
The case is designed to hold all electronics.  It then snaps into the mount which is secured to any surface.

# Security Setup
For logging of video we recommend BlueIris. It is inexpensive and works for any number of camera for a very low price (~$65).  For event monitoring and response, we recommend HomeAssistant.  It can process the realtime atomrust events and notify you via any number of methods (sms, smtp, etc.).  We plan to post sample configurations here soon.



