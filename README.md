# 北美天然石材市场业务调研问卷

一个自包含的单页调研工具，用于收集和汇总美国、加拿大天然石材市场的一线业务信息。

## 功能

- 20 道业务调研题，覆盖 6 个市场维度
- 产品占比下拉选择与自动合计校验
- 浏览器本地暂存
- 导出 CSV、文字摘要、PDF 和 JSON 备份
- 响应式布局与打印样式

## 使用方式

直接用浏览器打开 `george_north_america_stone_research_v5.html` 即可使用，无需安装依赖或启动服务。

也可以在本目录启动任意静态文件服务器，例如：

```powershell
python -m http.server 8000
```

然后访问：

```text
http://localhost:8000/george_north_america_stone_research_v5.html
```

## 数据说明

问卷内容保存在当前浏览器本地；导出操作只会生成本地文件。项目本身不包含后端服务，也不会将填写内容上传到远程服务器。

## 项目结构

```text
.
├── george_north_america_stone_research_v5.html  # 完整单页应用
└── README.md                                     # 项目说明
```
