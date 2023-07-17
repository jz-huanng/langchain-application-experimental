# langchain-application-experimental

### retrieval prompt
```
你是一個看過維基百科內容的機器人，請從給定的句子中抽取一個關鍵詞。

以下為範例：

"樂山大佛建造於唐朝而且花了 90 年。"

關鍵字:樂山大佛

"軟件開發是一項包括需求獲取 、 開發規劃 、 需求分析和設計 、 編程實現 、 軟件測試 、 版本控制的系統工程，其中包含任何最終獲得軟件產品的活動"

關鍵字:軟件開發

"由於人類的馴化使得雞超重，爬行能力不如一般野生雉科。"

關鍵字:雞

從以下用"包圍的python字串中找出一個關鍵詞

"{claim}"

關鍵詞:
```

### claims
天衛三軌道在天王星內部的磁層，以《 仲夏夜之夢 》作者緹坦妮雅命名。<br>

信天翁科的活動範圍位於北冰洋以及南太平洋，牠的翼展可達到3.7米，是世界上現存的翼展最大的鳥類。<br>

獅子座中亮於 5.5 等的恆星有52顆，是黃道帶星座之一。<br>

人因工程學和商品外型細節對工業設計而言，十分重要。<br>

臺南避病院是日治時代臺南專治療法定傳染病病人的法院。<br>

馬關條約取代了先前兩國簽署之 《 中日修好條規 》，並象徵甲午戰爭之正式結束，而同時大清帝國放棄了朝鮮的宗主權使得日本在此後基於 《 日韓合併條約 》 兼併了朝鮮。<br>

南京大學附屬中學，從中國江蘇省遷移。<br>

毒魚豆的萃取物被西印度群島的原住民發掘可以導致魚麻醉安靜 ， 讓他們得以趁機徒手抓魚 。<br>

國立臺灣大學應用力學研究所從1984年開始招收碩 、 博士班研究生 ， 首任所長爲理論及應用力學專家 ， 美國國家工程院院士 、 中央研究院院士鮑亦興教授 。<br>

威廉·倫琴拒絕定名新電子波爲倫琴射線，堅持稱作X射線。<br>

數學的基礎分支之一的幾何學在中古世紀的西方並未出現在教育中。<br>

許多百年以上的針插昆蟲標本收藏於國立臺灣大學昆蟲標本館。<br>

收入豐厚的湯姆克魯斯獲得了許多獎項。<br>

愛因斯坦光量子假說並未被證實。<br>

「五虎上將」的人物之一是三國時蜀漢的著名將領黃忠。<br>

### experiment
請輸入一個陳述句:收入豐厚的湯姆克魯斯獲得了許多獎項。<br>
湯姆 · 克魯斯 （ Tom Cruise ) 全名湯瑪斯 · 克魯斯 · 馬波瑟四世 （ Thomas Cruise Mapother IV ） ， 是知名美國籍男演員及電影製片人 。 作爲世界上收入最多的演員之一 ， 他獲得了多項榮譽 ， 包含三次金球獎和榮譽金棕櫚獎 ， 以及三次奧斯卡金像獎和英國電影學院獎提名 。 他的電影在北美擁有超過45億票房 ， 在全球擁有超過110億美元票房 ， 使他成爲有史以來票房最高的巨星 。 而他主演的電影共有19次位列全球年度票房前十 ， 爲歷史第一 。 克魯斯於1980年代開始他的演藝生涯 ， 並在喜劇片 《 保送入學 》 （ 1983 ） 和動作片 《 壯志凌雲 》 （ 1986 ） 中取得突破 。 他因在 《 金錢本色 》 （ 1986 ） 、 《 雨人 》 （ 1988 ） 和 《 生於七月四日 》 （ 1989 ） 的演出而備受好評 。 他在 《 生於七月四日 》 對的刻畫 ， 使他獲得第一個金球獎和奧斯卡最佳男主角提名 。 作爲1990年代好萊塢的領軍人物 ， 他出演了多部票房大賣的電影 ， 包括劇情片 《 軍官與魔鬼 》 （ 1992 ） 、 驚悚片 《 黑色豪門企業 》 （ 1993 ） 、 恐怖片 《 夜訪吸血鬼 》 （ 1994 ） 和愛情片 《 征服情海 》 （ 1996 ） 。 出於他在 《 征服情海 》 的演出 ， 他再次獲得金球獎最佳男主角和奧斯卡獎提名 。 克魯斯因其在劇情片 《 木蘭花 》 （ 1999 ） 中飾演一名演說家的演出 ， 第三次獲得金球獎和奧斯卡最佳男配角獎提名 。 從那時開始 ， 他主要在科幻或動作電影中演出 ， 確立自己動作第一巨星的地位 ， 他在不可能的任務系列電影中八次飾演伊森 · 韓特 。 他在該類型的著名演出包含 《 香草天空 》 （ 2001 ） 、 《 少數派報告 》 （ 2002 ） 、 《 最後武士 》 （ 2003 ） 、 《 落日殺神 》 （ 2004 ） 、 《 世界大戰 》 （ 2005 ） 、 《 騎士出任務 》 （ 2010 ） 、 《 俠探傑克 》 （ 2012 ） 、 《 遺落戰境 》 （ 2013 ） 、 《 明日邊緣 》 （ 2014 ） 和 《 捍衛戰士 ： 獨行俠 》 （ 2022 ） 。 克魯斯曾經與咪咪 · 羅傑斯 、 妮可 · 基嫚和姬蒂 · 荷姆絲結婚 。 他有三名子女 ， 其中兩名爲收養 ， 一名爲與荷姆絲所生 。<br>
文章中的句子 "作爲世界上收入最多的演員之一，他獲得了多項榮譽，包含三次金球獎和榮譽金棕櫚獎，以及三次奧斯卡金像獎和英國電影學院獎提名" 支持了陳述句的觀點，即湯姆克魯斯獲得了許多獎項。<br>

