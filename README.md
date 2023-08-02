# Install Sysmon
`sysmon -accepteula -i [config_file_path]`

# Dump current config file
`sysmon -c`

# Update file config
`sysmon -c [config_file_path]`
# Restore default config
`sysmon -c --`
# Print configuration schema
`sysmon -s`

# View In Event Viewer
Event Viewer -> Application and Services -> Microsoft -> Windows -> Sysmon -> Operational
