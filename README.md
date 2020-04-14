# Cilindro animado
A simple animation based on the povray animation proposed in http://www.f-lohmueller.de/pov_tut/animate/anim003e.htm

## How to animate

In linux use:

```
povray animation_a_.ini 
ffmpeg -framerate 24 -i animation_a_%02d.png  animacion.avi
```

In other systems can use the povray editor to render the images and use software like *format factory*.
