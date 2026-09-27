# Invest_rmAnnouncements |
|-|
| [[Ubuntu] `ubuntu-latest` label will use Ubuntu 26.04 in November 2026](https://github.com/actions/runner-images/issues/14748) |
| [[Ubuntu] Ubuntu 26.04 and Ubuntu 26.04 Arm64 are now generally available](https://github.com/actions/runner-images/issues/14747) |
| [[Ubuntu] The Ubuntu 22 based runner images will begin deprecation on September 17th and will be fully unsupported by April 17th for GitHub Actions and Azure DevOps](https://github.com/actions/runner-images/issues/14254) |
| [[Ubuntu] Ubuntu 26.04 and Ubuntu 26.04 Arm is now available as a public preview](https://github.com/actions/runner-images/issues/14226) |
***
# Ubuntu 24.04
- OS Version: 24.04.5 LTS
- Kernel Version: 6.17.0-1022-azure
- Image Version: 20260920.314.1
- Systemd version: 255.4-1ubuntu8.17

## Installed Software

### Language and Runtime
- Bash 5.2.21(1)-release
- Clang: 16.0.6, 17.0.6, 18.1.3
- Clang-format: 16.0.6, 17.0.6, 18.1.3
- Clang-tidy: 16.0.6, 17.0.6, 18.1.3
- Dash 0.5.12-6ubuntu5
- GNU C++: 12.4.0, 13.3.0, 14.2.0
- GNU Fortran: 12.4.0, 13.3.0, 14.2.0
- Julia 1.13.0
- Kotlin 2.4.20
- Node.js 22.23.2
- Perl 5.38.2
- Python 3.12.3
- Ruby 3.2.3
- Swift 6.4

### Package Management
- cpan 1.64
- Helm 3.22.0
- Homebrew 7.0.4
- Miniconda 26.7.1
- Npm 10.9.8
- Pip 24.0
- Pip3 24.0
- Pipx 1.16.7
- RubyGems 3.4.20
- Vcpkg (build from commit 5f96cd15fd)
- Yarn 1.22.22

#### Environment variables
| Name                    | Value                  |
| ----------------------- | ---------------------- |
| CONDA                   | /usr/share/miniconda   |
| VCPKG_INSTALLATION_ROOT | /usr/local/share/vcpkg |

#### Homebrew note
```
Location: /home/linuxbrew
Note: Homebrew is pre-installed on image but not added to PATH.
run the eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv)" command
to accomplish this.
```

### Project Management
- Ant 1.10.14
- Gradle 9.7.1
- Lerna 10.0.1
- Maven 3.9.16

### Tools
- Ansible 2.21.4
- AzCopy 10.32.7 - available by `azcopy` and `azcopy10` aliases
- Bazel 9.2.0
- Bazelisk 1.28.1
- Bicep 0.47.16
- Buildah 1.33.7
- CMake 3.31.6
- CodeQL Action Bundle 2.27.0
- Docker Amazon ECR Credential Helper 0.12.0
- Docker Compose 2.38.2
- Docker-Buildx 0.37.1
- Docker Client 28.0.4
- Docker Server 28.0.4
- Fastlane 2.240.1
- Git 2.55.0
- Git LFS 3.8.0
- Git-ftp 1.6.0
- Haveged 1.9.14
- jq 1.7
- Kind 0.33.0
- Kubectl 1.37.0
- Kustomize 5.8.1
- MediaInfo 24.01
- Mercurial 6.7.2
- Minikube 1.39.0
- n 10.2.0
- Newman 6.2.2
- nvm 0.40.7
- OpenSSL 3.0.13-0ubuntu3.15
- Packer 1.16.1
- Parcel 2.16.4
- Podman 4.9.3
