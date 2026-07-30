# 第三方资产授权核查清单 / Third-Party Asset Review Checklist

本清单用于核查 GeehySemi 组织中以压缩包、安装程序、预编译固件、驱动或历史资料形式保存的资产。核查完成前，不应假设这些文件可以自由修改或再分发。

This checklist tracks archives, installers, prebuilt firmware, drivers, and historical materials stored in the GeehySemi organization. Do not assume that these assets may be modified or redistributed until the review is complete.

## 核查原则 / Review principles

- 确认原始权利人、来源链接和获取日期。
- 检查仓库根目录及压缩包内部的 LICENSE、EULA、NOTICE 或版权说明。
- 确认是否允许公开托管、镜像、修改和再分发。
- 记录文件版本、发布日期和 SHA-256。
- 区分极海自有内容与第三方内容。
- 指定内部负责人和最终处理决定。
- 未发现根目录 LICENSE 不代表压缩包内部没有许可条款，也不能据此添加任意开源许可证。

- Confirm the original owner, source URL, and acquisition date.
- Inspect both the repository root and archive contents for licenses, EULAs, notices, and copyright statements.
- Confirm whether public hosting, mirroring, modification, and redistribution are permitted.
- Record versions, release dates, and SHA-256 checksums.
- Separate Geehy-owned materials from third-party assets.
- Assign an internal owner and record the final disposition.
- The absence of a root-level LICENSE does not prove that an archive contains no license, and does not justify adding an arbitrary open-source license.

## 待核查仓库 / Repositories pending review

| 仓库 | 主要资产 | 核查重点 | 建议动作 | 状态 |
| --- | --- | --- | --- | --- |
| `F103_FPU` | `ST_FPU.zip` | 原始项目来源、目标芯片、许可证、APM32 移植状态 | 核查完成前不作为正式 APM32 示例推广 | 待核查 |
| `JLink_Windows_V770a_x86_64` | J-Link v7.70a RAR | SEGGER EULA、公开镜像与再分发权限、文件完整性 | 优先完成授权确认并记录 SHA-256 | 待核查 |
| `xpack` | xPack Windows Build Tools ZIP | 上游版本、许可证、镜像权限 | 补上游链接、许可文件和 SHA-256 | 待核查 |
| `GW3323` | SDK、RV32 工具链、CP210x 驱动、下载工具 | 分离极海与第三方资产，逐项确认许可证 | 建立版本索引和逐文件许可记录 | 待核查 |
| `mbed-os-DAPLINK-Hardware` | BIN/HEX 预编译固件 | 源码仓库、构建提交、固件许可证、硬件对应关系 | 补源码来源、版本和 SHA-256 | 待核查 |
| `IAR-Package` | 极海 IAR Add-On EXE | 软件所有权、公开分发权限、IAR 版本兼容性 | 通过 GitHub Releases 管理版本和校验值 | 待核查 |
| `New-product-F035-L072-S103-BMP1601` | 新品介绍 PPTX | 内部版权、资料时效、是否已被官网内容替代 | 资料迁移确认后再决定是否归档 | 待核查 |
| `APM32F4XX` | 历史手册、草稿数据手册、SDRAM ZIP | 文档是否过期、草稿是否应继续公开、SDRAM 包来源 | 与官网正式资料核对后再整理 | 待核查 |

## 单项记录模板 / Per-asset record

- 仓库 / Repository:
- 文件 / Asset:
- 原始权利人 / Original owner:
- 来源链接 / Source URL:
- 获取日期 / Acquisition date:
- 版本与发布日期 / Version and release date:
- SHA-256:
- 许可证或 EULA / License or EULA:
- 允许公开托管 / Public hosting permitted:
- 允许再分发 / Redistribution permitted:
- 极海内部负责人 / Internal owner:
- 最终决定 / Final disposition:
- 备注 / Notes:
