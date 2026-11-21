# Archived configuration

Enabled: chassis, CAN board-command reception, INS, and referee tasks. Gimbal, robot-command, shooting, steering, and board-command sending task creation is commented out. This snapshot is configured for a chassis-side role.

Four-wheel velocity mixing, motor-feedback PID control, and referee-based power limiting. Gimbal source includes yaw/pitch control, inertial feedback, and CAN motor commands.

All three robot projects retain a shared framework. The existence of additional chassis/steering code in a snapshot does not prove that every variant is configured or used on this robot.
