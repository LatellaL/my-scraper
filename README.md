SPCA Scanner
An application that sends email notifications when the SPCA website has new pets available for adoption.

This watcher sends you email notifications for new cats at intervals of 5-10 minutes so that you can have a match soon (and then uninstall the app).

Usage
Create .env based on .env.example.
SMTP config must be correct for emails to work.

You can get a free basic SMTP account from SMTP service providers like SendGrid.

lando start (Lando must be installed).
lando spcas; Execute a scan.
Suggested usage: lando spcas -v --category=cats --email --interval 10

More options: lando spcas help scan.
