# strokesmith
Raster line art to ordered vector strokes, as a dataset.

strokesmith converts line art images (anime, manga, illustrations) into
sequenced stroke data, ready to train
stroke-based generative models.

There is no public stroke-sequential dataset for drawing line art.
This project builds the pipeline to create one.

<img width="5066" height="2522" alt="Firefly" src="https://github.com/user-attachments/assets/c114e040-873e-468b-a1f2-04f716585829" />

## Status

**This repository is open from commit zero, but nothing is finished.**

There is no working code yet. The pipeline is being designed first,
implemented second. If you're reading this, you arrived early.

- [ ] Pipeline spec & design
- [ ] Skeleton backend
- [ ] CLI & batch mode
- [ ] JSON/SVG/NPZ export
- [ ] First release (0.1.0)

### Why public from day one?

Because the interesting problems are unsolved. Junction topology,
stroke segmentation, and drawing-order heuristics all have open
questions.

## Contributing

Welcome, I will be happy if you wish to contribute!

Issues are the best entry point right now. Post questions, edge cases,
papers worth reading. PRs welcome once there's code to review.

### AI Use Policy

#### For Core Maintainers

All code, assets, and documentation in this repository are created manually by humans. Generative AI tools are strictly prohibited in the direct development pipeline; research assistance and documentation grammar checks are the only allowed exceptions.

#### For Contributors

We do not accept pull requests that contain AI-generated code or text. By submitting a contribution, you certify that:
1. You wrote the code yourself.
2. No automated code-generation utilities were used directly.

##### Please Note
There is no problem with using AI to answer questions or clear up confusion, as long as you are not using it to compensate for a lack of knowledge or to replace critical and logical thinking (as human reasoning and judgment remain essential, by now).

## License

BSD-3-Clause (see `LICENSE`)
