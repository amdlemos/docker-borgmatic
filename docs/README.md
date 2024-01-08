# Commands
borgmatic restore --repository magis_tecfund-postgres --archive latest --database tecfund --verbosity 2




(Oficial Documentation)[https://torsion.org/borgmatic/docs/how-to/extract-a-backup/]

(Tutorial)[https://www.modem7.com/books/docker-backup/page/backup-docker-using-borgmatic]


borgmatic mount --archive latest --mount-point /RestoreMount --repository ssh://jd1784dx@jd1784dx.repo.borgbase.com/./repo

borgmatic extract --archive latest --destination /Restore

borg umount /RestoreMount && exit