### keywrod extraction
```
根據思考，從陳述句中找出關鍵字

思考:我需要確認陳述句的真偽
陳述句:天衛三軌道在天王星內部的磁層，以《 仲夏夜之夢 》作者緹坦妮雅命名。
關鍵字:天衛三軌道、天王星、磁層、仲夏夜之夢、作者、緹坦妮雅、命名


根據思考，從陳述句中找出關鍵字

根據思考，從陳述句中找出一個關鍵字

思考:我需要確認陳述句的真偽
陳述句:天衛三軌道在天王星內部的磁層，以《 仲夏夜之夢 》作者緹坦妮雅命名。
關鍵字:緹坦妮雅


根據思考，從陳述句中找出一個關鍵字

思考:我需要確認陳述句的真偽
陳述句:獅子座中亮於 5.5 等的恆星有52顆，是黃道帶星座之一。
關鍵字:黃道帶星座


根據思考，從陳述句中找出一個關鍵字，返回一個可能的維基百科條目名稱

思考:我需要確認陳述句的真偽
陳述句:天衛三軌道在天王星內部的磁層，以《 仲夏夜之夢 》作者緹坦妮雅命名。
關鍵字:仲夏夜之夢


根據思考，從陳述句中找出一個主要關鍵字，返回一個可能的維基百科條目名稱

思考:我需要確認陳述句的真偽
陳述句:小元富太郎於荷西時期在臺灣創立了臺灣織布。
關鍵字:臺灣織布


根據思考，從陳述句中找出一個主要關鍵字，返回一個可能的維基百科條目名稱

思考:我需要確認陳述句的真偽
陳述句:中國人民解放軍武漢軍區，下轄湖北省軍區 、 河南省軍區 。
關鍵字:中國人民解放軍武漢軍區


根據思考，從陳述句中找出一個主要關鍵字，返回一個可能的維基百科條目名稱

思考:我需要確認陳述句的真偽
陳述句:柔軟且帶有白色光澤的石頭：銀，常用於投資型硬幣中，可作爲收藏和投資。
關鍵字:銀硬幣


根據思考，從陳述句中找出一個主要關鍵字，返回一個可能的維基百科條目名稱

思考:我需要確認陳述句的真偽
陳述句:人類在賽普勒斯的活動足跡最早可以追溯至舊石器時代。
關鍵字:賽普勒斯


根據思考，從陳述句中找出一個主要關鍵字，返回一個可能的維基百科條目名稱

思考:我需要確認陳述句的真偽
陳述句:直屬於國家水利部的中國政法大學學校類型是中央部屬高校，因此中國政法大學的行業特殊性強。
關鍵字:中國政法大學

```

