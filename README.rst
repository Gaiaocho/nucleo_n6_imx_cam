Use the video API to retrieve video frames from a capture device.


Currently depends on the state of zephyr at



Description
***********

This  application uses the :ref:`video_api` to capture frames from a video capture
device then uses the :ref:`display_api` to display them onto an LCD screen (if any).

Requirements
************

This sample needs a video capture device (e.g. a camera) but it is not mandatory.
Supported boards and camera modules include:
