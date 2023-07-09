# 鯖江市 ボードメンバー

## 鯖江市議候補2023

- [sabae-candidates-2023.csv](sabae-candidates-2023.csv) [[CSV](https://senkyo.sabae.cc/sabae-candidates-2023.csv)] (ライセンス: CC BY 鯖江市役所 / 出展: [令和5年7月2日執行鯖江市議会議員選挙の立候補届出状況について（確定） – めがねのまちさばえ 鯖江市](https://www.city.sabae.fukui.jp/about_city/senkyo/oshirase/Senkyo012023062501.html))
- [sabae-candidates-2023-senkyokoho.csv](sabae-candidates-2023-senkyokoho.csv) [[選挙公報画像](sabae-candidates-2023/senkyokoho)] [[CSV](https://senkyo.sabae.cc/sabae-candidates-2023-senkyokoho.csv)] (ライセンス: CC BY 鯖江市役所 / 出展: [選挙公報 – めがねのまちさばえ 鯖江市](https://www.city.sabae.fukui.jp/about_city/senkyo/Senkyokoho.html))
- [sabae-candidates-2023-result.csv](sabae-candidates-2023-result.csv) [[CSV](https://senkyo.sabae.cc/sabae-candidates-2023-result.csv)] (ライセンス: CC BY 鯖江市役所 / 出展: [令和5年7月2日執行 鯖江市議会議員選挙 投開票速報 – めがねのまちさばえ 鯖江市](https://www.city.sabae.fukui.jp/about_city/senkyo/kaihyosokuho/shigisen20230702.html))
- [sabae-candidates-2023-result-vote.csv](sabae-candidates-2023-result-vote.csv) [[CSV](https://senkyo.sabae.cc/sabae-candidates-2023-result-vote.csv)] (ライセンス: CC BY 鯖江市役所 / 出展: [投票区ごとの投票結果 - 令和5年7月2日執行 鯖江市議会議員選挙 投開票速報 – めがねのまちさばえ 鯖江市](https://www.city.sabae.fukui.jp/about_city/senkyo/kaihyosokuho/shigisen20230702.html))

- [sabae-candidates-2023-fukuishimbun1.csv](sabae-candidates-2023-fukuishimbun1.csv) [[CSV](https://senkyo.sabae.cc/sabae-candidates-2023-fukuishimbun1.csv)] (出展: [候補者アンケート㊤「力を入れたい政策は？」　福井県鯖江市議会議員選挙2023 | 政治・行政 | 福井のニュース | 福井新聞ONLINE](https://www.fukuishimbun.co.jp/articles/-/1811101))
- [sabae-candidates-2023-fukuishimbun2.csv](sabae-candidates-2023-fukuishimbun2.csv) [[CSV](https://senkyo.sabae.cc/sabae-candidates-2023-fukuishimbun2.csv)] (出展: [候補者アンケート㊦「佐々木勝久市長の市政運営や政策をどう評価するか」　福井県鯖江市議会議員選挙2023 | 政治・行政 | 福井のニュース | 福井新聞ONLINE](https://www.fukuishimbun.co.jp/articles/-/1812831))

### 使い方

```javascript
import { CSV } from "https://js.sabae.cc/CSV.js";

const data = await CSV.fetchJSON("https://senkyo.sabae.cc/sabae-candidates-2023.csv");
console.log(data);
```
([RUN on ES-Jam](https://ss.sabae.cc/#554))
