#### borg-backup

A wrapper script for Borg, with optional utilization of ZFS snapshots.
Stops the service which is to be backed up, dumps the database and pushes
to a borg repository defined in a separate config file.
