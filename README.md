# node
- Installs node Dependencies
- Installs nvm
- Installs node

The role only supports user installs. That is, it installs nvm in the
specified user's home.

## Role Variables

### Required Variables

| Variable | Description |
|----------|-------------|
|`node_user`| The user in whose home dir we install nvm |
|`node_version`| The version of node to install |

### Optional Variables

| Variable | Description |
|----------|-------------|
|`node_nvm_install_url`| The URL of the nvm install file |
|`node_nvm_version`| The nvm version to install |
|`node_nvm_path`| The path where we install nvm |

See `defaults/main.yml` for default values for these variables.

## License
BSD

