# Build an Apartment Starter Project

This project is part of [Udacity](https://www.udacity.com "Udacity - Be in demand")'s [VR Developer Nanodegree](https://www.udacity.com/course/vr-developer-nanodegree--nd017).

## Versions
- Unity 2017.1.0p4
- GVR Unity SDK v1.70.0

### About Lightmap Settings:

I tried different Lightmap Resolution settings 5, 40 and 80 texels per unit with compressed and uncompressed lightmaps. I activated Soft Shadows on each light.
The uncompressed lightmaps always produced smoother and nicer shadows,  so I stuck with the uncompressed setting. 5 texels per unit resolution was too low, the shadows were dark and sharp. The uncompressed 80 texels per unit resolution produced an 8 MB lightmap size, and the performance on my phone did not seem as good as before. Finally, I chose uncompressed 40 texels per unit setting.

#### Submitting for 
Android 
