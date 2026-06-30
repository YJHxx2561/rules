# Clash 配置规则项目

这是一个 Clash 代理工具的配置文件和规则集合项目。

## 项目简介

本项目包含了 Clash 代理工具的配置文件和多个分类的规则列表，用于实现智能分流和内容过滤。

## 项目结构

```
rules/
├── ini/                          # Clash 配置文件
│   ├── clash-easy-config.ini    # 易用型配置
│   └── yjhclash-blackmatrix7.ini # 基于 BlackMatrix7 的配置
│
├── list/                         # 规则列表文件
│   ├── Apple.list               # Apple 服务规则
│   ├── Block.list               # 拦截规则
│   ├── Check.list               # 检测规则
│   ├── Copilot.list             # Copilot 服务规则
│   ├── Crunchyroll.list         # Crunchyroll 规则
│   ├── Direct.list              # 直连规则
│   ├── Gemini.list              # Gemini 服务规则
│   ├── Grok.list                # Grok 服务规则
│   ├── MetaAi.list              # Meta AI 服务规则
│   ├── mydomain.list            # 自定义域名规则
│   ├── proxydns.list            # 代理 DNS 规则
│   ├── ProxyLite.list           # 轻量级代理规则
│   └── Singapore.list           # 新加坡节点规则
│
└── README.md                     # 项目说明文档

```

## 规则列表说明

| 规则文件 | 说明 |
|---------|------|
| **Direct.list** | 国内网站和服务直连规则 |
| **Block.list** | 拦截广告和恶意网站规则 |
| **Apple.list** | Apple 官方服务优化规则 |
| **Copilot.list** | Microsoft Copilot 和相关服务规则 |
| **Gemini.list** | Google Gemini AI 服务规则 |
| **Grok.list** | Grok AI 服务规则 |
| **MetaAi.list** | Meta AI 服务规则 |
| **Crunchyroll.list** | Crunchyroll 流媒体服务规则 |
| **Singapore.list** | 新加坡地区节点优化规则 |
| **Check.list** | 连接检测和延迟测试规则 |
| **ProxyLite.list** | 轻量级代理规则集 |
| **proxydns.list** | DNS 代理和解析规则 |
| **mydomain.list** | 自定义域名和本地规则 |

## 配置文件说明

### clash-easy-config.ini
易用型配置文件，适合初级用户使用，提供基础的代理功能。

### yjhclash-blackmatrix7.ini
基于 BlackMatrix7 规则库的高级配置文件，提供更加细致的分流和过滤功能。

## 使用建议

1. **规则文件引入**：在 Clash 配置中通过 URL 或本地路径引入相应的规则列表文件
2. **规则组合**：根据实际需求组合不同的规则文件，以实现最佳的代理效果
3. **定期更新**：建议定期更新规则文件以获得最新的网站分类和过滤信息
4. **配置备份**：修改配置前建议备份原配置文件

## 注意事项

- 本项目仅供学习和研究使用
- 使用过程中请遵守相关法律法规
- 规则文件需要与 Clash 配置文件正确关联使用

## 许可证

本项目规则和配置仅供参考使用。

---

*最后更新于：2026年6月*
