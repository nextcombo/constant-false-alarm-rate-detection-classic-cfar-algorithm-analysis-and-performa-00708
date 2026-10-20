# [Constant False Alarm Rate Detection]Classic CFAR Algorithm Analysis and Performance Chart Display [Attached MATLAB Code]

1. Basic Knowledge of CFAR
The concept of constant false alarm rate (CFAR) detection technology refers to the technique used by radar systems to distinguish between the signal and noise output from the receiver under constant false alarm probability conditions, thereby determining whether a target signal exists.
Prerequisite: Since there is always noise at the receiver output end (including atmospheric noise, man-made noise, internal noise, and clutter, etc.), and the signal is generally superimposed on the noise, it is necessary to use detection techniques to determine if there is a target signal when the noise or signal with noise is added to the receiver output.
Error Probabilities: Any form of decision inevitably involves two error probabilities: detection probability and false alarm probability. When there is a target echo signal at the receiver output end and the probability of making a decision as having a target is Pd, and the probability of making a decision as not having a target is 1 - Pd. When only noise is present at the receiver output end and the probability of making a decision as having a target is Pfa. Since noise is a random variable, its characteristic can be represented by a probability density function, so the signal with noise is also a random variable [1].
Specific Process: The Constant False Alarm Rate detector first processes the input noise to determine a threshold. This threshold is compared with the input signal; if the input signal exceeds this threshold, it is judged as having a target, otherwise, it is judged as not having a target.
Method: To keep the false alarm probability constant, the threshold is adjusted rapidly according to changes in the input noise. The noise processing method varies depending on the distribution of the noise, hence the Constant False Alarm Rate detection technology includes both Constant False Alarm Rate processing technology and Target Detection Technology. The Constant False Alarm Rate processing technology includes fast gate, slow gate processing technology, and target detection includes likelihood ratio detection, binary detection, sequential detection, and non-parametric detection, etc.
II. Classical CFAR Algorithm Analysis and Performance Map Display
① Mean Class CFAR
The core idea is to estimate the background power by taking the average of the sampling data within the reference window.
CA-CFAR, GO-CFAR, SO-CFAR algorithms are the most classic mean class CFAR algorithms, followed by their variations such as log-CFAR algorithm but with the same principle.
Figure 1: Principle diagram of mean class CFAR detector
2. Statistical Ordered CFAR
The core idea is to select the Kth value in the data within the reference window from smallest to largest, assuming it as clutter background noise.
Figure 2: OS-CFAR detector principle diagram
3. Adaptive CFAR
Different decision methods are adopted for different clutter types.
Figure 3: HCE-CFAR detector principle diagram
Figure 4: VI-CFAR detector principle diagram
4. Clutter Map CFAR
A classic airborne clutter map CFAR algorithm assumes that the squared rate values on each range element and azimuth angle follow an independent identical distribution, and fits the clutter background noise by forgetting iteration over time dimension.
Figure 5: Clutter map CFAR detector principle diagram
III. Current Development of CFRA
Mean-class - statistical ordered - adaptive - clutter map - transform domain - compression sensing - neural network

## Images

![(Constant False Alarm Ratio Detection)Classic CFAR algorithm analysis and performance map display [with MATLAB code]](01.jpg)
![(Constant False Alarm Ratio Detection)Classic CFAR algorithm analysis and performance map display [with MATLAB code]](02.png)
![(Constant False Alarm Ratio Detection)Classic CFAR algorithm analysis and performance map display [with MATLAB code]](03.png)
![(Constant False Alarm Ratio Detection)Classic CFAR algorithm analysis and performance map display [with MATLAB code]](04.png)
![(Constant False Alarm Ratio Detection)Classic CFAR algorithm analysis and performance map display [with MATLAB code]](05.png)

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
