# Learning through the noise: Computational Modeling of ADHD
## Directory Roadmap

### Data
Includes data files from BabyLM 100M (https://babylm.github.io/) that has been augmented in various ways to simulate ADHD auditory processing difficulties - two different settings:
  aochildes_frequent_interruptions.train - interruptions inserted within lines
  aochildes_less_frequent.train - interruptions every few lines
  aochildes.train - baseline (no interruptions)

### Training
Includes ipynb for training a gpt-wee model

### Evaluation
Includes ipynb for prompting the model and measuring semantic similarity
