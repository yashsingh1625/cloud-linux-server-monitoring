# VMStat Notes

## Purpose

The `vmstat` command provides system performance statistics related to:
- memory
- CPU
- processes
- swap
- I/O

## Command

```bash
vmstat
```

## Continuous Monitoring

```bash
vmstat 2
```

Displays statistics every 2 seconds.

## Important Columns

| Column | Meaning |
|---|---|
| r | Running processes |
| free | Free memory |
| si | Swap in |
| so | Swap out |
| us | User CPU |
| sy | System CPU |
| id | Idle CPU |

## Troubleshooting Use Case

Used for:
- detecting memory pressure
- checking swap activity
- analyzing CPU bottlenecks

## Learning

Learned how to monitor system performance using vmstat.