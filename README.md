# modals-cafe3y-kit

Validate JSON files and print a normalized form.

Small, dependency-free Python utility package generated for day-to-day file chores.
Standard library only — no third-party imports.

## Install

```bash
pip install -e .
```

## Usage

```bash
python -m modals_cafe3y_kit.cli --help
```

```python
from modals_cafe3y_kit.core import ModalsCafe3yTool

tool = ModalsCafe3yTool()
print(tool)
```

## Layout

```
modals_cafe3y_kit/
  __init__.py
  core.py
  cli.py
tests/
  test_core.py
```

## License

MIT © 2026 modals-cafe3y
