# Loadclear

Is this charger allowed back on?

A charger with no repair job is refused. Turning it on while it is locked is refused. A charger that is too hot, too empty, over its export limit, or past its cycle budget is refused. Chargers that pass are grouped. That group is the power the next checks use.

It takes the repair-job id from Bayline. It does not import Bayline. Cabinetfield measures the cabinet before that power is accepted.

It does not check the power numbers, and it does not sign the record.

Copyright 2026 DIGITAL CURRENSY INC / Module Kinetic Ltd. Apache-2.0. See [LICENSE](LICENSE).
Parent: [module-kinetic-ltd](https://github.com/DigitalCurrensy/module-kinetic-ltd)

## Tests

```bash
python -m pip install pytest
PYTHONPATH=. python -m pytest
```
