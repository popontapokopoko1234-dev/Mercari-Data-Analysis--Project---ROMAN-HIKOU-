#Mercari-Data-Analysis--Project---ROMAN-HIKOU-

メルカリでの取引データをPythonで分析し、在庫の「売り尽くし」と「利益最大化」を目指すプロジェクトです。家にある古い参考書をデータサイエンスの力で価値に変え、その成果で「大学の友人と海外旅行（浪漫飛行）」を実現することを最終目標としています。

## Goals
1. **Short-term** 2月上旬の「入試直前パニック需要」をターゲットにした動的プライシングモデルの構築
2. **Mid-term** 家にある参考書を1冊残らず完売させる
3. **Dream** 自分で稼いだ利益だけで海外旅行へ。米米CLUBの『浪漫飛行』をリアルに実現する！笑

## Current Analysis (EDA)
1月末、入試直前期の需要変化により在庫回転率が低下した問題を分析しています。
可視化した結果、市場価格と成約価格に相関が見られない「外れ値」を特定しました。原因が「指導要領改定前の旧課程在庫」に対する大幅な値下げ交渉にあることをデータから解明しています。

## Tech Stack
- Python (Pandas, Matplotlib, Seaborn) 
- Google Colab [cite: 14]
- Data Scraping / Market Research

<img width="859" height="547" alt="analysis_plot" src="https://github.com/user-attachments/assets/d434c597-aeaf-4e2c-a072-723942229213" />
