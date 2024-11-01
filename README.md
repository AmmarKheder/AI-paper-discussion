# AI-paper-discussion
Memo for weekly AI paper discussion

We should only post link if PDF is too large.

## [20240927](20240927)
- Graph Neural Networks for temporal graphs: State of the art, open challenges, and opportunities
    - Methods for snapshot-based GNN: model evolution / embedding evolution


## [20241011](20241011)
- Spectral Temporal Graph Neural Network for Multivariate Time-series Forecasting
    - A combine of GFT and DFT of both inter-serial and intra-serial spectral knowledge
    - Attention for detect graph structure

## [20241025](20241025)

- PHYMPGN: PHYSICS-ENCODED MESSAGE PASSING GRAPH NETWORK FOR SPATIOTEMPORAL PDE SYSTEMS
  - For PDE/ODE system, to find y(t1) = G(y(t0)), y(t1) = y(t0) + intergal of y'(t) between t0 and t1. y'(t) is a function of system state of time t, i.e, y'(t) = F(y(t)).
  - Numerical methods (Runge-Kutta) to approximate integral, so we only need to find y'(t) = F(y(t)), instead of find y(t1) = G(y(t0)).
- Neurons spike back
  - history of science and technology perspective
