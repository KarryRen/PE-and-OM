# Review: Platform Economics and Online Market

> 2025 年 M3 平台经济学复习笔记。基本题型只有不超过 10 个大题目，没有太复杂的证明，核心是在对知识点的理解和背诵上，也有对基本模型的拓展应用，可能类似于作业的题目，但不会有从 0 开始的证明题目。
>
> 接收到学长之前的考试经验，平台经济学的考试核心在于对概念的理解和记忆，一些比较复杂的推导在考试中并不要求。因此复习策略比较简单，就是把 PPT 全部梳理一遍，将其中的核心概念进行列举并反复记忆。同时结合学长提供的记忆单进行背诵。
>
> 整体来说这门课包括以下几块的内容，每天按照进度不断往后推（一天看四个 PPT）



## 1. Introduction

### 1.1 Definations

Platform brings together **different types of users** to enable economic or social interaction. A platform provides a way for two parties to enter into **mutually beneficial exchange or transaction**, platforms are matchmakers.

### 1.2 **Why are platforms taking over?** 

**Reason 1: network effects**

Platforms leverage network effects. Network effects mean that a user will pay more to connect to a larger network. Network effects create very significant inequality in sales and profits (**Winner-takes-most world**).

**Reason 2: Platforms usually have fewer employees and less fixed investment than traditional companies**

**Reason n: platform strength**

- **The focus is external**: A platform tries to bring together as many as possible from both (or all) sides, match them and create transactions. 
- Platforms disrupt traditional business

### 1.3 Role of platforms

**Four major roles of platforms:**

- **dealer**: buy from providers and resell to final consumers, brings together sellers and buyers and provides a substitute of directed trade (decentralized market). Uber, 滴滴, 高德, 亚马逊自营, Apple’s iTunes music store
- **pure platform operator**: provide platforms to allow sellers and buyers to interact. 购物网站, Airbnb, eBay, Amazon
- **infomediary**: an information gatekeeper which provides consumers with better information. 微博, 小红书
- **trusted third-party**: a certification agent which reveals product or reliability information. 支付宝, 安全认证

**How to set price ?**

A platform may collect from both sides (Airbnb)  or Collect from one side and subsidize the other (Amex). 定价的框架如下

<img src="./Final-Review-Note.assets/1.1.png" alt="1.1" style="zoom:25%;" />

### 1.4 Value of Platforms

**A simple model**

$v_H > c_H > v_L > c_L$ 的假设下画一个相交图，$v_L$ 和 $c_H$ 遇到后是无法交易的。Inefficiency comes from the matching friction (transaction cost)。对 Buyer 设定一个平台销售价格 $p_B$ 对 Seller 设定一个平台收购价格 $p_S$。将 $c_H$ 和 $v_L$ 赶出市场：$v_H - p_B \ge \frac{v_H - c_H}{2}$，$p_S - c_L \ge \frac{v_L - c_L}{2}$，同时又要保证 $p_B$ 尽可能高，$p_S$ 尽可能低，进而 $p_B = \frac{v_H + c_H}{2}$, $p_S = \frac{v_L + c_L}{2}$.  这样 $v_L$ 和 $c_H$ 都会推出市场，因为 $v_L-p_B<0$ 和 $p_S - c_H < 0$。这样只有 $v_H$ 和 $c_L$ 以及平台的交易中，达到了最优解，平台分利。

A platform that operates centralized exchanges may improve efficiency by sorting different types of participants.

**Further**

$v_H > v_L > c_H > c_L$ 本身就是最优均衡了，引入平台后 $v_L$ 和 $c_H$ 仍然会在平台下自由交易，这是和上面最大的区别，平台引入不会带来新的价值提升。

### 1.4 Dealer versus pure platform operators

**Model**

两种假设的模型推导下，得到的是相同的结果，profits 是 $\frac{1}{27}$。

Under our specification of uniform distribution, **a dealer platform and a pure platform operator obtain the same profits.** Moreover, the **optimal bid-ask spread (dealer) is equal to the transaction fee (pure platform operator)** and the trade volumes are the same.

但是这个结果并不是 General 的，是因为我们假设的均匀分布造成的。

**Conclusion**

哪种模式的利润或者销售量高是不确定的，平台可以根据自己的阶段转换角色

- If the platform acts as a dealer, trade is socially insufficient as the platform exerts monopoly power on both sides.
- If the platform acts as pure platform operator, sellers exert monopoly power over buyers, which yields high price but also high seller participation.
- In general, it is ambiguous under which role the platform makes higher profits and the transaction volumes are higher.

当然也有一些其他的因素导致 platform 选择的模式不同

- inventory **cost** of the platform,
- information **processing cost** of the platform,
- Information **asymmetry** between sellers and the platform



## 2. Network Effect

基本的概念要十分清楚，这也是平台的第一个基本属性

平台的三个均衡点是怎么转变的，是怎么推出来的，哪一个是稳定的，哪一个是不稳定的，要回分析



## 3. Platform Pricing

Two-sided 垄断, registration fees 是很关键的, 推导出来的结果需要记住

鸡蛋问题



## 4. Platform Competition

平台竞争来进行推导



## 5. Platform Launch

破解企鹅问题



## 6. Online Reputation

GTS 的例子很重要

以及怎么证明 Reputation 的因果关系很重要，三种方式，可能现场出一个其他的例子来进行

出现了设计问题，该如何一一应对解决



## 7. Position Auction

First Price 和 Second Price 之间有什么区别，怎么样化解，谷歌的 AdWords



## 8. Recommender System

2 种推荐方法，必须要十分清楚定义



## 9. Sharing Economy

