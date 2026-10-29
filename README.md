# Advance-Topics-in-Robotics

ATiR assignments based on lectures.

## Inverse Kinematics

* Desired configuration: $\begin{equation}
    T^* = \begin{bmatrix}
    {}^0x_7 & {}^0y_7 & {}^0z_7 & {}^0p_e\\
    0 & 0 & 0 & 0 
    \end{bmatrix}
\end{equation}$

* Wrist center-point: $
\begin{equation}
    {}^0w = {}^0T_{7^*}{}^{7^*}w =
    \begin{bmatrix}
        {}^0x_7 & {}^0y_7 & {}^0z_7 & {}^0p_e\\
        0 & 0 & 0 & 0 
    \end{bmatrix}
    \begin{bmatrix}
        0\\
        0\\
        -d_7\\
        1
    \end{bmatrix}
\end{equation}
$
