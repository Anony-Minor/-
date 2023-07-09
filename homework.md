<!-- cx热统作业 电子版 -->

### 3.15 

1.1，1.2，1.3，1.4，1.5，1.6

#### 1.1
解：
理想气体物态方程 $pV=nRT$，代入定义即得
$$ \alpha = \frac1V \left( \frac{\partial V}{\partial T} \right)_p = \frac1V \frac{nR}{p} = \frac1T $$
$$ \beta = \frac1p \left( \frac{\partial p}{\partial T} \right)_V = \frac1p \frac{nR}{V} = \frac1T $$
$$ \kappa_T = -\frac1V \left( \frac{\partial V}{\partial p} \right)_T = \frac1V \frac{nRT}{p^2} = \frac1p $$

#### 1.2
证明：
由于 $V=V(p,T)$，有全微分
$$ \mathrm{d}V = \left( \frac{\partial V}{\partial T} \right)_p \mathrm{d}T + \left( \frac{\partial V}{\partial p} \right)_T \mathrm{d}p $$
又由于
$$ \alpha = \frac1V \left( \frac{\partial V}{\partial T} \right)_p ,\quad 
\kappa_T = -\frac1V \left( \frac{\partial V}{\partial p} \right)_T $$
故
$$ \frac{\mathrm{d}V}{V} = \alpha \mathrm{d}T - \kappa_T \mathrm{d}p $$
积分即得
$$ \ln V = \int (\alpha \mathrm{d}T - \kappa_T \mathrm{d}p) $$

若 $\alpha = \frac1T, \kappa_T = \frac1p$，则
$$ \ln V = \int (\alpha \mathrm{d}T - \kappa_T \mathrm{d}p) = \ln V = \int \left(\frac1T \mathrm{d}T - \frac1p \mathrm{d}p \right) = \ln T - \ln p + C $$
即
$$ \frac{pV}{T} = C $$

#### 1.3
证明：
根据上题结论，我们有
$$ \frac{\mathrm{d}V}{V} = \alpha \mathrm{d}T - \kappa_T \mathrm{d}p $$
从 $(T,p)=(T_0,0)$ 积分到 $(T,p)=(T,p)$，得
$$ V(T,p) = V(T_0,p) \exp(\alpha(T-T_0) - \kappa_Tp) = V_0(T_0,p) [1 + \alpha(T-T_0) - \kappa_Tp] $$ 
上式中利用了 $\alpha(T-T_0),\kappa_Tp \ll 1$

#### 1.4
解：

