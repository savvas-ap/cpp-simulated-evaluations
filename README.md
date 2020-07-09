# CPP Simulated Evaluation

![mCPP plan](paths.png)

### Description
In this repository you can find a set of 20 polygon Regions of Interest (ROIs) that were used for the evaluation of an
innovative, optimized for real-life use, STC-based, multi-robot Coverage Path Planning (mCPP) algorithm, along with the
elaborate results for each ROI. In the context of this work, was developed and proposed an innovative optimization scheme,
consisted of three separate terms (J_1, J_2 and J_3). In the results you can find the performance evaluation for the plain,
non-optimized STC approach, and for the STC algorithm with the introduction of this optimization procedure, term-by-term.
In addition to that, for each ROI are also calculated coverage plans, according to the methodology described in
[https://arxiv.org/abs/1907.09224 | https://github.com/ethz-asl/polygon_coverage_planning], with two different cost
functions that intend to reduce the number of turns and overall length of path respectively. These results are also available
in details.

### Evaluation metrics
For each generated path were calculated the following evaluation metrics:

- Percentage of Coverage (PoC)
- Percentage of Overlapping Coverage (PoOC)
- Number of turns
- Normalized Number of Turns
- Path length
- Normalized path length

In addition to them were created a heatmap of coverage for the paths in each ROI (example in the following image)

![heatmap of coverage](HM.jpg)

and a histogram of overlapping coverage, showing the times that each coverage point of the ROI was scanned (example in the
following image)

![histogram of overlapping coverage](HOC.jpg)
