<p align="center">
  <strong>AsterCommunity</strong>
  <br />
  连接星宇，加速一切。
  <br />
  <a href="https://www.astercosm.com/">astercosm.com</a>
  <br />
  <a href="README.md">English</a>
</p>

## AsterCommunity 为什么存在

自托管基础设施存在一个断层。一端是什么都想做的私有云全家桶——笨重、不透明、难以修改；另一端是各司其职的单点工具——单个都好使，但拼不成一套协调的系统。

AsterCommunity 构建的是中间层：一组专注的、可自托管的服务，共享同一个 Rust 运行时底座（[AsterForge](https://github.com/AsterCommunity/AsterForge)）和同一套运维约定。每个服务只做一件事，代码为人可读、可改，部署不需要企业级技术栈。因为它们共享同一个内核——配置、存储、可观测性、后台任务、审计日志——运维三个 Aster 服务的体验像运维一个，而不是三个。

这里的一切都是 MIT 许可。一切都是为小团队能部署、能审计、能魔改而构建的。

## 项目一览

### 活跃开发

| 项目 | 简介 |
|---|---|
| [AsterDrive](https://github.com/AsterCommunity/AsterDrive) | 面向小团队的自托管文件基础设施：可靠上传、存储策略、S3 / 远程节点后端、WebDAV / WOPI、运维工具链。旗舰服务。 |
| [AsterForge](https://github.com/AsterCommunity/AsterForge) | 所有 Aster 服务共享的 Rust 运行时底座与基础设施内核——配置、存储、WebDAV/XML 设施、可观测性、定时任务。 |
| [AsterYggdrasil](https://github.com/AsterCommunity/AsterYggdrasil) | 自托管 Minecraft 皮肤站与 Yggdrasil / authlib-injector 认证服务器。 |

### 早期阶段

| 项目 | 简介 |
|---|---|
| [AsterPulse](https://github.com/AsterCommunity/AsterPulse) | 分布式可用性监控系统。 |

### 规划中

| 项目 | 简介 |
|---|---|
| [AsterMail](https://github.com/AsterCommunity/AsterMail) | 主权邮件系统。 |
| [AsterDriveClients](https://github.com/AsterCommunity/AsterDriveClients) | AsterDrive 桌面 / 移动原生客户端。 |

### 支撑项目

| 项目 | 简介 |
|---|---|
| [AsterDriveMigration](https://github.com/AsterCommunity/AsterDriveMigration) | AsterDrive 迁移工具。 |
| [www.astercosm.com](https://github.com/AsterCommunity/www.astercosm.com) | AsterCosmos 主站。 |

## 当前状态

AsterDrive 处于活跃开发中（`v0.4.x` 线）。AsterForge 与 AsterYggdrasil 持续维护中；AsterForge 的云文件核心（`aster_forge_cloud_files`）地基已经就绪，为 AsterDrive 各端与后续服务提供统一的文件抽象。AsterPulse 处于早期开发；AsterMail 与 AsterDrive 原生客户端在路线图上。

在 `0.x` 系列中，次版本号可能携带兼容性与范围变更。
