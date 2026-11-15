# educate

教育與親子創作相關的 Agent Skills。

## Skills

| Skill | 用途 | 入口 |
|---|---|---|
| storybooks maker | 製作與修改繁體中文親子互動故事書、HTML 繪本與可動立體書 | [SKILL.md](skills/storybooks-maker/SKILL.md) |

## storybooks maker

完整技能位於 [`skills/storybooks-maker/`](skills/storybooks-maker/)，包含 8 個檔案：

- `SKILL.md`：主要工作流程與交付規範。
- `references/`：分鏡與分層美術、互動與音訊、Taste 與字體排版、實作驗收與交付規範。
- `assets/production-brief.md`：故事書製作規格模板。
- `assets/icon.svg`：技能圖示。
- `agents/openai.yaml`：Agent 顯示與載入設定。

使用時保留整個技能資料夾與相對路徑，讓支援 `SKILL.md` 的 Agent 從主文件讀取流程，並依所在環境的技能載入方式使用。這份技能是工作流程與參考文件，執行製作時仍需要對應的圖片生成、瀏覽器驗收、Taste 排版與檔案保存能力；Google 雲端硬碟交付需要可用的連線與權限。

目前規範包括：原作／影視版本查閱、開頭交代角色背景、跨頁故事連續性、每頁 1–3 個圖上互動點、配樂與朗讀、活動物件裁切檢查，以及成品和後續修訂完成後預設上傳 Google 雲端硬碟。

