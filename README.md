# Question 3: Curriculum DQN on Breakout

## Overview  
Implement a curriculum-based DQN with dual-head (Q + spike detector) on Atari Breakout,  
track reward, detection accuracy, and recovery time after dynamic difficulty spikes.

## Files  
- *Q3_notebook.ipynb*  
  - Cell 1: Installs & Imports  
  - Cell 2: Environment & Curriculum wrapper  
  - Cell 3: DQNAgent w/ detection head & recovery tracking  
  - Cell 4: Safe training for 200 episodes + partial-save  
  - Cell 5: Plotting rewards, detect-acc, recovery times
  
## *Requirements.txt*
gym[atari,accept-rom-license]
autorom
tensorflow>=2.10
matplotlib

## Usage  
1. open Q3_notebook.ipynb in Colab (GPU runtime).  
2. Run Cells 1→5. Training for 200 episodes completes in ~6 min on T4.  
3. Find videos in videos/ and model in .h5.  
4. Reproduce plots in Cell 5.
