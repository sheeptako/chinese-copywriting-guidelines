# 中文文案排版指北

[![Crowdin](https://d322cqt584bo4o.cloudfront.net/chinese-copywriting-guidelines/localized.svg)](https://crowdin.com/project/chinese-copywriting-guidelines) [![Greenkeeper badge](https://badges.greenkeeper.io/sparanoid/chinese-copywriting-guidelines.svg)](https://greenkeeper.io/) [![devDependency Status](https://david-dm.org/sparanoid/chinese-copywriting-guidelines/dev-status.svg)](https://david-dm.org/sparanoid/chinese-copywriting-guidelines#info=devDependencies) [![Built with Almace Scaffolding](https://d349cztnlupsuf.cloudfront.net/amsf-badge.svg)](http://sparanoid.com/note/chinese-copywriting-guidelines/)

统一中文文案、排版的相关用法，降低团队成员之间的沟通成本，增强网站气质。

Other languages:

- [English](README.en-US.md)
- [Chinese Traditional](README.md)
- [Chinese Simplifed](README.zh-CN.md)
- [Chinese Simplifed](https://github.com/mzlogin/chinese-copywriting-guidelines)（外部链接）

* * *

## 目录

{:.no_toc}

- TOC {:toc}

## 空格

「有研究显示，打字的时候不喜欢在中文和英文之间加空格的人，感情路都走得很辛苦，有七成的比例会在 34 岁的时候跟自己不爱的人结婚，而其余三成的人最后只能把遗产留给自己的猫。 毕竟爱情跟书写都需要适时地留白。

與大家共勉之。」——[vinta/paranoid-auto-spacing](https://github.com/vinta/pangu.js)

### 中英文之间需要增加空格

正确：

> 在 LeanCloud 上，数据存储是围绕`AVObject` 进行的。

错误：

> 在LeanCloud上，數據存儲是圍繞`AVObject`進行的。
> 
> 在 LeanCloud上，數據存儲是圍繞`AVObject` 進行的。

完整的正确用法：

> 在 LeanCloud 上，数据存储是围绕 `AVObject` 进行的。每个 `AVObject` 都包含了与 JSON 兼容的 key-value 对应的数据。数据是 schema-free 的，你不需要在每个 `AVObject` 上提前指定存在哪些键，只要直接设定对应的 key-value 即可。

例外：「豆瓣FM」等產品名詞，按照官方所定義的格式書寫。

### 中文與數字之間需要增加空格

正確：

> 今天出去買菜花了 5000 元。

錯誤：

> 今天出去買菜花了 5000元。
> 
> 今天出去買菜花了5000元。

### 數字與單位之間需要增加空格

正確：

> 我家的光纖入屋寬頻有 10 Gbps，SSD 一共有 20 TB。

錯誤：

> 我家的光纖入屋寬頻有 10Gbps，SSD 一共有 20TB。

例外：度／百分比與數字之間不需要增加空格：

正確：

> 今天是 233° 的高溫。
> 
> 新 MacBook Pro 有 15% 的 CPU 性能提升。

錯誤：

> 今天是 233 ° 的高溫。
> 
> 新 MacBook Pro 有 15 % 的 CPU 性能提升。

### 全形標點與其他字符之間不加空格

正確：

> 剛剛買了一部 iPhone，好開心！

錯誤：

> 剛剛買了一部 iPhone ，好開心！
> 
> 剛剛買了一部 iPhone， 好開心！

### `text-spacing` to the rescue?

CSS Text Module Level 4 的 [`text-spacing`](https://www.w3.org/TR/css-text-4/#text-spacing-property) 和 Microsoft 的 [`-ms-text-autospace`](http://msdn.microsoft.com/en-us/library/ie/ms531164(v=vs.85).aspx) 可以實現自動為中英文之間增加空白。不過目前並未普及，另外在其他應用場景，例如 macOS、iOS、Windows 等用戶介面目前并不存在這個特性，所以請繼續保持隨手加空格的習慣。

## 標點符號

### 不重複使用標點符號

正確：

> 德國隊竟然戰勝了巴西隊！
> 
> 她竟然對你說「喵」？！

錯誤：

> 德國隊竟然戰勝了巴西隊！！
> 
> 德國隊竟然戰勝了巴西隊！！！！！！！！
> 
> 她竟然對你說「喵」？？！！
> 
> 她竟然對你說「喵」？！？！？？！！

## 全形和半形

不明白什麼是全形（全角）與半形（半角）符號？請查看維基百科詞條『[全形和半形](http://zh.wikipedia.org/wiki/%E5%85%A8%E5%BD%A2%E5%92%8C%E5%8D%8A%E5%BD%A2)』。

### 使用全形中文標點

正確：

> 嗨！你知道嘛？今天前台的小妹跟我說「喵」了哎！
> 
> 核磁共振成像（NMRI）是什麼原理都不知道？JFGI！

錯誤：

> 嗨! 你知道嘛? 今天前台的小妹跟我說 "喵" 了哎!
> 
> 嗨!你知道嘛?今天前台的小妹跟我說"喵"了哎!
> 
> 核磁共振成像 (NMRI) 是什麼原理都不知道? JFGI!
> 
> 核磁共振成像(NMRI)是什麼原理都不知道?JFGI!

### 數字使用半形字符

正確：

> 這件蛋糕只賣 1000 元。

錯誤：

> 這件蛋糕只賣 １０００ 元。

例外：在設計稿、宣傳海報中如出現極少量數字的情形時，為方便文字對齊，是可以使用全形數字的。

### 遇到完整的英文整句、特殊名詞，其內容使用半形標點

正確：

> 賈伯斯那句話是怎麼說的？「Stay hungry, stay foolish.」
> 
> 推薦你閱讀《Hackers & Painters: Big Ideas from the Computer Age》，非常的有趣。

錯誤：

> 賈伯斯那句話是怎麼說的？「Stay hungry，stay foolish。」
> 
> 推薦你閱讀《Hackers＆Painters：Big Ideas from the Computer Age》，非常的有趣。

## 名詞

### 專有名詞使用正確的大小寫

大小寫相關用法原屬於英文書寫範疇，不屬於本 wiki 討論內容，在這裡只對部分易錯用法進行簡述。

正確：

> 使用 GitHub 登錄
> 
> 我們的客戶有 GitHub、Foursquare、Microsoft Corporation、Google、Facebook, Inc.。

錯誤：

> 使用 github 登錄
> 
> 使用 GITHUB 登錄
> 
> 使用 Github 登錄
> 
> 使用 gitHub 登錄
> 
> 使用 gｲんĤЦ8 登錄
> 
> 我們的客戶有 github、foursquare、microsoft corporation、google、facebook, inc.。
> 
> 我們的客戶有 GITHUB、FOURSQUARE、MICROSOFT CORPORATION、GOOGLE、FACEBOOK, INC.。
> 
> 我們的客戶有 Github、FourSquare、MicroSoft Corporation、Google、FaceBook, Inc.。
> 
> 我們的客戶有 gitHub、fourSquare、microSoft Corporation、google、faceBook, Inc.。
> 
> 我們的客戶有 gｲんĤЦ8、ｷouЯƧquﾑгє、๓เςг๏ร๏Ŧt ς๏гק๏гคtเ๏ภn、900913、ƒ4ᄃëв๏๏к, IПᄃ.。

注意：當網頁中需要配合整體視覺風格而出現全部大寫／小寫的情形，HTML 中請使用標準的大小寫規範進行書寫；並通過 `text-transform: uppercase;`／`text-transform: lowercase;` 對表現形式進行定義。

### 不要使用不地道的縮寫

正確：

> 我们需要一位熟悉 JavaScript、HTML5，至少理解一种框架（如 Backbone.js、AngularJS、React 等）的前端开发者。

錯誤：

> 我們需要一位熟悉 Js、h5，至少理解一种框架（如 backbone、angular、RJS 等）的 FED。

## 爭議

以下用法略帶有個人色彩，即：無論是否遵循下述規則，從語法的角度來講都是**正確**的。

### 鏈接之間增加空格

用法：

> 请 [提交一个 issue](#) 并分配给相关同事。
> 
> 訪問我們網站的最新動態，請 [點擊這裡](#) 進行訂閱！

對比用法：

> 请[提交一个 issue](#) 并分配给相关同事。
> 
> 訪問我們網站的最新動態，請[點擊這裡](#)進行訂閱！

### 簡體中文使用直角引號

用法：

> 「老师，『有条不紊』的『紊』是什么意思？」

對比用法：

> “老师，‘有条不紊’的‘紊’是什么意思？”

## 工具

| 仓库                                                                                                                              | 语言              |
| ------------------------------------------------------------------------------------------------------------------------------- | --------------- |
| [vinta/paranoid-auto-spacing](https://github.com/vinta/paranoid-auto-spacing)                                                   | JavaScript      |
| [huei90/pangu.node](https://github.com/huei90/pangu.node)                                                                       | Node.js         |
| [huacnlee/auto-correct](https://github.com/huacnlee/auto-correct)                                                               | Ruby            |
| [sparanoid/space-lover](https://github.com/sparanoid/space-lover)                                                               | PHP (WordPress) |
| [nauxliu/auto-correct](https://github.com/NauxLiu/auto-correct)                                                                 | PHP             |
| [jxlwqq/chinese-typesetting](https://github.com/jxlwqq/chinese-typesetting)                                                     | PHP             |
| [hotoo/pangu.vim](https://github.com/hotoo/pangu.vim)                                                                           | Vim             |
| [sparanoid/grunt-auto-spacing](https://github.com/sparanoid/grunt-auto-spacing)                                                 | Node.js (Grunt) |
| [hjiang/scripts/add-space-between-latin-and-cjk](https://github.com/hjiang/scripts/blob/master/add-space-between-latin-and-cjk) | Python          |
| [hustcc/hint](https://github.com/hustcc/hint)                                                                                   | Python          |

## 誰在這樣做？

| 網站                                              | 文案  | UGC  |
| ----------------------------------------------- | --- | ---- |
| [Apple 中國](http://www.apple.com/cn/)            | Yes | N/A  |
| [Apple 香港](http://www.apple.com/hk/)            | Yes | N/A  |
| [Apple 台灣](http://www.apple.com/tw/)            | Yes | N/A  |
| [Microsoft 中國](http://www.microsoft.com/zh-cn/) | Yes | N/A  |
| [Microsoft 香港](http://www.microsoft.com/zh-hk/) | Yes | N/A  |
| [Microsoft 台灣](http://www.microsoft.com/zh-tw/) | Yes | N/A  |
| [LeanCloud](https://leancloud.cn/)              | Yes | N/A  |
| [V2EX](https://www.v2ex.com/)                   | Yes | Yes  |
| [Apple4us](http://apple4us.com/)                | Yes | N/A  |
| [Ruby China](https://ruby-china.org/)           | Yes | 標題達成 |
| [PHPHub](https://phphub.org/)                   | Yes | 標題達成 |
| [少數派](http://sspai.com/)                        | Yes | N/A  |

## 參考文獻

- [Guidelines for Using Capital Letters - About.com](http://grammar.about.com/od/punctuationandmechanics/a/Guidelines-For-Using-Capital-Letters.htm)
- [Letter case - Wikipedia](http://en.wikipedia.org/wiki/Letter_case)
- [Punctuation - Oxford Dictionaries](http://www.oxforddictionaries.com/words/punctuation)
- [Punctuation - The Purdue OWL](https://owl.english.purdue.edu/owl/section/1/6/)
- [How to Use English Punctuation Correctly - wikiHow](http://www.wikihow.com/Use-English-Punctuation-Correctly)
- [格式 - openSUSE](https://zh.opensuse.org/index.php?title=Help:%E6%A0%BC%E5%BC%8F)
- [全形和半形 - 維基百科](http://zh.wikipedia.org/wiki/%E5%85%A8%E5%BD%A2%E5%92%8C%E5%8D%8A%E5%BD%A2)
- [引號 - 維基百科](http://zh.wikipedia.org/wiki/%E5%BC%95%E8%99%9F)
- [疑問驚嘆號 - 維基百科](http://zh.wikipedia.org/wiki/%E7%96%91%E5%95%8F%E9%A9%9A%E5%98%86%E8%99%9F)