# Flatpak build for Basemark GPU

The build will download the pre-defined Basemark GPU archive from
basemark.com and create a flatpak that can be used to run the benchmark from it.

## Usage

Install flatpak and flatpak-builder for your environment (see https://flatpak.org/ for more information)

```sh
flatpak-builder --install-deps-from=flathub <build folder> com.basemark.BasemarkGPU.yaml
```