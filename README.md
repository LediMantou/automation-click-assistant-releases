## T 当前正式版本：3.1.0 / build 39（方案 A）

自助续期正式发布，App 名称继续为 **自动化点击助手.app**；不实施 T 更名。四种策略、30 有效局、Bundle ID、Keychain/P-256、配置/Profile 和原 T 更新通道保持。
正式产品 `6491d8a6de25d186234e9b30a5f23acdc3f68735`，`release/3.1` / `v3.1.0`；功能代码来源 `86f7fa6106f261197bf27cb967b97c93fdeac31a`。
[Release](https://github.com/LediMantou/automation-click-assistant-releases/releases/tag/v3.1.0) · [DMG](https://github.com/LediMantou/automation-click-assistant-releases/releases/download/v3.1.0/automation-click-assistant-mac-3.1.0.dmg) · [签名 Feed](https://raw.githubusercontent.com/LediMantou/automation-click-assistant-releases/main/appcast.xml)。
DMG SHA256 `24f00fee33f1e1bc846891b09bee3f9cc9491c2cefb36a89a139145720225350`；公网匿名和 Drive 独立完整回读通过。
发行层重封装/重签，未重编译业务；正式包不是验收候选原字节。旧 T 公钥及实际 Sparkle 比较器核验通过，真实跨版本安装仍 NOT_RUN。
本轮不访问 AWS、不真实发卡/续期/投注；H 1.1.0 不写入。T 更名未来另行研究：`T_RENAME_FUTURE_RESEARCH=PENDING`。
当前维护入口：`文档/发布基线/3.1.0/`。下方 3.0.0 及更早内容完整保留为历史时点记录，历史“当前版本”不覆盖本段结论。

---

# Automation Click Assistant Releases

Public distribution assets for the **Sparkle public-network experiment**.

Current experiment:

- App identity: `com.ledimantou.BrowserClickAssistant.SparkleExperiment`
- A: `0.3.0` / build `3`
- B: `0.4.0` / build `4`
- Update tag: `sparkle-exp-0.4.0`

This repository intentionally contains only:

- `README.md`
- signed `appcast.xml`
- experimental DMG assets attached to GitHub Releases

It must never contain application source code, private signing keys, production configuration, Chrome or Telegram data, formal 2.9 artifacts, or candidate packages.
