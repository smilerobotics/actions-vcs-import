# vcs-import

## Description

An action to run [vcs](https://github.com/dirk-thomas/vcstool) [import](https://github.com/dirk-thomas/vcstool#import-set-of-repositories) command.

## Required input

1. vcs_setting_file: Path of the file for vcs import.
1. target_dir: Path of the target directory.

## Example

```yaml
- uses: smilerobotics/actions-vcs-import@v1
  with:
    vcs_setting_file: ./vcs.repos
    target_dir: ./src
```
