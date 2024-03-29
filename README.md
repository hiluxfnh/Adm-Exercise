# Debugging Exercises README

## Introduction
This repository contains my solutions to a series of debugging exercises. Each exercise involved finding and fixing bugs in Python code. The exercises covered various topics, including function implementations, numpy array manipulation, data plotting, and neural network training.

## Exercises

### 1. `id_to_fruit` Function
- **Issue:** The function did not return the correct fruit name corresponding to the given ID.
- **Solution:** I fixed the function by properly iterating over the set of fruits and returning the fruit name when the index matched the given ID.

### 2. `swap` Function
- **Issue:** The function had an obvious error and did not produce the expected output after fixing it.
- **Solution:** I corrected the function by properly swapping the x and y coordinates in the numpy array.

### 3. `plot_data` Function
- **Issue:** The precision-recall curve plot did not show correctly.
- **Solution:** I fixed the issue by ensuring the correct data was being plotted and adjusting the plotting code as needed.

### 4. `train_gan` Function
- **Issue:** Changing the batch size triggered a structural bug, and there was a cosmetic bug related to plotting.
- **Solution:** I addressed the structural bug by ensuring consistency in input sizes, and I fixed the cosmetic bug related to plotting by adjusting the code to display the generated images properly.

## Usage
To use this repository:
1. Clone the repository to your local machine.
2. Navigate to each exercise directory to view the code and changes made.
3. Execute the code to verify the fixes and observe the expected output.

## Conclusion
Debugging exercises are essential for improving coding skills and understanding common errors. Through this series of exercises, I gained valuable experience in identifying and resolving bugs in Python code. These exercises helped me sharpen my problem-solving abilities and become more proficient in debugging techniques.
