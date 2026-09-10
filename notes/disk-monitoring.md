# Disk Monitoring Notes

## Commands Used

### Check Disk Usage

```bash
df -h
```

### Check Directory Sizes

```bash
du -sh *
```

### Sort Large Files

```bash
du -h --max-depth=1 | sort -hr
```

## Purpose

Disk monitoring helps identify:
- low storage
- large directories
- disk usage problems

## Troubleshooting Use Case

Used to:
- locate large files
- clean unnecessary data
- manage storage efficiently

## Learning

Learned how to analyze disk space usage in Linux.