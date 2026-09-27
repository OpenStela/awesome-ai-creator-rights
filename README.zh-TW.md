# Awesome AI Creator Rights [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> 給以 AI 創作音樂、圖像、角色與影片的創作者：產出是否受保護、工具條款允許做什麼、如何證明作品在先，以及遭他人抄襲時該怎麼辦——相關的原始資料與工具。

**本清單不構成法律意見。** 本清單蒐集第一手資料——法條、法院判決、主管機關函釋與各工具自身的條款——供創作者自行查閱。各國法律不同，且變動快速；每一節都標示最後查核日期。涉及自身作品的決定，請洽詢當地律師。

[English](README.md)

## 目錄

- [各國著作權現況](#各國著作權現況)
- [產出歸誰：AI 工具條款](#產出歸誰ai-工具條款)
- [證明作品在先](#證明作品在先)
- [作品遭他人抄襲時](#作品遭他人抄襲時)
- [授權與銷售](#授權與銷售)
- [標示與透明度規範](#標示與透明度規範)
- [延伸閱讀](#延伸閱讀)

## 各國著作權現況

多數著作權制度只保護人類著作人所貢獻的部分。怎樣才算足夠的人類貢獻——提示詞、選擇、編輯、編排——由各國自行認定。

最後查核：2026-09-27。

### 美國

須有人類著作人。由 AI 獨立生成的內容在申請登記時必須聲明排除；人類的選擇、編排與修改仍可受保護。大量下提示詞是否足以構成創作，仍在訴訟中。

- [含 AI 生成內容之著作登記指引](https://www.copyright.gov/ai/ai_policy_guidance.pdf) - 美國著作權局，2023 年 3 月：須揭露 AI 生成內容，並說明人類的貢獻。
- [著作權與 AI 報告第 2 部：可著作權性](https://www.copyright.gov/ai/Copyright-and-Artificial-Intelligence-Part-2-Copyrightability-Report.pdf) - 美國著作權局報告，2025 年 1 月。單憑提示詞通常不足；[AI 專區](https://www.copyright.gov/ai/)列有各部報告，包括討論訓練、尚屬發布前版本的第 3 部。
- [Zarya of the Dawn 案](https://www.copyright.gov/docs/zarya-of-the-dawn.pdf) - 2023 年決定：准予登記漫畫的文字與編排，但排除其中的 Midjourney 圖像。
- [Théâtre D'opéra Spatial 案](https://www.copyright.gov/rulings-filings/review-board/docs/Theatre-Dopera-Spatial.pdf) - 2023 年覆審委員會駁回一幅僅經有限人工修改之 Midjourney 圖像的登記。
- [Thaler v. Perlmutter 案](https://media.cadc.uscourts.gov/opinions/docs/2025/03/23-5233.pdf) - 哥倫比亞特區巡迴上訴法院，2025 年 3 月：人類著作人是法定要件。最高法院於 2026 年 3 月[駁回上訴許可聲請](https://www.supremecourt.gov/docket/docketfiles/html/public/25-449.html)。
- [Allen v. Perlmutter 案](https://www.courtlistener.com/docket/69198079/allen-v-perlmutter/) - 科羅拉多州繫屬中案件，爭點為反覆下提示詞與編輯是否使使用者成為著作人。
- [Bartz v. Anthropic 案合理使用裁定](https://copyrightalliance.org/wp-content/uploads/2025/06/Bartz-v.-Anthropic-Order.pdf) - 2025 年 6 月：以合法購買之書籍訓練屬合理使用；盜版複製物則否。後以 15 億美元和解。
- [Kadrey v. Meta 案合理使用裁定](https://law.justia.com/cases/federal/district-courts/california/candce/3:2023cv03417/415175/598/) - 2025 年 6 月：因未證明市場損害而認定合理使用；法院強調本裁定射程有限。

### 歐盟

歐盟並無規定 AI 產出歸屬的規範；原創性標準（「著作人自身的智慧創作」）意味著須有人類著作人。AI Act 課予義務的對象是 AI 提供者，而非創作者。

- [DSM 指令第 3–4 條](https://eur-lex.europa.eu/eli/dir/2019/790/oj) - 文字與資料探勘例外；權利人得「以機器可讀方式」排除第 4 條的探勘。
- [AI Act](https://eur-lex.europa.eu/eli/reg/2024/1689/oj) - 第 53 條要求通用模型提供者尊重排除聲明並公布訓練資料摘要；第 50 條要求標示合成內容。
- [Infopaq 案（C-5/08）](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:62008CJ0005) - 歐盟通用的原創性標準。
- [Like Company v Google 案（C-250/25）](https://curia.europa.eu/juris/liste.jsf?num=C-250/25&language=en) - 歐洲法院首件生成式 AI 著作權案件；繫屬中。
- [GEMA v OpenAI 案](https://www.justiz.bayern.de/gerichte-und-behoerden/landgericht/muenchen-1/presse/2025/11.php) - 慕尼黑地方法院，2025 年 11 月：被記憶於模型權重中的歌詞構成重製，不適用探勘例外。

### 英國

- [CDPA 1988 s.9(3)](https://www.legislation.gov.uk/ukpga/1988/48/section/9) - 少見地保護無人類著作人的「電腦生成」著作，歸屬於為其作出必要安排之人。目前仍有效。
- [著作權與 AI 報告](https://assets.publishing.service.gov.uk/media/69ba692226909a14239612e4/CP2602959_-_Report_on_Copyright_and_Artificial_Intelligence_web.pdf) - 政府報告，2026 年 3 月：提議刪除 s.9(3)，並放棄以附排除機制的廣泛探勘例外作為首選方案。
- [Getty Images v Stability AI 案](https://www.judiciary.uk/wp-content/uploads/2025/11/Getty-Images-v-Stability-AI.pdf) - 高等法院，2025 年 11 月：Getty 的間接侵權主張敗訴；訓練部分的主張因訓練發生在英國境外而撤回。

### 日本

- [著作權法第 30 條之 4](https://www.japaneselawtranslation.go.jp/en/laws/view/4207) - 允許以非享受著作表現為目的之利用，包括 AI 訓練，但不當損害權利人利益者除外。
- [AI 與著作權之一般見解（概要）](https://www.bunka.go.jp/english/policy/copyright/pdf/94055801_01.pdf) - 文化廳，2024 年：唯有人類以創作意圖與創作貢獻將 AI 作為工具使用時，產出才受保護。[日文全文](https://www.bunka.go.jp/seisaku/bunkashingikai/chosakuken/pdf/94037901_01.pdf)。

### 中國

無直接相關的法律規定；法院依使用者創作過程的證據個案判斷。

- [李某訴劉某案](https://english.bjinternetcourt.gov.cn/2024-02/28/c_695.htm) - 北京互聯網法院，2023 年：經反覆下提示詞與選擇參數產生的 Stable Diffusion 圖像受保護；使用者為著作人。
- [張家港案摘要](https://www.kingandwood.com/cn/en/insights/latest-thinking/chinese-court-found-ai-generated-pictures-not-copyrightable-convergence-with-the-us-standard.html) - 2025 年：以簡單提示詞產生的圖像因原告無法證明創作過程而不受保護（律師事務所摘要）。

### 韓國

- [生成式 AI 輔助著作之著作權登記指南](https://www.copyright.or.kr/eng/doc/etc_pdf/Guide_to_Copyright_Registration_for_Generative_AI-Assisted_Works.pdf) - 文化體育觀光部與韓國著作權委員會，2025 年 6 月：AI 自主產出不得登記，單憑提示詞難以構成創作，將 AI 產出登記為自己的著作屬刑事犯罪。

### 臺灣

著作權於著作完成時發生，並無登記制度。智慧財產局一貫見解認為 AI 自主產出不受保護，而以 AI 為工具且具實質人類創作投入者則受保護。目前尚未查得關於 AI 產出的法院判決。

- [著作權法](https://law.moj.gov.tw/LawClass/LawAll.aspx?pcode=J0070017) - 第 3 條規定著作人為創作著作之人；第 10 條規定著作人於著作完成時享有著作權。
- [智慧財產局函釋，2018 年](https://www.tipo.gov.tw/tw/copyright/692-15651.html) - AI 並非人，其自主產出原則上不是著作。
- [智著字第11460005900號函，2025 年 4 月](https://www.tipo.gov.tw/tw/copyright/692-33518.html) - 以 AI 為工具並投入自身創意者，成果受著作權保護，權利歸投入創意之人；AI 獨立完成者非著作。
- [智慧財產局函釋，2025 年 5 月](https://www.tipo.gov.tw/tw/copyright/692-34252.html) - 重申上述兩種情形，並提醒商業利用侵權產出的風險。
- [智慧財產局函釋，2025 年 10 月](https://www.tipo.gov.tw/tw/copyright/692-63403.html) - 人類的創作投入是否足夠，由法院個案認定。

## 產出歸誰：AI 工具條款

工具條款決定的是使用者與公司之間，使用者可以如何利用產出。條款無法使法律認定不受保護的產出取得著作權（見上一節）。

最後查核：2026-09-27。條款經常變動；請將各項目旁的日期與現行頁面比對。

| 工具          | 產出歸屬                         | 免費方案                                | 付費方案                                    |
| ------------- | -------------------------------- | --------------------------------------- | ------------------------------------------- |
| Suno          | 付費：讓與使用者                 | 僅限個人、非商業使用                    | 可商用，僅限經允許下載的檔案                |
| Udio          | Udio 及其授權人                  | 不得商用、不得下載                      | 同左                                        |
| ElevenLabs    | 使用者                           | 僅限非商業使用                          | 可商用；音樂另有限制                        |
| Midjourney    | 使用者，於法律允許範圍內         | —                                       | 年營收逾 100 萬美元的公司須使用 Pro 或 Mega |
| Leonardo.ai   | 付費：使用者。**免費：Leonardo** | 產出歸 Leonardo 所有                    | 產出歸使用者所有，且可設為不公開            |
| Runway        | Runway 不主張任何權利            | 不限制商業使用                          | 同左                                        |
| Adobe Firefly | 使用者                           | —                                       | 智慧財產權補償僅適用於符合資格的合約        |
| OpenAI        | 使用者（權利「如有」即讓與）     | 與付費相同                              | 與免費相同                                  |
| Google Gemini | Google 不主張任何權利            | 未付費 API 資料可能用於改善 Google 產品 | 付費 API 資料不用於改善 Google 產品         |
| Stability AI  | 使用者                           | 年營收未達 100 萬美元者免費             | 超過者須取得企業授權                        |
| Civitai       | 依各模型授權而定                 | 依各模型權限                            | 依各模型權限                                |

### 音樂

- [Suno 服務條款](https://suno.com/terms) - Pro 與 Premier 使用者受讓 Suno 的權利並可商業利用產出，但僅限經允許下載取得的檔案；免費與 Basic 方案僅限個人、非商業使用。Suno 不保證產出享有著作權，並可能依方案加上浮水印。（2026-09-03 生效；變更係於 [Warner Music 和解](https://www.wmg.com/news/warner-music-group-and-suno-forge-groundbreaking-partnership)之後。）
- [Udio 服務條款](https://www.udio.com/terms-of-service) - 所有產出歸 Udio 及其授權人所有；在 Udio 於 [Universal Music 和解](https://www.universalmusic.com/universal-music-group-and-udio-announce-udios-first-strategic-agreements-for-new-licensed-ai-music-creation-platform/)後轉型為授權平台期間，禁止下載、商業使用及發布至串流平台。（2025-11-12 修訂。）
- [ElevenLabs 服務條款](https://elevenlabs.io/terms-of-use) - 使用者保有產出的權利；免費使用者僅限非商業使用。音樂另有[專屬條款](https://elevenlabs.io/music-terms)，禁止在提示詞中使用藝人姓名、歌名或大量歌詞，且產出不具專屬性。（2026-03-31 更新；音樂條款 2026-05-26。）

### 圖像與影片

- [Midjourney 服務條款](https://docs.midjourney.com/hc/en-us/articles/32083055291277-Terms-of-Service) - 使用者「在適用法律允許的最大範圍內」擁有其圖像，取消訂閱後仍保有；年營收逾 100 萬美元的公司須使用 Pro 或 Mega。圖像預設為公開且可被他人混用，除非使用 Stealth 模式。（2026-05-27 生效。）
- [Leonardo.ai 服務條款](https://leonardo.ai/terms-of-service) - 付費使用者擁有其產出；免費方案的產出歸 Leonardo 所有（§8.7）。公開內容可能被用於訓練 Leonardo 的模型。（2026-01-19 更新。）
- [Runway 服務條款](https://runwayml.com/terms-of-use) - Runway 不主張所有權，也不限制商業使用，但取得永久授權，得以輸入與產出訓練其模型。（2026-09-15 更新。）
- [Adobe 一般條款](https://www.adobe.com/legal/terms.html) - 使用者保有其創作的所有權。[Firefly 智慧財產權補償](https://helpx.adobe.com/legal/product-descriptions/adobe-firefly.html)僅適用於合約有連結至該條款的客戶，且排除合作夥伴模型與測試版功能。禁止移除 Content Credentials。

### 通用模型

- [OpenAI 使用條款](https://openai.com/policies/row-terms-of-use/) - 使用者擁有產出，OpenAI 將其權利（「如有」）讓與使用者；類似的產出可能提供給其他使用者，且產出不得用於開發競爭模型。（2026-01-01 生效。）
- [Google 服務條款](https://policies.google.com/terms) - Google「不會主張」生成內容的所有權；[Gemini API 條款](https://ai.google.dev/gemini-api/terms)另規定 Google 可能為他人生成相同或類似的內容。（分別於 2026-07-30 及 2026-03-23 生效。）

### 開放模型與模型平台

- [Stability AI 社群授權](https://stability.ai/community-license-agreement) - 使用者擁有產出；年營收超過 100 萬美元後，免費授權即終止，且散布時須標示「Powered by Stability AI」。（2024-07-05 更新。）
- [CreativeML Open RAIL-M](https://github.com/CompVis/stable-diffusion/blob/main/LICENSE) - 許多 Stable Diffusion 1.x 模型採用的授權：授權人不主張產出的權利，但其使用限制會隨模型傳遞給任何受分享模型之人。
- [Civitai 服務條款](https://civitai.com/content/tos) - 產出的權利依各模型授權而定；模型頁面上的權限圖示（商業使用、署名、合併）是創作者自行聲明，不得授予超出基礎模型授權的權利。（2026-08-26 修訂。）

## 證明作品在先

發生爭議時，第一個問題往往就是誰先擁有該作品。以下方法記錄的是某個檔案在特定時間已存在。任何一種方法單獨使用，都無法證明誰是創作者或誰擁有權利。

最後查核：2026-09-27。

| 方法                            | 證明檔案於某日前已存在      | 證明創作者                            | 費用                                   | 不經提供者即可驗證                   |
| ------------------------------- | --------------------------- | ------------------------------------- | -------------------------------------- | ------------------------------------ |
| 認證（臺灣）                    | 是，限於公證人所見          | 否                                    | 約新臺幣 500 元（法定基本費用）        | 是，有公開紀錄                       |
| 臺灣存證信函                    | 是，文字內容與寄送日期      | 否                                    | 新臺幣 50 元＋每增一頁 30 元，另加郵資 | 郵局保存副本 3 年                    |
| RFC 3161 時間戳記（如 FreeTSA） | 是                          | 否                                    | 免費（FreeTSA）                        | 是，使用 OpenSSL                     |
| eIDAS 合格時間戳記              | 是，在歐盟具法律推定效力    | 否                                    | 依提供者而異                           | 是                                   |
| OpenTimestamps                  | 是，錨定於 Bitcoin          | 否                                    | 免費                                   | 是                                   |
| 商業錨定服務                    | 是                          | 否                                    | 付費方案或另行報價                     | 視匯出功能而定                       |
| OpenStela                       | 是，每晚錨定於 Arbitrum One | 否                                    | 免費登記                               | 是，使用 Proof Pack 中的 Merkle 證明 |
| C2PA / Content Credentials      | 記錄經簽章的編輯歷程        | 列出簽章者，通常是工具本身            | 免費標準                               | 是，但中繼資料可能被移除             |
| 美國著作權登記                  | 登記生效日                  | 於發行後 5 年內申請者，具表面證據效力 | 45–125 美元                            | 是，有公開紀錄                       |
| 寄信給自己／雲端歷程            | 證明力薄弱                  | 否                                    | 免費                                   | 否                                   |

### 官方紀錄

- [公證法](https://law.moj.gov.tw/LawClass/LawAll.aspx?pcode=B0010010) - 法院公證人或民間公證人可就附有列印本或檔案雜湊值的簽名聲明書辦理認證；經認證的文書推定為真正（[民事訴訟法第 358 條](https://law.moj.gov.tw/LawClass/LawSingle.aspx?pcode=B0010001&flno=358)）。民間公證人依法執行公證職務作成之文書，視為公文書（公證法第 36 條）。認證記錄的是公證人所見，而非誰創作了該作品。
- [存證信函](https://www.post.gov.tw/post/internet/Customer_service/index.jsp?ID=1610075122269) - 中華郵政保存一份相同副本，僅證明各份內容相符及寄送日期。僅限文字、使用中文格式，郵局保存副本三年。
- [美國著作權登記](https://www.copyright.gov/registration/) - 於發行後五年內登記者具表面證據效力（[17 U.S.C. §410(c)](https://www.law.cornell.edu/uscode/text/17/410)）。超過微量的 AI 生成內容必須揭露並排除（[88 FR 16190](https://www.federalregister.gov/documents/2023/03/16/2023-05321/copyright-registration-guidance-works-containing-material-generated-by-artificial-intelligence)）；規費為 [45–125 美元](https://www.copyright.gov/about/fees.html)。
- [臺灣無著作權登記制度（智慧財產局）](https://www.tipo.gov.tw/tw/copyright/692-16449.html) - 臺灣於 1998 年廢除著作權登記；著作人負舉證責任，建議保留創作過程紀錄（[智慧財產局關於舉證的說明](https://www.tipo.gov.tw/tw/copyright/696-21213.html)）。

### 時間戳記

- [RFC 3161](https://www.rfc-editor.org/rfc/rfc3161) - 可信時間戳記的標準：由時間戳記機構（TSA）簽發權杖，將檔案的雜湊值與時間綁定。只有雜湊值會離開使用者的電腦。
- [FreeTSA](https://freetsa.org/index_en.php) - 免費的 RFC 3161 時間戳記機構，可搭配 OpenSSL 使用。須保留原始位元組：重新匯出檔案會改變其雜湊值。
- [eIDAS 第 41 條](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:32014R0910) - 在歐盟，只有_合格_電子時間戳記具有日期正確與資料完整的推定效力；其他時間戳記仍可作為證據提出。
- [OpenTimestamps](https://opentimestamps.org/) - 免費、無須帳號，錨定於 Bitcoin。確認需時數小時；執行 `ots upgrade` 後，證明即可不經日曆伺服器驗證。

### 區塊鏈登記服務

- [Bernstein](https://www.bernstein.io/) - 以 Bitcoin 錨定及合格時間戳記登記設計與草稿的網頁應用程式；付費方案。其行銷用語提及所有權，但時間戳記證明的是存在，而非所有權。
- [OriginStamp](https://originstamp.com/en/timestamp) - 透過 API 提供企業區塊鏈時間戳記服務；價格另洽。
- [OpenStela](https://openstela.io) - AI 角色與作品的免費登記服務；指紋每晚錨定於 Arbitrum One，可下載的 Proof Pack 內含 Merkle 證明。其[服務條款](https://openstela.io/terms)載明登記不構成著作人身分或所有權的證明。_揭露：本清單由 OpenStela 維護。_

### 來源中繼資料

- [C2PA / Content Credentials](https://contentcredentials.org/) - 記錄檔案如何製作與編輯的簽章紀錄，通常由工具自動加入。其列出的是簽章者，不一定是創作者，且[可能被移除](https://spec.c2pa.org/specifications/specifications/2.2/explainer/Explainer.html)；宜搭配獨立的時間戳記使用。

### 效果不佳的方法

- [寄一份副本給自己](https://www.copyright.gov/help/faq/faq-general.html) - 美國著作權局表示，這種「窮人的著作權」沒有法律依據。雲端版本歷程與檔案日期容易遭爭執；僅宜作為輔助證據。
- [WIPO PROOF](https://www.wipo.int/wipoproof/en/) - 已停止服務：自 2022 年 1 月 31 日起不再核發新權杖。既有權杖仍可驗證。

## 作品遭他人抄襲時

最後查核：2026-09-27。

先保全證據：對方察覺後，抄襲內容可能隨時消失。接著使用平台自身的檢舉管道；多數平台即使在美國境外，也依循美國 DMCA 程序。

### 美國：DMCA 通知／取下

- [17 U.S.C. §512](https://www.law.cornell.edu/uscode/text/17/512) - 通知／取下制度的法源。向平台指定代理人發出的通知須包含簽名、著作、侵權內容位置、聯絡資料、善意聲明，以及願負偽證罪責的聲明。
- [Section 512 資源](https://www.copyright.gov/512/) - 美國著作權局的說明摘要，附通知與反通知範本。
- [DMCA 指定代理人名錄](https://dmca.copyright.gov/osp/) - 免費公開查詢平台受理取下通知的窗口。
- [反通知，§512(g)](https://www.law.cornell.edu/uscode/text/17/512#g) - 自己的作品遭誤取下時，提出反通知後，除非主張權利人提起訴訟，內容將於 10 至 14 個工作天內回復。明知不實的通知或反通知，依 [§512(f)](https://www.law.cornell.edu/uscode/text/17/512#f) 須負責任。

### 平台檢舉頁面

- [YouTube 著作權移除](https://support.google.com/youtube/answer/2807622?hl=en) - 透過 YouTube Studio 的網頁表單或電子郵件提出。[Content ID](https://support.google.com/youtube/answer/1311402?hl=en) 須具專屬權利，因此非專屬授權的音樂可能不符資格。
- [TikTok 著作權政策](https://www.tiktok.com/legal/page/global/copyright-policy/en) - 透過線上表單或 App 內檢舉。
- [X 著作權政策](https://help.x.com/en/rules-and-policies/copyright-policy) - 由權利人或其授權代表提出申訴，並設有反通知管道。
- [Instagram 與 Threads 著作權說明](https://help.instagram.com/126382350847838) - Meta 的檢舉表單、反通知說明與重複侵權者政策；[Facebook](https://www.facebook.com/help/1020633957973118) 另提供 Rights Manager 比對功能。
- [Spotify 著作權政策](https://www.spotify.com/us/legal/copyright-policy/) - 線上表單或指定著作權代理人。
- [SoundCloud 著作權檢舉](https://help.soundcloud.com/hc/en-us/articles/4402637577243-How-do-I-report-content-on-SoundCloud-that-infringes-my-copyright) - 檢舉表單、各曲目的檢舉按鈕或電子郵件。
- [DistroKid 取下](https://support.distrokid.com/hc/en-us/articles/360056369674-DMCA-Takedowns-and-Counterclaims) - 適用於由 DistroKid 發行的音樂；其他作品可查看 ℗/© 標示以找出發行商。
- [Etsy 智慧財產權政策](https://www.etsy.com/legal/ip/) - 以 IP Reporting Portal 檢舉商品、商店與影片。
- [Amazon 侵權檢舉](https://www.amazon.com/report/infringement) - 供權利人及其代理人登入後填寫的表單；[Brand Registry](https://sell.amazon.com/blog/brand-registry-requirements) 提供更多執行工具，但須具已註冊或申請中的商標。
- [Civitai DMCA 通知](https://civitai.com/content/dmca-notice) - 取下表單；其服務條款（§12）亦受理電子郵件或郵寄通知。[Suno](https://suno.com/terms) 與 [Udio](https://www.udio.com/terms-of-service) 也在其服務條款中列有 DMCA 代理人。

### 歐盟

- [數位服務法（DSA）第 16 條](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX:32022R2065) - 託管服務須受理任何人以電子方式提出的違法內容通知，包括著作權侵害；第 22 條優先處理「受信任檢舉者」的通知，此身分授予組織而非個人。

### 臺灣

- [著作權法第六章之一（第 90 條之 4 至第 90 條之 12）](https://law.moj.gov.tw/LawClass/LawSingle.aspx?pcode=J0070017&flno=90-4) - 臺灣適用於網路服務提供者的通知／取下制度。提出回復通知後，權利人須於 10 個工作日內提出已起訴的證明，否則內容將回復；通知應記載事項依[實施辦法](https://law.moj.gov.tw/LawClass/LawAll.aspx?pcode=J0070042)規定。
- [智慧財產局著作權爭議調解](https://www.tipo.gov.tw/tw/copyright/709.html) - 智慧財產局受理著作權爭議調解，每件新臺幣 4,000 元；調解採自願，經法院核定的調解成立即終結爭議（[辦法](https://law.moj.gov.tw/LawClass/LawAll.aspx?pcode=J0070020)）。
- [刑事訴訟法第 237 條](https://law.moj.gov.tw/LawClass/LawAll.aspx?pcode=C0010001) - 多數著作權犯罪為告訴乃論，須於知悉犯人之時起六個月內提出告訴。

### 證據保全

- [智慧財產局網路侵權常見問答](https://www.tipo.gov.tw/tw/tipo1/815-1213.html) - 侵權網頁隨時可能變更；應自行保存網頁，或請民間公證人辦理公證。
- [Wayback Machine Save Page Now](https://web.archive.org/save) - 免費的第三方公開網頁快照。Internet Archive 另可[提供宣誓書](https://archive.org/legal/)供法院使用，須付費。
- [法院證據保全](https://law.moj.gov.tw/LawClass/LawAll.aspx?pcode=B0010001) - 依民事訴訟法第 368 條，證據有滅失之虞者，法院得於起訴前或訴訟中保全證據。

## 授權與銷售

最後查核：2026-09-27。

### 自身作品的授權

- [Creative Commons 授權選擇器](https://creativecommons.org/chooser/) - 回答關於署名、商業使用與改作的問題，即可選出授權條款。
- [CC 授權與生成式 AI](https://creativecommons.org/2023/08/18/understanding-cc-licenses-and-generative-ai/) - 以 AI 工具製作的作品可以採用 CC 授權；人類創作性低時，CC 建議使用 CC0。另見 CC 的 [2026 年指引](https://creativecommons.org/2026/09/03/guidance-on-using-cc-licenses-in-an-ai-ecosystem/)。
- [CC0](https://creativecommons.org/public-domain/cc0/) - 在法律允許範圍內拋棄所有權利。

### 模型授權與產出

- [Responsible AI Licenses（RAIL）](https://www.licenses.ai/) - 許多圖像模型採用的行為使用授權系列；使用限制會延續至衍生模型。
- [FLUX.1 dev 非商業授權](https://github.com/black-forest-labs/flux/blob/main/model_licenses/LICENSE-FLUX1-dev) - 模型限非商業使用，但產出可商業利用，惟不得用於訓練競爭模型。
- [Llama 4 社群授權](https://github.com/meta-llama/llama-models/blob/main/models/llama4/LICENSE) - 不主張產出的所有權；以 Llama 產出訓練並散布的模型，名稱須以「Llama」開頭。

### 權利讓與

- [17 U.S.C. §204(a)](https://www.law.cornell.edu/uscode/text/17/204) - 在美國，著作權讓與須以經簽名的書面為之始生效力；讓與可向著作權局[辦理登錄](https://www.copyright.gov/recordation/)。
- [著作權法第 36 條至第 37 條](https://law.moj.gov.tw/LawClass/LawSingle.aspx?pcode=J0070017&flno=36) - 讓與或授權約定不明的部分，推定為未讓與；專屬被授權人得以自己名義提起訴訟。
- [智慧財產局契約範本](https://www.tipo.gov.tw/tw/copyright/719-19274.html) - 免費的臺灣契約範本，包括委託創作及授權圖案用於商品。

### AI 作品的銷售平台

- [Adobe Stock](https://helpx.adobe.com/stock/contributor/help/generative-ai-content.html) - 接受經標示的 AI 生成內容；提示詞不得指名藝術家、真實人物或虛構角色。
- [Shutterstock](https://submit.shutterstock.com/help/en/articles/10594622-content-policy-updates-ai-generated-content) - 不接受上傳 AI 生成內容。[Getty Images](https://contributors.gettyimages.com/article/9146)、[iStock](https://www.istockphoto.com/legal/ai-free-imagery-policy) 與 [Pond5](https://www.pond5.com/help/en/articles/10086182-does-pond5-allow-ai-generated-content-for-licensing) 也不接受。
- [Etsy](https://www.etsy.com/seller-handbook/article/1275449912004) - 允許由賣家下提示詞的 AI 創作，但商品頁須揭露使用 AI。
- [Bandcamp](https://blog.bandcamp.com/2026/01/13/keeping-bandcamp-human/) - 自 2026 年 1 月起，不允許全部或主要由 AI 生成的音樂。

### 音樂發行與串流

- [DistroKid](https://support.distrokid.com/hc/en-us/articles/41182362733715-Can-I-Upload-Music-Made-With-AI-Tools-to-DistroKid) - 接受以 AI 工具製作、且上傳者擁有全部權利的音樂；要求填寫會顯示於 Spotify、Apple Music 與 YouTube 的 [AI credits](https://support.distrokid.com/hc/en-us/articles/50784235803411-What-Are-AI-Credits)。
- [TuneCore](https://support.tunecore.com/hc/en-us/articles/46914166185236-TuneCore-s-GenAI-Music-Content-Framework) - 僅發行以完全取得授權之資料訓練的模型所產生的 AI 音樂。
- [CD Baby](https://support.cdbaby.com/hc/en-us/articles/23638450756237-Understanding-Production-Sounds) - 不接受任何 AI 生成內容，部分使用 AI 者亦同。
- [Spotify AI 保護措施](https://newsroom.spotify.com/2025-09-25/spotify-strengthens-ai-protections/) - 冒用藝人身分須經該藝人授權，垃圾內容過濾器針對大量上傳，AI 使用情形會揭露於演職員資訊；[AI Persona 徽章](https://newsroom.spotify.com/2026-08-11/ai-persona-badges-transparency/)用以標示 AI 藝人身分。
- [Deezer AI 標籤](https://newsroom-deezer.com/2025/06/deezer-launches-worlds-first-ai-tagging-system-for-music-streaming/) - 為含完全 AI 生成曲目的專輯加上標籤，並將其排除於推薦之外。

## 標示與透明度規範

最後查核：2026-09-27。

多數規範將標示義務課予 AI 提供者與平台，但也有若干規範及於發布內容的人。

### 法規

- [EU AI Act 第 50 條](https://ai-act-service-desk.ec.europa.eu/en/ai-act/article-50) - 自 2026 年 8 月 2 日起適用：提供者須以機器可讀方式標示 AI 產出，深度偽造內容須揭露，明顯屬藝術或諷刺性質的作品義務較輕。依 [Digital Omnibus](https://eur-lex.europa.eu/eli/reg/2026/1744/oj/eng)，已上市的系統於 2026 年 12 月 2 日前完成標示即可。
- [歐盟 AI 生成內容行為準則](https://digital-strategy.ec.europa.eu/en/policies/code-practice-ai-generated-content) - 關於如何標記與標示 AI 產出的自願性準則，並有執委會[指引](https://digital-strategy.ec.europa.eu/en/policies/guidelines-ai-transparency-obligations)及免費的[歐盟標示圖示](https://digital-strategy.ec.europa.eu/en/policies/eu-icons-labelling-ai-generated-content)。
- [中國：人工智能生成合成內容標識辦法](https://www.cac.gov.cn/2025-03/14/c_1743654684782215.htm) - 自 2025 年 9 月 1 日起施行，並搭配強制性國家標準 GB 45438-2025：須有顯式標識與中繼資料標識，發布 AI 內容的使用者須主動聲明，且不得移除標識。
- [韓國：AI 透明度指引](https://www.msit.go.kr/eng/bbs/view.do?sCode=eng&mId=4&bbsSeqNo=42&nttSeqNo=1215) - 依 2026 年 1 月施行的 AI 基本法，AI 產出須標示，擬真的深度偽造內容須明確標記。
- [加州 AI 透明法（AB 853）](https://leginfo.legislature.ca.gov/faces/billNavClient.xhtml?bill_id=202520260AB853) - 自 2026 年 8 月 2 日起施行：大型 AI 提供者須為 AI 圖像、影片與音訊提供顯性與隱性揭露，以及免費的偵測工具。政治廣告另有[專屬揭露規定](https://leginfo.legislature.ca.gov/faces/billNavClient.xhtml?bill_id=202320240AB2355)。
- [人工智慧基本法](https://law.moj.gov.tw/LawClass/LawAll.aspx?pcode=H0160093) - 自 2026 年 1 月施行；訂有透明原則，但未直接課予創作者標示義務。另依[詐欺犯罪危害防制條例第 31 條](https://law.moj.gov.tw/LawClass/LawAll.aspx?pcode=D0080226)，大型廣告平台須揭露廣告是否使用深度偽造或 AI 生成的人物影像。
- [FTC Operation AI Comply](https://www.ftc.gov/news-events/news/press-releases/2024/09/ftc-announces-crackdown-deceptive-ai-claims-schemes) - 「現行法律沒有 AI 豁免」：關於 AI 產品的欺罔宣稱，與其他宣稱一樣受到追究。

### 平台規範

- [YouTube：經變造或合成的內容](https://support.google.com/youtube/answer/14328491?hl=en) - 經實質變造或合成的擬真內容須揭露；明顯不真實的內容與輕微編輯不在此限。
- [TikTok：AI 生成內容](https://www.tiktok.com/support/faq_detail?id=7636670084747893268) - 擬真的 AI 內容須加標示；附有 C2PA 憑證的內容會自動標示，且標示無法移除。
- [Meta：AI 內容標示](https://transparency.meta.com/governance/tracking-impact/labeling-ai-content/) - Facebook、Instagram 與 Threads 上的「AI 資訊」標籤，依偵測到的訊號或發布者自行揭露而加上。
- [Amazon KDP 內容指引](https://kdp.amazon.com/en_US/help/topic/G200672390) - AI 生成的文字、圖像與翻譯須揭露，即使經大幅編輯亦同；以 AI 輔助編輯則無須揭露。
- [Steam 內容問卷](https://partner.steamgames.com/doc/gettingstarted/contentsurvey) - 開發者須說明遊戲中預先生成及即時生成的 AI 內容。

## 延伸閱讀

最後查核：2026-09-27。

### 報告

- [WIPO：智慧財產與前沿科技](https://www.wipo.int/en/web/frontier-technologies) - WIPO 關於 AI 與智慧財產對話的專區，附有簡短的[生成式 AI 概況說明](https://www.wipo.int/export/sites/www/about-ip/en/frontier_technologies/pdf/generative-ai-factsheet.pdf)。
- [EUIPO：從著作權角度看生成式 AI](https://www.euipo.europa.eu/en/publications/genai-from-a-copyright-perspective-2025) - 2025 年研究，探討歐盟法下的訓練資料、排除聲明、產出及對創作者的影響。
- [OECD：以爬取資料訓練之 AI 的智慧財產議題](https://www.oecd.org/en/publications/intellectual-property-issues-in-artificial-intelligence-trained-on-scraped-data_d5241a23-en.html) - 2025 年政策文件，探討資料爬取及其涉及的著作權、資料庫與營業秘密議題。

### 案件追蹤

- [BakerHostetler AI 案件追蹤](https://www.bakerlaw.com/services/artificial-intelligence-ai/case-tracker-artificial-intelligence-copyrights-and-class-actions/) - 美國生成式 AI 著作權案件的進度與重要書狀。
- [Chat GPT Is Eating the World](https://chatgptiseatingtheworld.com/aicopyrightcasetracker/) - 獨立追蹤針對 AI 公司之著作權訴訟，附美國案件地圖。
- [AI 訴訟資料庫](https://blogs.gwu.edu/law-eti/ai-litigation-database/) - GW Law 建置、可搜尋的 AI 訴訟綜合資料庫。

### 論文

- [Authors and Machines](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3233885) - Ginsburg 與 Budiardjo 探討機器生成產出的著作人是程式設計者、使用者，或無人。
- [How Generative AI Turns Copyright Upside Down](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4517702) - Lemley 說明生成式 AI 為何衝擊實質近似判斷，並使創作價值轉向提示詞。
- [Talkin' 'Bout AI Generation](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4523551) - Lee、Cooper 與 Grimmelmann 將 AI 供應鏈的各階段對應到著作權法理。
- [Copyright Safety for Generative AI](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4438593) - Sag 論訓練屬非表現性利用，以及模型記憶的風險。

### 創作者組織

- [Authors Guild 的 AI 專區](https://authorsguild.org/advocacy/artificial-intelligence/) - 最佳實務、契約範本條款，以及 [Human Authored](https://authorsguild.org/human-authored/) 認證。
- [Society of Authors：實務步驟](https://societyofauthors.org/2025/06/26/artificial-intelligence-practical-steps-for-members/) - 給作者的實務建議，說明如何保護作品免遭 AI 利用。
- [Musicians' Union：AI 與音樂產業](https://musiciansunion.org.uk/all-campaigns/artificial-intelligence-and-the-music-industry) - 關於音樂人同意、署名與報酬的倡議專區。
- [Concept Art Association 倡議](https://www.conceptartassociation.com/advocacy) - 契約條款範例，避免委託創作的美術作品被納入 AI 資料集。
- [文化部生成式 AI 參考指引](https://www.moc.gov.tw/News.aspx?n=9149&sms=16053) - 不具拘束力的指引，供藝術工作者參考訓練資料、風格模仿與著作權風險等議題。

## 貢獻

歡迎提供更正與補充——請見 [CONTRIBUTING.md](CONTRIBUTING.md)。每個項目都必須附上來源。
