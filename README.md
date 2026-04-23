# VoidLinux Cachy Kernel

*Provides CachyOS kernel support for Void Linux.*

## Build

### Requirements
- Docker
- xbps-src (optional - use directly if running Void Linux; Docker is better otherwise)

### Building with Docker
```bash
docker build -f Dockerfile.kernelbuild -t npkg-kernelbuild . && docker run --rm --privileged -v ~/kernel-output:/output npkg-kernelbuild | tee /tmp/build.log # Build logs will be written to /tmp/build.log
```

## Notice

This project is in early development and currently targets glibc x86_64 systems only. Install at your own risk. Issues can be reported to the project repository.

# Install
*options:*
- Build Yourself. # May take a lot of time via docker for me persanly it was 4h53m43s,you can use xbps-src but since im too lazy explain all xbps-src workflow you'll have to figure out on your own.
- Download prebuilt binary package from [Release Tags](https://github.com/binarylinuxx/voidlinux-cachy-kernel/tags) maybe delayed from the newest commit sha256sum included. 

# Questions May can appear
- will the package will be officially in void repos? - no. im already had tried suggest the package and got rejected and probably it wont happen since void maintainers maintain only what they're wants selectively and what fit their standards not cachy-kernel case.
