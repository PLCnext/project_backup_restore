# project_backup_restore

## Project Description

This project provides two bash scripts to **backup** and **restore** a PLCnext project, including configurations such as **WBM user management** and **firewall settings**.  
The idea is inspired by the PLCnext USA SDCardCopy project.

The scripts were tested with:
- **AXC F 2152** (Firmware 2024)
- PLCnext Engineer project
- WBM user management and firewall configurations

### Scripts

- `backup.sh`:  
  Copies data from a PLCnext SD card to your computer **without deleting or affecting license files**.

- `restore.sh`:  
  Deletes all contents on the SD card **except the license folder**, and copies selected project data from your computer to the SD card.

## Requirements

- Developed and tested on **Lubuntu**
- Recommended: **Ubuntu-based Linux distributions**

## Usage

1. Place the scripts in their own **empty folder**
2. Run the scripts using:
   ```bash
   sudo bash ./backup.sh
   sudo bash ./restore.sh
   ```

## Contributing

You can participate in this project by submitting bugs and feature requests.
Help us by checking the guide on how bugs are reported. Please let us know if anything is not working as expected.

## Feedback

Ask a question in our Forum.
Request a new feature on GitHub.
File a bug in GitHub Issues.

## License

Copyright (c) Phoenix Contact GmbH & Co. KG.
Licensed under the MIT License.
