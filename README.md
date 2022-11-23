Singularity recipe files for ImageMagick https://imagemagick.org/

Generate symlinks like:
```
singularity exec imagemagick-7.1.0.52.sif ls -1 /opt/imagemagick/bin | xargs -L1 ln -s imagemagick-7.1.0.52.sif
```

