sbgrab is a bash script designed to monitor a directory on a remote server and use rsync to transfer any new files present to the local machine. Generates a flat HTML report.

Designed to be repeated regularly via a cron job.

Potential use cases:
  * One way syncing
  * Incremental backups
  * Maintaining multiple off-site backups
  * Transferring data home from Bit Torrent seedbox