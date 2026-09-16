# 安装指引 · 马老师短视频文案引擎（双大师融合版）

三种安装方式，任选其一。

---

## 方式一：Coze（扣子）智能体商店

1. 打开 Coze 平台「技能」→「技能商店」搜索 **马老师短视频文案**
2. 点击安装，添加到你的智能体
3. 在智能体中调用即可

> 也可直接下载本仓库 Release 中的 `ma-teacher-shortvideo-copywriting-coze.zip`，在 Coze 中"导入技能 ZIP"安装。

---

## 方式二：扣子 CLI（coze）

```bash
# 安装
coze skill install Kafka-Oreo/ma-teacher-shortvideo-copywriting

# 使用
coze skill run ma-teacher-shortvideo-copywriting "写一条讲半导体板块的短视频文案"
```

---

## 方式三：Skills AI CLI（跨平台）

```bash
# 添加技能
npx skills add Kafka-Oreo/ma-teacher-shortvideo-copywriting

# 列出已安装
npx skills list
```

> `npx skills` 是 Skills 生态的标准 CLI，支持本仓库的 `SKILL.md` 标准协议安装，使技能可在任意遵循该协议的智能体中复用。

---

## 前提

- 本 Skill 为纯文档/提示词引擎，**无外部 API 依赖**，安装即用
- 涉及"当日复盘"时需联网获取真实盘面数据（本 Skill 不生成金融数据，严格遵守不编造）

---

## 验证安装成功

安装后运行：
```
写一条30秒的短视频，讲"市场地量+等美联储"，用马老师的判断叠加老高式开场
```
应产出：钩子开头 + 主轴 + 马老师条件式判断 + 类比 + 与你有关收束，长度 150–400 字。