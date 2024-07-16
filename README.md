### EEG Signal Classification Project

This project focuses on classifying EEG signals into three categories: Left Hand (LH), Right Hand (RH), and Neutral (N). Utilizing neural networks, specifically convolutional neural networks (CNNs) with temporal and spatial convolutions, we aim to accurately classify motor imagery signals.

### Project Scope

- **EEG Signals**: Collected from participants performing motor imagery tasks.
- **Classification**: Three-class classification (LH, RH, N).
- **Neural Networks**: Implementation and experimentation with Conv1D and Conv2D architectures.

### Dataset

- **Frequency**: 200 Hz
- **Participants**: 7 participants
- **Labels**:
  - 1: Left Hand
  - 2: Right Hand
  - 3: Passive State
  - 99: Initial Relaxation
  - 91: Pause inter-trial
  - 92: End of experiment

### Preprocessing

- **Principal Component Analysis (PCA)**: 12 principal components.
- **Independent Component Analysis (ICA)**: 11 components.
- **Frequency Range**: Alpha + Beta waves (8-30Hz).
- **Normalization**: Z-Score normalization.

### Learning Frameworks

- **Basic CNN with Conv1D**
- **Recurrent CNN with Conv1D**
- **GRU (Gated Recurrent Unit)**
- **Recurrent Network with Conv2D layers**

### Results and Achievements

- **Accuracy**: 0.84
- **Best Performing Network**: Conv1D for single participant data, demonstrating higher accuracy and speed compared to Conv2D.
- **Observations**:
  - Conv2D requires more precise preprocessing and configurations.
  - Conv1D is easier to implement and provides better performance for time-series data.

### Conclusion

The project successfully demonstrates the potential of using CNNs for EEG signal classification. Future developments include experimenting with different frequencies, stream data for real-world applications, and improving preprocessing techniques.

### Future Development

- Utilize different frequencies as additional dimensions or columns.
- Implement real-time stream data for practical applications.
- Enhance preprocessing methods to improve overall classification performance.

### Challenges

- Preprocessing the data effectively.
- Synthesizing results into a comprehensive paper.

---

### Repository Structure

- **HDA_project.ipynb**: Jupyter notebook containing the code for data preprocessing, model training, and evaluation.
- **HDA-Presentation.pdf**: Presentation summarizing the project scope, methodology, and results.

---

This project showcases my skills and experience in data preprocessing, neural network implementation, and EEG signal analysis.
