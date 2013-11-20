Really simple Python Sentry with minimal dependencies.

Usage:

```
import ravensimple
try:
    foobar
except Exception:
    ravensimple.report_exception(dsn='http[s]://[key]:[secret]@[host]/[projectid]')
```
