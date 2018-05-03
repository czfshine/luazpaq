# luazpaq
LuaZPAQ is a Lua scripting language wrapper around the ZPAQ Compression library. 
ZPAQ是一个压缩比很高（比7z的最优压缩还高）的压缩库，本项目将ZPAQ提供的接口绑定到lua库里，使得能够在lua脚本内调用其数据压缩的功能。

# 性能问题
核心的压缩代码还是原来的ZPAQ，本项目只是提供一个调用的方式，对性能影响不大。

