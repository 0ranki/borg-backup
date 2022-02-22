#### borg-backup

A wrapper script for Borg, with optional utilization of ZFS snapshots.

- Stops the service which is to be backed up, restarts afterwars
- Dumps the possible database to the data directory
- Optionally takes a ZFS snapshot
- Makes a borg archive of the defined data directory
- Writes the status and time of latest backup to a file, meant to be echoed on interactive logins
- Keeps a log file
- Sends email on failures
