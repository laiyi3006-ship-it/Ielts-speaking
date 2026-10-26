# IELTS 口說模考室

雅思口說 Part 1–3 模擬考，全部在瀏覽器裡執行：考官唸題、計時、錄音，考完依 IELTS 官方評分規則給四項分數和總分。

開啟：https://laiyi3006-ship-it.github.io/Ielts-speaking/

## 功能

- 完整模擬考或單練 Part 1 / 2 / 3，Part 2 有 1 分鐘準備和 2 分鐘倒數。
- 直接用麥克風錄音，或上傳手機錄音 App 的檔案。
- 用 Whisper（base.en）在瀏覽器裡轉成文字稿，附每個字的時間點；錄音不會上傳。
- 依現行 IELTS Speaking Band Descriptors 評分：每項給整數分數，要「完全符合」某個分數段的特徵才給那一分，四項平均後依官方規則進位。
- 發音分數用 speechocean762 公開資料集（250 位母語為中文的學習者、5 位專家評分）校準。
- 可選擇填入自己的 Anthropic API 金鑰，讓 Claude 評詞彙、文法和連貫性。金鑰只存在瀏覽器裡。

## 限制

分數是練習用的估計，不能代替真正的考官。發音分數聽不出個別音是否發錯。本工具與 IELTS 官方無關。

## 資料來源

- IELTS Speaking Band Descriptors 與 Key Assessment Criteria（ielts.org）
- speechocean762（OpenSLR 101，CC BY 4.0）
- LINDSEI 學習者語料的語速研究
