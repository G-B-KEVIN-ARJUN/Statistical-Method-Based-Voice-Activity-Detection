# Statistical-Method-Based-Voice-Activity-Detection
A statistical model based voice activity detector has been made, where the decision rule is derived from the likelihood ratio test (LRT) by estimating unknown parameters using the decision-directed method. Hang-over scheme based on the hidden Markov model (HMM) is applied for window initial boundary smoothening for variable-rate speech coding applications increases and the role of voice activity detector (VAD) becomes crucial for the efficient bandwidth reduction

Flow of our Designed Approach-
1) Divide the Signal into L dimensional frames
2) Decision Based LRT (Likelihood Ratio Test)​- We calculate the Likelihood Ratio which is the ratio of presence of audio signal given speech signal is present upon presence of audio signal given speech signal is absent
3)  We will be calculating this Ratio for each of the window and getting the geometric mean of Likelihood Ratio of all the windows
4)  Then we will be calculating maximum likelihood Value of unknown parameter which is the posterior Signal-Noise Ratio assuming the variance of signal and noise is already known
5)  Using that maximum likelihood Value of unknown parameter which is the posterior Signal-Noise Ratio we wouldbe estimating the maximum likelihood value of the Likelihood ratio and with this likelihood ratiowe would be thresholding our signal for both the hypothesis we considered
6)  Now we will apply the Hidden Markov Model (HMM) based hangover scheme to prevent clipping of weak speech tails considering previous decision results in two consecutive windows.​

​
