# Vision-Neuroscince-Final-Project

This project explores decision-making processes in visual neuroscience using computational modeling and psychophysical analysis. Specifically, the study employs the **Random Dot Motion (RDM) task** to gather behavioral data and analyze it using the **Drift Diffusion Model (DDM)** and the **Wang Model**. The goal is to understand how the brain accumulates evidence and makes decisions under varying levels of task difficulty.

## Project Overview

The study focuses on:
1. **Random Dot Motion Task (RDM)**: A classic task used in visual neuroscience to study perceptual decision-making. Subjects observe dots moving on a screen and are asked to decide the overall direction of movement under different coherence levels.
2. **Drift Diffusion Model (DDM)**: Used to model the decision-making process, capturing parameters such as drift rate, decision boundary, and non-decision time.
3. **Wang Model**: Simulates decision-making as a competition between neural populations, offering insights into the dynamics of neural competition in perceptual decisions.

### Key Objectives
- **Perceptual Decision-Making**: Understand how participants accumulate evidence to make decisions.
- **Learning and Performance**: Track how learning affects decision-making performance across different phases.
- **Neural Dynamics**: Use computational models to simulate and analyze neural competition during decision-making tasks.

## Materials and Methods

### Random Dot Motion Task
Participants performed multiple trials of the RDM task, observing dots on a screen with varying levels of coherence (3.2%, 6.4%, 12.8%, and 25.6%). Participants were required to judge the direction of dot motion (left or right) by pressing a corresponding button.

- **Stimulus Duration**: 500 milliseconds per trial.
- **Response Collection**: Reaction time and accuracy were recorded for each trial.
- **Phases**: The experiment was divided into three phases: pre-training, training, and post-training, to measure how learning affected decision-making performance.

### Drift Diffusion Model (DDM)
The DDM models the decision-making process as the accumulation of evidence over time until a decision boundary is reached. The key parameters analyzed include:
- **Drift Rate**: The rate of evidence accumulation.
- **Decision Boundary**: The amount of evidence required for a decision.
- **Non-Decision Time**: Time taken for sensory and motor processes outside of decision-making.

DDM parameters were fitted to the data using the **fast-dm software**, and changes in these parameters were tracked across different phases of the experiment.

### Wang Model
The Wang model simulates decision-making as a competition between neural populations, incorporating:
- **Recurrent Excitation**: Within each population of neurons.
- **Mutual Inhibition**: Between opposing populations.
- **Stochastic Inputs**: To account for variability in sensory input and cognitive processing.

The model was used to simulate the RDM task, and the results were compared to the experimental data.

## Results

- **Psychometric Results**: Higher coherence levels resulted in faster and more accurate decisions.
- **Learning Effects**: As participants progressed through the phases, their accuracy improved, and their reaction times decreased.
- **DDM Analysis**:
  - **Drift Rate**: Increased with task difficulty, indicating more efficient evidence accumulation.
  - **Decision Boundary**: Decreased over time, suggesting participants became more confident in their decisions as they learned the task.
  - **Non-Decision Time**: Remained relatively stable.
- **Wang Model Results**: The model successfully replicated human-like accuracy and reaction times, providing a deeper understanding of neural competition during decision-making.

## Figures

- **Accuracy vs Coherence Level**: Psychometric curves showing performance across coherence levels.
- **Reaction Time vs Coherence Level**: Graphs illustrating how reaction times varied with task difficulty.
- **DDM Parameter Changes**: Drift rate, decision boundary, and non-decision time plotted over different phases.

## Conclusion

This study combines computational models and psychophysical experiments to analyze decision-making in visual neuroscience. The results contribute to the understanding of neural mechanisms involved in perceptual decision-making and demonstrate the importance of integrating experimental data with computational modeling.
