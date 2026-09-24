# ai-class-lab

高中 AI 課的 Prompt 實驗室。學生用自己的 Google 帳號登入、輸入班級代碼加入班級，
在課堂任務底下寫 prompt、存版本、上傳產出，並和同組比較。

- 網站：https://rthtsai.github.io/ai-class-lab/
- 原始碼：建置自 [`rthtsai/prompt-search`](https://github.com/rthtsai/prompt-search) 的班級模式
  （`npm run pages:build:class`），本 repo 只存放建置結果。
- 資料庫與登入：獨立的 Supabase 專案，與原版 Prompt 辭典完全分離。
- [隱私權政策](https://rthtsai.github.io/ai-class-lab/privacy.html) ·
  [使用條款](https://rthtsai.github.io/ai-class-lab/terms.html)

學生的電子郵件與姓名只有該班老師看得到；同學之間只顯示暱稱。
