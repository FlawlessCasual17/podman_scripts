# `podman` scripts
My shell scripts for configuring a new podman machine instance

> [!IMPORTANT]
> Make sure you change the password or set a 
> password for the user before executing the first script!

```bash
sudo passwd $USER
```

## Do the following in order


1. Make sure to do this in a bash shell

```bash
curl -sL 'https://github.com/FlawlessCasual17/podman_scripts/raw/main/podman_configuration_bash' | bash
```

2. Make sure to do this in a fish shell

```fish
curl -sL 'https://github.com/FlawlessCasual17/podman_scripts/raw/main/podman_configuration_fish' | fish
```
