AI影響分析ワークシート Ver1.00
                                                            2023/09/25
                             日本ソフトウェア科学会 機械学習工学研究会
                        　　　　機械学習セキュリティワーキンググループ
                    機械学習システムセキュリティガイドライン策定委員会

影響分析の進め方	
　１．影響分析ワークシートのシート「I. 説明」のタブを開いて頂き、内容を
　　　理解してください
　２．「II. ヒアリングシート」のタブに書かれている質問について、回答を
　　　それぞれ水色の欄に記入してください。
　３．「III. 影響分析のための準備」のタブに書かれている質問について、
　　　回答を検討ください。
　　　オレンジの欄は元になる欄（HS2）の反転（○○できない）で回答して
　　　ください。
　　　緑の欄は、直上の灰色の欄から選んで（複数選択可）記入してください。
　４．「IV-1. AIの誤判断被害の影響分析」のタブの黄色の欄について、シー
　　　トの上の方の欄の内容を書き写してください。（ワークシートの実装の
　　　都合上、自動での複写にはなっておりません。）
　　　その後、水色の欄を検討して埋めて下さい。引き起こされる被害が想定
　　　されない場合は、「なし」と記入してください。
　　　対処必要性は左の欄の被害が生じたと仮定した際にどの程度問題とする
　　　かを判断して大中小無で記入してください。
　５．「IV-2. 情報漏洩被害の影響分析」のタブについてもIV-1のシートと同
　　　様に記入してください。訓練済モデルの漏洩被害と、訓練データ漏洩の
　　　被害の2つのテーブルがありますのでご注意ください。
　　　黄色の欄については、シートの上の方の欄の内容を書き写してください。
　　　（ワークシートの実装の都合上、自動での複写にはなっておりません。）
　　　その後、水色の欄を検討して埋めて下さい。引き起こされる被害が想定
　　　されない場合は、「なし」と記入してください。
　　　対処必要性は左の欄の被害が生じたと仮定した際にどの程度問題とする
　　　かを判断して大中小無で記入してください。
　６．AIの誤判断、訓練済モデルの漏洩、訓練データの漏洩のそれぞれのテー
　　　ブルにおいて、例えば対処必要性が「大」になっているなど、対処が必
　　　要と考えられる場合には、同梱のAIリスク問診ツールを実行して、その
　　　被害を生じる攻撃が実際に実施できそうかどうかを判断してください。
　　　各被害は以下の攻撃が成功すると生じる可能性がありますので、AIリス
　　　ク問診ツールで対応する攻撃が実施できそうかを判定してください。
　　　AIの誤判断： 回避攻撃、ポイズニング攻撃
　　　訓練済モデルの漏洩： モデル抽出攻撃
　　　訓練データの漏洩： モデルインバージョン攻撃、メンバシップ推測攻撃
　　　詳細はガイドラインのリスク分析編をご覧ください。

改版履歴
・Ver1.0
-- Ver0.8版を正式版とし、Ver1.0として公開

・Ver0.8
-- Ver0.8版公開


　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　以上

