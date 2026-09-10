# Process Management Notes

## View Processes

```bash
ps aux
```

## Sort by CPU Usage

```bash
ps aux --sort=-%cpu
```

## Kill Process

```bash
kill -9 PID
```

## Kill by Process Name

```bash
pkill process_name
```

## Generate CPU Load

```bash
yes > /dev/null &
```

## Troubleshooting Use Case

Used for:
- stopping unwanted processes
- reducing CPU load
- managing running applications

## Learning

Learned how to manage Linux processes and troubleshoot high CPU usage.