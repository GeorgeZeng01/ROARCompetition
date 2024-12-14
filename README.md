ROAR_Competition
FORKED from BHS Racing SUMMER 2024 AS BASE

Requires progress module and ROAR_PY


Unofficial time over 10 runs:
325.15s

325.10s

325.25s

325.65s

325.45s

325.45s

325.45s

325.45s

325.55s

325.45s

Fastest: 325.10s
Average: 325.395s
Slowest: 325.65s

Reliability:
10 runs with no crashes

CHANGES FROM PREVIOUS YEAR SOLUTION:

NEW PURSUIT ALGORITHM:
Weighs angle to the next 20 waypoints based inversely on the distance away
Constant to counteract the weight slightly

TUNED ThrottleController.py:
Due to the new LateralController.py the throttle mu values were tuned again
