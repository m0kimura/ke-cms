## Classes

<dl>
<dt><a href="#Cms">Cms</a></dt>
<dd></dd>
</dl>

## Functions

<dl>
<dt><a href="#server">server(fn, op)</a> ⇒ <code>Void</code></dt>
<dd><p>サーバー起動</p>
</dd>
<dt><a href="#setting">setting(op)</a> ⇒ <code>Object</code></dt>
<dd><p>実行オプションのセット（省略値解釈）</p>
</dd>
<dt><a href="#sessionIn">sessionIn(req, res, op)</a> ⇒ <code>Void</code></dt>
<dd><p>セッションイン時の処理・クッキー情報など</p>
</dd>
<dt><a href="#analyzeRequest">analyzeRequest(req)</a> ⇒ <code>Void</code></dt>
<dd><p>リクエストストリング（URI)の解析・分解</p>
</dd>
<dt><a href="#getCookies">getCookies(req)</a> ⇒ <code>Array</code></dt>
<dd><p>ウッキー情報の取り出し</p>
</dd>
<dt><a href="#setCookies">setCookies(key, value)</a></dt>
<dd><p>クッキーインタフェイスへのセット</p>
</dd>
<dt><a href="#valCookies">valCookies(key)</a> ⇒ <code>String</code></dt>
<dd><p>クッキー血の参照</p>
</dd>
<dt><a href="#putCookies">putCookies()</a> ⇒ <code>String</code></dt>
<dd><p>出力用クッキーストリングの編集</p>
</dd>
<dt><a href="#ctype">ctype(mdf)</a> ⇒ <code>String</code></dt>
<dd><p>コンテンツタイプを拡張子から編集</p>
</dd>
<dt><a href="#putFile">putFile(res, base)</a> ⇒ <code>Void</code></dt>
<dd><p>単純なファイル転送手続き</p>
</dd>
<dt><a href="#genFileCss">genFileCss(res, base)</a> ⇒ <code>Void</code></dt>
<dd><p>jcssファイルを併合して出力</p>
</dd>
<dt><a href="#putExpand">putExpand(res, base)</a> ⇒ <code>Void</code></dt>
<dd><p>パラメータ展開による出力（CSSなど）</p>
</dd>
<dt><a href="#putEscape">putEscape(res, base)</a> ⇒ <code>Void</code></dt>
<dd><p>ソースデータ用の「&lt;&gt;」などのエスケープ出力</p>
</dd>
<dt><a href="#sendConfig">sendConfig(res)</a> ⇒ <code>Void</code></dt>
<dd><p>コンフィグ情報（INFOJ）を送信</p>
</dd>
<dt><a href="#debugSetdate">debugSetdate(res, op)</a> ⇒ <code>Void</code></dt>
<dd><p>タイムシフト再生</p>
</dd>
<dt><a href="#putHtml">putHtml(url, base, res)</a> ⇒ <code>Void</code></dt>
<dd><p>通常のCMS展開出力</p>
</dd>
<dt><a href="#getInfoj">getInfoj(base)</a> ⇒ <code>Void</code></dt>
<dd><p>INFOJテーブルを作成</p>
</dd>
<dt><a href="#pageinfo">pageinfo(fname, base)</a> ⇒ <code>Void</code></dt>
<dd><p>ページ定義ファイルの読み込み</p>
</dd>
<dt><a href="#layer">layer(lines)</a> ⇒ <code>Void</code></dt>
<dd><p>階層化対応</p>
</dd>
<dt><a href="#expand">expand(buf, base, dt)</a> ⇒ <code>String</code></dt>
<dd><p>HTMLへの挿入と展開</p>
</dd>
<dt><a href="#appendScript">appendScript($)</a> ⇒ <code>Object</code></dt>
<dd><p>スクリプトタグの追加（Jquery,Google,responsive）</p>
</dd>
<dt><a href="#devPage">devPage($, dt)</a> ⇒ <code>Object</code></dt>
<dd><p>Attr[cms-page]を展開</p>
</dd>
<dt><a href="#escape">escape(x, force)</a> ⇒ <code>String</code></dt>
<dd><p>HTML文字をエスケープ</p>
</dd>
<dt><a href="#devInclude">devInclude($)</a> ⇒ <code>Object</code></dt>
<dd><p>Attr[cms-include]を展開</p>
</dd>
<dt><a href="#devParts">devParts($)</a> ⇒ <code>Object</code></dt>
<dd><p>Attr[cms-parts]を展開</p>
</dd>
<dt><a href="#devFrame">devFrame($)</a> ⇒ <code>Object</code></dt>
<dd><p>Attr[cms-frame]を展開</p>
</dd>
<dt><a href="#devBlock">devBlock($)</a> ⇒ <code>Object</code></dt>
<dd><p>Attr[cms-block]を展開</p>
</dd>
<dt><a href="#devCss">devCss($)</a> ⇒ <code>Object</code></dt>
<dd><p>Attr[cms-css]を展開</p>
</dd>
<dt><a href="#debugInfo">debugInfo()</a> ⇒ <code>Object</code></dt>
<dd><p>デバッグ情報をページに追加</p>
</dd>
<dt><a href="#pankuzu">pankuzu()</a> ⇒ <code>String</code></dt>
<dd><p>パンくずパーツ生成</p>
</dd>
<dt><a href="#navbar">navbar()</a> ⇒ <code>String</code></dt>
<dd><p>ナビゲーションパーツ生成</p>
</dd>
<dt><a href="#sidemenu">sidemenu()</a> ⇒ <code>String</code></dt>
<dd><p>サイドメニューパーツ生成</p>
</dd>
<dt><a href="#foot">foot()</a> ⇒ <code>String</code></dt>
<dd><p>フッターパーツ</p>
</dd>
<dt><a href="#guide">guide()</a> ⇒ <code>String</code></dt>
<dd><p>ページ内ガードパーツ生成</p>
</dd>
<dt><a href="#menu">menu()</a> ⇒ <code>string</code></dt>
<dd><p>グループ内メニューパーツ生成</p>
</dd>
<dt><a href="#history">history()</a> ⇒ <code>string</code></dt>
<dd><p>更新履歴パーツ生成</p>
</dd>
<dt><a href="#develop2">develop2(fname, dt, tp, ix)</a> ⇒ <code>String</code></dt>
<dd><p>２段階構造展開パーツ生成</p>
</dd>
<dt><a href="#selection">selection(type, grp)</a> ⇒ <code>Array</code></dt>
<dd><p>メニューデータをパターン選択</p>
</dd>
<dt><a href="#toolbox">toolbox()</a> ⇒ <code>Void</code></dt>
<dd><p>ツールボックスパーツ</p>
</dd>
<dt><a href="#color">color()</a> ⇒ <code>String</code></dt>
<dd><p>カラーサンプルを生成</p>
</dd>
<dt><a href="#menuBuild">menuBuild(op, force)</a> ⇒ <code>Void</code></dt>
<dd><p>メニューデータのインコア</p>
</dd>
<dt><a href="#sitemap">sitemap(res)</a> ⇒ <code>String</code></dt>
<dd><p>サイトマップXMLの生成</p>
</dd>
<dt><a href="#sort">sort(dt, key, asc)</a> ⇒ <code>Array</code></dt>
<dd><p>メニューデータのソート</p>
</dd>
<dt><a href="#validation">validation(term)</a> ⇒ <code>Boolean</code></dt>
<dd><p>有効期間の判定</p>
</dd>
<dt><a href="#cleanup">cleanup(op)</a> ⇒ <code>Void</code></dt>
<dd><p>セッションデータのクリーンアップ</p>
</dd>
</dl>

