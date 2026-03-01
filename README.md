# Bigram Language Model

This repository contains a simple bigram language model implementation.

- **Dataset:** Trained on the Shakespeare dataset.
- **Architecture:** Decoder-only model that uses a multi-head attention mechanism (no encoder block).
- **Positional encoding:** Inputs are positionally encoded before being fed into the attention layers.
- **Output:** Token probabilities are produced using softmax.

See the implementation in [bigram.py](bigram.py) and the training data in [input.txt](input.txt).

## Usage

To add this README and push the repository to GitHub (replace `<YOUR_REMOTE_URL>` with your remote):

```bash
git init
git add .
git commit -m "Add README"
git branch -M main
git remote add origin <YOUR_REMOTE_URL>
git push -u origin main
```

If you'd like, provide the remote URL and I can run the commit and push commands for you.

i would like to thank https://github.com/karpathy for inspiring me to build this
