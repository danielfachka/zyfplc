百度搜索引擎的自动抓取程序，主要用于访问互联网网页、图片、视频等内容并建立索引数据库，以支持用户检索服务。其抓取机制包含补充数据区和主检索区的分层处理，抓取策略结合深度优先与权重优先算法，优先抓取高质量或外链较多的页面，并通过站点地图引导路径。该程序支持Robots协议与Meta标签控制权限（特定商务爬虫除外），针对不同产品线设有专用爬虫标识（如Baiduspider-image、Baiduspider-video等） 。百度蜘蛛通过分析网站内链布局和外链数量计算页面权重，动态调整抓取频率以适应服务器负载及网站更新节奏，持续更新的站点会获得更高抓取频次。其访问结果通过HTTP状态代码（如200、301、404）反馈，并采用DNS反查机制验证身份以防止冒充 。优化策略包括优化URL结构、提升加载速度、提交站点地图等，以实现高效收录。
孪鞘窒比弦诓安履叛刻眯挛吹殉屡

状态代码

成功
200 正常;请求已完成。
201 正常;紧接POST命令。
202 正常;已接受用于处理，但处理尚未完成。
203 正常;部分信息 — 返回的信息只是一部分。
204 正常;无响应 — 已接收请求，但不存在要回送的信息。
重定向
301 永久重定向 — 请求的数据具有新的位置且更改是永久的。
302 暂时重定向 — 请求的数据临时具有不同URI。
303 请参阅其它 — 可在另一URI下找到对请求的响应，且应使用 GET方法检索此响应。
304 未修改 — 未按预期修改文档。
305 使用代理 — 必须通过位置字段中提供的代理来访问请求的资源。
306 未使用 — 不再使用;保留此代码以便将来使用。
代码中的错误
400 错误请求 — 请求中有语法问题，或不能满足请求。
401 未授权 — 未授权客户机访问数据。
402 需要付款 — 表示计费系统已有效。
403 禁止— 即使有授权也不需要访问。
404 找不到—服务器找不到给予的资源;文档不存在。
406 不可接受 — 根据此请求中所发送的“接受”标题，此请求所标识的资源只能生成内容特征为“不可接受”的响应实体。
407 代理认证请求 — 客户机首先必须使用代理认证自身。
410 请求的网页不存在(永久);
415 介质类型不受支持 —服务器拒绝服务请求，因为不支持请求实体的格式。
500 内部错误 — 因为意外情况，服务器不能完成请求。
501 未执行 —服务器不支持请求的工具。
502 错误网关—服务器接收到来自上游服务器的无效响应。
503 无法获得服务 — 由于临时过载或维护，服务器无法处理请求。

问题解答

Baiduspider对一个网站服务器造成的访问压力如何？
答：Baiduspider会自动根据服务器的负载能力调节访问密度。在连续访问一段时间后，Baiduspider会暂停一会，以防止增大服务器的访问压力。所以在一般情况下，Baiduspider对您网站的服务器不会造成过大的压力。
为什么Baiduspider不停的抓取我的网站？
答：或许您的网站权重高或者对于您网站上新产生的或者持续、有规律更新的页面，Baiduspider会持续抓取。此外，您也可以检查网站访问日志中Baiduspider的访问是否正常，以防止有人恶意冒充Baiduspider来频繁抓取您的网站。 如果您发现Baiduspider非正常抓取您的网站，请反馈至，并请尽量给出Baiduspider对贵站的访问日志，以便于我们跟踪处理。
我不想我的网站被Baiduspider访问，我该怎么做？
答：Baiduspider遵守互联网robots协议。您可以利用robots.txt文件完全禁止Baiduspider访问您的网站，或者禁止Baiduspider访问您网站上的部分文件。 注意：禁止Baiduspider访问您的网站，将使您的网站上的网页，在百度搜索引擎以及所有百度提供搜索引擎服务的搜索引擎中无法被搜索到。
ps:关于robots.txt的写作方法，请参看我们的介绍：robots.txt写作方法
为什么我的网站已经加了robots.txt，还能在百度搜索出来？
答：因为搜索引擎索引数据库的更新需要时间。虽然Baiduspider已经停止访问您网站上的网页，但百度搜索引擎数据库中已经建立的网页索引信息，可能需要二至四周才会清除。 另外也请检查您的robots配置是否正确。
我希望我的网站内容被百度索引但不被保存快照，我该怎么做？
答：Baiduspider遵守互联网metarobots协议。您可以利用网页meta的设置，使百度显示只对该网页建索引，但并不在搜索结果中显示该网页的快照。
和robots的更新一样，因为搜索引擎索引数据库的更新需要时间，所以虽然您已经在网页中通过meta禁止了百度在搜索结果中显示该网页的快照，但百度搜索引擎数据库中如果已经建立了网页索引信息，可能需要二至四周才会在线上生效。
百度蜘蛛在robots.txt中的名字是什么？
答：“Baiduspider” 首字母B大写，其余为小写。
Baiduspider多长时间之后会重新抓取我的网页？
答：百度搜索引擎每周更新，网页视重要性有不同的更新率，频率在几天至一月之间，Baiduspider会重新访问和更新一个网页。
Baiduspider抓取造成的带宽堵塞？
答：Baiduspider的正常抓取并不会造成您网站的带宽堵塞，造成此现象可能是由于有人冒充baidu的spider恶意抓取。如果您发现有名为Baiduspider的agent抓取并且造成带宽堵塞，请尽快和我们联系。您可以将信息反馈至百度网页投诉中心，如果能够提供您网站该时段的访问日志将更加有利于我们的分析。