<a name="Cms"></a>

## Cms
**Kind**: global class  
<a name="new_Cms_new"></a>

### new Cms()
オブジェクトコンストラクション

<a name="server"></a>

## server(fn, op) ⇒ <code>Void</code>
サーバー起動

**Kind**: global function  
**Returns**: <code>Void</code> - none  

| Param | Type | Description |
| --- | --- | --- |
| fn | <code>function</code> | RESTインターフェイス処理 |
| op | <code>Object</code> | 起動オプション |

<a name="setting"></a>

## setting(op) ⇒ <code>Object</code>
実行オプションのセット（省略値解釈）

**Kind**: global function  
**Returns**: <code>Object</code> - 編集後オプションオブジェクト  

| Param | Type | Description |
| --- | --- | --- |
| op | <code>Object</code> | オプションオブジェクト |

<a name="sessionIn"></a>

## sessionIn(req, res, op) ⇒ <code>Void</code>
セッションイン時の処理・クッキー情報など

**Kind**: global function  
**Returns**: <code>Void</code> - none  

| Param | Type | Description |
| --- | --- | --- |
| req | <code>Object</code> | http request インターフェイス |
| res | <code>Object</code> | http response インターフェイス |
| op | <code>Object</code> | 実行オプション |

<a name="analyzeRequest"></a>

