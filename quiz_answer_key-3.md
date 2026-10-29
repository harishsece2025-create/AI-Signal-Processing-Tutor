# 10-Question Quiz — Answer Key

**Q1. What is the sampling interval when fs = 200 Hz?**

A. 200 s  B. 0.2 s  C. 0.005 s  D. 100 s

**Answer: C.** Ts = 1/fs = 1/200 = 0.005 s.

**Q2. For a band-limited signal with highest frequency B, the ideal Nyquist condition is:**

A. fs < B  B. fs > 2B  C. fs = B/2  D. fs = 0

**Answer: B.** Sampling frequency should exceed twice the highest frequency under ideal assumptions.

**Q3. A 30 Hz sine sampled at 40 Hz has alias magnitude:**

A. 30 Hz  B. 20 Hz  C. 10 Hz  D. 40 Hz

**Answer: C.** It folds about Nyquist: |30 - 40| = 10 Hz.

**Q4. The FFT is used primarily to:**

A. Integrate any function exactly  B. Reveal frequency content  C. Remove all noise  D. Increase sample rate

**Answer: B.** The FFT efficiently computes the DFT and helps inspect spectral content.

**Q5. With N samples and sampling frequency fs, FFT-bin spacing is:**

A. N/fs  B. fs/N  C. fs*N  D. 1/N

**Answer: B.** The bin spacing is fs/N.

**Q6. A low-pass filter generally:**

A. Keeps low frequencies and attenuates high frequencies  B. Keeps only high frequencies  C. Randomizes time  D. Changes Hz to seconds

**Answer: A.** This is the defining behavior of a low-pass filter.

**Q7. For sequences of lengths 3 and 2, full linear convolution length is:**

A. 1  B. 3  C. 4  D. 6

**Answer: C.** Length = 3 + 2 - 1 = 4.

**Q8. For x=[1,2,3] and h=[1,1], full convolution is:**

A. [1,2,3]  B. [1,3,5,3]  C. [2,4,6]  D. [1,1,2,3]

**Answer: B.** Direct convolution yields [1,3,5,3].

**Q9. A fixed random seed is useful because it:**

A. Removes noise  B. Makes a pseudo-random run reproducible  C. Guarantees true randomness  D. Raises SNR to infinity

**Answer: B.** It reproduces the same pseudo-random sequence in a compatible environment.

**Q10. Which is the best practice for AI-generated signal-processing code?**

A. Trust it if it runs  B. Use only its plot  C. Verify formulas, units, and assertions against known results  D. Skip references

**Answer: C.** Running code is not enough; numerical checks and domain verification are needed.