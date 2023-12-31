**词汇表修订会议记录 - 5**

***日期***：2023.12.1

***目标***：

***待讨论事项***：

|        英文         |       建议译法        |                             释义                             |     结论     |   类别   |
| :-----------------: | :-------------------: | :----------------------------------------------------------: | :----------: | :------: |
|       oracle        | 预言机；断言机;谕言机 |          为一个智能合约提供合约外部的信息的参与者。          |    （-）     | 智能合约 |
| stuck funds problem |     资金滞留问题      | 因为有意或无意的原因，资金以 HTLC 的形式在通道内长期滞留，既不结算，也不取消。 | 资金滞留问题 | 闪电网络 |
| multipart payments  |     多路径支付；      | 将一笔支付切分为更小额度的多个部分，尝试使用多条有差异的路径分发（这些路径可能有一部分是相同的）。 |  多路径支付  | 闪电网络 |
|   block template    |  区块模板；区块样板   | 作为挖矿迭代运算基础的数据，形式上是一个区块、包含有效的比特币交易，需要插入无意义的数据以求得有效的工作量证明。 |   区块模板   |   挖矿   |
|   legacy outputs    |      传统输出；       |                专指未使用隔离见证技术的输出。                |              |   交易   |
|    dual funding     |  双向注资；对向注资   |           形成通道的双方都为这条通道提供资金输入。           |   双向注资   | 闪电网络 |
|    malleability     |       熔融性；        | 因为输入脚本可以被第三方改变而造成相同含义的交易可能产生多个 txid 的问题。 |    熔融性    |   交易   |

**笔记：**

1. 增加词条 oracle，但指出可以不翻译，以及各翻译的理由。“预言机” 可能脱谬于 “谕言机”；“断言机” 可能更准确。
2. “block template” 取通行翻译 “区块模板”，两个竞争翻译的字面信息差不多。
3. “stuck funds problem” 翻译 “资金滞留问题” 没有异议。
4. “multipart payments”与 “multipath payments” 基本可互用，“多路径支付” 信息更多。
5. “dual funding” 翻译成 “双向注资” 无异议，与 “单向注资” 相对，提供了足够多的信息。
6. “malleability” 及其动词形式往 “熔融”、“熔铸” 的方向翻译，相比其它翻译已足够好。
7. “legacy outputs” 难以翻译。搁置。