# License and attribution

This assignment is adapted from **"Dimensionality Reduction Adventures with Animal Faces"**
by **Varada Kolhatkar** (University of British Columbia, Master of Data Science; EAAI-2026
model assignment). Copyright © 2025 Varada Kolhatkar.

* Instructional material (text, questions) is used and adapted under
  [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).
* Code is used and adapted under the MIT License (below).

**Changes for MCS 3950 (UPEI, Fall 2026):** course-specific setup and submission through
GitHub; self-check cells in place of Otter Grader; data repackaged as a NumPy `.npz` file and
downloaded by the notebook; a reworked off-distribution exercise (3.2); a new retrieval
challenge (Exercise 5) in place of the CNN-autoencoder extension; additional questions on PSNR,
explained variance and storage cost.

## Images

The animal faces are a 1,500-image grayscale subset of **Animal Faces-HQ (AFHQ)**,
Y. Choi, Y. Uh, J. Yoo, J.-W. Ha, *StarGAN v2: Diverse Image Synthesis for Multiple Domains*,
CVPR 2020, released under
[CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/). Use them for this course only;
do not redistribute them.

The probe images in Exercise 3.2 ship with [scikit-image](https://scikit-image.org).

## MIT License (code)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software
and associated documentation files (the "Software"), to deal in the Software without
restriction, including without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or
substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING
BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM,
DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
