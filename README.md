# Regolith for Ubuntu Bionic

## Install

1. From a terminal, add the Regolith key to your apt keychain:

```bash
$ wget -qO - https://ubuntu-bionic.regolith-desktop.org/archive.key | sudo apt-key add -
```

2. Add this repository to your apt sources:

```bash
$ echo deb [arch=amd64] https://ubuntu-bionic.regolith-desktop.org bionic main | sudo tee /etc/apt/sources.list.d/regolith.list
```

3. Update your apt state:

```bash
$ sudo apt update
```

4. Install Regolith desktop

```bash
$ sudo apt install regolith-desktop-small
```

