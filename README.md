# sqlite-migrate

Numbered migration files applied in order, with a version table.

## Why

The existing libraries were either abandoned or pulled in a large dependency tree.

## Install

```bash
pip install sqlite-migrate
```

## Usage

```python
from sqlite_migrate import sqliteMigrate

result = sqliteMigrate("example")
print(result)
```

## Notes

- No runtime dependencies outside the standard library.
- Tested on Python 3.9 and newer.

## License

MIT
