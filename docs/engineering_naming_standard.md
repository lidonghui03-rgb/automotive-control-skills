# Engineering Naming Standard
# 工程命名规范

This document defines naming rules for automotive engineering resources.
本文档定义汽车电子工程资源命名规则。

---

# General Rules
# 通用规则

- Use uppercase for ECU names.
- ECU名称使用大写。

- Use underscore (_) between words.
- 单词之间使用下划线。

- Avoid spaces in identifiers.
- 标识符中禁止空格。

- Use meaningful abbreviations only.
- 仅允许有意义的缩写。

- Naming must remain consistent across all documents.
- 所有文档中的命名必须保持一致。

---

# ECU Naming
# ECU命名规则

Format:
格式：

ECU_FUNCTION

Examples:
示例：

- BCM
- Body Control Module

- SCM
- Seat Control Module

- VCU
- Vehicle Control Unit

---

# Signal Naming
# 信号命名规则

Format:
格式：

SYSTEM_FUNCTION_DIRECTION

Examples:
示例：

- SEAT_FWD_REQ
- Seat forward request

- DOOR_LOCK_STS
- Door lock status

- IGN_ON_SIG
- Ignition ON signal

Direction keywords:
方向关键字：

- REQ → Request
- 请求

- STS → Status
- 状态

- CMD → Command
- 命令

- FB → Feedback
- 反馈

---

# CAN Message Naming
# CAN报文命名规则

Format:
格式：

ECU_FUNCTION_MSG

Examples:
示例：

- BCM_BODY_MSG
- SCM_SEAT_MSG
- VCU_POWER_MSG

---

# DID Naming
# DID命名规则

Format:
格式：

DID_FUNCTION

Examples:
示例：

- DID_VIN
- DID_SW_VERSION
- DID_HW_VERSION

---

# DTC Naming
# DTC命名规则

Format:
格式：

SYSTEM_FAILURE_TYPE

Examples:
示例：

- SEAT_OVERCURRENT
- MOTOR_SHORT_GND
- CAN_TIMEOUT

---

# Connector Naming
# 连接器命名规则

Format:
格式：

C + NUMBER

Examples:
示例：

- C1
- C2
- C3

---

# Pin Naming
# 引脚命名规则

Format:
格式：

MODULE_SIGNAL_DIRECTION

Examples:
示例：

- MCU_PWM_OUT
- HALL_SENSOR_IN
- LIN_TX_OUT

---

# Future Expansion
# 后续扩展

This document will continue to expand with engineering standards.
本文档后续会持续扩展工程规范。