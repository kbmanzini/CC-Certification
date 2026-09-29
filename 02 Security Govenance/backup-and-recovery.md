# Backup and Recovery

## What Are Backups?

A backup is a separate copy of data that can be used to restore information if the original data is lost, damaged, corrupted, or unavailable.

## Why Backups Matter

Backups can help an organization recover from:

* Accidental deletion
* Hardware failure
* Software problems
* Data corruption
* Cybersecurity incidents
* Natural disasters

## Types of Backups

### Full Backup

Copies all selected data.

**Advantage:** Restoration is generally straightforward.

**Disadvantage:** Requires more storage space and time.

### Incremental Backup

Copies changes made since the most recent backup.

**Advantage:** Usually uses less storage and takes less time.

**Disadvantage:** Restoring data may require multiple backup sets.

### Differential Backup

Copies changes made since the last full backup.

**Advantage:** Restoration generally requires the full backup and the latest differential backup.

**Disadvantage:** Differential backups can grow larger over time.

## Backup Security

Organizations should protect backups from unauthorized access, alteration, and destruction.

Common practices include:

* Encrypting backups
* Restricting access
* Keeping copies in separate locations
* Testing restoration procedures
* Maintaining offline or otherwise isolated copies

A backup that cannot be restored may not be useful during a recovery.

## Example

A company accidentally deletes an important database table. Its IT team uses a verified backup to restore the missing information.

## CC Exam Tips

* Full backup = all selected data.
* Incremental backup = changes since the last backup.
* Differential backup = changes since the last full backup.
* Always consider whether backups can actually be restored.

## What I Learned

Backups provide recoverable copies of data. Organizations should protect backups and test restoration procedures so that information can be recovered when needed.
