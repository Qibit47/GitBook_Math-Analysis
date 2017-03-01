# Riemann 积分
## 定义
若存在 $$I \in R$$ 使得当 $$||P|| \to 0$$ 时， $$\sum_{i=0} ^n f(\xi _i)(x_{i+1} - x_i)$$ 的极限为 $$I$$ ，则称 $$f$$ 在 $$[a,b}$$ 上（Riemann）可积，且极限 $$I$$ 称为 $$f$$ 在 $$[a,b]$$ 上的 **定积分**
### Riemann 和与 Darboux 和
- $$||P||$$ 是划分 $$P$$ 中区间长度的最大值，称为 **范数**
- $$S_n = \sum _{i=1}^n {f(\xi _i) \Delta x_i}$$ 称为 **Riemann 和**
	- 要求 Riemann 和的极限值与划分及代表点的取法无关
- 对区间 $$[a,b]$$ 的划分 $$P$$ ，对应的
	- Darboux 上和为： $$U(f;P) \equiv U_{[a,b]}(f,P) = \sum_{j=1}^n sup_{x \in [x_{j-1}, x_j]} f(x)(x_j - x_{j-1})$$
	- Darboux 下和为： $$L(f;P) \equiv L_{[a,b]} (f,P) = \sum_{j=1}^n inf_{x \in [x_{j-1}, x_j]} f(x)(x_j - x_{j-1})$$
- 好处
	1. 消除了代表点的任意性
	2. **Darboux 上和与下和的极限一定存在**
- 性质
	- $$L(f;P) = inf \sum, U(f;P) = sup \sum$$
	- 若 Q 是 P 的“加细”，$$U(f;P) ≥ U(f;Q), L(f,P) ≤ L(f;Q)$$
	- Darboux 上和总是比下和大
	- $$U(-f;P) = -L(f;P)$$
### 可积性
有界函数在区间 $$[a, b]$$ 上（Riemann）可积等价于：
- 其 Darboux 上和与下和的极限相等
- 不连续点为零测度集
	- **零测度集** 指可以用至多可列个 **总长度** 小于任意给定正实数的区间覆盖的集合
	- 对可测集而言，其测度非零的充要条件是 $$\exists [a, b], {[a_k, b_k]}$$ 使得 $$\cup_{k=1}^{\infty} [a_k, b_k] \supseteq [a, b] \setminus E, \sum_{k=1}^{\infty} (b_k - a_k) < b - a$$