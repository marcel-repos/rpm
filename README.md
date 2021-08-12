# Marcel's Red Hat Enterprise Linux Repository

## Setup

You have to add the repository to the package sources:

```bash
cat << EOF > /etc/yum.repos.d/m4rc3l.repo
[m4rc3l.de]
name=m4rc3l.de
baseurl=https://rpm.m4rc3l.de/all/$basearch
enabled=1
gpgcheck=1
gpgkey=https://m4rc3l.de/static/rpm-repo.pem
EOF
```

## Packages

```bash
sudo dnf install <package>
```

| Package                 | Description                                               | Reposetory                                                                                  |
| ----------------------- | --------------------------------------------------------- | ------------------------------------------------------------------------------------------- |
| `genpw`                 | Generate strong passwords directly from the command line. | [MarcelCoding/debian-genpw](https://github.com/MarcelCoding/debian-genpw)                   |
| `docker-network-viewer` | Liste docker networks and according subnet.               | [MarcelCoding/docker-network-viewer](https://github.com/MarcelCoding/docker-network-viewer) |

## License

[LICENSE](LICENSE)
