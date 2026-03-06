# jspsych-stroop-visual-world
Implementation of a hybrid cognitive experiment: Interleaved Stroop and Visual World Paradigm using the jsPsych framework.
# Interleaved Stroop & Visual World Paradigm (VWP) with Web-Based Eye-Tracking
This project is a cognitive psychology experiment developed using the jsPsych library and WebGazer.js integration. The design aims to examine the relationship between language processing and cognitive control mechanisms through both eye movements and mouse trajectories.

## Project Overview and Technical Features

The experimental design is based on the interleaved presentation of two core cognitive tasks:

1. Stroop Task: Measures reaction times and accuracy rates for stimuli containing color-word interference.
2. Visual World Paradigm (VWP): Tracks eye movements and selections among objects on the screen accompanied by auditory commands.

### Data Collection and Analysis Parameters

- Eye-Tracking: Real-time gaze data is collected via the browser using WebGazer.js. Calibration and validation phases are integrated into the experimental flow.
- ROI Analysis: Fixation counts for predefined Regions of Interest (ROI) and transitions between these areas are recorded.
- Mouse Trajectory: Coordinates and timestamps of the mouse movements during drag-and-drop tasks are included in the dataset.
- Coordinate-Based Accuracy: The overlap between the dragged object and the target area is verified using spatial algorithms.

## Directory Structure

The following folders must be present in the root directory for the experiment to function correctly:

- jspsych/: Contains the jsPsych core files and necessary plugins (free-sort (customised version), webgazer-validate, etc.).
- audio/: Audio files in .wav format used in the experiment.
- images/: Visual stimuli and object images.
- index.html: The main file containing the experimental logic and data collection scripts.

## How to Run

1. Download all files and folders from the repository.
2. Ensure the directory structure remains unchanged to maintain correct file paths.
3. Open index.html in a modern web browser (Google Chrome or Firefox recommended).
4. Grant camera access through the browser for the eye-tracking system to function.

## License

This project is developed for academic and personal use.
