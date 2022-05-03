# generate-article-for-blog

# table of content

- [generate-article-for-blog](#generate-article-for-blog)
- [table of content](#table-of-content)
- [convert_to_wp_table](#convert_to_wp_table)

# convert_to_wp_table

## Example

source

```fundamental:source
スクリプトの保存：control(⌃) + S、command(⌘) + S
文字カーソルを指定行に移動：control(⌃) + G
改行：control(⌃) + O
検索および置換：command(⌘) + F
選択中の文字列と同じ文字列を複数選択：command(⌘) + D
コメント：command(⌘) + /
選択行にインデントを１段階追加：tab
選択行にインデントを１段階削除：Shift(⇧) + tab
選択中の行の記述を上下に移動：option(⌥) + ↑ か ↓
単語ごとに右方に移動：option(⌥) + →、option(⌥) + control⌃) + F
単語ごとに左方に移動：option(⌥) + ←、option(⌥) + control⌃) + B
選択中の文字列を/*  */形式でコメントアウト：option(⌥) + Shift(⇧) + A
```

converted

```fundamental:converted
<figure class="wp-block-table"><table><thead><tr><th>操作の内容</th><th>キー組み合わせ</th></tr></thead><tbody><tr><td>スクリプトの保存</td><td>control(⌃) + S、command(⌘) + S</td></tr>
<tr><td>文字カーソルを指定行に移動</td><td>control(⌃) + G</td></tr>
<tr><td>改行</td><td>control(⌃) + O</td></tr>
<tr><td>検索および置換</td><td>command(⌘) + F</td></tr>
<tr><td>選択中の文字列と同じ文字列を複数選択</td><td>command(⌘) + D</td></tr>
<tr><td>コメント</td><td>command(⌘) + /</td></tr>
<tr><td>選択行にインデントを１段階追加</td><td>tab</td></tr>
<tr><td>選択行にインデントを１段階削除</td><td>Shift(⇧) + tab</td></tr>
<tr><td>選択中の行の記述を上下に移動</td><td>option(⌥) + ↑ か ↓</td></tr>
<tr><td>単語ごとに右方に移動</td><td>option(⌥) + →、option(⌥) + control⌃) + F</td></tr>
<tr><td>単語ごとに左方に移動</td><td>option(⌥) + ←、option(⌥) + control⌃) + B</td></tr>
<tr><td>選択中の文字列を/*  */形式でコメントアウト</td><td>option(⌥) + Shift(⇧) + A</td></tr>
</tbody></table></figure>
```
