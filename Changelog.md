# Changelog
All notable changes to this project will be documented in this file.  
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).   
This project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

# [0.4.3] - 2022-02-22
## Added
- Added the process to check the environment variable GOBIN
# [0.4.2] - 2022-02-22
## Changed
- Use mattn/go-colorable for Windows.
- Changed to be able to get the HOME directory path in the Windows environment.
- Changed to output the command name when the package path could not be obtained.
# [0.4.0] - 2022-02-22
## Added
- export subcommand. 
  - When updating to the latest version, gup.conf is no longer generated. Generate gup.conf with export subcommand.

# [0.3.0] - 2022-02-22
## Added
- --dry-run option.