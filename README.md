## [EpicOnlineTransport](https://dev.epicgames.com/en-US/services) for [Mirror](https://github.com/vis2k/Mirror)
> Forked from https://github.com/FakeByte/EpicOnlineTransport


### Main Differences
- Support Mirror `86.13.4`
- `No suitable method found to override` error fixed
- With EOS SDK `v1.16.1`
- Lobby UI removed

### Development Environment
- Unity `2022.3.11f1`
- Mirror `86.13.4`
- EOS SDK `v1.16.1`

Add dynamic library to `Libs` folder and ask Rider to reference it.

### Installation
1. Navigate to [Epic Games Dev Portal](https://dev.epicgames.com/en-US/services) and download EOS SDK.
2. Be sure to add SDK source files to your project properly.
3. Open `Package Manager` and click `+` button, then select `Add package from git URL...` and paste the following URL:
```
https://github.com/wintbiit/EpicOnlineTransport.git
```
> For legal reasons, This repo does not provide EOS SDK source files. You need to download it from Epic Games Dev Portal.
