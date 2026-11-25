# 第6回 解答

## 演習

<!-- [tool call] の行は、表示された行をそのまま貼り付けてください。終わらなかった STEP は、空欄のままでかまいません。 -->

- STEP 1 のツールの名前：glossary_search_glossary
- STEP 2 の [tool call]：fetch_fetch
- STEP 3 の [tool call]：aws_aws___search_documentation
- STEP 4 の [tool call]：glossary_get_lecture_summary
- 気づき・疑問：設定ファイルを書き換えることで簡単にツールを呼び出せることが分かった。

## 宿題

<!-- 基礎・実装・発展のどれか1つに取り組めば完了です。 -->

- 取り組んだレベル：基礎
- やったこと：演習で使った用語集の MCP サーバーに、ツールをもう 1 つ公開した。
- 結果：glossary_get_lecture_summaryが加わり、モデルに見えているツールが8個になった。
- 気づき・疑問：一覧にツールが1つ増えtraceからツールが呼び出されていることが確認できた。エージェント側を書き換えなくても設定ファイルに書き足したツールが使えることが分かった。簡単であるからこそ、信頼できるサイトであるか注意が必要であることも理解できた。
