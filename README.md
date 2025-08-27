# AI@TT Project

## Overview
This project contains internal resources and configuration files for the AI@TT development environment.

## How to Use

### 1. Cursor Rules Configuration
The `.cursorrules` file contains important execution rules and guidelines for AI development workflows.

### 2. Internal File Access
To access internal files and resources:

1. **Read the `.cursorrules` file first** - This file contains execution rules and internal resource links
2. **Check `inhouse_files.txt`** - This file contains SharePoint locations and internal resource paths
3. **Follow the execution order** - Always read internal files before proceeding with other instructions

### 3. File Structure
```
ai@tt/
├── .cursorrules          # Execution rules and guidelines
├── inhouse_files.txt     # Internal resource links and SharePoint locations
└── README.md            # This file
```

### 4. Important Notes
- **Priority**: Always read `ai@tt/inhouse_files.txt` first
- **Execution Order**: Internal files → Rules → User Instructions
- **Resource Access**: Use the paths provided in `inhouse_files.txt` to locate internal resources

## Internal Resources
The `inhouse_files.txt` file contains:
- SharePoint locations
- Internal resource links
- Access guidelines
- Execution rules

## Usage Example
```bash
# 1. Read internal files first
cat ai@tt/inhouse_files.txt

# 2. Follow cursor rules
cat .cursorrules

# 3. Proceed with development tasks
```

## Support
For internal resource access, refer to the `inhouse_files.txt` file for the most up-to-date information.
