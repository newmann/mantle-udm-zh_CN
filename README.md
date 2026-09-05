# mantle-udm-zh_CN

mantle-udm 的简体中文本地化组件。通过 `LocalizedMessage` / `LocalizedEntityField` 覆盖枚举、状态、角色等种子文案，不改 mantle-udm 源码。

## 约定

- locale 统一为 `zh_CN`（与 Java `Locale.toString()` 一致）。
- 不要覆盖英文种子记录本身，只用 LocalizedEntityField / LocalizedMessage。
- 计量单位（Uom）和货币译文由 `framework-zh_CN` 的 `UnitData.xml` / `CurrencyData.xml` 提供。
- 不翻译 OpenSearch `dataDocument` 配置和实体字段元数据 `<description>`。