## analyzeRequest(req) ⇒ <code>Void</code>
リクエストストリング（URI)の解析・分解

**Kind**: global function  
**Returns**: <code>Void</code> - none  

| Param | Type | Description |
| --- | --- | --- |
| req | <code>Object</code> | httpリクエストインターフェイス |

<a name="getCookies"></a>

## getCookies(req) ⇒ <code>Array</code>
ウッキー情報の取り出し

**Kind**: global function  
**Returns**: <code>Array</code> - クッキーストリング配列  

| Param | Type | Description |
| --- | --- | --- |
| req | <code>Object</code> | http リクエストインターフェイス |

<a name="setCookies"></a>

## setCookies(key, value)
クッキーインタフェイスへのセット

**Kind**: global function  

| Param | Type | Description |
| --- | --- | --- |
| key | <code>String</code> | クッキーキー |
| value | <code>String</code> | クッキー値 |

<a name="valCookies"></a>

## valCookies(key) ⇒ <code>String</code>
クッキー血の参照

**Kind**: global function  
**Returns**: <code>String</code> - 参照値  

| Param | Type | Description |
| --- | --- | --- |
| key | <code>String</code> | クッキーキー |

<a name="putCookies"></a>

## putCookies() ⇒ <code>String</code>
出力用クッキーストリングの編集

**Kind**: global function  
**Returns**: <code>String</code> - 出力用クッキーストリング  
<a name="ctype"></a>

## ctype(mdf) ⇒ <code>String</code>
コンテンツタイプを拡張子から編集

**Kind**: global function  
**Returns**: <code>String</code> - コンテンツタイプ  

| Param | Type | Description |
| --- | --- | --- |
| mdf | <code>String</code> | 拡張子 |

<a name="putFile"></a>

## putFile(res, base) ⇒ <code>Void</code>
単純なファイル転送手続き

**Kind**: global function  
**Returns**: <code>Void</code> - none  

| Param | Type | Description |
| --- | --- | --- |
| res | <code>Object</code> | httpレスポンスインターフェイス |
| base | <code>Steing</code> | 基準フォルダ |

<a name="genFileCss"></a>

## genFileCss(res, base) ⇒ <code>Void</code>
jcssファイルを併合して出力

**Kind**: global function  
**Returns**: <code>Void</code> - none  

| Param | Type | Description |
| --- | --- | --- |
| res | <code>Object</code> | responseオブジェクト |
| base | <code>String</code> | 基底パス |

<a name="putExpand"></a>

## putExpand(res, base) ⇒ <code>Void</code>
パラメータ展開による出力（CSSなど）

**Kind**: global function  
**Returns**: <code>Void</code> - none  

| Param | Type | Description |
| --- | --- | --- |
| res | <code>Object</code> | httpレスポンスインターフェイス |
| base | <code>string</code> | 基本ホルダ |

<a name="putEscape"></a>

## putEscape(res, base) ⇒ <code>Void</code>
ソースデータ用の「<>」などのエスケープ出力

**Kind**: global function  
**Returns**: <code>Void</code> - none  

| Param | Type | Description |
| --- | --- | --- |
| res | <code>Object</code> | httpレスポンスインターフェイス |
| base | <code>String</code> | 基本フォルダ |

<a name="sendConfig"></a>

## sendConfig(res) ⇒ <code>Void</code>
コンフィグ情報（INFOJ）を送信

**Kind**: global function  
**Returns**: <code>Void</code> - none  

| Param | Type | Description |
| --- | --- | --- |
| res | <code>Object</code> | httpレスポンスインターフェイス |

<a name="debugSetdate"></a>

## debugSetdate(res, op) ⇒ <code>Void</code>
タイムシフト再生

**Kind**: global function  
**Returns**: <code>Void</code> - none  

| Param | Type | Description |
| --- | --- | --- |
| res | <code>Object</code> | httpレスポンスオブジェクト |
| op | <code>Object</code> | 実行オプション |

<a name="putHtml"></a>

## putHtml(url, base, res) ⇒ <code>Void</code>
通常のCMS展開出力

**Kind**: global function  
**Returns**: <code>Void</code> - none  

| Param | Type | Description |
| --- | --- | --- |
| url | <code>String</code> | 指定URL |
| base | <code>string</code> | 基本フォルダ |
| res | <code>Object</code> | httpレスポンスオブジェクト |

<a name="getInfoj"></a>

