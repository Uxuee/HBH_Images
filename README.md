# Procedural Black-Hole Ringdown Illustration

This repository contains the code used to generate a schematic illustration of black-hole ringdown for science communication and press-release material.

The image shows a black-hole/photon-ring schematic together with a damped oscillatory waveform, representing the ringdown stage of a perturbed black hole.

## Important note

This image is **not generative-AI artwork**.

It is generated procedurally from Python code using `numpy` and `matplotlib`. The waveform is a mathematical damped oscillation, and the black-hole/ring structure is drawn using deterministic plotting commands.

The figure is intended as a **schematic illustration**, not as an observational image, numerical-relativity simulation, or detector waveform.

## Scientific context

After a black hole is perturbed, for example after a merger, the final remnant settles down by emitting a fading gravitational-wave signal known as ringdown. This signal can be described by damped oscillations called quasinormal modes.

In the high-frequency/eikonal approximation, the ringdown frequency and damping rate are related to the properties of unstable photon orbits around the black hole. This connection motivates using ringdown signals to study black-hole geometry and possible surrounding effective matter.

## Files

- `procedural_black_hole_ringdown.py`  
  Python script that generates the illustration.

- `procedural_black_hole_ringdown.png`  
  High-resolution PNG version of the figure.

- `procedural_black_hole_ringdown.svg`  
  Editable vector version of the figure.

## Requirements

The code requires:

```bash
python >= 3.9
numpy
matplotlib
pillow
```

Install dependencies with:

```bash
pip install numpy matplotlib pillow
```

## Usage

Run:

```bash
python procedural_black_hole_ringdown.py
```

This will generate the image files in the output directory.

## Suggested caption

Schematic illustration of black-hole ringdown. After a black hole is perturbed, its gravitational-wave signal fades as a damped oscillation. The frequency and damping rate can carry information about the black-hole geometry and possible surrounding effective matter.

## Credit

Ariadna Uxue Palomino Ylla 

## License

Please check with the author before reusing this image in press, outreach, or publication material.
