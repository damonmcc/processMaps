# processMaps
This is a set of Python functions that processes optical mapping data.

Image Processing Order of Operations:
1. Remove Background
2. Smooth (Blur)
3. Normalization
4. Rotate Image

Signal Processing Order of Operations (After Image Processing):
1. Temporal Filtering
2. Drift Removal
3. Peak Detection (the peak detector is indifferent to Y-axis, but you may want max dF/dt in fluorescence/sec)
4. Normalization
5. Feature Extraction
