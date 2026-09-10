# Memory Monitoring Notes

## Commands Used

### Check Memory Usage

```bash
free -h
```

### Monitor Memory Continuously

```bash
watch free -h
```

## Understanding Output

| Field | Meaning |
|---|---|
| total | Total RAM |
| used | Used memory |
| free | Free memory |
| buff/cache | Cached memory |
| available | Available memory |

## Swap Memory

Swap is disk space used as virtual memory when RAM becomes full.

## Troubleshooting Use Case

Used for:
- identifying low memory situations
- checking swap usage
- analyzing RAM utilization

## Learning

Learned how Linux manages RAM and swap memory.