## getInfoj(base) ⇒ <code>Void</code>
INFOJテーブルを作成

**Kind**: global function  
**Returns**: <code>Void</code> - none  

| Param | Type | Description |
| --- | --- | --- |
| base | <code>String</code> | 基本フォルダ |

<a name="pageinfo"></a>

## pageinfo(fname, base) ⇒ <code>Void</code>
ページ定義ファイルの読み込み

**Kind**: global function  
**Returns**: <code>Void</code> - none  

| Param | Type | Description |
| --- | --- | --- |
| fname | <code>String</code> | ファイル名 |
| base | <code>String</code> | 基本フォルダ |

<a name="layer"></a>

## layer(lines) ⇒ <code>Void</code>
階層化対応

**Kind**: global function  
**Returns**: <code>Void</code> - none  

| Param | Type | Description |
| --- | --- | --- |
| lines | <code>Array</code> | 階層データ |

<a name="expand"></a>

## expand(buf, base, dt) ⇒ <code>String</code>
HTMLへの挿入と展開

**Kind**: global function  
**Returns**: <code>String</code> - HTML文  

| Param | Type | Description |
| --- | --- | --- |
| buf | <code>String</code> | バッファデータ |
| base | <code>String</code> | 基本フォルダ |
| dt | <code>Object</code> | 展開用変数データ |

<a name="appendScript"></a>

## appendScript($) ⇒ <code>Object</code>
スクリプトタグの追加（Jquery,Google,responsive）

**Kind**: global function  
**Returns**: <code>Object</code> - 編集後オブジェクト  

| Param | Type | Description |
| --- | --- | --- |
| $ | <code>Object</code> | Jqueryオブジェクト |

<a name="devPage"></a>

## devPage($, dt) ⇒ <code>Object</code>
Attr[cms-page]を展開

**Kind**: global function  
**Returns**: <code>Object</code> - 編集後オブジェクト  

| Param | Type | Description |
| --- | --- | --- |
| $ | <code>Object</code> | Jqueryオブジェクト |
| dt | <code>Object</code> | 展開変数 |

<a name="escape"></a>

## escape(x, force) ⇒ <code>String</code>
HTML文字をエスケープ

**Kind**: global function  
**Returns**: <code>String</code> - 結果文字列  

| Param | Type | Description |
| --- | --- | --- |
| x | <code>String</code> | 対象文字列 |
| force | <code>Boolean</code> | 奇数、偶数行クラスを編集するtrue/false |

<a name="devInclude"></a>

## devInclude($) ⇒ <code>Object</code>
Attr[cms-include]を展開

**Kind**: global function  
**Returns**: <code>Object</code> - 展開結果オブジェクト  

| Param | Type | Description |
| --- | --- | --- |
| $ | <code>Object</code> | Jqueryオブジェクト |

<a name="devParts"></a>

## devParts($) ⇒ <code>Object</code>
Attr[cms-parts]を展開

**Kind**: global function  
**Returns**: <code>Object</code> - 展開結果オブジェクト  

| Param | Type | Description |
| --- | --- | --- |
| $ | <code>Object</code> | Jqueryオブジェクト |

<a name="devFrame"></a>

## devFrame($) ⇒ <code>Object</code>
Attr[cms-frame]を展開

**Kind**: global function  
**Returns**: <code>Object</code> - 展開後結果オブジェクト  

| Param | Type | Description |
| --- | --- | --- |
| $ | <code>Object</code> | 編集対象Jqueryオブジェクト |

<a name="devBlock"></a>

## devBlock($) ⇒ <code>Object</code>
Attr[cms-block]を展開

**Kind**: global function  
**Returns**: <code>Object</code> - 展開後オブジェクト  

| Param | Type | Description |
| --- | --- | --- |
| $ | <code>Object</code> | 対象Jqueryオブジェクト |

<a name="devCss"></a>

## devCss($) ⇒ <code>Object</code>
Attr[cms-css]を展開

**Kind**: global function  
**Returns**: <code>Object</code> - 展開結果オブジェクト  

| Param | Type | Description |
| --- | --- | --- |
| $ | <code>Object</code> | 対象Jqueryオブジェクト |

<a name="debugInfo"></a>

## debugInfo() ⇒ <code>Object</code>
デバッグ情報をページに追加

**Kind**: global function  
**Returns**: <code>Object</code> - 展開結果オブジェクト  
**Parm**: <code>Object</code> $ 展開対象Jqueryオブジェクト  
<a name="pankuzu"></a>

