# How Myopia Blurs Vision

An interactive educational simulation that shows how near-sightedness (myopia) blurs distant vision, built as part of a high school independent study on myopia and the optics of the eye. It is intended for teenagers with little background in eye science.

**Live site:** https://wt0ast.github.io/how-myopia-blurs-vision/

## What it includes

- **Guided examples.** A short opening choice ("Distant things look blurry", "Close things look blurry", "Both or not sure") opens a learning example. The choices are not a diagnosis.
- **Eye simulation.** A schematic eye shows where light focuses relative to the retina. Users can change the combined eye power (cornea and crystalline lens as one equivalent lens), eye length, object distance and glasses, or use the Typical, Near-sighted and High myopia presets.
- **Optional calculations.** Vergence (`U + P = V`) and focal distance (`d = n / V`, with n = 1.336) are worked out live and can be opened or closed at any step.
- **Myopia and hyperopia comparison.** A brief side-by-side comparison.
- **Dioptres demo.** A separate lens-in-air example of `P = 1 / f`.
- **Why myopia develops.** A compact summary of current research ideas (retinal feedback, near work and accommodation, defocus, outdoor light and dopamine, contrast and ON/OFF pathways, and genetics), each with its evidence and what remains uncertain.

## Scope and limitations

This is a simplified model for learning. It is not a personal prescription or prediction, the blur is an illustration, and astigmatism is not modelled. The example models axial myopia (an eye too long for its focusing power). Eye length is measured from the model's single focusing plane to the retina, so it is not a clinical axial-length measurement. The simulation shows how a longer eye blurs distant vision, not why an eye grows too long.

## Sources

The full reference list, with links, is inside the simulation (Sources and the "Why myopia develops" tab). Key references include the University of Arizona schematic eyes lecture, the American Academy of Ophthalmology optics reference, EyeWiki, and International Myopia Institute (IMI) reports on definitions, light, and genetics.

## Running it

The site is a single self-contained `index.html` file with no build step and no data collection. Open it in any modern browser, or view the live site above.
