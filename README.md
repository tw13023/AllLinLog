## Large Logs

The original logs are too large for GitHub.  
They have been compressed and split into smaller chunks.

### Reconstruct BGL.log
```bash
gunzip BGL.log.gz

### Reconstruct HDFS.log

cat logs/HDFS_part_*.gz | gunzip > HDFS.log
