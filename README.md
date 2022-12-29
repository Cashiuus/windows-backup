Backup Windows
==============

Backup script I wrote to accomplish the following:
- Copy individual important files to a cloud destination that is on my local system (Dropbox, Google Drive, etc.)
- Copy a full list of files/dirs to a zip file archive saved to same cloud destination
- Also, copy some files from a connected USB drive as part of this backup (say, if you keep PW database on it)
- Ability to prune out old zip archives with preferences in config on if we delete and how many to keep



Tip: If you set this up as a Scheduled Task, you can have it run every night and always have your most important files sync'ed to the cloud


## Usage

If you don't know what you are doing, just run it. Upon first run it'll create a `settings.py` starter file where you can choose your preferences and build your list of files to backup in the respective lists.


Quick Start
```commandline
git clone https://github.com/cashiuus/windows-backup.git
cd windows-backup
python backup_files.py
```

