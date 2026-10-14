# ServiceNow PDI Backup

## Overview
This repository contains backups of my ServiceNow Personal Developer Instance (PDI), including application configurations, Update Set XML exports, and selected table data exports.

## Purpose
- Preserve ServiceNow development work.
- Maintain versioned backups using GitHub.
- Support recovery of backed-up configurations and selected data.
- Document restoration procedures and project dependencies.

## Repository Structure

```text
servicenow-pdi-backup/
├── README.md
├── applications/
├── update-sets/
├── data-exports/
├── documentation/
└── screenshots/
```

## Backup Contents

### Applications
Supported application files maintained through ServiceNow source control.

### Update Sets
XML exports of completed Update Sets containing captured configuration changes.

### Data Exports
Selected table records exported for backup and recovery.

### Documentation
Notes about applications, dependencies, configuration, and restoration procedures.

### Screenshots
Reference screenshots of important configurations and application features.

## Restoration Notes
1. Clone or download the required application repository.
2. Link or retrieve the source-controlled application using the supported ServiceNow workflow.
3. Import required Update Set XML files into the target instance.
4. Preview and resolve conflicts before committing Update Sets.
5. Import selected table data using the appropriate import method.
6. Verify application functionality and access permissions.

## Important Limitations
This repository is not a complete ServiceNow instance or database backup. Some instance settings, users, plugins, platform data, and records may not be included.

## Security
- Do not commit passwords, access tokens, credentials, or secrets.
- Do not upload confidential company information or personal data.
- Keep this repository private unless its contents have been reviewed and approved for public sharing.

## Backup Maintenance
Update this repository whenever important configuration or data changes are made, and periodically verify that the backed-up files can be restored.
