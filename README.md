# Marcel's Red Hat Enterprise Linux Repository

## Setup

You have to add the repository to the package sources:

```bash
sudo dnf -y install dnf-plugins-core

sudo dnf config-manager \
  --add-repo \
  https://rpm.m4rc3l.de/config/all.repo
```

## Packages

```bash
sudo dnf install <package>
```

When you install the first package, you have to verify the GPG key.
<br>
The fingerprint is `C907 8A5C CE5C 9256 E175 C0BD 94C7 2B06 F259 2DD0`.

| Package                 | Description                                               | Reposetory                                                                                  |
| ----------------------- | --------------------------------------------------------- | ------------------------------------------------------------------------------------------- |
| `genpw`                 | Generate strong passwords directly from the command line. | [MarcelCoding/debian-genpw](https://github.com/MarcelCoding/debian-genpw)                   |
| `docker-network-viewer` | Liste docker networks and according subnet.               | [MarcelCoding/docker-network-viewer](https://github.com/MarcelCoding/docker-network-viewer) |

## License

[LICENSE](LICENSE)
