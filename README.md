# FRA631_HW_Peeradon

Repository for FRA631 Class Homework

**67340700403 พีรดนย์ เรืองแก้ว**

## Installation

step 1 create venv and activate it

For Windows
```bash
set-executionpolicy -Scope CurrentUser -ExecutionPolicy Unrestricted
python -m venv venv
venv/Scripts/Activate.ps1
```

For Linux or Mac

```bash
python3 -m venv venv
source venv/bin/activate
```

step 2 install requirements

```bash
pip install -r robot-requirements.txt
```


## 1. Forward and Inverse Kinematics

- **PDF:** [forward & inverse kinematics](./forward&inv_kinematics.pdf)
- **Code:** [forward & inverse kinematics notebook](./forward&inv_kinematics.ipynb)
- **Results:**  
```bash
q_HOME: [ 0.71448904 -1.93802991 -2.05205607 -2.27198233 -0.90031845  2.36535263]
q_IK  : [ 0.71448904 -1.93802991 -2.05205607 -2.27198233 -0.90031845  2.36535263]
Error : [ 0.0000000e+00  0.0000000e+00 -4.4408921e-16  4.4408921e-16 0.0000000e+00  00000000e+00]
RMSE  : 0.000000 rad
```
## 2. Trajectory Planning and speed control

- **PDF:** [trajectory planning & speed control](./tracjectory-planning&speed-control.pdf)
- **Code:** [trajectory planning notebook](./trajectory_planning.ipynb)
- **Results:**  
    ![Trajectory Result](./images/trajectory_result.gif)
