## Cyclic Network Gradients


### Time-varying cyclic interaction and its cumulative DC-Wasserstein average


Subject **139637**, the first subject in Figure 2.


<p align="center">
  <img src="dc_wasserstein_subject_139637_cumulative.gif" width="100%" alt="Left: current-window cyclic flow. Right: cumulative DC-Wasserstein average from the beginning of the recording through the current time, for subject 139637.">
</p>


- **Left:** the projected cyclic flow from the current sliding window.
- **Right:** the cumulative DC-Wasserstein average of all window-level cycle measures available from the beginning of the recording through the displayed time. It is not an arithmetic average of edge flows or rendered images.
- **Time:** seconds since the first acquired frame. The displayed time is the end of the current window. The recording contains 1,200 frames at TR = 0.72 seconds, with 28-frame (20.16-second) windows advancing by one frame.


For the first $k$ windows, the cumulative average solves numerically


$$
\bar\mu_{1:k}\in\arg\min_{\nu}
\frac{1}{k}\sum_{i=1}^{k}W_{2,\mathbb S}^{2}(\nu,\mu_i).
$$


The animation contains 60 displayed time points. **All intervening windows are included in each cumulative fit**, not only the windows shown in the animation. The streamlines show cyclic edge flows; the cumulative measure is visualized through its first moment. Both panels use the same superior view and brain outline. 


### Time-varying streamline animations for 3 subjects

<p align="center">
  <img src="harmonic_superior_subject_01.gif" width="32%" alt="Harmonic streamlines">
  <img src="harmonic_superior_subject_02.gif" width="32%" alt="Harmonic streamlines">
  <img src="harmonic_superior_subject_03.gif" width="32%" alt="Harmonic streamlines">
</p>

