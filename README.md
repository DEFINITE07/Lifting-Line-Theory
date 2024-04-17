This repository contains Python code for implementing lifting line theory to calculate lift coefficient (Cl) and drag coefficient (Cd) of an airfoil.

Overview
Lifting line theory is a fundamental aerodynamic theory used to analyze the lift and drag characteristics of wings, particularly for low aspect ratio wings. The provided Python script computes Cl and Cd using lifting line theory based on given parameters.

Parameters
a_01: Angle of Attack where Cl is 0 (in degrees).
a_0: Lift curve slope (in per radian).
lambda_val: Taper Ratio.
AR: Aspect Ratio.
phi: An array containing random values of phi (angle in degrees) for computation.

Output
The script will output the calculated lift coefficient (Cl) and drag coefficient (Cd) for the specified range of angles of attack.
