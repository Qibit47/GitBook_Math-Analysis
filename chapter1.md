# 集合与函数（映射）

## 集合中元素的关系
### 等价关系 $$R$$
- 性质：
	- 反身性： $$a R a$$
	- 对称性： $$(a R b) \Rightarrow (b R a)$$
	- 传递性： $$(a R b) \wedge (b R c) \Rightarrow (a R c)$$

等价关系用符号 ～ 表示
### 偏序关系
- 性质：
	- 反身性： $$a R a$$
	- **反**对称性： $$(a R b) \wedge (b R a) \Rightarrow a = b$$
	- 传递性： $$(a R b) \wedge (b R c) \Rightarrow (a R c)$$

偏序关系用符号 $$\preceq$$ 表示
### 拟序关系
- 性质：
	- **反**自反性： $$\forall a, \neg (a R a)$$
	- **反**对称性： $$(a R b) \wedge (b R a) \Rightarrow a = b$$
	- 传递性： $$(a R b) \wedge (b R c) \Rightarrow (a R c)$$

拟序关系用符号 $$\prec$$ 表示

## 有序集
具有序关系及三歧性的集合称为有序集
- 三歧性： $$x \prec y, x = y, x \succ y$$ 三者必居其一

## 域