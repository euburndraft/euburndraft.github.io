---
layout: post
title: OrthoIrCam Algorithm in on Github
description: Code for image orthorectification from handheld aiborne Long Wave IR camera is available on Github.
image:
thumbnail: "/img/posts/thumbnail/orthoircam_thumbnail.png"
tags: [news]
---


<figure>
  <img src="{{site.url}}/img/posts/full/orthoircam.png" alt="orthoircam: feature tracking on shabeni1 fire" class="image-post-header"/>
  <figcaption class="small text-center"> Example of feature tracking performed in OrthoIrCam. on the left is the image to be orthorectified, on the right the reference image at that time. </figcaption>
</figure>
<br>
<br>
The OrthoIrCam algorithm for the orthorectification of Long Wave Infra Red (LWIR) images presented in [paugam et al 2021](https://doi.org/10.3390/rs13234913) is now available on open source on [Github](https://github.com/3dfirelab/OrthoIrCam). It is provided with a full test case also made available on open source on the [dataverse.csuc.ca](https://doi.org/10.34810/data565) repository.

The test case is a 1-hectare experimental burn conducted in 2008 during a field campaign in Ngarkat Conservatory Park in Australia. The campaign was organized within the FuSE Aerial Suppression Experiments project run by CSIRO and Bushfire CRC. The camera used were a Long Wave Infra Red (LWIR) FLIR 570 and a standard visible camera. Both were handheld from a hovering off-nadir helicopter located on the side of the burn plot with a large view angle of around 60 degree. The fire lasted 5.20 min and the camera collected radiometric frames at 5Hz, so that 1335 frames were recorded.

Results of the OrhtoIrCam algorithm is shown below:

{% include youtubePlayer.html id="bIaeLFx3yBM" label="orthoircam test case"%}
