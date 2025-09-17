# manim-voiceover-plus

[pypi page](https://pypi.org/project/manim-voiceover-plus/)

Follow [manim-voiceover installation guide](https://voiceover.manim.community/en/stable/installation.html) but just replace `manim-voiceover` for `manim-voiceover-plus`. For example: 

```
pip install --upgrade "manim-voiceover-plus[azure,elevenlabs]"
```

This is a fork from https://github.com/ManimCommunity/manim-voiceover/.

Unlike the upstream repository, this repository contains portable code and custom features for Viso.

View [manim_voiceover_plus/services/elevenlabs.py](./manim_voiceover_plus/services/elevenlabs.py) for all available options, and [examples/elevenlabs-example.py](./examples/elevenlabs-example.py) for an example.
