## Rectified Flow

> By JamesSand

### 0 Current result

I have trained the second order model. The loss curve is not so good. But the visualization result is quite reasonable.

#### Loss curve

First order loss is ok. But second order loss has some spikes.

<div style="display: flex; justify-content: center; gap: 10px;">
  <img src="images\first_order_loss.png" alt="Figure 1" width="80%">
</div>

<br>

<div style="display: flex; justify-content: center; gap: 10px;">
  <img src="images\second_order_loss.png" alt="Figure 2" width="80%">
</div>

<br>

<div style="display: flex; justify-content: center; gap: 10px;">
  <img src="images\total_loss.png" alt="Figure 3" width="80%">
</div>


#### Visualization Result

<div style="display: flex; justify-content: center; gap: 10px;">
  <img src="images/second_order_v2_gen_scatters.png" alt="Figure 1" width="45%">
  <img src="images/second_order_v2_trajectory.png" alt="Figure 2" width="45%">
</div>


### 1 Env setup

```bash
pip install -r requirements.txt
```

### 2 Run code
```bash
python second_order_code.py
```

### 3 Visualize results

Please refer to `model_eval.ipynb`


