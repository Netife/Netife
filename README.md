# Netife  
一款适用于Windows的高效，精练的应用层数据包分析工具。Netife可以高效的抓取、分析、修改另分发HTTP/HTTPS/WS/WSS协议请求和回复。Netife是一款专精于网络安全从业者高效调试，软件开发中定向MOCK的有力工具  
# 介绍  
本仓库为Netife的默认前端仓库，其为NetifeCore+可视化界面的前端包装，除本仓库以外，以下仓库也为NetifeCore的包装版本：NetifeShell（Solo Debugger）和NetifeScript（AutoScript Wrapper）。  
# Netife特点  
- Netife支持协议分析工具，提供`Stream Mode`和`Proxy Mode`。前者旨在监听和捕获网络包，后者旨在通过代理服务器，以`MITM`方式修改另分发网络包。  
- Netife具有网络包调试工具，支持若干高自由度的调试模式：`Interceptor`(对所有请求进行全响应拦截)、`AutoRules`(基于策略的静态定向响应拦截)、`AutoScript`(基于JS脚本的动态响应拦截)、`Replay`(重放请求)，调试工具支持HTTP和WS两套。  
- Netife具有数据分析工具，提供包含但不限于`Session Comparer`(会话比较)、`Payload Analysis`(载体自动分析器)等等。  
- Netife具有数据发送工具，提供HTTP和WS和`Composer`，可以自由调试，且支持更多的自由度。  
- Netife支持插件包和脚本包，在数据修改层提供`JS`脚本注入，可定制为特定脚本包，在整个软件层面提供`DLL`式插件加载，可极大程度扩展软件。  
# Netife优势  
相较于`Fiddler`，Netife明显改进的地方有：  
- WS/WSS全套调试功能支持  
- `Payload Analysis`分析工具支持，方便调试  
- 请求链分析  
- 高效响应，采取QT作为界面，摆脱卡顿  