### 一個文章內多個證據句
label: supports<br>
claim: 王禮在朱一貴民變後棄職而逃，後遭清朝政府在市場公開執刑。<br>
evidence pages: {'王禮_(清朝)'}<br>
predict: {'清朝政府', '清朝', '朱一貴', '王禮', '政府'}<br>
evidence:<br>
王禮  ， 字立山 ， 號虞山 ， 中國清朝官員 ， 本籍直隸順元宛平縣 。<br>
康熙六十年十二月十八日 （ 1721年2月3日 ） ， 他因爲朱一貴民變應變不力 ， 並棄職脫逃 ， 遭清朝閩浙總督覺羅滿保審明而因此案正法 。<br>
<br>
### 需要多個證據句組合
label: refutes<br>
claim: 蔡元培提倡liberalism，這是一種以自由作爲政治價值的廣告。<br>
evidence pages: {'自由主義', '蔡元培'}<br>
predict: {'廣告', '蔡元培', '自由'}<br>
evidence:<br>
倡導自由思想 、 民權與女權 ， 致力革除 「 讀書爲官 」 之舊俗 ， 開科學性研究風氣 。<br>
自由主義 （ liberalism ） 是一種意識形態和哲學 ， 以自由作爲主要政治價值的一系列思想流派的集合 。<br>
<br>
label: supports<br>
claim: 越戰和國內局勢不穩定使得美國總統約翰遜的支持率下降。<br>
evidence pages: {'越南戰爭', '林登·約翰遜'}<br>
predict: {'總統', '林登·約翰遜', '美國總統', '美國'}<br>
evidence:<br>
約翰遜上任初期廣受民衆歡迎 ， 但越南戰爭及國內社會不穩定導致其支持率逐漸下跌 。<br>
越南戰爭 （ Chiến tranh Việt Nam ， Vietnam War ； 1955年 － 1975年 ） ， - { zh : 簡稱越戰 ; zh - tw : 簡稱越戰 ; zh - hk : 全稱越南戰爭 ; zh - cn : 簡稱越戰 ; } - ， 又稱越南抗美救國戰爭 、 第二次印度支那戰爭 、 第二次越南戰爭 ， 是受中華人民共和國和蘇聯等國家支持的北越 （ 越南民主共和國 ） 協同南越 “ 越南南方民族解放陣線 ” 對抗受美國等國家支持的南越 （ 越南共和國 ） 的一場戰爭 。<br>
<br>
label: refutes<br>
claim: 研究天文 、 宇宙 、 天體物理等相關學科者建議木衛三以希臘神話中的萬神殿作爲命名。<br>
evidence pages: {'天文學家', '伽倪墨得斯', '木衛三'}<br>
predict: {'希臘神話', '神話', '希臘', '木衛三'}<br>
evidence:<br>
後來天文學家西門 · 馬裏烏斯建議以希臘神話中神的斟酒者 、 宙斯的愛人蓋尼米德爲之命名 。<br>
伽倪墨得斯 （ 古希臘語 ： Γανυμήδης ） ， 希臘神話中的一個美少年 。<br>
天文學家是研究天文學 、 宇宙學 、 天體物理學等相關學科的 。<br>
<br>
### missing info in claim(corpus sentence)
label: supports<br>
claim: 馬爾代夫在斯里蘭卡及印度西南偏南，是亞洲地區。<br>
evidence pages: {'馬爾代夫', '南亞'}<br>
predict: {'印度', '西南', '馬爾代夫', '斯里蘭卡'}<br>
evidence:<br>
馬爾代夫共和國 （ -LSB- ދިވެހިރާއްޖޭގެ ޖުމުހޫރިއްޔާ , Dhivehi Raajjeyge Jumhooriyya -RSB- ） ， 通稱馬爾代夫 （ ދިވެހިރާއްޖެ ） ， 古稱溜山 ， 位於斯里蘭卡及印度西南偏南對出的印度洋水域約500公里處 ， 屬於南亞地區 。<br>
馬爾地夫面積爲298平方公里 ， 爲亞洲面積最小的國家之一 ， 人口爲人 ， 馬累爲該國首都及最大城市 ， 傳統上稱之爲 「 國王之島 」 （ King 's Island ） 。<br>
<br>

### 預測關鍵字不匹配
label: refutes<>
claim: 冷室氣體中碳氟化合物因爲化學鍵強度高所以難以降解。<br>
evidence pages: {'氟'}<br>
predict: {'化學鍵', '碳氟化合物'}<br>
evidence:<br>
碳氟化合物氣體是溫室氣體 ， 其溫室效應是二氧化碳的100到20000倍 。<br>
<br>
label: supports<br>
claim: 工業設計構應考量人體工學及其特徵。<br>
evidence pages: {'工業設計', '人因工程學'}<br>
predict: {'特徵'}<br>
evidence:<br>
工業設計者的設計構思 ， 應該包括產品的整體外型 、 各種細節特徵的相關位置 、 顏色 、 材質 、 音效 ； 還要考慮產品使用時的人因工程學 。<br>
人體工學 （ 又稱人類工效學 、 人機工程學 、 人因工程學 、 人因學 ） 是一門重要的工程技術學科 ， 爲管理科學中工業工程專業的一個分支 ， 是研究人和機器 、 環境的相互作用及其合理結合 ， 使設計的機器和環境系統適合人的生理及心理等特點 ， 達到在生產中提高效率 、 安全 、 健康和舒適目的的一門科學 。<br>
工業設計 （ industrial design ） 是以工學 、 美學 、 經濟學爲基礎對工業產品進行的設計 ， 它是20世紀初工業化社會的產物 ， 其設計理念從產生之初的 “ 形式隨機能 ” 發展到現今的 “ 在符合各方面需求的基礎上兼具特色 ” 。<br>
### agent 
#### babyagi
### retrieval-augmented llm
#### CRITIC
