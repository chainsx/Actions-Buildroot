# Actions-Buildroot

Build Buildroot using GitHub Actions

## Usage

- Click the [Use this template](https://github.com/chainsx/Actions-Buildroot/generate) button to create a new repository.
- Generate `.config` files using [Buildroot Offical Sources](https://github.com/buildroot/buildroot) source code. ( You can change it through environment variables in the workflow file. )
- Push `.config` file to the GitHub repository, and the build starts automatically.Progress can be viewed on the Actions page.
- When the build is complete, click the `Artifacts` button in the upper right corner of the Actions page to download the binaries.

## Thanks

This project based on [Actions-Openwrt](https://github.com/P3TERX/Actions-OpenWrt) , You can refer to this [tutorial](https://p3terx.com/archives/build-openwrt-with-github-actions.html).
