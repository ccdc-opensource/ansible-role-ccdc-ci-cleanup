# Ansible Role: Build machine cleanup

Remove unnecessary default packages from build machines

Applying this role will remove various unused software packages from the build machines.

### Windows

- Windows Defender
- XPS Viewer

### Linux

- Currently nothing

### macOS

- Currently nothing

## Requirements

None.

## Role Variables

None.

## Dependencies

None.

## Example Playbook

    - hosts: all
      roles:
        - ccdc.ci_cleanup

## License

MIT / BSD

## Author Information

This role was created in 2020 by Claudio Bantaloukas, based on existing roles at CCDC, by Jeff Geerling and google searches