群发外链
对应名称
产品名称 对应user-agent
网页搜索 Baiduspider
无线搜索 Baiduspider
图片搜索 Baiduspider-image
视频搜索 Baiduspider-video
新闻搜索 Baiduspider-news
百度搜藏 Baiduspider-favo
百度联盟Baiduspider-cpro
竞价蜘蛛Baiduspider-sfkr

https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md?/447=466
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md?/318=050
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md?/544=790
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md?/646=356
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md?/816=755
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md?/578=523
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md?/378=533
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md?/911=899
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md?/244=896
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md?/817=921
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md?/469=199
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md?/467=533
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md?/033=249
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md?/588=022
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md?/132=601
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md?/801=700
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md?/911=114
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md?/912=643
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md?/733=577
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md?/194=795
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md?/689=801
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md?/947=830
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md?/831=215
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md?/044=383
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md?/519=375
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md?/481=214
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md?/820=509
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md?/325=781
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md?/003=113
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/684=028
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/145=306
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/226=396
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/932=598
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/559=027
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/141=832
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/683=044
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/770=265
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/115=505
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/500=615
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/837=837
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/359=167
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/683=350
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/722=607
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/050=933
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/155=004
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/871=104
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/330=949
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/052=551
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/276=730
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/166=726
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/056=494
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/771=832
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/785=499
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/276=593
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/273=774
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/849=505
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/842=610
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/005=337
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/994=596
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/616=559
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/782=594
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/385=061
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/295=730
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/700=807
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/572=465
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/363=918
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/327=338
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/550=993
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/938=151
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/716=327
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/948=618
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/371=504
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/509=671
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/115=593
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/882=728
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/832=255
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/105=950
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/505=984
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b?/387=050
https://github.com/schowffer/nmghjj/commit/67ac9b2aa199f3c000e0b333678b0a6d5e15427b
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/409=372
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/082=619
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/395=404
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/103=737
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/959=404
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/303=173
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/628=539
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/658=426
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/204=214
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/317=418
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/284=919
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/848=981
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/659=732
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/182=382
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/725=731
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/326=982
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/518=250
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/637=062
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/727=752
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/525=202
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/629=317
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/749=964
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/404=317
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/515=326
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/547=730
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/417=397
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/446=610
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/941=164
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/071=602
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/335=519
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/053=931
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/447=821
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/941=941
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/058=618
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/114=335
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/457=275
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/422=982
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/199=356
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/038=916
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/922=240
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/926=594
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/364=478
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/144=755
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/411=033
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/407=793
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/241=466
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/574=571
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/805=799
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/798=078
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/395=396
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/849=495
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/403=536
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/536=315
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/971=394
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/536=640
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/726=850
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/739=860
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/748=962
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/959=951
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/614=394
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/528=171
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/192=082
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/759=204
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/628=536
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/395=417
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/425=515
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/636=971
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/406=293
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/405=628
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/537=848
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/063=515
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/404=751
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/345=356
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/759=658
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/446=438
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/558=436
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/306=805
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/688=577
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/800=755
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/911=107
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/654=687
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/611=155
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/682=717
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/578=801
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/144=367
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/467=906
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/245=499
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/201=688
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/367=024
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/023=477
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/659=955
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/345=134
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/136=918
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/756=134
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/795=576
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/134=967
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/255=159
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/500=463
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140?/255=245
https://github.com/schowffer/nmghjj/commit/d461431af2ef2a5c6097b6692fbb45b040931140
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/023=133
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/423=290
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/244=857
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/780=144
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/477=579
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/467=134
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/245=259
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/817=588
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/366=246
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/133=918
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/790=028
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/134=240
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/215=251
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/916=590
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/029=199
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/156=917
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/601=700
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/578=533
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/688=466
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/812=466
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/685=927
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/134=356
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/687=922
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/878=469
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/699=499
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/690=258
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/467=133
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/244=350
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/800=570
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/289=799
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/892=799
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/044=700
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/476=134
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/834=255
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/427=139
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/925=912
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/352=462
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/134=755
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/689=690
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/956=822
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/285=394
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/517=061
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/316=194
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/658=205
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/051=284
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/951=840
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/073=759
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/103=172
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/594=739
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/092=286
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/669=507
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/124=847
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/597=002
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/385=225
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/969=619
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/618=002
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/113=983
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/224=618
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/830=374
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/718=036
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/446=830
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/446=668
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/436=307
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/265=668
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/380=426
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/945=992
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/669=982
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/470=393
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/016=831
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/525=498
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/927=793
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/676=463
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/193=144
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/264=649
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/191=800
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/907=690
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/922=039
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/354=466
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/134=560
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/789=244
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/236=366
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/923=580
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/688=392
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/401=573
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/028=584
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/356=803
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/132=366
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/914=790
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/912=700
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/144=466
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/248=870
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/901=355
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/345=649
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/350=472
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/924=915
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/255=755
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/700=680
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/920=917
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137?/800=579
https://github.com/schowffer/nmghjj/commit/c0c6ff93abc1d2dab3cd7914f5347040dc072137
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/688=506
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/970=801
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/922=800
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/147=361
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/644=699
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/912=808
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/801=801
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/700=805
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/178=150
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/790=572
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/890=799
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/922=033
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/356=155
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/124=794
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/289=717
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/877=912
