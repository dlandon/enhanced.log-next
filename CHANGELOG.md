# Changelog

The **Next** series continues development of the plugin by the original author and focuses on ongoing maintenance, reliability improvements, and compatibility with current Unraid releases.

Development of the plugin will continue with ongoing fixes, enhancements, and maintenance improvements.

## 2026.11.17

### Fixes
- Validate configured highlight colors to prevent CSS injection.
- Improve regular expression handling with processing limits and safer pattern delimiters.
- Prioritize error highlighting over less severe syslog messages.
- Validate the rsyslog configuration before restarting the service and roll back on failure.
- Improve configuration backup validation and rollback error reporting.
- Improve JavaScript encoding of syslog download filenames.

## 2026.11.03

### Fixes
- Validate the plugin bundle before installation.
- Report bundle extraction failures.
- Preserve the current plugin bundle when removing older bundles.
- Apply syslog filtering after configuration files are created.

## 2026.07.26

### New Feature
- Add 'Today Only' to filter log activity to only today's activity.

## 2026.07.24

### New Feature
- Added a powerful log filter.
  - Filter using one or more comma-separated search terms.
  - Prefix a term with `!` to exclude matching entries.
  - Supports `*` and `?` wildcards.
  - Filter settings are remembered between sessions.

### Notes
- Detailed technical changes are documented in the GitHub release notes
