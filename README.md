# performerRelativeClassifier
Experimental performer metadata classification using proportions, height normalization and percentile-based context

# Performer Relative Classifier

An experimental tool to analyze and classify performer body data based on industry proportions rather than general population averages.

## The Concept
Most body classifiers use absolute numbers or medical standards (like BMI) that don't always translate well to the adult industry. This tool explores **relative tagging**:

- **Proportional Context:** Acknowledges that 36” hips look completely different on a 4'11" frame vs. a 5'11" frame.
- **Industry Percentiles:** Labels (Curvy, Petite, etc.) are calculated based on a dataset of performers, showing where an individual sits compared to their peers within this specific niche.

## Features
- **Relative Tagging Logic:** Percentile-based classification for bust and hips relative to height.
- **Side-by-Side Comparison:** A dedicated overlay to contrast measurements and metrics between two profiles.
- **Gaussian Visualizer (Alpha):** A simplified, illustrative silhouette generator to help visualize proportions (Note: This is an aesthetic aid, not a scientific anatomical simulation).

## Disclaimer
This is a **VibeCode** project—built through intuition, trial, and error. It is intended for metadata enthusiasts as an illustrative exercise. It does not account for bone structure, fat distribution, or medical reality.

## How to use
Live Demo:
The easiest way to explore the tool is through https://kensatli84-pixel.github.io/performerRelativeClassifier/.
(Note: The live demo includes a sample set of records to demonstrate the classification logic and visualizer functionality).

Local Use:

Clone or download this repository.

Open index.html in any modern web browser.

Load the performers_classified.csv

(Optional) You can replace performers_classified.csv with your own dataset following the same column structure.
