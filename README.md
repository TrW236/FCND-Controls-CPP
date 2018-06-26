# Control System for Quadrotor

## Thrusts for each propellers

There are **four** forces `F_0, F_1, F_2, F_3` called thrusts needing to be calculated, given the collective thrust command `F_c`, the moment commands `M_p, M_q, M_r` for each axis in the body frame.

We can form four equations from the known given commands and use algebra to solve these equations, to get the thrusts for each propeller.

## Body Rate control

Given the measured rotation speed `pqr` in the body frame, and the rotations speed commands `pqrCmd`, the moment for each axis should be calculated.

A P-controller is used here for the body-rate-control.

## Roll pitch control

A P-controller is used 

## Altitude control

## lateral position control

## yaw control

## References
* [Udacity Flying Car Nanodegree](https://www.udacity.com)
* [original repository from Udacity](https://github.com/TrW236/FCND-Controls-CPP)
* [convert outputs to motor thrusts](https://www.overleaf.com/read/thzntmhcqkkp#/63267348/) - A. Karpinska