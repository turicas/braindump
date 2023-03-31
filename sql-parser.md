# SQL parsers

- [pglast][pglast] (uses [`libpg_query`][libpg_query])
- [sqlglot][sqlglot] (pure Python)
- [sqlparse][sqlparse] (pure Python)
- [sqlparser][sqlparser] (NOT MAINTAINED ANYMORE)
- [psqlparse][psqlparse] (NOT MAINTAINED ANYMORE, uses [`libpg_query`][libpg_query])


## Format code

Using [sqlparse][sqlparse]:

Create the file `sqlfmt.py`:
```python
# pip install sqlparse
import sys

import sqlparse


sql = sys.stdin.read()
statements = sqlparse.split(sql)
for statement in statements:
    formatted = sqlparse.format(statement, reindent=True, keyword_case="upper")
    print(f"{formatted}\n")
```

Usage:

```shell
cat file.sql | python sqlfmt.py
```

[Documentation about formatting options][sqlparse-fmt-docs].


[libpg_query]: https://github.com/pganalyze/libpg_query
[pglast]: https://pypi.org/project/pglast/
[psqlparse]: https://github.com/alculquicondor/psqlparse
[sqlglot]: https://sqlglot.com/sqlglot.html
[sqlparse]: https://sqlparse.readthedocs.io/en/latest/
[sqlparse-fmt-docs]: https://sqlparse.readthedocs.io/en/latest/api/#formatting
[sqlparser]: https://github.com/timogasda/python-sqlparser
