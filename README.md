# Caleb Bloch

Electrical Engineering student at Northeastern University, working on machine learning, computer vision, and decision-making under uncertainty.

I like improvement where there is no established path forward: choosing what to try, learning from what happens, and deciding where to go next.

## Selected projects

### [Market Forecasting Under Drift](https://github.com/cblocb/market-forecasting-under-drift)

A LightGBM forecasting study on 47.1 million anonymized market observations. The central question was whether temporal features improved performance on later data, or just looked promising because of how I selected them.

- Compared raw and temporal features using chronological splits and five expanding evaluation windows.
- Repeated feature selection inside each fold after identifying an optimistic comparison. The apparent improvement weakened, so I retained the simpler model.
- Published evaluation scripts, aggregate results, figures, and tests for metrics, chronological splits, causal features, and the final evaluation contract.

[Research walkthrough](https://github.com/cblocb/market-forecasting-under-drift#read-the-evidence) | [Results](https://github.com/cblocb/market-forecasting-under-drift#results) | [Tests](https://github.com/cblocb/market-forecasting-under-drift/blob/main/tests/test_project.py)

### [Distracted-Driver Classification](https://github.com/cblocb/distracted-driver-yolo)

A YOLO11n image classifier evaluated on five held-out drivers. Saved validation accuracy is **95.14%**, compared with an **88.12%** majority baseline; macro F1 is **0.8694**. Classwise analysis exposes weaker focused-driver recall. Includes configurable training/evaluation scripts, split and metric tests, original logs, and corrected evidence figures.

### [DQN Variants in a Stochastic Maze](https://github.com/cblocb/stochastic-maze-dqn)

Implemented standard, Double and Dueling DQN with replay and target networks in an 8-by-8 stochastic maze. Includes saved training curves, learned policy/value visualizations and a single-seed comparison, with training results distinguished from independent policy evaluation.

### [Motion Detection and Image Filtering](https://github.com/cblocb/motion-detection-image-filtering)

Compared temporal derivatives, spatial smoothing and adaptive thresholding on a fixed-camera sequence. Includes the filtering pipeline and qualitative mask/overlay comparisons.

## Other relevant work

These are experience summaries; the source code is not published on this profile.

- **Ramona Optics, ML / Computer Vision internship:** worked on microscopy segmentation, GPU-memory-aware tiled inference, and annotation tools for scientists. I focused on model errors and the practical time saved by improvements to the workflow.
- **ADIA Lab / CrunchDAO, real-time structural break detection:** directed experiments involving density representations, tree models, convolutional models, and augmentation. Used local validation to guide model choices and reduce reliance on public-test feedback. Final competition scoring is pending as of October 2026.

## How I work

I use AI extensively as an engineering collaborator. My work includes problem framing, model and experiment choices, reviewing outputs, and interpreting results. I care about understanding when an apparent improvement survives a more careful evaluation.

**Tools:** Python, PyTorch, LightGBM, NumPy, Pandas, Polars, OpenCV, Git, Linux.

[LinkedIn](https://www.linkedin.com/in/caleb-b-0968203a3/)
