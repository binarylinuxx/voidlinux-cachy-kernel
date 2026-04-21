# VoidLinux Cachy Kernel

*Provides CachyOS kernel support for Void Linux.*

## Build

### Requirements
- Docker
- xbps-src (optional - use directly if running Void Linux; Docker is better otherwise)

### Building with Docker
```bash
docker build -f Dockerfile.kernelbuild -t npkg-kernelbuild . && docker run --rm --privileged -v ~/kernel-output:/output npkg-kernelbuild
```

## Notice

This project is in early development and currently targets glibc x86_64 systems only. Install at your own risk. Issues can be reported to the project repository.

# Install
- Build Yourself.
- Download prebuilt binary package from [Release Tags](https://github.com/binarylinuxx/voidlinux-cachy-kernel/tags) maybe delayed from the newest commit sha256sum included.
