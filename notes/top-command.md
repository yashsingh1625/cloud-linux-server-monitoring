# Top Command Notes

## Purpose
The `top` command is used for real-time monitoring of Linux system resources and running processes.

## Command

```bash
top
```

## Information Displayed

- CPU usage
- Memory usage
- Load average
- Running processes
- Process IDs (PID)

## Important Fields

| Field | Meaning |
|---|---|
| PID | Process ID |
| USER | Process owner |
| %CPU | CPU utilization |
| %MEM | Memory usage |
| TIME+ | CPU time consumed |

## Useful Shortcuts

| Key | Function |
|---|---|
| P | Sort by CPU |
| M | Sort by Memory |
| k | Kill process |
| r | Change priority |
| q | Quit |

## Troubleshooting Use Case

Used to identify:
- high CPU processes
- memory consuming applications
- stuck or hung processes

## Learning

Learned how to monitor Linux processes and analyze server load using `top`.