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

### 2.1 Introduction

**Network effects**, or network externalities are said to exist when the benefit that a consumer derives from owning a product increases when the number of other consumers of the product increases. 当拥有某种产品的其他消费者数量增加时，消费者从该产品中获得的效用也随之增加，也就是说个人获得的效用不仅取决于平台，还取决于使用平台的人数。

**Two types of network effects:**

- **Direct**: buyers form a network of users **who communicate with each other**. 我用了，会直接联系其他人一起用
  - Phones, Emails, Fax Machines, Operating Systems
  - DVD Players, Social Media, E-commerce and Games
- **Indirect**: the number of buyers of a good stimulates production of goods (supply side) that enhance the value of initial product. 买家多了 ⇒ 买家就会更多⇒ 买家获得更大效用
  - **Operating Systems:** more Windows users ⇒ more firms develop software ⇒ higher utility for Windows users. 
  - **Payment Cards:** 用的人多的话，Pos 机就多，用的人的效用就会很增加
  - **Shopping Malls**: more shoppers ⇒ more stores in the mall ⇒ higher utility to go there.
  - <font color="red">**Dating Agencies:** more males ⇒ higher male to female ratio ⇒ lower utility for males. (Negative)</font>

**Critical Mass**

The required network size for the network to take off. After reaching a certain scale, i.e. **critical mass**, the value offered by the network becomes really high for one or more user classes.

<img src="./Final-Review-Note.assets/2.1.png" alt="2.1 " style="zoom:33%;" />

In practice, predicting the critical mass is very difficult:

- Diffusion within vs. across groups – targeting issue (不同的目标结果不同)
- Benefits from the size of the network – depends on product/service (不同内容效果不同)
- Competition from other networks/platforms – standard wars (竞争对手)

### 2.2 Demand Curve

和一般的需求函数可能只取决于所使用东西本身的质量不同，Network Effect 的需求曲线需要考虑使用的人数。How to create a demand curve when consumer WTP depends on how many people are using the product/service?

**Demand Curve without Network Effect**

<img src="./Final-Review-Note.assets/2.2.png" alt="2.2" style="zoom:30%;" />

**Demand Curve with Network Effect**

核心在于对 Utility 方程的重新定义，过程再次不再说明，直接给出结果 $p=100f(1-f)$ 和后续分析：

<img src="./Final-Review-Note.assets/2.3.png" alt="2.3 " style="zoom:40%;" />

There is always a Nash equilibrium, in which nobody purchases the fax machine.（所有人都不参与，本身就是一个 Nash 均衡）；

在 Price 不为 0 的情况下不可能所有人都参与进来，也就是说 $f \ != 1$。

Price 在 0 和 1 之间的时候有三个均衡点，两边的点是稳定的，中间的点不稳定很容易向左右两边滑落

<img src="./Final-Review-Note.assets/2.4.png" alt="2.4 " style="zoom:30%;" />

关于均衡点 2：

- Given a price, marginal individual’s WTP is higher than the price when the network size is in between $f_- (p)$ and $f_+ (p)$
- Individuals whose WTP is above the price will purchase, which forces the network size to converge to the eq’m 3.
- Similarly, if the network size is lower than $f_- (p)$ or higher than $f_+ (p)$, marginal individual’s WTP is lower than the price, which discourage customers to purchase.
- Conversely**, the zero-demand and high-demand Nash equilibria are stable**: after a small perturbation (or even a large one, here), the industry goes back to the initial equilibrium.

上述分析可以得到 Critical Mass:

- Threshold $f_- (p)$ is usually thought of as the **critical mass** of buyers which leads to the buildup of the network.
- Once the monopoly has reached this critical mass, the snowball starts rolling (in the right direction), and consumers demand converges to the high-demand equilibrium $f_+ (p)$.
- Sometimes, it may take a lot of time to reach the critical mass. Example: Fax machines in the U.S.

Solve the Optimal Price:

$Π(f)=P(f)×(100f)=10^4 f^2 (1 -f).$

This yields a price $p=100×2/9=200/9$ and profits $Π=4×10^4/27$.

**Which Equilibrium to Reach?**

平台肯定希望到达均衡点 3，但是这取决于很多的因素，不一定是能够自然达到的。However, as a company, you can create an **external “shock**” to the system in order to shift from one equilibrium to another. 后面要多多讨论公司的策略。

Firm’s Strategies: (这些 Strategies 都是很 make sense 很容易被想到的)

- **Penetration pricing / introductory pricing**: Set a low price until you reach the critical mass. 
- **Price discrimination**: give away your products to some consumers (say, households), and make other consumers (say, businesses) pay. 
- **Pirated software.** 盗版软件
- **Government intervention** is necessary sometimes to rule out the zero-demand equilibrium.

After Reaching Critical Mass

Once we’ve reached a critical mass, we are in a good position. But we might also have to work hard to keep it. 

### 2.3 Path Dependence

**If there is a better product, it may not actually win**, especially if it’s a bit late getting started. The eventual outcome may depend crucially on a small number of initial adoptions. **History** can play a big role.

VHS 的胜利是网络效应主导标准战争的经典案例。Ohashi 的模型表明，尽管 Betamax 在非网络因素（如音质）上占优，但 VHS 通过内容生态、价格策略和开放合作，放大了网络效应的权重（*ω*），最终突破临界质量。这一案例揭示了平台经济中“连接价值”对“产品价值”的超越，并为现代技术标准竞争提供了理论参考。



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

