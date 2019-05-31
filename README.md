# Compare W&B and TensorBoard
Curious how TensorBoard and Weights & Biases compares? Try a quick example:

Step 1: Run the script
```
pip install --upgrade tensorflow
pip install --upgrade wandb
python mnist-tboard.py
```

Step 2: Click the W&B link printed at the top of the run
```
https://app.wandb.ai/...your-run-here...
```

Step 3: Run TensorBoard
```
tensorboard --logdir=/tmp/tensorflow/mnist
```

# Running multiple runs
With W&B, just re-run your script and we automatically start a new run for you. TensorBoard gets all gummed up unless you tell it to start logging events for a new run.
