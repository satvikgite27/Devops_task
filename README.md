# 📦 satvik_devops - Automated Backup Script

This project automates the backup of a local project folder, supports cloud uploads to Google Drive using `rclone`, implements a clean backup rotation strategy, and can optionally send webhook notifications on successful backup.

See the full documentation in the README provided above.

# 📦 satvik_devops - Automated Backup Script

This project automates the backup of a local project folder, supports cloud uploads to Google Drive using `rclone`, implements a clean backup rotation strategy, and can optionally send webhook notifications on successful backup.

---

## 🔧 Features

- Zips the entire project folder.
- Stores the backup locally with a timestamped name.
- Uploads backup to a Google Drive folder using `rclone`.
- Implements rotation policy (daily/weekly/monthly) to manage old backups.
- Sends a cURL POST request on successful backup.

---

## 📁 Folder Structure

```bash
/opt/local/shell-scripts/
├── backup_script.sh
├── backup_config.env
└── README.md
