# Control bootcamp

Notes from Steve Brunton's YouTube series 'Control Bootcamp'. https://www.youtube.com/watch?v=Pi7l8mMjYVE&list=PLMrJAkhIeNNR20Mz-VpzgfQs5zrYi085m

## Control in Python

The following is a fantastic website for control in Python:
https://apmonitor.com/pdc/index.php/Main/ModelSimulation

A nuance with the Scipy.Signal.StateSpace(A,B,C,D) function is that values must not be integers. 

# Kalman filters
Kalman filters are an example of feedback control, where the K feedback value for the feedback system (A-Bk)X is the Kalman gain value.

Kalman filters provide a methodology for state estimation and are known as linear state estimation. State estimation is allows a subset of the control parameters to be measured but can form a prediction of the entire state space.

# Difference equations
Difference equations = discrete
Differential equations = equations

https://studylib.net/doc/13559493/18.03-difference-equations-and-z-transforms-jeremy-orloff

## Time-invariant system
A time-invariant system is a system where output y(t) does only implicitly depends on time through X(t).
A time-invariant system
y(t) = X(t)
Non-time-invariant
y(t) = tx(t)