## pankuzu() ⇒ <code>String</code>
パンくずパーツ生成

**Kind**: global function  
**Returns**: <code>String</code> - パンくずパーツHTML  
<a name="navbar"></a>

## navbar() ⇒ <code>String</code>
ナビゲーションパーツ生成

**Kind**: global function  
**Returns**: <code>String</code> - ナビゲーションパーツHTMLテキスト  
<a name="sidemenu"></a>

## sidemenu() ⇒ <code>String</code>
サイドメニューパーツ生成

**Kind**: global function  
**Returns**: <code>String</code> - サイドメニューHTMLテキスト  
<a name="foot"></a>

## foot() ⇒ <code>String</code>
フッターパーツ

**Kind**: global function  
**Returns**: <code>String</code> - フッター用HTMLストリング  
<a name="guide"></a>

## guide() ⇒ <code>String</code>
ページ内ガードパーツ生成

**Kind**: global function  
**Returns**: <code>String</code> - 結果HTMLテキスト  
<a name="menu"></a>

## menu() ⇒ <code>string</code>
グループ内メニューパーツ生成

**Kind**: global function  
**Returns**: <code>string</code> - 結果HTMLテキスト  
<a name="history"></a>

## history() ⇒ <code>string</code>
更新履歴パーツ生成

**Kind**: global function  
**Returns**: <code>string</code> - 結果HTMLテキスト  
<a name="develop2"></a>

## develop2(fname, dt, tp, ix) ⇒ <code>String</code>
２段階構造展開パーツ生成

**Kind**: global function  
**Returns**: <code>String</code> - 生成結果HTMLテキスト  

| Param | Type | Description |
| --- | --- | --- |
| fname | <code>String</code> | テンプレートファイル名 |
| dt | <code>Object</code> | 変数テーブル |
| tp | <code>String</code> | タイプside/top2 |
| ix | <code>Integer</code> | データインデックス |

<a name="selection"></a>

## selection(type, grp) ⇒ <code>Array</code>
メニューデータをパターン選択

**Kind**: global function  
**Returns**: <code>Array</code> - メニューオブジェクト配列  

| Param | Type | Description |
| --- | --- | --- |
| type | <code>String</code> | パターン top/top2/2nd/sibling/side |
| grp | <code>String</code> | グループID |

<a name="toolbox"></a>

## toolbox() ⇒ <code>Void</code>
ツールボックスパーツ

**Kind**: global function  
**Returns**: <code>Void</code> - none  
<a name="color"></a>

## color() ⇒ <code>String</code>
カラーサンプルを生成

**Kind**: global function  
**Returns**: <code>String</code> - HTMLテキスト  
<a name="menuBuild"></a>

## menuBuild(op, force) ⇒ <code>Void</code>
メニューデータのインコア

**Kind**: global function  
**Returns**: <code>Void</code> - none  

| Param | Type | Description |
| --- | --- | --- |
| op | <code>Object</code> | 実行オプション |
| force | <code>Boolean</code> | 日付に関係なく更新 true/false |

<a name="sitemap"></a>

## sitemap(res) ⇒ <code>String</code>
サイトマップXMLの生成

**Kind**: global function  
**Returns**: <code>String</code> - 生成XMLテキスト  

| Param | Type | Description |
| --- | --- | --- |
| res | <code>Object</code> | httpレスポンスインターフェイス |

<a name="sort"></a>

## sort(dt, key, asc) ⇒ <code>Array</code>
メニューデータのソート

**Kind**: global function  
**Returns**: <code>Array</code> - 結果オブジェクト配列  

| Param | Type | Description |
| --- | --- | --- |
| dt | <code>Array</code> | メニューオブジェクト配列 |
| key | <code>String</code> | キー項目 |
| asc | <code>String</code> | asc/dsc 昇順/降順 |

<a name="validation"></a>

## validation(term) ⇒ <code>Boolean</code>
有効期間の判定

**Kind**: global function  
**Returns**: <code>Boolean</code> - true/false OK/NG  

| Param | Type | Description |
| --- | --- | --- |
| term | <code>String</code> | 有効期間表示（yy/mm/dd:yy/mm/dd） |

<a name="cleanup"></a>

## cleanup(op) ⇒ <code>Void</code>
セッションデータのクリーンアップ

**Kind**: global function  
**Returns**: <code>Void</code> - none  

| Param | Type | Description |
| --- | --- | --- |
| op | <code>Object</code> | 実行オプション |