(1) 
根据上题结论，
$$ V(T,p') = V_0(T_0,p) [1 + \alpha(T-T_0) - \kappa_T\Delta p] $$ 
因为 $V(T,p')=V_0(T_0,p)$，即 $\alpha(T-T_0) - \kappa_T\Delta p = 0$。所以
$$ \Delta p = \frac{\alpha}{\kappa_T} (T-T_0) = \frac{4.85\times10^{-5}}{7.8\times10^{-7}}\times10 = 622\,\mathrm{atm} $$

(2)
根据上题结论，
$$ \frac{\Delta V}{V} = \alpha \Delta T - \kappa_T \Delta p = 4.85\times10^{-5} \times 10 - 7.8\times10^{-7} \times 100 = 4.07\times10^{-4} $$
即铜块体积增加 $4.07\times10^{-4}$ 倍。

#### 1.5
证明：
金属丝两端固定，$L$ 为常数。

根据物态方程 $f(\mathscr{J},L,T) = 0$，得偏导关系
$$ \left( \frac{\partial \mathscr{J}}{\partial L} \right)_T \left( \frac{\partial L}{\partial T} \right)_\mathscr{J} \left( \frac{\partial T}{\partial \mathscr{J}} \right)_L = -1 $$
故
$$ \left( \frac{\partial \mathscr{J}}{\partial T} \right)_L 
= -\left( \frac{\partial \mathscr{J}}{\partial L} \right)_T \left( \frac{\partial L}{\partial T} \right)_\mathscr{J} 
= -EA\alpha_l $$
在温度变化不大时，$\alpha_l=\alpha$ 视为常数。则
$$ \Delta \mathscr{J} = -EA\alpha (T_2-T_1) $$

#### 1.6
证明：
有物态方程 $\mathscr{J} = \mathscr{J}(L,T)$

(a)
等温弹性模量
$$ E = \frac{L}A \left( \frac{\partial \mathscr{J}}{\partial L} \right)_T = \frac{L}A bT\left( \frac1{L_0} + \frac{2L_0^2}{L^3} \right) 
= \frac{bT}A \left( \frac{L}{L_0} + \frac{2L_0^2}{L^2} \right) $$

(b)
线膨胀系数
$$ \alpha_l = \frac1L \left( \frac{\partial L}{\partial T} \right)_\mathscr{J} 
= -\frac1L \left( \frac{\partial \mathscr{J}}{\partial T} \right)_L / \left( \frac{\partial \mathscr{J}}{\partial L} \right)_T 
= -\frac1T \frac{L/L_0 - L_0^2/L^2}{L/L_0 + 2L_0^2/L^2} + \frac1{L_0} \frac{\mathrm{d}L_0}{\mathrm{d}T} $$


### 3.20 

1.7，1.8，1.9，1.10

#### 1.7
证明：
将该部分气体作为系统，过程中来不及热量交换，$Q=0$。在大气将气体等压压入盒中时，大气对系统做功
$$ W = p_0V_0 $$
根据热力学第一定律，系统内能
$$ U-U_0 = W = p_0V_0 $$

若气体是理想气体，$U=U(T)$，那么 
$$ U-U_0 = C_V(T-T_0) = \frac{nR}{\gamma-1} (T-T_0) $$
又由理想气体状态方程 $p_0V_0=nRT_0,p_0V=nRT$，得
$$ T = \gamma T_0,V = \gamma V_0 $$


#### 1.8
证明：
多方过程 $pV^n=C$。理想气体 $pV=nRT$，故 $TV^{n-1}=C'$
$$ \left(\frac{\partial V}{\partial T} \right)_n = -\frac{V}{(n-1)T} $$
又
$$ C_V = \left( \frac{\partial U}{\partial T} \right)_n = \frac{nR}{\gamma-1} $$
得到热容 
$$ C_n = \lim_{\Delta T \rightarrow0} \left( \frac{\Delta Q}{\Delta T} \right)_n = \left( \frac{\partial U}{\partial T} \right)_n + p\left( \frac{\partial V}{\partial T} \right)_n = C_V - \frac{pV}{(n-1)T} = \frac{n-\gamma}{n-1}C_V $$

#### 1.9
证明：
根据热力学第一定律，
$$ C_V \mathrm{d}T = C_n \mathrm{d}T - p\mathrm{d}V $$
由状态方程 $pV=\nu RT$，且 $C_p-C_V = \nu R$，得
$$ (C_n - C_V) \frac{\mathrm{d}T}{T} = (C_p - C_V) \frac{\mathrm{d}V}{V}, \frac{\mathrm{d}p}{p} + \frac{\mathrm{d}V}{V} = \frac{\mathrm{d}T}{T} $$

记 $n=(C_n - C_p)/(C_n - C_V)$，上式消去 $T$ 项，得到
$$ \frac{\mathrm{d}p}{p} + n\frac{\mathrm{d}V}{V} = 0 $$
积分得
$$ pV^n = C $$
这是一个多方过程。

#### 1.10
证明：
引入比体积 $v=1/\rho$。在绝热过程中，气体
$$ \left( \frac{\partial p}{\partial v} \right)_S = -\gamma \frac{p}{v} $$
声速
$$ a^2 = \left( \frac{\partial p}{\partial \rho} \right)_S = -v^2 \left( \frac{\partial p}{\partial v} \right)_S = \gamma pv $$
又由理想气体状态方程，$pmv = nRT$。
单位质量的内能和焓
$$ u = u_0 + \int c_V \mathrm{d}T/m = u_0 + \frac{nRT}{(\gamma-1)m} = u_0 + \frac{a^2}{\gamma(\gamma-1)} $$
$$ h = h_0 + \int c_p \mathrm{d}T/m = h_0 + \frac{\gamma nRT}{(\gamma-1)m} = h_0 + \frac{a^2}{\gamma-1} $$


### 3.22 

1.11，1.12，1.13

#### 1.11
讨论 $z$ 处的空气。由于 $p(z+\mathrm{d}z) = p(z) + \rho(z)g\mathrm{d}z$，得到
$$ \frac{\mathrm{d}p}{\mathrm{d}z} = -\rho(z)g $$
又由物态方程，
$$ p \frac{m}{\rho} = nRT \Rightarrow \rho(z) = \frac{M}{RT}p(z) $$
又绝热过程中
$$ \left( \frac{\partial T}{\partial p} \right)_S = \frac{\gamma-1}{\gamma} \frac{T}{p} $$
代入，得
$$ \frac{\mathrm{d}T}{\mathrm{d}z} = \left( \frac{\partial T}{\partial p} \right)_S \frac{\mathrm{d}p}{\mathrm{d}z} = -\frac{\gamma-1}{\gamma} \frac{Mg}{R} $$

大气中，$\gamma=1.41, M=29$。故
$$ \frac{\mathrm{d}T}{\mathrm{d}z} = -10\,\mathrm{K}\cdot\mathrm{km}^{-1} $$

#### 1.12
理想气体在准静态绝热过程中，$C_V\mathrm{d}T+p\mathrm{d}V=0$。根据
$$ C_p-C_V = nR, C_p/C_V=\gamma \Rrightarrow C_V = \frac{1}{\gamma-1} nR $$
故
$$ \frac{1}{\gamma-1} \frac{\mathrm{d}T}{T} + \frac{\mathrm{d}V}{V} = 0 $$
定义
$$ \ln F(T) = \int \frac{\mathrm{d}T}{(\gamma-1)T} $$
积分得到
$$ F(T)V = C $$

#### 1.13
卡诺循环中，
$$ Q_1 = RT_1 \ln \frac{V_2}{V_1}, Q_2 = RT_2 \ln \frac{V_3}{V_4} $$
由于绝热过程中，有
$$ F(T_1)V_2 = F(T_2)V_3, F(T_2)V_4 = F(T_1)V_1 $$
消去温度函数得到 $V_2/V_1 = V_3/V_4$。故 $Q_1/Q_2 = T_1/T_2$。效率
$$ \eta = \frac{W}{Q_1} = 1 - \frac{T_2}{T_1} $$


### 3.27

1.14

#### 1.14
证明：
假设有两条绝热线相交于点X。现做一等温线，交两条绝热线于点A,B。现在我们让一个热机工作在ABXA的正循环下。此时系统从单一热源T吸热，并对外做功，且回到了原来的状态。这一点违反了热力学第二定律。故两条绝热线不相交。

![](https://gchat.qpic.cn/download?appid=1407&fileid=Chh1X1pvQWpGb1JZWjNCZzhISS1aWENNN3cSFHwGsJ9VXCfam1v_wEqjDawngfa4GKOCAiD_CiilypOh0oX-AjD9tegDOLTN6ZkPUIC9owFYgIl6&rkey=CAMSSJY5X_KUSNXsIre8PeNKpnSAT3oxeYNEgOmLf-tX2kMpeAwp1kL-nD61FNB-cqkTKC0xN2PizAy8hmMGdmd-9FpLqTxq6Z_1kQ&spec=0&file=bb305b6f6f197f81bcd21ac1d9fbf2b233059-481-440.png&vscodeDragFlag=1)


### 3.29

1.15，1.16，1.17，1.18，1.19

#### 1.15
证明：
根据克劳修斯不等式，有
$$ \oint \frac{đQ}{T} \leqslant 0 $$
若将 $đQ$ 重定义为吸热/放热，分别为 $Q_j,Q_k$。那么
$$ \sum_j \frac{Q_j}{T_j} \leqslant  \sum_k \frac{Q_k}{T_k} $$
在热机吸收热源最高温度为 $T_1$，最低热源温度为 $T_2$。那么
$$ \frac{1}{T_1} \sum_j Q_j \leqslant \sum_j \frac{Q_j}{T_j} \leqslant  \sum_k \frac{Q_k}{T_k} \leqslant \frac{1}{T_2} \sum_k Q_k $$
记总吸热/放热为 $Q_1,Q_2$，则 $Q_1/T_1 \leqslant Q_2/T_2$。故
$$ \eta = 1- \frac{Q_2}{Q_1} \leqslant 1-\frac{T_2}{T_1} $$

#### 1.16
证明：
等压过程中，$S=C_p \ln T-nR\ln p+S_0$，故
$$ (\Delta S)_p = C_p \ln \frac{T_2}{T_1} $$
等容过程中，$S=C_V \ln T+nR\ln V+S_0$，故
$$ (\Delta S)_V = C_V \ln \frac{T_2}{T_1} $$
所以
$$ \frac{(\Delta S)_p}{(\Delta S)_V} = \frac{C_p}{C_V} = \gamma $$

#### 1.17
解：
水分别经历 $0\degree \mathrm{C}-100\degree \mathrm{C}$ 的每个温度，故
$$ \Delta_\text{水} = \int_{T_0}^{T_1} \frac{mc\mathrm{d}T}{T} = mc\ln\frac{T_1}{T_0} = 4.18\times10^3\times\ln\frac{373.15}{273.15} = 1304\,\mathrm{J}\cdot\mathrm{K}^{-1} $$
热源保持温度不变，故
$$ \Delta_\text{源} = -\frac{mc\Delta T}{T} = \frac{4.18\times10^3 \times 100}{373.15} = -1120\,\mathrm{J}\cdot\mathrm{K}^{-1} $$ 
故系统总熵变
$$ \Delta_\text{总} = \Delta_\text{水} + \Delta_\text{源} = 1304-1120 = 184\,\mathrm{J}\cdot\mathrm{K}^{-1} $$

若要加热水使得体系没有熵增，应该采用可逆过程，用无穷多个热源依次给水加热，使得水温升高。

#### 1.18
解：
电阻产生焦耳热
$$ Q = I^2Rt = 10^2 \times 25 \times 1 = 2500\,\mathrm{J} $$

(a)
电阻器保持 $27\degree\mathrm{C}$ 温度不变，电阻仍处在初始状态，故熵不变，$\Delta S = 0$。

(b)
焦耳热全部被电阻吸收，
$$ T' = T_0 + \frac{Q}{mc_p} = 300.15 + \frac{2500}{10\times0.84} = 597.77\,\mathrm{K} $$
故熵增
$$ \Delta S = \int_{T_0}^{T'} \frac{mc_p\mathrm{d}T}{T} = mc_p\ln\frac{T'}{T_0} = 0.84\times10\times\ln\frac{597.77}{300.15} = 5.79\,\mathrm{J}\cdot\mathrm{K}^{-1} $$

#### 1.19
解：
设杆长为 $L$，单位长度热容量为 $c$。在杆方向上建坐标系，中心处为原点。初始温度分布为
$$ T(x) = \frac{T_1+T_2}{2} + \frac{T_2-T_1}{L}x, \quad -\frac{L}{2} \leqslant x \leqslant \frac{L}{2} $$
在 $x$ 处长度为 $\mathrm{d}x$ 的杆元熵变为
$$ \mathrm{d}S(x) = \int_{T(x)}^{T(0)} \frac{c\mathrm{d}x\,\mathrm{d}T}{T} = c\mathrm{d}x \ln\frac{T(0)}{T(x)} $$
故全杆熵增为
$$ \Delta S = \int_{-L/2}^{L/2} c\mathrm{d}x \ln\frac{T(0)}{T(x)} 
= c \int_{-L/2}^{L/2} \left(\ln \frac{T_1+T_2}{2} - \ln \left(\frac{T_1+T_2}{2} + \frac{T_2-T_1}{L}x \right)\right) \,\mathrm{d}x \\
= cL \ln\frac{T_1+T_2}{2} - \frac{c}{(T_2-T_1)/L} (T_2\ln T_2 - T_1\ln T_1 - T_2 + T_1) \\
= C \left( \ln\frac{T_1+T_2}{2} - \frac{T_2\ln T_2 - T_1\ln T_1}{T_2-T_1} + 1 \right) $$


### 4.3 

1.20，1.21，1.22，1.23

#### 1.20
在固定压强下，过冷液体和固体在 $T_0-T_1$ 的熵变，以及相变的熵变分别为
$$ \Delta S_l = \int_{T_0}^{T_1} \frac{C_l\mathrm{d}T}{T} = C_l\ln\frac{T_1}{T_0},\;
 \Delta S_g = \int_{T_0}^{T_1} \frac{C_g\mathrm{d}T}{T} = C_g\ln\frac{T_1}{T_0} \\
 \Delta S_{lg} = \frac{Q_0}{T_0} $$
故
$$ \Delta S = \Delta S_l + \Delta S_{lg} - \Delta S_g = \frac{Q_0}{T_0} + (C_s - C_l)\ln\frac{T_0}{T_1} $$

#### 1.21
证明：
用 $Q'$ 表示热机在热源处的总放热。根据热力学第一定律，有
$$ Q_1 = Q_2 + W $$
过程中，物体和热源熵变分别为 $S_2 - S_1, Q'/T_2$。热机经历可逆循环回到初始状态，故熵变为0。根据熵增原理，
$$ \Delta S = S_2 - S_1 + Q'/T_2 \geqslant 0 $$
故
$$ W \leqslant Q - T_2(S_1-S_2) $$

#### 1.22
证明：
制冷机回到初始状态，熵不变。而两个物体
$$ \Delta S_1 = C_p \ln \frac{T_1}{T_i} \\
\Delta S_2 = C_p \ln \frac{T_2}{T_i} $$
根据熵增原理
$$ \Delta S = \Delta S_1 + \Delta S_2 \geqslant 0 $$
得
$$ T_1 T_2 / T_i^2 \geqslant 1 $$
制冷机
$$ W = Q_2 - Q_1 = C_p (T_1-T_2-2T_i) \geqslant C_p \left( \frac{T_i^2}{T_2} + T_2 - 2T_i \right) $$

#### 1.23
解：
如图所示。

![](https://gchat.qpic.cn/download?appid=1407&fileid=Chh1X1pvQWpGb1JZWjNCZzhISS1aWENNN3cSFAs-LqvM0yh9pN1v6KgbZe2iXgQmGOeoASD_Cij5k9yUxJr-AjD9tegDOPWywbUOUIC9owFYgIl6&rkey=CAISSOB8NTZXfT-wSw7yC-Pz8vdV49E2uhShFuDMt2SOrlchd0VMjRtL3Alm5r94XMuAvHBKYvBBAy64wmnYjtGcdJ4EK7zZuwwi6g&spec=0&file=3c79e3186f58cad8cae99e8cca83408021607-507-395.png&vscodeDragFlag=1)

因为卡诺循环由两个绝热过程和两个等温过程构成，故在 $T-S$ 图上为一个长方形。显然，系统在高温热源吸热 $Q_1=T_1(S_2-S_1)$，在低温热源放热 $Q_2=T_2(S_2-S_1)$。故卡诺热机的效率
$$ \eta = 1 - \frac{Q_2}{Q_1} = 1 - \frac{T_2}{T_1} $$


### 4.10

2.1，2.2，2.3，2.4，2.5

#### 2.1
证明：
由题意
$$ \left(\frac{\partial p}{\partial T} \right)_V = C > 0 \Rightarrow p = f(V)T, \;f(V)>0 $$
故根据麦克斯韦关系，有
$$ \left(\frac{\partial S}{\partial V} \right)_T = \left(\frac{\partial p}{\partial T} \right)_V = f(V) > 0 $$
即在物质温度不变时，熵随着体积的增加而增加。

#### 2.2
证明：
根据麦克斯韦关系，有
$$ \left(\frac{\partial U}{\partial V} \right)_T = T \left(\frac{\partial p}{\partial T} \right)_V - p = Tf(V)-p = 0 $$
故内能与体积无关。

#### 2.3
证明：
$$ \mathrm{d}H = T\mathrm{d}S + V\mathrm{d}p = 0 $$
故
$$ \left(\frac{\partial S}{\partial p} \right)_H = -\frac{V}{T} < 0 $$
同理，
$$ \mathrm{d}U = T\mathrm{d}S - p\mathrm{d}V = 0 $$
故
$$ \left(\frac{\partial S}{\partial V} \right)_U = \frac{p}{T} > 0 $$

#### 2.4
证明：
$$ \left(\frac{\partial U}{\partial p} \right)_T = \left(\frac{\partial U}{\partial V} \right)_T \left(\frac{\partial V}{\partial p} \right)_T = 0 $$

#### 2.5
证明：
$$ \left(\frac{\partial S}{\partial V} \right)_p = \left(\frac{\partial S}{\partial T} \right)_p \left(\frac{\partial T}{\partial V} \right)_p 
= \frac1T \left(\frac{\partial U}{\partial T} \right)_p \left(\frac{\partial T}{\partial V} \right)_p = \frac {C_p}T \left(\frac{\partial T}{\partial V} \right)_p $$
其中 $C_p/T>0$。故前一项的正负取决于后一项的正负，即一个均匀物体在等压过程中熵随体积的增减取决于等压下温度随体积的增减。


### 4.12

2.8，2.9，2.10，2.11，2.12，2.13，2.14

#### 2.8
解：
$$ \left(\frac{\partial U}{\partial V} \right)_T = T \left(\frac{\partial p}{\partial T} \right)_V - p = \frac{T}{V}f'(T) - p = 0 $$
故
$$ Tf'(T) = f(T) \Rightarrow f(T) = CT $$
所以状态方程 $pV=CT$。

#### 2.9
证明：
$$ C_V = \left(\frac{\partial U}{\partial T} \right)_V = T \left(\frac{\partial S}{\partial T} \right)_V  $$
故
$$ \left(\frac{\partial C_V}{\partial V} \right)_T 
= T \left(\frac{\partial^2 S}{\partial V\partial T} \right) = T \left(\frac{\partial^2 p}{\partial T^2} \right)_V $$
积分后有
$$ C_V = C_V^0 + T \int_{V_0}^V \left(\frac{\partial^2 p}{\partial T^2} \right)_V \mathrm{d}V $$
同理，有
$$ \left(\frac{\partial C_p}{\partial p} \right)_T 
= T \left(\frac{\partial^2 S}{\partial p\partial T} \right) = -T \left(\frac{\partial^2 V}{\partial T^2} \right)_p $$
$$ C_p = C_p^0 - T \int_{p_0}^p \left(\frac{\partial^2 V}{\partial T^2} \right)_p \mathrm{d}p $$
理想气体有 $pV=nRT$，故
$$ \left(\frac{\partial^2 p}{\partial T^2} \right)_V = \left(\frac{\partial^2 V}{\partial T^2} \right)_p = 0 $$
所以 $C_V,C_p$ 均只为 $T$ 的函数。

#### 2.10
证明：
范式气体
$$ \left( p + \frac{n^2a}{V^2} \right)(V-nb) = nRT $$
由
$$ \left(\frac{\partial C_V}{\partial V} \right)_T = T \left(\frac{\partial^2 p}{\partial T^2} \right)_V = 0 $$
故范式气体的定容热容只是温度 $T$ 的函数，与体积无关。

#### 2.11
证明：
理想气体
$$ U_m = \int C_{V,m}\mathrm{d}T + U_{m0} $$
$$ S_m = \int \frac{C_{V,m}}{T}\mathrm{d}T + R\ln V_m + S_{m0} $$
故
$$ F_m = U_m - TS_m = \int C_{V,m}\mathrm{d}T + U_{m0} -T\int \frac{C_{V,m}}{T}\mathrm{d}T - RT\ln V_m - TS_{m0} \\
= -T \int \frac{\mathrm{d}T}{T^2} \int C_{V,m}\mathrm{d}T + U_{m0} - TS_{m0} - RT\ln V_{m0} $$

#### 2.12
解：
考虑 1mol 范式气体，特性函数
$$ F_m = -S_m\mathrm{d}T - p\mathrm{d}V $$
故
$$ \left(\frac{\partial F_m}{\partial V_m} \right)_T = -p = -\frac{RT}{V_m-b} + \frac{a}{V_m^2} $$
积分，得到
$$ F_m(T,V_m) = -RT \ln(V_m-b) - \frac{a}{V_m} + f(T) $$
我们有边界条件，即 $V_m\rightarrow\infty$ 时回到理想气体，则
$$ f(T) = \int C_{V,m}\mathrm{d}T + U_{m0} -T\int \frac{C_{V,m}}{T}\mathrm{d}T - TS_{m0} $$

熵和内能
$$ S_m = - \left(\frac{\partial F_m}{\partial T} \right)_V = \int \frac{C_{V,m}}{T}\mathrm{d}T + R\ln(V_m-b) + S_{m0} $$
$$ U_m = F_m + TS_m = \int C_{V,m}\mathrm{d}T - \frac{a}{V_m} + U_{m0} $$

#### 2.13
证明：
对于弹簧，有
$$ \mathrm{d}U = T\mathrm{d}S - F_x \mathrm{d}x \Rightarrow \mathrm{d}F = -S\mathrm{d}T - F_x\mathrm{d}x $$
故
$$ \left(\frac{\partial F}{\partial x} \right)_T = -F_x = Ax $$
积分得到
$$ F(T,x) = F(T,0) + \frac12 Ax^2 $$
所以
$$ S(T,x) = -\left(\frac{\partial F}{\partial T} \right)_x = S(T,0) - \frac{x^2}{2} \frac{\mathrm{d}A}{\mathrm{d}T} $$
$$ U = F + TS = U(T,0) + \frac12 \left( A - T\frac{\mathrm{d}A}{\mathrm{d}T} \right) x^2 $$

#### 2.14
解：

(a) 
橡皮筋经过拉伸，从无定形结构变为晶体结构，即从无序度降低了，所以熵减小了。

(b) 证明：
橡皮筋的自由能
$$ \mathrm{d}F = -S\mathrm{d}T + \mathscr{J}\mathrm{d}L $$
故
$$ \left(\frac{\partial \mathscr{J}}{\partial T} \right)_L = -\left(\frac{\partial S}{\partial L} \right)_T > 0 $$

所以膨胀系数
$$ \alpha = \frac1L \left(\frac{\partial L}{\partial T} \right)_\mathscr{J} = -\frac1L \left(\frac{\partial L}{\partial \mathscr{J}} \right)_T \left(\frac{\partial \mathscr{J}}{\partial T} \right)_L < 0 $$


### 4.17

2.15，2.16，2.17

#### 2.15
解：
黑体辐射通量密度 $J_u = \sigma T^4$。由
$$ J_u R_s^2 = J_s R_{se}^2 $$
得
$$ T = \left(\frac{J_u}{\sigma}\right)^{1/4} = \left(\frac{J_s R_{se}^2}{\sigma R_s^2}\right)^{1/4} 
= \left(\frac{1.35\times10^3 \times (1.495\times10^{11})^2}{5.67\times10^{-8} \times (6.955\times10^8)^2}\right)^{1/4} = 5760\,\mathrm{K} $$

#### 2.16
解：
辐射场的熵 $S = \frac43 aT^3V$。等温吸热
$$ \Delta Q = T\Delta S = \frac43 a T^3 (V_2-V_1) $$

#### 2.17
解：
在 $T-S$ 图上讨论卡诺循环。等温膨胀吸热 $Q_1 = T_1(S_2-S_1)$，等温压缩放出 $Q_2 = T_2(S_2-S_1)$。故循环效率
$$ \eta = 1 - \frac{Q_2}{Q_1} = 1 - \frac{T_2}{T_1} $$


### 4.19

2.18，2.19，2.20，2.21，2.22

#### 2.18
解：
对于电介质，
$$ dW = VE \mathrm{d}D $$
介电常量 $\varepsilon(T) = D/E$，故
$$ \left(\frac{\partial D}{\partial T} \right)_E = E \frac{\mathrm{d}\varepsilon}{\mathrm{d}T},\;
\left(\frac{\partial E}{\partial T} \right)_D = -\frac{D}{\varepsilon^2} \frac{\mathrm{d}\varepsilon}{\mathrm{d}T} $$
类比简单热力学系统，有
$$ C_E - C_D = -VT \left(\frac{\partial E}{\partial T} \right)_D \left(\frac{\partial D}{\partial T} \right)_E 
= VT \frac{DE}{\varepsilon^2} \left( \frac{\mathrm{d}\varepsilon}{\mathrm{d}T} \right)^2 $$

#### 2.19
证明：
对于磁介质，
$$ dW = \mu_0 \mathscr{H} \mathrm{d}\mathscr{M} $$
类比简单热力学系统，有
$$ C_\mathscr{H} - C_\mathscr{M} = -\mu_0T \left(\frac{\partial \mathscr{H}}{\partial T} \right)_\mathscr{M} \left(\frac{\partial \mathscr{M}}{\partial T} \right)_\mathscr{H} \\
= \mu_0T \left(\frac{\partial \mathscr{H}}{\partial T} \right)_\mathscr{M}^2 \left(\frac{\partial \mathscr{M}}{\partial \mathscr{H}} \right)_T  $$

#### 2.20
解：
根据居里定律，$\mathscr{m} = CV/T\mathscr{H}$，则
$$ \left(\frac{\partial S}{\partial \mathscr{H}} \right)_T = \mu_0\left(\frac{\partial \mathscr{m}}{\partial T} \right)_\mathscr{H} 
= -\mu_0 \frac{CV}{T^2} \mathscr{H} $$
在等温过程中，熵增
$$ \Delta S = \int_0^H \left(\frac{\partial S}{\partial \mathscr{H}} \right)_T \mathrm{d}\mathscr{H} = -\mu_0 \frac{CV}{2T^2}\mathscr{H}^2 $$
故吸热
$$ Q = T\Delta S = -\mu_0 \frac{CV}{2T}\mathscr{H}^2 $$

#### 2.21
证明：

(a)
因为超导体有 $\mathscr{H}+\mathscr{M}=0$，故
$$ \left(\frac{\partial \mathscr{M}}{\partial T} \right)_\mathscr{H} = \left(\frac{\partial \mathscr{H}}{\partial T} \right)_\mathscr{M} = 0 $$
$$ \left(\frac{\partial C_\mathscr{M}}{\partial \mathscr{M}} \right)_T = -\mu_0 T \left(\frac{\partial^2 \mathscr{H}}{\partial T^2} \right)_\mathscr{M} = 0 $$
即 $C_\mathscr{M}$ 与 $\mathscr{M}$ 无关，只是$T$的函数。

(b)
内能的全微分
$$ \mathrm{d}U = \left(\frac{\partial U}{\partial T} \right)_\mathscr{M} \mathrm{d}T + \left(\frac{\partial U}{\partial \mathscr{M}} \right)_T \mathrm{d}\mathscr{M} = C_\mathscr{M} \mathrm{d}T - \mu_0 \mathscr{M} \mathrm{d}\mathscr{M} $$
故
$$ U = \int C_\mathscr{M} \mathrm{d}T - \frac{\mu_0\mathscr{M}^2}2 + U_0 $$

(c)
熵的全微分
$$ \mathrm{d}S = \left(\frac{\partial S}{\partial T} \right)_\mathscr{M} \mathrm{d}T + \left(\frac{\partial S}{\partial \mathscr{M}} \right)_T \mathrm{d}\mathscr{M} 
= \frac{C_\mathscr{M}}T \mathrm{d}T  $$
故
$$ S = \int \frac{C_\mathscr{M}}T \mathrm{d}T + S_0 $$

#### 2.22
解：
当 $dW = \mu_0 \mathscr{H} \mathrm{d} \mathscr{M}$ 时，
$$ \mathrm{d}F = -S\mathrm{d}T + \mu_0 \mathscr{H} \mathrm{d} \mathscr{M} = -S\mathrm{d}T + \mu_0 \frac{\mathscr{M}}{C/T} \mathrm{d} \mathscr{M} $$
积分得
$$ F = \frac{\mu_0 \mathscr{M}^2}{2C/T} + F_0(T) $$
$$ S = -\left(\frac{\partial F}{\partial T} \right)_\mathscr{M} = - \frac{\mu_0 \mathscr{M}^2}{2C} + S_0(T) $$
$$ U = F + TS = U_0(T) $$

当 $dW = -\mu_0 \mathscr{M} \mathrm{d} \mathscr{H}$ 时，
$$ \mathrm{d}F = -S\mathrm{d}T - \mu_0 \mathscr{M} \mathrm{d} \mathscr{H} = -S\mathrm{d}T - \mu_0 {C/T}{\mathscr{H}} \mathrm{d} \mathscr{H} $$
积分得
$$ F = -\frac{\mu_0 C/T\mathscr{H}^2}{2} + F_0(T) $$
$$ S = -\left(\frac{\partial F}{\partial T} \right)_\mathscr{M} = - \frac{\mu_0 C\mathscr{H}^2}{2T^2} + S_0(T) $$
$$ U = F + TS = -\mu_0 C/T \mathscr{H}^2 + U_0(T) $$
两种表述的熵是等价的，但是内能有所不同。后者描述的内能与磁场有关。


### 4.24

3.1，3.2，3.3，3.4，3.5，4.11

#### 3.1
证明：

(a)
在 $S,V$ 不变的情况下，虚变动
$$ \delta U < T \delta S - p \delta V = 0 $$
故稳定平衡态的 $U$ 最小。

(b)
在 $S,p$ 不变的情况下，虚变动
$$ \delta H < T \delta S + V \delta p = 0 $$
故稳定平衡态的 $H$ 最小。

(c)
在 $H,p$ 不变的情况下，虚变动
$$ \delta S > \frac1T (\delta H - V \delta p) = 0 $$
故稳定平衡态的 $S$ 最大。

(d)
在 $F,V$ 不变的情况下，虚变动
$$ \delta T < \frac1S (-\delta F - p \delta V) = 0 $$
故稳定平衡态的 $T$ 最小。

(e)
在 $G,p$ 不变的情况下，虚变动
$$ \delta T < \frac1S (-\delta G + V \delta p) = 0 $$
故稳定平衡态的 $T$ 最小。

(f)
在 $U,S$ 不变的情况下，虚变动
$$ \delta V < \frac1p (\delta U - T \delta S) = 0 $$
故稳定平衡态的 $V$ 最小。

(g)
在 $F,T$ 不变的情况下，虚变动
$$ \delta V < \frac1p (-\delta F - S \delta T) = 0 $$
故稳定平衡态的 $V$ 最小。

#### 3.2
证明：
$$ \delta^2 S = \left(\frac{\partial^2 S}{\partial U^2} \right) (\delta U)^2 + 2\left(\frac{\partial^2 S}{\partial V \partial U} \right) (\delta U \delta V) + \left(\frac{\partial^2 S}{\partial V^2} \right) (\delta V)^2 $$
由
$$ \left(\frac{\partial S}{\partial U} \right)_V = \frac1T,\; \left(\frac{\partial S}{\partial V} \right)_U = \frac pT $$
可得
$$ \frac{\partial^2 S}{\partial U^2} = \left(\frac{\partial (1/T)}{\partial U} \right)_V 
= -\frac1{T^2}\left(\frac{\partial T}{\partial U} \right)_V = \frac1{C_VT^2} \\ 
\frac{\partial^2 S}{\partial V \partial U} = -\frac1{T^2} \left(\frac{\partial T}{\partial V} \right)_U = \frac1{T^2} \frac1{C_V} \left[ T \left(\frac{\partial p}{\partial T} \right)_V - p \right] = \frac{p}{C_VT}\left(\beta-\frac1T\right) \\ 
\frac{\partial^2 S}{\partial V^2} = \left(\frac{\partial (p/T)}{\partial V} \right)_U = \frac1{T^2} \left[ T \left(\frac{\partial p}{\partial V} \right)_U - p \left(\frac{\partial T}{\partial V} \right)_U \right] \\ 
= -\frac1T \left[ T \left(\frac{\partial p}{\partial T} \right)_V - p + C_V \left(\frac{\partial T}{\partial V} \right)_p \right] / \left[ C_V \left(\frac{\partial T}{\partial p} \right)_V \right] + \frac{p}{T^2} \frac1{C_V} \left[ T \left(\frac{\partial p}{\partial T} \right)_V - p \right] \\ 
= - \frac{p^2 \beta^2}{C_V} + \frac{p^2 \beta}{C_VT} - \frac{1}{TV\kappa_T} + \frac{p^2}{T} \frac{\beta}{C_V} - \frac{p^2}{T^2} \frac{1}{C_V} \\
= \frac{2p^2 \beta}{C_VT} - \frac{p^2}{C_VT^2} - \frac{p^2 \beta^2}{C_V} - \frac{1}{TV\kappa_T} $$
即有所证式。

#### 3.3
解：
对于孤立系统任意切分的两个子系统，有
$$ \delta U_1 + \delta U_2 = 0, \; \delta V_1 + \delta V_2 = 0 $$
系统熵变
$$ \delta S = \delta S_1 + \delta S_2 
= \delta U_1 \left( \frac{1}{T_1} - \frac{1}{T_2} \right) + \delta V_1 \left( \frac{p_1}{T_1} - \frac{p_2}{T_2} \right) 
= 0 $$
故有 $p_1=p_2=p,T_1=T_2=T$。
稳定性要求 $\delta^2S<0$，故
$$ \delta^2 S 
= \sum_{i=1,2} \left[ -\frac{C_{V,i}}{T^2} (\delta T)^2 + \frac1T \left(\frac{\partial p}{\partial V_i} \right)_T (\delta V_i)^2 \right] 
< 0 $$
故
$$ C_{V,i} > 0 ,\, \left( \frac{\partial p}{\partial V_i} \right)_T < 0, \; i=1,2 $$

#### 3.4
证明：
$$ C_p - C_V = T \left(\frac{\partial p}{\partial T} \right)_V \left(\frac{\partial V}{\partial T} \right)_p = -T \left(\frac{\partial p}{\partial V} \right)_T \left(\frac{\partial V}{\partial T} \right)_p^2 \geqslant 0 $$
故
$$ C_p \geqslant C_V > 0 $$
又
$$ \left(\frac{\partial p}{\partial V} \right)_S / \left(\frac{\partial p}{\partial V} \right)_T = \left(\frac{\partial S}{\partial T} \right)_V / \left(\frac{\partial S}{\partial T} \right)_p = C_p / C_V \geqslant 1 $$
故
$$ \left(\frac{\partial p}{\partial V} \right)_S \geqslant \left(\frac{\partial p}{\partial V} \right)_T < 0 $$

#### 3.5
解：
两个子系统间有 $p_1=p_2=p,T_1=T_2=T$。
根据
$$ T \delta S_i = \delta U_i + p \delta V_i $$
变分得
$$ \delta T \delta S_i + T \delta^2 S_i = \delta^2 U_i + \delta p \delta V_i + p \delta^2 V_i $$
对 $i$ 求和，注意到 $U,V$ 是不变量，有
$$ \delta^2 S = \sum_{i=1,2} \frac{\delta p \delta V_i - \delta T \delta S_i}{T} < 0 $$
根据两系统独立性，有
$$ \delta p_i \delta V_i - \delta T_i \delta S_i < 0,\; i = 1,2 $$
取 $T,V$ 为自变量，有
$$ C_{V,i} > 0, \, \left(\frac{\partial V_i}{\partial p} \right)_T < 0 $$
取 $S,p$ 为自变量，有
$$ C_{p,i} > 0, \, \left(\frac{\partial V_i}{\partial p} \right)_S < 0 $$

#### 4.11
证明：
表面系统中，$dW=\sigma\mathrm{d}A$。根据自由能 $F=-S\mathrm{d}T+\sigma\mathrm{d}A$ 的全微分
$$ \left(\frac{\partial \sigma}{\partial T} \right)_A = \left(\frac{\partial S}{\partial A} \right)_T $$
根据热力学第三定律，
$$ \lim_{T\rightarrow0^+} \left(\frac{\partial S}{\partial A} \right)_T = 0 $$
又 $\sigma=\sigma(T)$，与 $A$ 无关，故
$$ \lim_{T\rightarrow0^+} \frac{\mathrm{d}\sigma}{\mathrm{d}T} = \lim_{T\rightarrow0^+} \left(\frac{\partial S}{\partial A} \right)_T = 0 $$


### 4.26

3.6，3.7，3.8，3.10，3.11，3.13

#### 3.6
证明：

(a)
自由能的全微分
$$
\mathrm{d}F = -S\mathrm{d}T - p\mathrm{d}V + \mu \mathrm{d}n
$$
得
$$
\left(\frac{\partial \mu}{\partial T} \right)_{V,n} = -\left(\frac{\partial S}{\partial n} \right)_{V,T} 
$$

(b)
吉布斯自由能的全微分
$$
\mathrm{d}G = -S\mathrm{d}T + V\mathrm{d}p + \mu \mathrm{d}n
$$
得
$$
\left(\frac{\partial \mu}{\partial p} \right)_{T,n} = -\left(\frac{\partial V}{\partial n} \right)_{T,p} 
$$

#### 3.7
证明：
自由能的全微分
$$
\mathrm{d}F = -S\mathrm{d}T - p\mathrm{d}V + \mu \mathrm{d}n
$$
得
$$
\mu = \left(\frac{\partial F}{\partial n} \right)_{V,T} ,\; 
\left(\frac{\partial \mu}{\partial T} \right)_{V,n} = -\left(\frac{\partial S}{\partial n} \right)_{V,T} 
$$
又 $F=U-TS$，得
$$
\left(\frac{\partial F}{\partial n} \right)_{V,T} = \left(\frac{\partial U}{\partial n} \right)_{V,T} - T \left(\frac{\partial S}{\partial n} \right)_{V,T} 
$$
故
$$
\left(\frac{\partial U}{\partial n} \right)_{V,T} - \mu = - T \left(\frac{\partial \mu}{\partial T} \right)_{V,n} 
$$

#### 3.8
解：
由一阶变分
$$
\delta S^i = \frac{\delta U^i + p^i \delta V^i - \mu^i \delta n^i}{T^i}
$$
得到 $p^1=p^2=p,T^1=T^2=T,\mu^1=\mu^2=\mu$。二阶变分
$$
\delta^2 S^i = \frac{\delta^2 U^i + p \delta^2 V^i + \delta p \delta V^i - \mu \delta^2 n^i - \delta \mu \delta n^i - \delta T \delta S^i}{T}
$$
对 $i$ 求和，注意到 $U,V,n$ 是不变量，有
$$ \delta^2 S = \sum_{i=1,2} \frac{\delta p \delta V^i - \delta \mu \delta n^i - \delta T \delta S^i}{T} < 0 $$
根据两系统独立性，有
$$ \delta p^i \delta V^i - \delta T^i \delta S^i < 0,\; i = 1,2 $$
取 $T,V$ 为自变量，有
$$ C_{V}^i > 0, \, \left(\frac{\partial V^i}{\partial p} \right)_T < 0 $$
取 $S,p$ 为自变量，有
$$ C_{p}^i > 0, \, \left(\frac{\partial V^i}{\partial p} \right)_S < 0 $$

#### 3.10
证明：
相变潜热即焓变 $\Delta H_m = L$。根据克拉伯龙方程，
$$
\frac{\mathrm{d}p}{\mathrm{d}T} = \frac{L}{T \Delta V_m} \Rightarrow 
\Delta V_m = \frac{L}{T} \frac{\mathrm{d}T}{\mathrm{d}p} 
$$
故内能变化
$$
\Delta U_m = \Delta H_m - p\Delta V_m = L \left( 1 - \frac{p}{T} \frac{\mathrm{d}T}{\mathrm{d}p} \right) 
$$
若一相为理想气体，另一相为凝聚态，则
$$
\Delta V_m = V_{g,m} = \frac{RT}{p} 
$$
那么
$$
\Delta U_m = L - RT 
$$

#### 3.11
解：
联立两蒸气压方程，得到
$$
\ln p_0 = 27.92 - \frac{3754}{T_0} = 24.38 - \frac{3063}{T_0} \Rightarrow T_0 = 195.2\,\mathrm{K}
$$
根据蒸气压近似方程，
$$
\ln p = - \frac{L}{RT} + A
$$
得到
$$
L_\textrm{汽} = 3754 \times 8.31 = 3.12\times10^4\,\mathrm{J} \\
L_\textrm{升} = 3063 \times 8.31 = 2.55\times10^4\,\mathrm{J}
$$

#### 3.13
证明：
相变潜热 $L_m = H_m^\beta - H_m^\alpha$，故
$$
\frac{\mathrm{d}L}{\mathrm{d}T} = \left(\frac{\partial H_m^\beta}{\partial T} \right)_p + \left(\frac{\partial H_m^\beta}{\partial p} \right)_T \frac{\mathrm{d}p}{\mathrm{d}T} - \left(\frac{\partial H_m^\alpha}{\partial T} \right)_p - \left(\frac{\partial H_m^\beta}{\partial p} \right)_T \frac{\mathrm{d}p}{\mathrm{d}T} \\
= C_p^\beta - C_p^\alpha + (V_m^\beta - V_m^\alpha) \frac{\mathrm{d}p}{\mathrm{d}T} - T \left[ \left(\frac{\partial V_m^\beta}{\partial T} \right)_p - \left(\frac{\partial V_m^\alpha}{\partial T} \right)_p \right] \frac{\mathrm{d}p}{\mathrm{d}T} \\
= C_p^\beta - C_p^\alpha + \frac{L}{T} - \left[ \left(\frac{\partial V_m^\beta}{\partial T} \right)_p - \left(\frac{\partial V_m^\alpha}{\partial T} \right)_p \right] \frac{L}{V_m^\beta - V_m^\alpha} 
$$
若 $\beta$ 相是气相，$\alpha$ 相是凝聚相，则 $V_m^\alpha$ 项可忽略。故
$$
\frac{\mathrm{d}L}{\mathrm{d}T} = C_p^\beta - C_p^\alpha + \frac{L}{T} - \left(\frac{\partial V_m^\beta}{\partial T} \right)_p \frac{L}{V_m^\beta} 
= C_p^\beta - C_p^\alpha 
$$


### 4.27

3.14，3.15，3.16，3.19，3.20，3.21，4.3，4.8，4.13

#### 3.14
证明：
由
$$
\frac{\mathrm{d}L}{\mathrm{d}T} = C_p^\beta - C_p^\alpha 
$$
积分得
$$
L = (C_p^\beta - C_p^\alpha) T + L_0 
$$
又
$$
\frac{1}{p} \frac{\mathrm{d}p}{\mathrm{d}T} = \frac{L}{RT^2} 
= \frac{L_0}{RT^2} + \frac{C_p^\beta - C_p^\alpha}{RT} 
$$
积分得
$$
\ln p = A - \frac{B}{T} + C \ln T
$$
其中 $B=L_0/R,C=(C_p^\beta - C_p^\alpha)/R$。

#### 3.15
证明：
根据克拉伯龙方程，
$$
\frac{\mathrm{d}p}{\mathrm{d}T} = \frac{pL}{RT^2} 
$$
对理想气体，有
$$
\left(\frac{\partial V_m}{\partial T} \right)_p = \frac1T,\; 
\left(\frac{\partial V_m}{\partial p} \right)_T = -\frac1p 
$$
故
$$
\frac1{V_m} \frac{\mathrm{d}V_m}{\mathrm{d}T} = \frac1{V_m} \left[ \left(\frac{\partial V_m}{\partial T} \right)_p + \left(\frac{\partial V_m}{\partial p} \right)_T \frac{\mathrm{d}p}{\mathrm{d}T} \right] \\
= \frac1T - \frac{L}{RT^2}
$$

#### 3.16
证明：
范式气体方程
$$
p = \frac{RT}{V_m - b} - \frac{a}{V_m^2}
$$
等温线极值点
$$
\left(\frac{\partial p}{\partial V_m} \right)_T = -\frac{RT}{(V_m-b)^2} + \frac{2a}{V_m^3} = 0
$$
故有
$$
p V_m^3 = \left( \frac{RT}{V_m - b} - \frac{a}{V_m^2} \right) V_m^3 
= \left( \frac{2a}{V_m^3}(V_m-b) - \frac{a}{V_m^2} \right) V_m^3  = a(V_m-2b)
$$

区域 II 为不稳定平衡点，会迅速演化到两相平衡的稳定状态。区域 I，III 为亚稳态，可以作为过热液体和过饱和蒸汽单相存在。

#### 3.19
证明：
二级相变下，有 $\mathrm{d}v^1 = \mathrm{d}v^2, \mathrm{d}s^1 = \mathrm{d}s^2$。由
$$
\mathrm{d}v = \left(\frac{\partial v}{\partial p} \right)_T \mathrm{d}p + \left(\frac{\partial v}{\partial T} \right)_p \mathrm{d}T = -\kappa v \mathrm{d}p + \alpha v \mathrm{d}T \\
\mathrm{d}s = \left(\frac{\partial s}{\partial p} \right)_T \mathrm{d}p + \left(\frac{\partial s}{\partial T} \right)_p \mathrm{d}T = -\alpha v \mathrm{d}p + \frac{C_p}{T} \mathrm{d}T 
$$
故
$$
-\kappa^1 \mathrm{d}p + \alpha^1 \mathrm{d}T = -\kappa^2 \mathrm{d}p + \alpha^2 \mathrm{d}T \\
-\alpha^1 v \mathrm{d}p + \frac{C_p^1}{T} \mathrm{d}T = -\alpha^2 v \mathrm{d}p + \frac{C_p^2}{T} \mathrm{d}T 
$$
整理得到
$$
\frac{\mathrm{d}p}{\mathrm{d}T} = \frac{\alpha^2 - \alpha^1}{\kappa^2 - \kappa^1} = \frac{C_p^2 - C_p^1}{Tv(\alpha^2 - \alpha^1)}
$$

#### 3.20
证明：
平衡下自由能取极小值，有
$$
F = F_0,\; T>T_C ; \quad
F = F_0 - \frac{a^2}{4b},\; T<T_C 
$$
故熵
$$
S = - \left(\frac{\partial F}{\partial T} \right)_V = -F_0'(T) ,\; T>T_C \\
S = - \left(\frac{\partial F}{\partial T} \right)_V = -F_0'(T) + \frac{a(T)a'(T)}{2b} = -F_0'(T) + \frac{a_0^2}{2b} \frac{T-T_C}{T_C^2} ,\; T<T_C 
$$
在 $T=T_C$ 处，熵连续。

#### 3.21
解：
根据朗道自由能，得到
$$
\mu_0 \mathscr{H} = a\mathscr{M} + b\mathscr{M}^3 
$$
求导得
$$
\left(\frac{\partial \mathscr{H}}{\partial T} \right)_\mathscr{M} = \frac{a_0}{\mu_0T_C} \mathscr{M} 
$$
故
$$
C_\mathscr{H} - C_\mathscr{M} 
= \mu_0T \left(\frac{\partial \mathscr{H}}{\partial T} \right)_\mathscr{M}^2 \left(\frac{\partial \mathscr{M}}{\partial \mathscr{H}} \right)_T 
= T \frac{a_0^2 \mathscr{M}^2}{\mu_0 T_C^2} \left(\frac{\partial \mathscr{M}}{\partial \mathscr{H}} \right)_T
$$
因为无序相 $\mathscr{M}=0$，故 $C_\mathscr{H} - C_\mathscr{M} = 0$。
对于有序相，
$$
\mathscr{M}^2 = -\frac{a_0}{b}t \\
\left(\frac{\partial \mathscr{M}}{\partial \mathscr{H}} \right)_T = - \frac{\mu_0}{2a_0} \frac1t
$$
故
$$
C_\mathscr{H} - C_\mathscr{M} = \frac{a_0^2 T}{2bT_C^2} 
$$

#### 4.3
证明：

(a)
混合前 $G_0 = n_1g_1+n_2g_2$，混合后 $G = n_1\mu_1 + n_2\mu_2$。故
$$
\Delta G = G - G_0 = n_1 RT\ln x_1 + n_2 RT\ln x_2 
$$

(b)
$$
\Delta V = \left(\frac{\partial \Delta G}{\partial p} \right)_{T,n_i} = 0 
$$

(c)
$$
\Delta S = -\left(\frac{\partial \Delta G}{\partial T} \right)_{p,n_i} = -R(n_1\ln x_1 + n_2 \ln x_2) 
$$

(d)
等温等压下，焓变
$$
\Delta H = \Delta G + T\Delta S = 0 
$$

(e)
$$
\Delta U = \Delta H - p \Delta V = 0 
$$

#### 4.8
解：

(a)
混合前
$$
p_1 V_1 = n_1 RT,\;
p_2 V_2 = n_2 RT 
$$
混合后
$$
p (V_1+V_2) = (n_1+n_2)RT 
$$
故
$$
p = \frac{n_1 + n_2}{n_1/p_1 + n_2/p_2} 
$$

(b)
$$
\Delta S = \Delta S_1 + \Delta S_2 = n_1 R \ln \frac{V_1 + V_2}{V_1} + n_2 R \ln \frac{V_1 + V_2}{V_2} 
$$

(c)
$$
\Delta S = (n_1 + n_2) R \ln \frac{V_1 + V_2}{n_1 + n_2} - n_1 R \ln \frac{V_1}{n_1} - n_2 R \ln \frac{V_2}{n_2} 
$$

#### 4.13
解：
温度为 $T_0$ 的白锡的熵
$$
S(T_0) = S_w(0) + \int_0^{T_0} \frac{C_w(T)}{T} \,\mathrm{d}T 
= S_g(0) + \int_0^{T_0} \frac{C_g(T)}{T} \,\mathrm{d}T + \frac{L}{T_0} 
$$
故
$$
S_w(0) - S_g(0) = \int_0^{T_0} \frac{C_g(T)}{T} \,\mathrm{d}T - \int_0^{T_0} \frac{C_w(T)}{T} \,\mathrm{d}T + \frac{L}{T_0} \\
= 44.12-51.44+\frac{2242}{292} = 0.25\,\mathrm{J}/\mathrm{mol.K} 
$$
是适用的


### 5.10 

6.1，6.2，6.3，6.4

#### 6.1
证明：
在体积 $V=L^3$ 内，自由粒子的量子态数目有
$$
\mathrm{d} n = \frac{V}{h^3} \mathrm{d}^3 p = \frac{4\pi V}{h^3} p^2 \mathrm{d}p 
$$
根据自由粒子能量动量关系，有
$$
\varepsilon = \frac{p^2}{2m} 
$$
故
$$
\mathrm{d}n = D(\varepsilon) \mathrm{d}\varepsilon = \frac{4\pi V}{h^3} p^2 \frac{\mathrm{d}p}{\mathrm{d}\varepsilon} \mathrm{d}\varepsilon  = \frac{2\pi V}{h^3} (2m)^{3/2} \varepsilon^{1/2} \mathrm{d}\varepsilon 
$$

#### 6.2
证明：
在长度 $L$ 内，自由粒子可能的状态数为
$$
\mathrm{d}n = \frac{2L}{h} \mathrm{d}p
$$
根据 $\varepsilon=p^2/2m$，得
$$
\mathrm{d}n = D(\varepsilon) \mathrm{d}\varepsilon = \frac{2L}{h} \frac{\mathrm{d}p}{\mathrm{d}\varepsilon} \mathrm{d}\varepsilon  = \frac{2L}{h} \sqrt{\frac{m}{2\varepsilon}} \mathrm{d}\varepsilon 
$$

#### 6.3
证明：
在面积 $L^2$ 内，自由粒子可能的状态数为
$$
\mathrm{d}n = \frac{2\pi L^2}{h^2} p \mathrm{d}p 
$$
根据 $\varepsilon=p^2/2m$，得
$$
\mathrm{d}n = D(\varepsilon) \mathrm{d}\varepsilon = \frac{2\pi L^2}{h^2} p\frac{\mathrm{d}p}{\mathrm{d}\varepsilon} \mathrm{d}\varepsilon  = \frac{2\pi L^2}{h^2} m \mathrm{d}\varepsilon 
$$

#### 6.4
解：
在体积 $V=L^3$ 内，相对论粒子的量子态数目有
$$
\mathrm{d} n = \frac{4\pi V}{h^3} p^2 \mathrm{d}p 
$$
根据极端相对论粒子能量动量关系 $\varepsilon=cp$，有
$$
\mathrm{d}n = D(\varepsilon) \mathrm{d}\varepsilon = \frac{4\pi V}{h^3} p^2 \frac{\mathrm{d}p}{\mathrm{d}\varepsilon} \mathrm{d}\varepsilon  = \frac{4\pi V}{c^3 h^3} \varepsilon^2 \mathrm{d}\varepsilon 
$$


### 5.22 

6.5

#### 6.5
证明：
两种粒子的分布 $\{a_l\},\{a_l'\}$ 满足
$$
\sum_l a_l = N, \;
\sum_l a_l' = N', \; 
\sum_l (a_l \varepsilon_l + a_l' \varepsilon_l') = E 
$$
由于粒子可分辨，处在一个个体量子态的粒子数不受限制，故微观状态数有
$$
\Omega = \frac{N!}{\prod_l a_l!} \prod_l \omega_l^{a_l} \\
\Omega' = \frac{N'!}{\prod_l a_l'!} \prod_l \omega_l'^{a_l'} 
$$
系统的总状态数 $\Omega\Omega'$ 应该达到极大值。故
$$
\ln (\Omega\Omega') 
= N\ln N - \sum_l a_l \ln a_l + \sum_l a_l \ln \omega_l + N'\ln N' - \sum_l a_l' \ln a_l' + \sum_l a_l' \ln \omega_l' 
$$
取极大值。对分布取变分得
$$
\delta \ln(\Omega\Omega') 
= - \sum_l \ln \frac{a_l}{\omega_l} \delta a_l - \sum_l \ln \frac{a_l'}{\omega_l'} \delta a_l' = 0 
$$
由约束条件，
$$
\delta N = \sum_l \delta a_l = 0, \; 
\delta N' = \sum_l \delta a_l' = 0, \; 
\delta E = \sum_l (\varepsilon_l \delta a_l + \varepsilon_l' \delta a_l') = 0 
$$
对任意 $\alpha,\alpha',\beta$ 有
$$
\delta \ln (\Omega\Omega') - \alpha \delta N - \alpha' \delta N' - \beta \delta E \\ 
= - \sum_l \left( \ln \frac{a_l}{\omega_l} + \alpha + \beta \varepsilon \right) \delta a_l - \sum_l \left( \ln \frac{a_l'}{\omega_l'} + \alpha' + \beta \varepsilon' \right) \delta a_l' = 0 
$$
故
$$
\ln \frac{a_l}{\omega_l} + \alpha + \beta \varepsilon = \ln \frac{a_l'}{\omega_l'} + \alpha' + \beta \varepsilon' = 0
$$
即分布满足
$$
a_l = \omega_l \mathrm{e}^{-\alpha-\beta\varepsilon_l}, \;
a_l' = \omega_l' \mathrm{e}^{-\alpha'-\beta\varepsilon_l'}
$$
系数由约束式确定。故互为热平衡的两个子系统有相同的 $\beta$。


### 5.24

6.6

#### 6.6
证明：
由上题我们知道，两种不同的粒子相互不影响，最后的状态数是对两种分布变分之和，不同粒子的区别只是状态数的表达式不同。故我们可以分开讨论，详细过程与上题相同。

若粒子为波色子，则微观状态数
$$
\Omega_B = \prod_l \frac{(\omega_l + a_l - 1)!}{a_l! (\omega_l - 1)!} 
$$
若粒子为费米子，则微观状态数
$$
\Omega_F = \prod_l \frac{\omega_l!}{a_l! (\omega_l - a_l)!} 
$$
故
$$
\delta \ln \Omega_B = \sum_l \ln\frac{\omega_l + a_l}{a_l} \delta a_l,\; 
\delta \ln \Omega_F = \sum_l \ln\frac{\omega_l - a_l}{a_l} \delta a_l
$$

以下步骤相同。两种粒子的分布 $\{a_l\},\{a_l'\}$ 满足
$$
\sum_l a_l = N, \;
\sum_l a_l' = N', \; 
\sum_l (a_l \varepsilon_l + a_l' \varepsilon_l') = E 
$$
系统的总状态数 $\Omega\Omega'$ 应该达到极大值。对分布取变分，两者求和为0。由约束条件，
$$
\delta N = \sum_l \delta a_l = 0, \; 
\delta N' = \sum_l \delta a_l' = 0, \; 
\delta E = \sum_l (\varepsilon_l \delta a_l + \varepsilon_l' \delta a_l') = 0 
$$
对任意 $\alpha,\alpha',\beta$ 有
$$
\delta \ln (\Omega\Omega') - \alpha \delta N - \alpha' \delta N' - \beta \delta E = 0 
$$
故对于波色子，有
$$
\ln \frac{\omega_l + a_l}{a_l} -\alpha - \beta \varepsilon_l = 0
$$
故对于费米子，有
$$
\ln \frac{\omega_l - a_l}{a_l} -\alpha - \beta \varepsilon_l = 0
$$
即波色子和费米子的分布分别满足
$$
a_{l,B} = \frac{\omega_l}{\exp(\alpha + \beta \varepsilon_l) - 1}, \;
a_{l,F} = \frac{\omega_l}{\exp(\alpha + \beta \varepsilon_l) + 1} 
$$
系数由约束式确定。


### 5.29

7.1，7.2，7.3，7.4，7.5，7.6

#### 7.1
证明：
取 $L^3$ 的立方体，对于非相对论的粒子
$$
\varepsilon = \frac{p^2}{2m} 
= \frac{1}{2m} \left( \frac{2\pi\hbar}{L} \right)^2 (n_x^2 + n_y^2 + n_z^2) ,\quad n_x,n_y,n_z \in \mathbb{Z} 
$$
我们记
$$
l = n_x^2 + n_y^2 + n_z^2 ,\;
a_l = \frac{(2\pi\hbar)^2}{2m} l 
$$
故 $\varepsilon_l = a_l V^{-2/3}$。根据公式，
$$
p = - \sum_l a_l \frac{\partial \varepsilon_l}{\partial V} 
= - \sum_l a_l \cdot -\frac23 a_l V^{-5/3} 
= \sum_l \frac2{3V} a_l \varepsilon_l 
= \frac23 \frac{U}{V} 
$$
与具体分布无关，故均适用。

#### 7.2
证明：
取 $L^3$ 的立方体，对于极端相对论的粒子
$$
\varepsilon = cp 
= c \frac{2\pi\hbar}{L} (n_x^2 + n_y^2 + n_z^2)^{1/2} ,\quad n_x,n_y,n_z \in \mathbb{Z} 
$$
我们记
$$
l = (n_x^2 + n_y^2 + n_z^2)^{1/2} ,\;
a_l = {2\pi c\hbar} l 
$$
故 $\varepsilon_l = a_l V^{-1/3}$。根据公式，
$$
p = - \sum_l a_l \frac{\partial \varepsilon_l}{\partial V} 
= - \sum_l a_l \cdot -\frac13 a_l V^{-4/3} 
= \sum_l \frac1{3V} a_l \varepsilon_l 
= \frac13 \frac{U}{V} 
$$
与具体分布无关，故均适用。

#### 7.3
证明：
不同能量零点的选取，有 $\varepsilon_l^* = \varepsilon_l + \Delta$。故配分函数
$$
Z_1 = \sum_l \omega_l \mathrm{e}^{-\beta \varepsilon_l} \\
$$
$$
Z_1^* = \sum_l \omega_l \mathrm{e}^{-\beta \varepsilon_l^*} = \mathrm{e}^{-\beta \Delta} \sum_l \omega_l \mathrm{e}^{-\beta \varepsilon_l} = \mathrm{e}^{-\beta \Delta} Z_1 
$$
这样两个配分函数之差 $\ln Z_1^* = \ln Z_1 - \beta \Delta$。故相应热力学函数有
$$
U^* = -N \frac{\partial}{\partial\beta} \ln Z_1^* = U + N\Delta \\
p^* = \frac{N}{\beta} \frac{\partial}{\partial V} \ln Z_1^* = p \\
S^* = Nk \left( \ln Z_1^* - \beta \frac{\partial}{\partial\beta} \ln Z_1^* \right) = S 
$$

#### 7.4
证明：
粒子处在量子态 s 上的概率
$$
P_s = \frac{\mathrm{e}^{-\beta \varepsilon_s}}{Z_1} 
$$
取对数得
$$
\ln P_s = -\ln Z_1 - \beta \varepsilon_s 
$$
系统的熵为
$$
S = Nk \left( \ln Z_1 - \beta \frac{\partial}{\partial\beta} \ln Z_1 \right) 
= Nk (\ln Z_1 + \beta \bar\varepsilon) \\
= Nk (\ln Z_1 + \beta \sum_s P_s \varepsilon_s) \\
= Nk \sum_s P_s (\ln Z_1 + \beta\varepsilon_s) \\
= -Nk \sum_s P_s \ln P_s 
$$

对于满足经典极限的非定域系统，熵
$$
S = Nk \left( \ln Z_1 - \beta \frac{\partial}{\partial\beta} \ln Z_1 \right) - k \ln N! \\
= -Nk \sum_s P_s \ln P_s - Nk (\ln N - 1) \\
= -k \sum_s f_s \ln f_s + Nk 
$$

#### 7.5
证明：
所有随机分布的微观状态数为
$$
\Omega = \frac{N!}{(Nx)![N(1-x)]!} 
$$
故熵
$$
S = k \ln \Omega = k \ln \frac{N!}{(Nx)![N(1-x)]!} \\
= k \{ N (\ln N - 1) - Nx (\ln Nx - 1) - N(1-x) [\ln N(1-x) - 1] \} \\
= - Nk [ x\ln x + (1-x) \ln(1-x) ]
$$

#### 7.6
证明：

(a)

格点和间隙的位置都是 $N$ 选 $n$，故可能的微观状态数为
$$
\Omega = \left( \frac{N!}{n!(N-n)!} \right)^2 
$$
故熵
$$
S = k \ln \Omega = 2k \ln \frac{N!}{n!(N-n)!} 
$$

(b)

自由能
$$
F = nu - TS 
= nu - 2kT \ln \frac{N!}{n!(N-n)!} \\
= nu - 2kT [ N \ln N - n \ln n - (N-n) \ln (N-n) ] 
$$
自由能极小条件
$$
\frac{\partial F}{\partial n} = u - 2kT \ln\frac{N-n}{n} \approx u - 2kT \ln\frac{N}{n} = 0 \quad (n \ll N)
$$
得到
$$
n \approx N \mathrm{e}^{-\frac{u}{2kT}} 
$$


### 5.31

7.7，7.8，7.9，7.11，7.14，7.16

#### 7.7
证明：
可能的微观状态数为
$$
\Omega = \frac{N!}{n!(N-n)!} 
$$
故熵
$$
S = k \ln \Omega = k \ln \frac{N!}{n!(N-n)!} 
$$
自由能
$$
F = nW - TS 
= nW - kT \ln \frac{N!}{n!(N-n)!} \\
= nW - kT [ N \ln N - n \ln n - (N-n) \ln (N-n) ] 
$$
自由能极小条件
$$
\frac{\partial F}{\partial n} = W - kT \ln\frac{N-n}{n} \approx W - kT \ln\frac{N}{n} = 0 \quad (n \ll N)
$$
得到
$$
n \approx N \mathrm{e}^{-\frac{W}{kT}} 
$$

#### 7.8
解：
探测器只能探测沿着一个方向传播的光的频率。根据对称性，我们不妨设探测器检测的光来自 z 方向。根据多普勒效应，频率改变
$$
\Delta \omega = \omega - \omega_0 = \omega_0 \frac{v_z}{c} \quad (v_z \ll c)
$$
故频率分布即为速度分布。
根据速度分布律，
$$
f_v(v_z) \mathrm{d} v_z = \mathrm{e}^{-\frac{m}{2kT} v_z^2} \mathrm{d} v_z 
$$
故有频率分布
$$
f_\omega(\omega) \mathrm{d}\omega = \frac{c}{\omega_0} \mathrm{e}^{-\frac{m}{2kT} \frac{(\omega - \omega_0)^2}{(\omega_0/c)^2}} \mathrm{d} \omega 
$$

#### 7.9
证明：
以气体本身为参考系，相对实验室系以恒定速度沿着z方向运动。在气体参考系即零动量系中，气体自然满足玻尔兹曼分布，即
$$
f = \mathrm{e}^{-\alpha -\frac{\beta}{2m}(p_x^2 + p_y^2 + p_z^2)} \frac{V\mathrm{d}p_x \mathrm{d}p_y \mathrm{d}p_z}{\hbar^3} 
$$
换回实验室系后，动量发生平移，即
$$
f' = \mathrm{e}^{-\alpha -\frac{\beta}{2m}[p_x^2 + p_y^2 + (p_z-p_0)^2]} \frac{V\mathrm{d}p_x \mathrm{d}p_y \mathrm{d}p_z}{\hbar^3} 
$$

#### 7.11
解：
二维气体的速度分布为
$$
f_{\vec{v}}(\vec{v}) = \frac{m}{2\pi kT} \mathrm{e}^{-\frac{m}{2kT} (v_x^2 + v_y^2)} \mathrm{d}v_x \mathrm{d}v_y 
$$
速率分布为
$$
f(v) = \frac{m}{2\pi kT} \mathrm{e}^{-\frac{m}{2kT} v^2} 2\pi v \mathrm{d}v = \frac{m}{kT} \mathrm{e}^{-\frac{m}{2kT} v^2} v \mathrm{d}v
$$
故平均速率，最概然速率，方均根速率分别为
$$
\bar{v} = \int v f(v) \mathrm{d} v = \frac{m}{kT} \int_0^{+\infty} \mathrm{e}^{-\frac{m}{2kT} v^2} v^2 \mathrm{d}v = \sqrt{\frac{\pi kT}{2m}} \\
\frac{\mathrm{d}f(v)}{\mathrm{d}v} = 0 \Rightarrow v_m = \sqrt{\frac{kT}{m}} \\
v_s = \sqrt{\bar{v^2}} = \sqrt{\int v^2 f(v) \mathrm{d} v} = \sqrt{\frac{m}{kT} \int_0^{+\infty} \mathrm{e}^{-\frac{m}{2kT} v^2} v^3 \mathrm{d}v} = \sqrt{\frac{2kT}{m}} 
$$

#### 7.14
解：
泻流分布
$$
\mathrm{d} \Gamma(v) = \pi n \left( \frac{m}{2\pi kT} \right)^{3/2} \mathrm{e}^{-\frac{m}{2kT} v^2} v^3 \mathrm{d}v 
$$
故平均速率，方均根速率，平均能量分别为
$$
\bar{v} = \frac{\int v \mathrm{d} \Gamma(v)}{\int \mathrm{d} \Gamma(v)} 
= \frac{\int_0^{+\infty} \mathrm{e}^{-\frac{m}{2kT} v^2} v^4 \mathrm{d} v}{\int_0^{+\infty} \mathrm{e}^{-\frac{m}{2kT} v^2} v^3 \mathrm{d} v} 
= \sqrt{\frac{9\pi kT}{8m}} 
$$
$$
v_s = \sqrt{\bar{v^2}} = \sqrt{\frac{\int v^2 \mathrm{d} \Gamma(v)}{\int \mathrm{d} \Gamma(v)}} 
= \sqrt{\frac{\int_0^{+\infty} \mathrm{e}^{-\frac{m}{2kT} v^2} v^5 \mathrm{d} v}{\int_0^{+\infty} \mathrm{e}^{-\frac{m}{2kT} v^2} v^3 \mathrm{d} v}} 
= \sqrt{\frac{4kT}m}
$$
$$
\bar{E_k} = \frac12 m \bar{v^2} = 2kT 
$$

#### 7.16
解：
$$
\varepsilon = \frac{1}{2m} (p_x^2 + p_y^2 + p_z^2) + ax^2 + bx 
= \frac{1}{2m} (p_x^2 + p_y^2 + p_z^2) + a \left(x + \frac{b}{2a} \right)^2 - \frac{b^2}{4a} 
$$
根据能量均分定理，
$$
\bar{\varepsilon} 
= \frac{1}{2m} (\bar{p_x^2} + \bar{p_y^2} + \bar{p_z^2}) + a \bar{\left(x + \frac{b}{2a} \right)^2} - \frac{b^2}{4a} 
= 2kT - \frac{b^2}{4a} 
$$


### 6.5

7.10，7.12，7.13

#### 7.10
解：
速度分布满足
$$
f = \left( \frac{m}{2\pi kT} \right)^{3/2} \mathrm{e}^{-\frac{m}{2kT}[v_x^2 + v_y^2 + (v_z-v_0)^2]} \mathrm{d}v_x \mathrm{d}v_y \mathrm{d}v_z 
$$
故平均平动动能
$$
\bar{\varepsilon} = \left( \frac{m}{2\pi kT} \right)^{3/2} \iiint \frac12 m (v_x^2 + v_y^2 + v_z^2) \mathrm{e}^{-\frac{m}{2kT}[v_x^2 + v_y^2 + (v_z-v_0)^2]} \mathrm{d}v_x \mathrm{d}v_y \mathrm{d}v_z \\ 
= kT + \left( \frac{m}{2\pi kT} \right)^{1/2} \int_{-\infty}^{+\infty} \frac12 m v_z^2 \mathrm{e}^{-\frac{m}{2kT}(v_z-v_0)^2} \mathrm{d}v_z \\ 
= kT + \frac12 kT + m v_0^2 - \frac12 m v_0^2 
= \frac32 kT + \frac12 m v_0^2  
$$

#### 7.12
解：
两个粒子的速度联合分布
$$
\left( \frac{m}{2\pi kT} \right)^{3/2} \mathrm{e}^{-\frac{m\vec{v}_1^2}{2kT}} \mathrm{d}\vec{v}_1 \left( \frac{m}{2\pi kT} \right)^{3/2} \mathrm{e}^{-\frac{m\vec{v}_2^2}{2kT}} \mathrm{d}\vec{v}_2 
$$
做变换
$$
\vec{v}_c = \frac12 (\vec{v}_1 + \vec{v}_2),\; 
\vec{v}_r = \vec{v}_1 - \vec{v}_2 
$$
又因为
$$
\frac12 m \vec{v}_1^2 + \frac12 m \vec{v}_2^2 = \frac12 2m \vec{v}_c^2 + \frac12 \frac{m}2 \vec{v}_r^2 
$$
故联合分布可以写为
$$
\left( \frac{2m}{2\pi kT} \right)^{3/2} \mathrm{e}^{-\frac{2m\vec{v}_c^2}{2kT}} \mathrm{d}\vec{v}_c \left( \frac{m/2}{2\pi kT} \right)^{3/2} \mathrm{e}^{-\frac{m\vec{v}_r^2/2}{2kT}} \mathrm{d}\vec{v}_r 
$$
其中可以看出第二项为相对速度分布。积分得相对速率分布
$$
4\pi \left( \frac{m/2}{2\pi kT} \right)^{3/2} \mathrm{e}^{-\frac{m{v}_r^2/2}{2kT}} v_r^2 \mathrm{d}{v}_r 
$$
平均相对速率
$$
\bar{v}_r = 4\pi \int_0^{+\infty} \left( \frac{m/2}{2\pi kT} \right)^{3/2} \mathrm{e}^{-\frac{m{v}_r^2/2}{2kT}} v_r^3 \mathrm{d}{v}_r 
= \sqrt{\frac{8kT}{\pi m/2}} = \sqrt2 \bar{v} 
$$

#### 7.13
证明：
单位速度分布，单位时间碰壁（假设为z方向垂直）的分子数为
$$
\mathrm{d}\Gamma = f(\vec{v}) v_z \mathrm{d}\vec{v} 
= f(\vec{v}) v \cos\theta v^2 \sin\theta \mathrm{d}v \mathrm{d}\theta \mathrm{d}\phi 
$$
角向积分得
$$
\int_0^{2\pi} \int_0^{\pi/2} \cos\theta \sin\theta \mathrm{d}\theta \mathrm{d}\phi = \pi 
$$
故得泻流分布
$$
\mathrm{d}\Gamma(v) = \pi n \left( \frac{m}{2\pi kT} \right)^{3/2} \mathrm{e}^{-\frac{m{v}^2}{2kT}} v^3 \mathrm{d}{v} 
$$


### 6.7 

7.17，7.18，7.19，7.20，7.21，7.22，7.23，7.24

#### 7.17
证明：
重力场下，粒子能量为
$$
\varepsilon = \frac1{2m} (p_x^2 + p_y^2 + p_z^2) + mgz 
$$
故配分函数
$$
Z_1 = \frac1{h^3} \iiint \iiint \mathrm{e}^{-\frac{\beta}{2m}(p_x^2 + p_y^2 + p_z^2) - \beta mgz} \,\mathrm{d}^3 x \mathrm{d}^3 p \\
= \left( \frac{2\pi m}{h^2 \beta} \right)^{3/2} \iint \mathrm{d}x \mathrm{d}y \int_0^H \mathrm{e}^{-\beta mgz} \,\mathrm{d}z \\ 
= \left( \frac{2\pi m}{h^2 \beta} \right)^{3/2} S \frac{1 - \mathrm{e}^{-\beta mgH}}{\beta mg} 
$$
气体内能
$$
U = -N \frac{\partial}{\partial\beta} \ln Z_1 
= \frac32 \frac{N}\beta + \frac{N}\beta - \frac{NmgH}{\mathrm{e}^{\beta mgH} - 1} 
= U_0 + NkT - \frac{NmgH}{\mathrm{e}^{mgH/kT} - 1} 
$$
热容
$$
C_V = \frac{\partial U}{\partial T} 
= C_V^0 + Nk - \frac{N(mgH)^2 \mathrm{e}^{mgH/kT}}{(\mathrm{e}^{mgH/kT} - 1)^2} \frac{1}{kT^2}
$$

#### 7.18
解：
双原子分子中的相对振动可以看作线性谐振子，能级为
$$
\varepsilon_n = \left(n + \frac12\right) \hbar \omega ,\quad n = 0,1,2,\dots
$$
振动配分函数
$$
Z_1^V = \sum_{n=0}^{+\infty} \mathrm{e}^{-\beta\hbar\omega \left(n + \frac12\right)} 
= \frac{\mathrm{e}^{-\frac{\beta\hbar\omega}2}}{1 - \mathrm{e}^{-\beta\hbar\omega}} 
$$
故振动熵
$$
S^V = Nk \left( \ln Z_1^V - \beta \frac{\partial}{\partial\beta} \ln Z_1^V \right) \\
= Nk \left[ \frac{\beta\hbar\omega}{\mathrm{e}^{\beta\hbar\omega} - 1} - \ln(1 - \mathrm{e}^{-\beta\hbar\omega}) \right] \\ 
= Nk \left[ \frac{\theta_V/T}{\mathrm{e}^{\theta_V/T} - 1} - \ln(1 - \mathrm{e}^{-\theta_V/T}) \right] 
$$
其中 $\theta_V = \hbar\omega/k$ 为振动特征温度。

#### 7.19
解：
能级间距远小于 $kT$，可以采用经典近似。转动配分函数
$$
Z_1^r = \int \mathrm{e}^{-\frac{\beta}{2l}(p_\theta^2 + \frac1{\sin^2\theta} p_\varphi^2)} \,\frac{\mathrm{d}p_\theta \mathrm{d}p_\varphi \mathrm{d}\theta \mathrm{d}\varphi}{h^2} 
= \frac{8\pi^2 I}{h^2 \beta} 
$$
故转动熵
$$
S^r = Nk \left( \ln Z_1^r - \beta \frac{\partial}{\partial\beta} \ln Z_1^r \right) \\
= Nk \left( \ln \frac{2I}{\hbar^2 \beta} + 1 \right) \\ 
= Nk (\ln T / \theta_r + 1) 
$$
其中 $\theta_r = \hbar^2/2Ik$ 为转动特征温度。

#### 7.20
解：
爱因斯坦固体配分函数
$$
Z_1 = \sum_{n=0}^{+\infty} \mathrm{e}^{-\beta\hbar\omega \left(n + \frac12\right)} 
= \frac{\mathrm{e}^{-\frac{\beta\hbar\omega}2}}{1 - \mathrm{e}^{-\beta\hbar\omega}}
$$
熵
$$
S = 3Nk \left( \ln Z_1 - \beta \frac{\partial}{\partial\beta} \ln Z_1 \right) \\
= 3Nk \left[ \frac{\beta\hbar\omega}{\mathrm{e}^{\beta\hbar\omega} - 1} - \ln(1 - \mathrm{e}^{-\beta\hbar\omega}) \right] \\ 
= 3Nk \left[ \frac{\theta_E/T}{\mathrm{e}^{\theta_E/T} - 1} - \ln(1 - \mathrm{e}^{-\theta_E/T}) \right] 
$$
其中 $\theta_E = \hbar\omega/k$ 为爱因斯坦特征温度。

#### 7.21
解：
配分函数
$$
Z_1 = \mathrm{e}^{-\beta\varepsilon_0} + \mathrm{e}^{-\beta\varepsilon_1} 
= \mathrm{e}^{-\beta\varepsilon_0} [1 + \mathrm{e}^{-\beta(\varepsilon_1 - \varepsilon_0)}] 
$$
故内能
$$
U = -N \frac{\partial}{\partial\beta} \ln Z_1 
= N\varepsilon_0 + \frac{N(\varepsilon_1 - \varepsilon_0)}{1 + \mathrm{e}^{\beta(\varepsilon_1 - \varepsilon_0)}} 
$$
熵
$$
S = Nk \left( \ln Z_1 - \beta \frac{\partial}{\partial\beta} \ln Z_1 \right) \\
= Nk \left\{ \ln[1 + \mathrm{e}^{-\beta(\varepsilon_1 - \varepsilon_0)}] + \frac{\beta(\varepsilon_1 - \varepsilon_0)}{1 + \mathrm{e}^{\beta(\varepsilon_1 - \varepsilon_0)}} \right\} 
$$
高温极限下
$$
U = N \frac{\varepsilon_1 + \varepsilon_0}{2} ,\quad 
S = Nk \ln2 
$$
低温极限下
$$
U = N \varepsilon_0 ,\quad 
S = 0 
$$

#### 7.22
解：
原子磁矩在外磁场中的势能可能为 $0,\pm\mu B$。故配分函数
$$
Z_1 = 1 + \mathrm{e}^{\beta\mu B} + \mathrm{e}^{-\beta\mu B} 
= 1 + 2 \cosh(\beta\mu B) 
$$
磁化强度
$$
\mathscr{M} = \frac{n}{\beta} \frac{\partial}{\partial B} \ln Z_1 
= n\mu \frac{2\sinh \beta\mu B}{1 + 2\cosh \beta\mu B} 
$$
弱场高温极限下 $\beta\mu B \ll 1$，
$$
\mathscr{M} = \frac23 \frac{n\mu^2}{kT} B 
$$
强场低温极限下 $\beta\mu B \gg 1$，
$$
\mathscr{M} = n\mu 
$$

#### 7.23
证明：
根据公式
$$
\varepsilon^r = \frac1{2I} \left( p_\theta^2 + \frac1{\sin^2\theta} p_\varphi^2 \right) - d_0 E \cos \theta 
$$
经典转动配分函数
$$
Z_1^r = \int \mathrm{e}^{-\frac{\beta}{2l}(p_\theta^2 + \frac1{\sin^2\theta} p_\varphi^2)} \mathrm{e}^{\beta d_0 E \cos\theta} \,\frac{\mathrm{d}p_\theta \mathrm{d}p_\varphi \mathrm{d}\theta \mathrm{d}\varphi}{h^2} \\ 
= \frac{4\pi^2 I}{h^2 \beta} \int_0^\pi \mathrm{e}^{\beta d_0 E \cos\theta} \sin\theta \,\mathrm{d}\theta \\ 
= \frac{I}{\beta\hbar^2} \frac{\mathrm{e}^{\beta d_0 E} - \mathrm{e}^{-\beta d_0 E}}{\beta d_0 E} 
$$

#### 7.24
证明：
在高温极限下 $\beta d_0 E \ll 1$，电极化强度
$$
P = \frac{n}{\beta} \frac{\partial}{\partial E} \ln Z_1 
= n d_0 \left[ \frac{\mathrm{e}^{\beta d_0 E} + \mathrm{e}^{-\beta d_0 E}}{\mathrm{e}^{\beta d_0 E} - \mathrm{e}^{-\beta d_0 E}} - \frac1{\beta d_0 E} \right] 
\approx \frac{n d_0^2}{3kT} E 
$$


### 6.12 

8.1，8.2，8.3 

#### 8.1
证明：
对于理想波色系统，
$$
\Omega = \prod_l \frac{(\omega_l + a_l - 1)!}{a_l! (\omega_l - 1)!} \\
\ln \Omega = \sum_l [ (\omega_l + a_l - 1) \ln (\omega_l + a_l - 1) - a_l \ln a_l - (\omega_l - 1) \ln (\omega_l - 1) ] 
$$
巨配分函数
$$
\ln \Xi = - \sum_l \omega_l \ln (1 - \mathrm{e}^{- \alpha - \beta \varepsilon_l}) 
% = \sum_l \omega_l \ln \frac{\omega_l}{\omega_l - a_l} 
$$
故熵
$$
S = k \left( \ln \Xi - \alpha \frac{\partial}{\partial\alpha} \ln \Xi - \beta \frac{\partial}{\partial\beta} \ln \Xi \right) \\
= - k \sum_l \left[ (\omega_l - 1) \ln \frac{\omega_l - 1}{\omega_l - a_l - 1} + a_l \ln \frac{\omega_l - a_l - 1}{a_l} \right] \\
= k \sum_l [ (\omega_l + a_l - 1) \ln (\omega_l + a_l - 1) - a_l \ln a_l - (\omega_l - 1) \ln (\omega_l - 1) ] \\
= k \ln \Omega 
$$

对于理想费米系统，
$$
\Omega = \prod_l \frac{\omega_l!}{a_l! (\omega_l - a_l)!} \\
\ln \Omega = \sum_l [ \omega_l \ln \omega_l - a_l \ln a_l - (\omega_l - a_l) \ln (\omega_l - a_l) ] 
$$
巨配分函数
$$
\ln \Xi = \sum_l \omega_l \ln (1 + \mathrm{e}^{- \alpha - \beta \varepsilon_l}) 
= \sum_l \omega_l \ln \frac{\omega_l}{\omega_l - a_l} 
$$
故熵
$$
S = k \left( \ln \Xi - \alpha \frac{\partial}{\partial\alpha} \ln \Xi - \beta \frac{\partial}{\partial\beta} \ln \Xi \right) \\
= k \sum_l \left( \omega_l \ln \frac{\omega_l}{\omega_l - a_l} + a_l \ln \frac{\omega_l - a_l}{a_l} \right) \\
= k \sum_l [ \omega_l \ln \omega_l - a_l \ln a_l - (\omega_l - a_l) \ln (\omega_l - a_l) ] 
= k \ln \Omega 
$$

#### 8.2
证明：
对于理想费米系统，
$$
S_\textrm{F.D.} = k \sum_l [ \omega_l \ln \omega_l - a_l \ln a_l - (\omega_l - a_l) \ln (\omega_l - a_l) ] \\
= - k \sum_l \omega_l \left[ \left( 1 - \frac{a_l}{\omega_l} \right) \ln \left( 1 - \frac{a_l}{\omega_l} \right) + \frac{a_l}{\omega_l} \ln \frac{a_l}{\omega_l} \right] \\
= - k \sum_l [ f_s \ln f_s + (1 - f_s) \ln (1 - f_s) ] 
$$
对于理想波色系统，
$$
S_\textrm{B.E.} = k \sum_l [ (\omega_l + a_l - 1) \ln (\omega_l + a_l - 1) - a_l \ln a_l - (\omega_l - 1) \ln (\omega_l - 1) ] \\
= - k \sum_l (\omega_l - 1) \left[ \left( 1 + \frac{a_l}{\omega_l - 1} \right) \ln \left( 1 + \frac{a_l}{\omega_l - 1} \right) - \frac{a_l}{\omega_l - 1} \ln \frac{a_l}{\omega_l - 1} \right] \\
= - k \sum_l [ f_s \ln f_s - (1 + f_s) \ln (1 + f_s) ] 
$$
当 $f_s \ll 1$ 时，
$$
(1 - f_s) \ln (1 - f_s) \approx - f_s,\; 
- (1 + f_s) \ln (1 + f_s) \approx - f_s 
$$
故有
$$
S_\textrm{B.E.} \approx S_\textrm{F.D.} \approx S_\textrm{M.B.} = - k \sum_s (f_s \ln f_s - f_s) 
$$

#### 8.3
解：
弱简并费米（波色）气体的内能
$$
U = \frac32 NkT \left[ 1 \pm \frac1{4\sqrt2} \frac1g \frac{N}V \left( \frac{h^2}{2\pi m kT} \right)^\frac32 \right] 
$$
其中上面表示费米，下面表示波色。压强
$$
p = \frac23 \frac{U}{V} 
= nkT \left[ 1 \pm \frac1{4\sqrt2} \frac1g \frac{N}V \left( \frac{h^2}{2\pi m kT} \right)^\frac32 \right] 
$$
定容热容
$$
C_V = \left( \frac{\partial U}{\partial T} \right)_V 
= \frac32 Nk \left[ 1 \mp \frac1{8\sqrt2} \frac1g \frac{N}V \left( \frac{h^2}{2\pi m kT} \right)^\frac32 \right] 
$$
熵
$$
S = \int \frac{C_V}{T} \,\mathrm{d}T + S_0(V) \\
= \frac32 Nk \ln T \pm Nk \frac1{8\sqrt2} \frac1g \frac{N}V \left( \frac{h^2}{2\pi m kT} \right)^\frac32 + S_0(V) 
$$
根据理想极限，$N/V (h^2/2\pi mkT)^{3/2} \ll 1$，有
$$
S = Nk \left[ \ln ng \left( \frac{2\pi m kT}{h^2} \right)^\frac32 + \frac52 \pm \frac1{8\sqrt2} \frac1g \frac{N}V \left( \frac{h^2}{2\pi m kT} \right)^\frac32 \right] 
$$


### 6.14

8.4，8.5，8.6，8.8，8.10，8.11

#### 8.4
证明：
二维自由粒子
$$
\mathrm{d}n = D(\varepsilon) \mathrm{d}\varepsilon = \frac{2\pi L^2}{h^2} m \mathrm{d}\varepsilon 
$$
假设临界温度 $T_C$ 应满足
$$
\int_0^{+\infty} \frac{D(\varepsilon)\,\mathrm{d}\varepsilon}{\mathrm{e}^{\varepsilon/kT_C} - 1} = n 
$$
令 $x = \varepsilon/kT_C$，则
$$
\frac{2\pi L^2}{h^2} mkT_C \int_0^{+\infty} \frac{\mathrm{d}x}{\mathrm{e}^{x} - 1} = n 
$$
但是上式中积分发散，故不存在这样的 $T_C$，即二维理想波色气体不会发生波色-爱因斯坦凝聚。

#### 8.5
证明：
三维谐振势场下原子能级
$$
\varepsilon(n_x,n_y,n_z) = \hbar \omega_x \left( n_x + \frac12 \right) + \hbar \omega_y \left( n_y + \frac12 \right) + \hbar \omega_z \left( n_z + \frac12 \right) 
$$
即 $\varepsilon_0 = \frac12\hbar(\omega_x + \omega_y + \omega_z)$。当温度降到临界温度时，有
$$
\sum_{n_x,n_y,n_z} \frac1{\mathrm{e}^{\frac{\hbar}{kT_C}(n_x\omega_x + n_y\omega_y + n_z\omega_z)} - 1} = N 
$$
记 $\tilde{n}_x = \hbar\omega_x n_x/kT_C,\tilde{n}_y = \hbar\omega_y n_y/kT_C,\tilde{n}_z = \hbar\omega_z n_z/kT_C$，在 $N\rightarrow\infty,\bar\omega\rightarrow0$ 的情况下，变求和为积分，即
$$
\left( \frac{kT_C}{\hbar\bar\omega} \right)^3 \iiint \frac{\mathrm{d}\bar{n}_x \mathrm{d}\bar{n}_y \mathrm{d}\bar{n}_z}{\mathrm{e}^{\bar{n}_x + \bar{n}_y + \bar{n}_z} - 1} = N 
$$
上式中积分式的结果为 $1.202$。故
$$
N = 1.202 \left( \frac{kT_C}{\hbar\bar\omega} \right)^3 
$$
当温度 $T<T_C$ 时，基态原子数
$$
N - N_0 = 1.202 \left( \frac{kT_C}{\hbar\bar\omega} \right)^3 
$$
即
$$
\frac{N_0}{N} = 1 - \left( \frac{T}{T_C} \right)^3 
$$

#### 8.6
证明：
同上题，z方向上原子冻结在基态。故上题中三维改为二维情况。
$$
\iint \frac{\mathrm{d}\bar{n}_x \mathrm{d}\bar{n}_y}{\mathrm{e}^{\bar{n}_x + \bar{n}_y} - 1} = 1.645 
$$
故
$$
N = 1.645 \left( \frac{kT_C}{\hbar\bar\omega} \right)^2 
$$
当温度 $T<T_C$ 时，基态原子数
$$
N - N_0 = 1.645 \left( \frac{kT_C}{\hbar\bar\omega} \right)^2 
$$
即
$$
\frac{N_0}{N} = 1 - \left( \frac{T}{T_C} \right)^2 
$$

#### 8.8
证明：
辐射内能密度
$$
u(\omega, T) \mathrm{d}\omega = \frac1{\pi^2c^3} \frac{\hbar\omega^3}{\mathrm{e}^{\frac{\hbar\omega}{kT}} - 1} \mathrm{d}\omega 
$$
根据 $\omega = 2\pi c/\lambda$，有
$$
u_\lambda \mathrm{d}\lambda = \frac{8\pi hc}{\lambda^5} \frac{\mathrm{d}\lambda}{\mathrm{e}^{\frac{hc}{\lambda kT}} - 1} 
$$
令 $x = hc/\lambda kT$，则极大值应该有
$$
\frac{\mathrm{d}}{\mathrm{d}x} \left( \frac{x^5}{\mathrm{e}^x - 1} \right) = 0 
$$
即 $\lambda_m$ 满足 $x_m = hc/\lambda_m kT$ 是
$$
5\mathrm{e}^{-x} + x = 5 
$$
的根。这个根为 $x=4.9651$。故
$$
\lambda_m T = \frac{hc}{4.9651 k} 
$$

#### 8.10
解：
根据光子气体内能，得到热容
$$
C_V = \left( \frac{\partial U}{\partial T} \right)_V 
= \frac{4\pi^2 k^4}{15c^3 \hbar^3} VT^3 
$$
光子气体的熵
$$
S = \int_0^T \frac{C_V}{T} \,\mathrm{d}T 
= \frac{4\pi^2 k^4}{15c^3 \hbar^3}V \int_0^T T^2 \,\mathrm{d}T 
= \frac{4\pi^2 k^4}{45c^3 \hbar^3} VT^3 
$$

#### 8.11
解：
根据辐射通量密度公式
$$
J_u = \frac{\pi^2 k^4}{60c^2 \hbar^3} T^4 
$$
当 $T = 6000\,\mathrm{K}$ 时，$J_u = 7.14\times10^7 \,\mathrm{J\cdot m}^{-2}$。
当 $T = 1000\,\mathrm{K}$ 时，$J_u = 5.51\times10^4 \,\mathrm{J\cdot m}^{-2}$。


### 6.19

8.17，8.20，8.22，8.23，8.24，8.25

#### 8.17
证明：
$0\,\mathrm{K}$ 的费米气体压强
$$
p = \frac25 n \mu(0) 
= \frac25 \frac{\hbar^2}{2m} (3\pi^2 N)^{\frac23} N \frac1V^\frac53 
$$
故
$$
\left( \frac{\partial p}{\partial V} \right)_T = - \frac23 \frac{\hbar^2}{2m} (3\pi^2 N)^{\frac23} N \frac1V^\frac73 
= - \frac23 n \mu(0) \frac1V 
$$
故等温压缩系数
$$
\kappa_T = -\frac1V \left( \frac{\partial V}{\partial p} \right)_T = \frac32 \frac1{n\mu(0)} 
$$
在 $T=0$ 下，绝热压缩系数
$$
\kappa_S = -\frac1V \left( \frac{\partial V}{\partial p} \right)_S = -\frac1V \left( \frac{\partial V}{\partial p} \right)_T = \frac32 \frac1{n\mu(0)} 
$$

#### 8.20
解：
一级修正值
$$
\mu(T) - \mu(0) = - \mu(0) \frac{\pi^2}{12} \left[ \frac{kT}{\mu(0)} \right]^2 
= - 7.04 \times \frac{\pi^2}{12} \left[ \frac{kT}{\mu(0)} \right]^2 
= - 7.88 \times 10^{-5} \,\mathrm{eV}
$$

#### 8.22
解：
粒子能级
$$
\varepsilon(n_x,n_y,n_z) = \hbar\omega_r (n_x + n_y + \lambda n_z) + \frac12 \hbar\omega_r (2 + \lambda) 
$$
取常数项为势能零点。由 $kT \gg \hbar\omega_r$，化学势有
$$
N = \sum_{n_x,n_y,n_z} \frac1{\mathrm{e}^{\beta [\hbar \omega_r(n_x + n_y + \lambda n_z) - \mu]} + 1} \\
= \iiint \frac{\mathrm{d}{n}_x \mathrm{d}{n}_y \mathrm{d}{n}_z}{\mathrm{e}^{\beta [\hbar \omega_r(n_x + n_y + \lambda n_z) - \mu]} + 1} \\ 
= \frac1{\lambda(\hbar\omega_r)^3} \int \frac{\varepsilon^2}{2} \frac{\mathrm{d}\varepsilon}{\mathrm{e}^{\beta (\varepsilon - \mu)} + 1} 
$$
在绝对零度，有
$$
N = \frac1{\lambda(\hbar\omega_r)^3} \int_0^{\mu(0)} \frac{\varepsilon^2}{2} \,\mathrm{d}\varepsilon 
= \frac1{\lambda(\hbar\omega_r)^3} \frac{\mu^3(0)}{6} 
$$
故化学势
$$
\mu(0) = \hbar\omega_r (6\lambda N)^\frac13 
$$
平均能量
$$
\bar \varepsilon = \frac1N \frac1{\lambda(\hbar\omega_r)^3} \int_0^{\mu(0)} \frac{\varepsilon^2}{2} \varepsilon \,\mathrm{d}\varepsilon 
= \frac34 \mu(0) 
$$
代入数值得
$$
\mu(0) = 2.98 \times 10^{-10} \,\mathrm{eV} \\
\bar{\varepsilon} = 2.24 \times 10^{-10} \,\mathrm{eV} 
$$

#### 8.23
解：
低温极限下，
$$
N = \frac1{\lambda(\hbar\omega_r)^3} \int_0^{+\infty} \frac{\varepsilon^2}{2} \frac{\mathrm{d}\varepsilon}{\mathrm{e}^{\frac{\varepsilon - \mu}{kT}} + 1} \\ 
\approx \frac1{\lambda(\hbar\omega_r)^3} \frac{\mu^3}{6} \left[ 1 + \pi^2 \left(\frac{kT}{\mu}\right)^2 \right] 
$$
故有化学势
$$
\mu \approx \mu(0) \left\{ 1 - \frac{\pi^2}{3} \left[ \frac{kT}{\mu(0)} \right]^2 \right\} 
$$
内能
$$
U = \frac1{\lambda(\hbar\omega_r)^3} \int_0^{+\infty} \frac{\varepsilon^2}{2} \frac{\varepsilon \mathrm{d}\varepsilon}{\mathrm{e}^{\frac{\varepsilon - \mu}{kT}} + 1} \\ 
\approx \frac34 N \mu(0) \left\{ 1 + \frac{2\pi^2}{3} \left[ \frac{kT}{\mu(0)} \right]^2 \right\} 
$$
热容
$$
C = \frac{\mathrm{d}U}{\mathrm{d}T} = Nk\pi^2 \frac{kT}{\mu(0)} 
$$
在高温极限下，费米气体近似非简并，故采用玻尔兹曼统计。配分函数
$$
Z_1 = \frac1{\lambda(\hbar\omega_r)^3} \int_0^{+\infty} \frac{\varepsilon^2}{2} {\mathrm{e}^{-\beta\varepsilon}} \,{\mathrm{d}\varepsilon} 
= \frac1{\lambda(\hbar\omega_r)^3} \frac1{\beta^3} 
$$
化学势
$$
\mu = -kT \ln \frac{Z_1}{N} 
= -kT \ln 6 \left[ \frac{kT}{\mu(0)} \right]^3 
$$
内能
$$
U = -N \frac{\partial}{\partial\beta} \ln Z_1 = 3NkT 
$$

#### 8.24
解：
简并费米气体密度
$$
n = \frac{A/2}{\frac43 \pi (1.3\times10^{-15})^3 A} = \frac38 \pi \frac1{(1.3\times10^{-15})^3} \,\mathrm{m}^{-3} 
$$
$$
\mu(0) = \frac{\hbar^2}{2m} (3\pi^2n)^\frac23 = 0.43\times10^{-11} \,\mathrm{J} 
$$
平均动能
$$
\bar \varepsilon = \frac35 \mu(0) = 0.26\times10^{-11} \,\mathrm{J} 
$$

#### 8.25
解：
$$
\mu(0) = \frac{\hbar^2}{2m} (3\pi^2n)^\frac23 
$$
热容
$$
C_V = Nk \frac{\pi^2}{2} \frac{kT}{\mu(0)} 
= \frac{\pi^2}{\hbar^2} \frac{m^* kT}{(3\pi^2n)^\frac23}
= 2.89 NkT 
$$
故有有效质量
$$
m^* \approx 3m 
$$


### 6.21 

9.1，9.3，9.4，9.5，9.6，9.15，9.16，9.19，9.21，9.22

#### 9.1
证明：
根据 $\rho_s = 1/\Omega$，有熵
$$
S = k \ln \Omega = k \sum_s \rho_s \ln \Omega 
= - k \sum_s \rho_s \ln \rho_s 
$$

#### 9.3
解：
N个单原子分子气体
$$
E = \sum_{i=1}^{3N} \frac{p_i^2}{2m} 
$$
配分函数
$$
Z = \frac{1}{N!h^{3N}} \int \mathrm{e}^{-\beta E} \,\mathrm{d}\Omega \\ 
= \frac{V^N}{N!h^{3N}} \prod_{i=1}^{3N} \int \mathrm{e}^{-\beta \frac{p_i^2}{2m}} \,\mathrm{d}p_i \\ 
= \frac{V^N}{N!h^{3N}} \left( \frac{2\pi m}{\beta} \right)^{\frac{3N}{2}} 
$$
压强
$$
p = \frac{1}{\beta} \frac{\partial}{\partial V} \ln Z = \frac{N}{V\beta} = \frac{NkT}{V}  
$$
即物态方程
$$
pV = NkT 
$$
内能
$$
U = - \frac{\partial}{\partial\beta} \ln Z = \frac{3N}{2} kT 
$$
熵
$$
S = k \left( \ln Z - \beta \frac{\partial}{\partial\beta} \ln Z \right) \\ 
= Nk \left[ \frac32 \ln \frac{2\pi mkT}{h^2} + \ln\frac{V}{N} + \frac52 \right] 
$$
化学势
$$
\mu = - kT \ln Z = -kT \left[ \frac32 \ln \frac{2\pi mkT}{h^2} + \ln\frac{V}{N} \right] 
$$

#### 9.4
解：
对于单原子分子，有
$$
C_V = \frac32 Nk 
$$
故能量相对涨落
$$
\frac{\bar{(E - \bar{E})^2}}{\bar{E}^2} = \frac{kT^2 C_V}{\bar{E}^2} 
= \frac{2}{3N} 
$$
对于双原子分子，有
$$
C_V = \frac52 Nk 
$$
故能量相对涨落
$$
\frac{\bar{(E - \bar{E})^2}}{\bar{E}^2} = \frac{kT^2 C_V}{\bar{E}^2} 
= \frac{2}{5N} 
$$

#### 9.5
解：
混合气体能量
$$
E = \sum_{i=1}^{3N_A} \frac{p_{Ai}^2}{2m_A} + \sum_{i=1}^{3N_B} \frac{p_{Bi}^2}{2m_B} 
$$
配分函数
$$
Z = \frac{1}{N_A!N_B!h^{3N_A}h^{3N_B}} \int \mathrm{e}^{-\beta E} \,\mathrm{d}\Omega \\ 
= \frac{1}{N_A!h^{3N_A}} \int \mathrm{e}^{-\beta E_A} \,\mathrm{d}\Omega_A \cdot \frac{1}{N_B!h^{3N_B}} \int \mathrm{e}^{-\beta E_B} \,\mathrm{d}\Omega_B \\ 
= Z_A Z_B 
$$
故物态方程
$$
pV = (N_A + N_B) kT 
$$
内能
$$
U = - \frac{\partial}{\partial\beta} \ln Z = \frac{3}{2} (N_A + N_B) kT 
$$
熵
$$
S = k \left( \ln Z - \beta \frac{\partial}{\partial\beta} \ln Z \right) \\ 
= N_A k \left[ \frac32 \ln \frac{2\pi m_AkT}{h^2} + \ln\frac{V}{N_A} + \frac52 \right] + N_B k \left[ \frac32 \ln \frac{2\pi m_BkT}{h^2} + \ln\frac{V}{N_B} + \frac52 \right] 
$$

#### 9.6
解：
极端相对论气体能量
$$
E = \sum_{i=1}^{3N} cp_i 
$$
配分函数
$$
Z = \frac{1}{N!h^{3N}} \int \mathrm{e}^{-\beta E} \,\mathrm{d}\Omega \\ 
= \frac{V^N}{N!} \prod_{i=1}^{N} \frac1{h^3} \int \mathrm{e}^{-\beta cp_i} \,\mathrm{d}\vec{p}_i \\ 
= \frac{V^N}{N!} \left[ 8\pi \left( \frac{kT}{hc} \right)^3 \right]^N 
$$
压强
$$
p = \frac{1}{\beta} \frac{\partial}{\partial V} \ln Z = \frac{N}{V\beta} = \frac{NkT}{V} 
$$
即物态方程
$$
pV = NkT 
$$
内能
$$
U = - \frac{\partial}{\partial\beta} \ln Z = {3N} kT 
$$
熵
$$
S = k \left( \ln Z - \beta \frac{\partial}{\partial\beta} \ln Z \right) \\ 
= Nk \left[ 3 \ln \frac{kT}{hc} + \ln\frac{8\pi V}{N} + 4 \right] 
$$
化学势
$$
\mu = - kT \ln Z = -kT \left[ 3 \ln \frac{kT}{hc} + \ln\frac{8\pi V}{N} \right] 
$$

#### 9.15
解：
巨配分函数
$$
\Xi = \sum_{N=0}^{+\infty} \sum_s \mathrm{e}^{-\alpha N - \beta E_s} 
= \sum_{N=0}^{+\infty} \mathrm{e}^{-\alpha N} Z_N \\ 
= \sum_{N=0}^{+\infty} \frac{1}{N!} \left[ \mathrm{e}^{-\alpha} V \left( \frac{2\pi m}{\beta h^2} \right)^\frac32 \right]^N \\ 
= \exp\left[ \mathrm{e}^{-\alpha} V \left( \frac{2\pi m}{\beta h^2} \right)^\frac32 \right]
$$
故气体的平均粒子数
$$
\bar N = -\frac{\partial}{\partial\alpha} \ln \Xi 
= \mathrm{e}^{-\alpha} V \left( \frac{2\pi m}{\beta h^2} \right)^\frac32 
$$
得
$$
\alpha = \ln \left[ \frac{V}{\bar N} \left( \frac{2\pi m}{\beta h^2} \right)^\frac32 \right] 
$$
压强
$$
p = \frac{1}{\beta} \frac{\partial}{\partial V} \ln \Xi = \frac{kT}{V} \bar N 
$$
即物态方程
$$
pV = \bar NkT 
$$
内能
$$
U = - \frac{\partial}{\partial\beta} \ln \Xi = \frac{3}{2} \bar N kT 
$$
熵
$$
S = k \left( \ln \Xi - \alpha \frac{\partial}{\partial\alpha} \ln \Xi - \beta \frac{\partial}{\partial\beta} \ln \Xi \right) \\
= \bar N k \left( \alpha + \frac52 \right) 
$$
化学势
$$
\mu = - kT\alpha = -kT \ln \left[ \frac{V}{\bar N} \left( \frac{2\pi m}{\beta h^2} \right)^\frac32 \right] 
$$

#### 9.16
解：
单原子和双原子理想气体物态方程均有 $pV = \bar NkT$，故
$$
\left( \frac{\partial V}{\partial p} \right)_{\bar N,T} = - \frac{\bar NkT}{p^2} 
$$
粒子数相对涨落
$$
\frac{\bar{(N - \bar{N})^2}}{\bar{N}^2} 
= -\frac{kT}{V^2} \left( \frac{\partial V}{\partial p} \right)_{\bar N,T} 
= \frac1{\bar N} 
$$

#### 9.19
解：
巨配分函数
$$
\Xi = \sum_{N=0}^{+\infty} \sum_s \mathrm{e}^{-\alpha N - \beta E_s} 
= \sum_{N=0}^{+\infty} \mathrm{e}^{-\alpha N} Z_N \\ 
= \sum_{N=0}^{+\infty} \frac{1}{N!} \left[ \mathrm{e}^{-\alpha} A \left( \frac{2\pi m}{\beta h^2} \right) \mathrm{e}^{\beta\varepsilon_0} \right]^N \\ 
= \exp\left[ \mathrm{e}^{-\alpha} A \left( \frac{2\pi m}{\beta h^2} \right) \mathrm{e}^{\beta\varepsilon_0} \right]
$$
故吸附的平均粒子数
$$
\bar N = -\frac{\partial}{\partial\alpha} \ln \Xi 
= \mathrm{e}^{-\alpha} A \left( \frac{2\pi m}{\beta h^2} \right) \mathrm{e}^{\beta\varepsilon_0} 
= A \left( \frac{2\pi m kT}{h^2} \right) \mathrm{e}^{\frac{\varepsilon_0 + \mu}{kT}} 
$$
单原子分子化学势
$$
\mu = hT \ln \left[ \frac{p}{kT} \left( \frac{h^2}{2\pi m kT} \right)^\frac32 \right] 
$$
故吸附分子的面密度为
$$
\frac{\bar N}{A} = \frac{p}{kT} \left( \frac{h^2}{2\pi m kT} \right)^\frac12 \mathrm{e}^{\frac{\varepsilon_0}{kT}} 
$$

#### 9.21
证明：
玻尔兹曼分布
$$
\bar a_l = \omega_l \mathrm{e}^{-\alpha-\beta\varepsilon_l} 
$$
粒子数涨落
$$
\bar{(a_l - \bar a_l)^2} = - \frac{\partial \bar a_l}{\partial \alpha} = \bar a_l 
$$

#### 9.22
证明：
光子气体有 $\alpha=0$，故巨配分函数
$$
\Xi = \sum_{a_l} \mathrm{e}^{-\beta \varepsilon_l a_l} 
$$
平均粒子数
$$
\bar a_l = \frac{\sum_{a_l} a_l \mathrm{e}^{-\beta \varepsilon_l a_l}}{\sum_{a_l} \mathrm{e}^{-\beta \varepsilon_l a_l}} 
$$
故
$$
-\frac1\beta \frac{\partial \bar a_l}{\partial \varepsilon_l} 
= \frac{\sum_{a_l} a_l^2 \mathrm{e}^{-\beta \varepsilon_l a_l}}{\sum_{a_l} \mathrm{e}^{-\beta \varepsilon_l a_l}} - \frac{(\sum_{a_l} a_l \mathrm{e}^{-\beta \varepsilon_l a_l})^2}{(\sum_{a_l} \mathrm{e}^{-\beta \varepsilon_l a_l})^2} 
= \bar{(a_l - \bar a_l)^2} 
$$
又光子气体有
$$
\bar a_l = \frac1{\mathrm{e}^{\beta\varepsilon_l} - 1} 
$$
故
$$
\bar{(a_l - \bar a_l)^2} = \bar a_l (1 + \bar a_l) 
$$


### 6.23 

9.7，9.8，9.13，9.14

#### 9.7
解：
实际气体能量
$$
E = \sum_{i=1}^{N} \frac{p_i^2}{2m} + \sum_{i<j} \phi(r_{ij}) 
$$
动量分布概率
$$
f(p_j) \,\mathrm{d}p_j 
= \frac{\mathrm{e}^{-\beta \frac{p_j^2}{2m}} \,\mathrm{d}p_j}{\int \mathrm{e}^{-\beta \frac{p_j^2}{2m}} \,\mathrm{d}p_j} 
= \left( \frac{1}{2\pi m kT} \right)^\frac32 \mathrm{e}^{-\beta \frac{p_j^2}{2m}} \,\mathrm{d}p_j 
$$
故速度分布律
$$
f(\vec v)\,\mathrm{d}\vec{v} = \left( \frac{m}{2\pi kT} \right)^\frac32 \mathrm{e}^{-\frac{m}{2kT} \vec v^2} \,\mathrm{d}\vec v 
$$

#### 9.8
证明：
二维气体能量
$$
E = \sum_{i=1}^{2N} \frac{p_i^2}{2m} + \sum_{i<j} \phi(r_{ij}) 
$$
配分函数
$$
Z = \frac{1}{N!h^{2N}} \int \mathrm{e}^{-\beta E} \,\mathrm{d}\Omega 
= \frac{1}{N!} \left( \frac{2\pi m}{\beta h^2} \right)^{N} Q 
$$
定义函数
$$
f_{ij} = \mathrm{e}^{-\beta \phi(r_{ij})} - 1 
$$
位形积分
$$
Q = \int \mathrm{e}^{-\beta \sum_{i<j} \phi(r_{ij})} \, \mathrm{d}^N \vec r \\ 
\approx \int (1 + \sum_{i<j} f_{ij}) \, \mathrm{d}^N \vec r \\ 
\approx A^N \left[ 1 + \frac{N^2}{2A} \int_0^{+\infty} (\mathrm{e}^{-\beta \phi(r)} - 1) 2\pi r \,\mathrm{d}r \right] \\ 
= A^N \left( 1 - \frac{N^2}{N_AA} B \right) 
$$
其中
$$
B = - \frac{N_A}{2} \int_0^{+\infty} (\mathrm{e}^{-\beta \phi(r)} - 1) 2\pi r \,\mathrm{d}r 
$$
代入配分函数，得
$$
pA = A \frac{1}{\beta} \frac{\partial}{\partial V} \ln Z 
= \frac{NkT}{A} \left( 1 + \frac{N}{N_AA} B \right) 
$$

#### 9.13
解：
平均场近似下，弱场高温下，顺磁体磁化强度
$$
M = n\mu \tanh \frac{\mu \bar B}{kT} 
\approx n\mu \frac{\mu \bar B}{kT} \\ 
= \frac{n\mu^2}{kT}B + \frac{n\mu \bar \sigma}{kT}ZJ \\ 
= \frac{n\mu^2}{kT}B + \frac{M}{kT}ZJ \\ 
= \frac{n\mu^2\mu_0}{k(T - ZJ/k)} H \\ 
= \frac{C}{T - \theta} H 
$$

#### 9.14
解：
用平均场表示其他分子对单个分子的作用，有
$$
E = \sum_{i=1}^N \left[ \frac{p_i^2}{2m} + \phi(\vec r_i) \right] 
$$
记位形积分
$$
Z_1 = \int \mathrm{e}^{-\beta \phi(r)} \,\mathrm{d}\vec r
$$
除去钢球体积 $\tilde{V}$，相互作用用平均 $\phi$ 表示。设
$$
\tilde{V} = \frac{N}{N_A} b ,\quad
\phi = - \frac{a}{N_A^2} \frac{N}{V} 
$$
故
$$
Z_1 = (V - \tilde{V}) \mathrm{e}^{-\beta \phi} 
$$
则气体压强
$$
p = \frac{1}{\beta} \frac{\partial}{\partial V} \ln Z 
= NkT \frac{\partial}{\partial V} \ln Z_1 \\ 
= \frac{NkT}{V - \frac{N}{N_A} b} - \frac{N^2}{N_A^2} \frac{a}{V^2} 
$$
即得范德瓦尔斯方程
$$
\left( p + \frac{n^2a}{V^2} \right) (V - nb) = NkT 
$$




<!-- 

-->

