

> 兴趣是最好的老师，**HelloGitHub** 让你对编程感兴趣！


![](https://img2024.cnblogs.com/blog/759200/202409/759200-20240927004130239-1590395992.png)


## 简介


**HelloGitHub** 分享 GitHub 上有趣、入门级的开源项目。



> [github.com/521xueweihan/HelloGitHub](https://github.com)


这里有实战项目、入门教程、黑科技、开源书籍、大厂开源项目等，涵盖多种编程语言 Python、Java、Go、C/C\+\+、Swift...让你在短时间内感受到开源的魅力，对编程产生兴趣！




---



> 以下为本期内容｜每个月 **28** 号更新


### C 项目


1、[Ditto](https://github.com)：Windows 的剪贴板历史管理工具。这是一款免费的 Windows 剪贴板增强工具。它能够将复制到剪贴板的内容存储到数据库中（SQLite），方便日后检索，支持设定保存日期、条目总数、合并粘贴、分组、快速搜索和热键粘贴等功能。此外，还可以通过网络共享剪贴板内容，并对传输数据进行加密保护。来自 [@Veeja Liu](https://github.com) 的分享


![](https://img2024.cnblogs.com/blog/759200/202409/759200-20240927004210271-1089702704.png)


2、[FlappyBird](https://github.com)：仅 100KB 的愤怒小鸟游戏。该项目是用 C 语言编写的愤怒小鸟游戏（Flappy Bird），它运行流畅、安装包不到 100KB，适用于 Android 5\.1 及以上系统。


![](https://img2024.cnblogs.com/blog/759200/202409/759200-20240927004210497-232552667.png)


3、[system\-bus\-radio](https://github.com)：用电脑轻松发射无线电信号。该项目通过控制计算机系统总线在特定频率上切换电流，实现了无需额外硬件设备，仅用电脑发送 AM 无线电信号的功能。


![](https://img2024.cnblogs.com/blog/759200/202409/759200-20240927004210443-1303716555.png)


### C\# 项目


4、[eShop](https://github.com)：开源的 .NET 电商平台。该项目是由 .NET 官方开源的电子商务平台，基于 .NET Aspire 构建。作为示例项目，它采用最新的 .NET 8 和微服务架构，并实现了核心的电商功能。


![](https://img2024.cnblogs.com/blog/759200/202409/759200-20240927004210459-1491057292.png)


5、[Loaf](https://github.com)：假装 Windows 更新的工具。这是一款专为摸鱼设计的小工具。点击“摸鱼”按钮后，它会显示 Windows Update 界面，营造电脑正在升级的假象，让你能够名正言顺地摸鱼。来自 [@刘睿华](https://github.com) 的分享


![](https://img2024.cnblogs.com/blog/759200/202409/759200-20240927004210447-618836119.png)


### C\+\+ 项目


6、[alien](https://github.com)：强大的人工生命模拟工具。该项目是基于 CUDA 的 2D 粒子引擎构建的人工生命模拟工具。它提供了图形化用户界面和粒子编辑器，能够轻松模拟软体、流体、数字生物体、遗传和进化等过程。生物行为由神经网络控制，支持实时交互和模拟百万量级的粒子。


![](https://img2024.cnblogs.com/blog/759200/202409/759200-20240927004210560-1238538693.jpg)


7、[vcmi](https://github.com)：《英雄无敌 III》的开源重制版。该项目是经典策略游戏《魔法门之英雄无敌 III》的开源重制版，它采用 C\+\+ 重新编写了游戏引擎，支持更高的分辨率、多人游戏和自定义地图等功能，可以在 Windows、macOS、Android 和 iOS 等系统上运行，但需要自行准备启动游戏所需的数据文件。


![](https://img2024.cnblogs.com/blog/759200/202409/759200-20240927004210566-1231794740.jpg)


### Go 项目


8、[clickhouse\-sql\-parser](https://github.com)：纯 Go 实现的 ClickHouse SQL 解析器。这是一款用 Go 实现的 ClickHouse SQL 解析器，兼容大多数 DML/DDL/Query 语句。它的代码简洁易懂，可作为 Go 开发者学习 SQL 解析器的入门项目。



```
package main

import (
    clickhouse "github.com/AfterShip/clickhouse-sql-parser/parser"
)

query := "SELECT * FROM clickhouse"
parser := clickhouse.NewParser(query)
// Parse query into AST
statements, err := parser.ParseStmts()
if err != nil {
    return nil, err
}

```

9、[go2rtc](https://github.com)：支持各种流媒体协议的处理工具。这是一个用 Go 语言编写的库，支持 RTSP、WebRTC、HomeKit、FFmpeg、RTMP 等视频流协议的处理。在 FFMPEG 的加持下，它几乎能将任何媒体格式作为输入源，转换为适用于主流流媒体服务和浏览器的格式。来自 [@猎隼丶止戈reNo7](https://github.com) 的分享


![](https://img2024.cnblogs.com/blog/759200/202409/759200-20240927004210461-206425269.png)


10、[maroto](https://github.com)：用 Go 生成样式美观的 PDF 文件。这一个 Go 语言开发的用于创建 PDF 文件的库，其灵感来源于 Bootstrap 框架。它允许你像使用 Bootstrap 创建网站一样，轻松编写和生成不同样式的 PDF 文件。来自 [@DeShuiYu](https://github.com) 的分享


![](https://img2024.cnblogs.com/blog/759200/202409/759200-20240927004210471-1805650225.png)


11、[nginx\-ui](https://github.com)：全新的 Nginx 在线管理平台。该项目是用 Go\+Vue.js 构建的 Nginx 在线管理平台，它开箱即用、功能丰富，支持流量统计、在线查看 Nginx 日志、编辑 Nginx 配置文件、自动检查和重载配置文件等功能。来自 [@kekylin](https://github.com) 的分享


![](https://img2024.cnblogs.com/blog/759200/202409/759200-20240927004210422-1085090949.png)


12、[watchtower](https://github.com)：自动更新 Docker 容器的工具。该项目能够自动监测并更新正在运行的 Docker 容器。它会定期检查并拉取 Docker Hub 或私有镜像仓库中的最新镜像版本，并自动重启容器。适用于开发、测试和个人使用场景，但不建议在生产环境中使用。



```
docker run -d \
--name watchtower \
-v /var/run/docker.sock:/var/run/docker.sock \
containrrr/watchtower

```

### Java 项目


13、[graphhopper](https://github.com)：高效灵活的开源路线规划引擎。该项目是用 Java 开发的高性能路径规划引擎，能够快速计算两点或多点之间的距离。它支持 Dijkstra、A\* 和收缩层级（CH）等算法，可以作为 Java 库或 Web 服务使用。基于 OpenStreetMap 地图数据，可实现汽车、自行车、步行等多种交通方式的路线规划和导航服务。


![](https://img2024.cnblogs.com/blog/759200/202409/759200-20240927004210472-1296583391.png)


14、[J2ME\-Loader](https://github.com)：在 Android 上玩 J2ME 游戏。这是一款 Android 的 J2ME 模拟器，支持大多数 2D 和 3D 游戏。它内置虚拟键盘，适用于 Android 4\.0\+ 系统。


![](https://img2024.cnblogs.com/blog/759200/202409/759200-20240927004210565-832077369.png)


15、[spring\-ai](https://github.com)：帮助开发 AI 应用的 Spring 框架。这是由 Spring 官方开源的用于简化包含 AI 功能的应用开发的 Java 框架，它可以轻松接入 OpenAI、Microsoft、Amazon、Google 和 Huggingface 等主流模型供应商，以及聊天、文本生成图像的模型类型，支持提示工程、AI 模型转 POJO 对象、矢量数据库、RAG（检索增强生成）等有助于开发 AI 应用的功能。


![](https://img2024.cnblogs.com/blog/759200/202409/759200-20240927004210445-1754355677.png)


### JavaScript 项目


16、[create\-t3\-app](https://github.com)：创建全栈、类型安全的 Next.js 项目的工具。这是一个用于创建全栈且类型安全的 Next.js 项目的脚手架工具。它开箱即用，仅需一条命令就能快速创建一个全新的 Next.js 项目。


![](https://img2024.cnblogs.com/blog/759200/202409/759200-20240927004210343-298653321.png)


17、[markmap](https://github.com)：将 Markdown 可视化为思维导图。这是一个支持使用 Markdown 语法绘制思维导图的工具。它开箱即用并提供多种使用方式，包括在线、命令行以及 VSCode、Vim 和 Emacs 插件。


![](https://img2024.cnblogs.com/blog/759200/202409/759200-20240927004210462-1911572894.png)


18、[pglite](https://github.com)：在浏览器中运行 Postgres 数据库。该项目将 PostgreSQL 数据库编译成 WebAssembly (WASM)，并打包成一个 TypeScript/JavaScript 客户端库。它压缩后体积不到 3MB，可以在浏览器、Node.js、Bun 和 Deno 环境中运行，无需安装任何额外的依赖。提供灵活的存储选项，支持内存存储、本地持久化或 IndexedDB。



```
import { PGlite } from "@electric-sql/pglite";

const db = new PGlite();
await db.query("select 'Hello world' as message;");
// -> { rows: [ { message: "Hello world" } ] }

```

![](https://img2024.cnblogs.com/blog/759200/202409/759200-20240927004210442-1722901599.png)


19、[staticrypt](https://github.com)：为静态网站提供密码保护功能。该项目无需服务器端支持，即可实现对 HTML 页面进行密码认证访问的功能。它使用 AES\-256 加密算法和设定的密码，对需要保护的页面进行加密。生成的页面包含密码输入框，只有在输入正确的密码后，才会显示原始的 HTML 页面内容。


![](https://img2024.cnblogs.com/blog/759200/202409/759200-20240927004210422-1895560177.gif)


20、[ui](https://github.com)：流行、设计精美的 UI 组件集合。这是一款由 Vercel 开源、基于 React 开发的 UI 组件集合，包括仪表板、卡片、模型对话、表单、登录等组件，拿来即用。通过 CLI 引入组件后，将得到该组件的源码，可随意修改和定制。


![](https://img2024.cnblogs.com/blog/759200/202409/759200-20240927004210567-667820856.png)


### Kotlin 项目


21、[game2048](https://github.com):[FlowerCloud机场](https://hushicha.org)：开源的 2048 游戏。该项目是基于 Kotlin 和 KorGe 游戏引擎开发的 2048 游戏。它免费、开源且没广告，支持存档、无限撤回、AI 模式和回放等功能。作者仅提供了 Android 安装包，其他平台需要自行编译。


![](https://img2024.cnblogs.com/blog/759200/202409/759200-20240927004210562-566962493.png)


22、[ImageToolbox](https://github.com)：Android 的多功能图像编辑工具。这是一款专为 Android 设计的图像编辑工具。它完全免费，支持批量处理、滤镜、背景移除、尺寸调整和裁剪等多种功能。


![](https://img2024.cnblogs.com/blog/759200/202409/759200-20240927004210498-436705661.png)


### Python 项目


23、[aiofiles](https://github.com)：Python 异步文件处理库。在 Python 中，传统的文件 I/O 是阻塞的，该项目提供了异步（非阻塞）的文件操作。它的 API 与 Python 标准库相似，支持 async/await 语法。



```
async with aiofiles.open('filename', mode='r') as f:
    contents = await f.read()
print(contents)
'My file contents'

```

24、[cupy](https://github.com)：GPU 版的 NumPy 和 SciPy。这是一个利用 GPU 加速数值计算的 Python 库，与 NumPy 和 SciPy 兼容。你可以轻松地将现有的 NumPy/SciPy 代码，迁移到 NVIDIA CUDA 或 AMD ROCm 平台上运行，部分情况下速度可提升 100 倍以上。



```
>>> import cupy as cp
>>> x = cp.arange(6).reshape(2, 3).astype('f')
>>> x
array([[ 0.,  1.,  2.],
       [ 3.,  4.,  5.]], dtype=float32)
>>> x.sum(axis=1)
array([  3.,  12.], dtype=float32)

```

![](https://img2024.cnblogs.com/blog/759200/202409/759200-20240927004210380-970361447.png)


25、[curl\_cffi](https://github.com)：模拟浏览器指纹的 HTTP 客户端。这是一个用 Python 写的 HTTP 客户端库，可以模拟浏览器 TLS、JA3 和 HTTP/2 指纹。它开箱即用、速度快，并且支持 WebSocket 和异步。



```
from curl_cffi import requests

# Notice the impersonate parameter
r = requests.get("https://tools.scrapfly.io/api/fp/ja3", impersonate="chrome")

print(r.json())
# output: {..., "ja3n_hash": "aa56c057ad164ec4fdcb7a5a283be9fc", ...}
# the js3n fingerprint should be the same as target browser

# To keep using the latest browser version as `curl_cffi` updates,
# simply set impersonate="chrome" without specifying a version.
# Other similar values are: "safari" and "safari_ios"
r = requests.get("https://tools.scrapfly.io/api/fp/ja3", impersonate="chrome")

```

![](https://img2024.cnblogs.com/blog/759200/202409/759200-20240927004210443-1170670903.png)


26、[LibreTranslate](https://github.com)：可离线部署的翻译 API 服务。该项目是基于离线翻译引擎 Argos Translate 构建的翻译 API 服务。它不依赖第三方翻译服务，可轻松自建翻译 API 服务，支持自动语言检测、API 密钥和访问频率限制等功能。


![](https://img2024.cnblogs.com/blog/759200/202409/759200-20240927004210442-948089774.png)


27、[s\-tui](https://github.com)：基于终端的 CPU 监控和压测工具。这是一个 Python 写的命令行工具，可在终端中以图形方式实时显示 CPU 温度、频率、功率和利用率等信息。它还支持安装 FIRESTARTER 等工具，对 CPU 进行压力测试。


![](https://img2024.cnblogs.com/blog/759200/202409/759200-20240927004210561-1441535403.gif)


### Rust 项目


28、[uv](https://github.com)：超快的 Python 包管理工具。该项目是基于 Rust 开发的下一代 Python 包管理工具，可用于替代传统的 Python 包和环境管理工具。它兼容 pip、pip\-tools 和 virtualenv 命令，速度比这些工具快 10\-100 倍，并通过全局依赖缓存节省更多的硬盘空间，开箱即用支持 Windows、Linux 和 macOS 系统。



```
# On macOS and Linux.
$ curl -LsSf https://astral.sh/uv/install.sh | sh

# On Windows.
$ powershell -c "irm https://astral.sh/uv/install.ps1 | iex"

# With pip.
$ pip install uv

```

![](https://img2024.cnblogs.com/blog/759200/202409/759200-20240927004210462-1011252172.png)


29、[yazi](https://github.com)：超快的终端文件管理器。这是一个用 Rust 编写的终端文件管理器，所有 I/O 操作均为异步。它提供了友好的界面、自由可定制和流畅的使用体验，支持图片预览、代码高亮、滚动预览和插件系统，并集成了 ripgrep、fd、fzf 等高效的命令行工具。来自 [@fortystory](https://github.com) 的分享


![](https://img2024.cnblogs.com/blog/759200/202409/759200-20240927004210441-413289898.png)


### Swift 项目


30、[BBackupp](https://github.com)：轻松备份 iOS 设备数据的工具。这是一款免费的 iOS 备份工具，支持显示备份进度、自动备份计划、无线备份、加密保护等功能。


![](https://img2024.cnblogs.com/blog/759200/202409/759200-20240927004210386-53905282.png)


31、[OpenScanner](https://github.com)：适用于 iPhone 的免费文档扫描工具。这是一款用 Swift 编写的文档扫描工具，完全免费，没广告且无内购。它可以扫描收据、合同、笔记等，支持自动识别文本、编辑扫描件、签名和导出 PDF 文件等功能，适用于 iOS 16\.0\+ 和 visionOS 1\.2\+ 系统。


![](https://img2024.cnblogs.com/blog/759200/202409/759200-20240927004210447-352463423.png)


### 人工智能


32、[miniMNIST\-c](https://github.com)：C 语言实现的极简神经网络。该项目展示了如何用 C 语言从头实现一个最小的神经网络。它用不到 200 行代码和 C 标准库，实现了一个极简的神经网络，能够对 MNIST 数据集中的手写数字进行分类。


33、[openvino](https://github.com)：优化和部署深度学习模型的工具包。该项目是英特尔开源的工具库，旨在加速和优化深度学习模型部署。它能帮助开发者将训练好的模型部署到多种硬件平台，支持 TensorFlow、PyTorch 和 ONNX 等深度学习框架。



```
import openvino as ov
import torch
import torchvision

# load PyTorch model into memory
model = torch.hub.load("pytorch/vision", "shufflenet_v2_x1_0", weights="DEFAULT")

# convert the model into OpenVINO model
example = torch.randn(1, 3, 224, 224)
ov_model = ov.convert_model(model, example_input=(example,))

# compile the model for CPU device
core = ov.Core()
compiled_model = core.compile_model(ov_model, 'CPU')

# infer the model on random data
output = compiled_model({0: example.numpy()})

```

![](https://img2024.cnblogs.com/blog/759200/202409/759200-20240927004210442-2063411757.png)


### 其它


34、[90DaysOfDevOps](https://github.com)：为期 90 天的 DevOps 免费教程。该项目最初是作者记录自己学习 DevOps 知识的笔记，如今已发展为一个由社区驱动的 DevOps 免费教程，内容涵盖了 DevOps 概念、Linux 基础、计算机网络、容器、Kubernetes、CI/CD、监控和云服务商等。


![](https://img2024.cnblogs.com/blog/759200/202409/759200-20240927004210389-1687359659.png)


35、[Atlas](https://github.com)：开源的精简版 Windows 操作系统。这是一个经过优化的 Windows 操作系统，移除了许多用不到但会拖慢系统的组件。瘦身后减少了系统进程数、网络和内存占用，获得了更快的启动速度和更流畅的操作体验。该系统能够正常运行各种 Windows 软件和游戏，是一份送给游戏爱好者和追求高性能用户的开源礼物。


![](https://img2024.cnblogs.com/blog/759200/202409/759200-20240927004210542-964524876.png)


36、[GPU\-Puzzles](https://github.com)：学习 GPU 并行编程的互动式教程。该项目提供了 14 道题，帮助学习 GPU 编程。你需要编写代码来解决这些问题。尽管代码看起来像 Python，但实际上是使用 numba 库编写 CUDA 代码。更有趣的是，运行代码后会生成一张示意图，帮助你理解代码运行过程。此外，作者还制作了讲解视频，指导如何运行项目并查看答案。


![](https://img2024.cnblogs.com/blog/759200/202409/759200-20240927004210437-1024030729.png)


37、[kando](https://github.com)：跨平台的环形状菜单工具。这是一款桌面圆形菜单（Pie menu）工具，可用于启动应用、模拟键盘快捷键、打开文件等，尤其适合与触控笔和触摸屏配合使用，支持 Windows、Linux 和 macOS 等系统。来自 [@有故事的徐同学](https://github.com) 的分享


![](https://img2024.cnblogs.com/blog/759200/202409/759200-20240927004210647-1806307242.gif)


38、[omakub](https://github.com)：精美的 Ubuntu 配置方案。该项目可以将全新的 Ubuntu 24\.04 系统配置成美观、功能齐全、适合 Web 开发的系统。只需简单的一条命令，即可拥有配置好的 GNOME 桌面环境、窗口管理工具、Alacritty 终端、Neovim 和 VSCode 编辑器等应用，还会将 Chrome 设置成默认浏览器。


![](https://img2024.cnblogs.com/blog/759200/202409/759200-20240927004210438-1841279921.png)


39、[weather\_landscape](https://github.com)：用有趣的动画显示天气预报。这是一个基于气象数据生成景观图的项目，通过动画形式生动地展现天气，替代了枯燥的气象数值显示。


![](https://img2024.cnblogs.com/blog/759200/202409/759200-20240927004210389-138343637.jpg)


### 开源书籍


40、[DictionaryByGPT4](https://github.com)：用 GPT\-4 生成的英语单词书。该项目通过 GPT\-4 分析中考、高考、及四六级考试中的 8000 多个英语单词，生成了一本英语词汇书。书中详细介绍了每个单词的词义、词根、词缀、例句，以及发展历史和文化背景等。


41、[SystemDesign](https://github.com)：《System Design Interview: An Insider’s Guide》中文翻译。该项目是《系统设计面试：内幕指南》一书的中文翻译，内容是传授面试中关于系统设计架构的技巧，例如如何设计一个 YouTube 等系统。来自 [@刘睿华](https://github.com) 的分享


## 最后


感谢参与分享开源项目的小伙伴们，欢迎更多的开源爱好者来 HelloGitHub 自荐/推荐开源项目。如果你发现了 GitHub 上有趣的项目，就[点击这里](https://github.com)分享给大家伙吧！


本期有你感兴趣的开源项目吗？如果有的话就留言告诉我吧～如果还没看过瘾，可以[点击阅读](https://github.com)往期内容。


感谢您的阅读，如果觉得本期内容还不错的话 **求赞、求分享** ❤️


