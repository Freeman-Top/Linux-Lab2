# Linux Lab: Text Processing Practice

Hands-on practice with grep, awk, sed, find, sort/uniq and pipes
on sample web-server and application logs.

## Files
- `access.log`, `app.log`: sample logs
- `report.txt`: generated security report (failed logins, 404s)
- `project/`: folder structure created with brace expansion

## Key commands practiced
| Task | Command |
|---|---|
| Lines 3-6 | `sed -n '3,6p' app.log` |
| Count errors | `grep -c ERROR app.log` |
| Top paths | `awk '{print $4}' access.log \| sort \| uniq -c \| sort -nr \| head -n 3` |
| Bytes from one IP | `awk '$1=="192.168.1.99" {sum+=$6} END{print sum}' access.log` |
| Safe in-place edit | `sed -i.bak 's/ERROR/CRITICAL/g' app.log` |
| Find recent logs | `find ~ -name "*.log" -mtime -1 2>/dev/null` |
