# Definition
 $$T^q_p (V) \equiv (\otimes^q V) \otimes (\otimes ^p V^*)$$
	where $\otimes^q V \equiv V \otimes ... \otimes V$ being q times 
	(*intuitive but not really correct idea: the direct products of V and $V^*$ are like rows and columns of a matrix*)
- a **tensor** is an element fo this set $$t = t^{j_1, ...,j_p}_{i_1,...,i_p} e_{j_1} \otimes ... \otimes e_{j_q} \otimes ... \otimes e^{i_p}$$
	*Comments:
	- it can all be written in one line,because it's linear per definition of the [[direct product, tensor product]] 
	- the t with many indicies is a **coefficient of the tensor** 

# Characteristics 
- stays **invariant under coordinate transformation** 
- is made up of [[covariant]] and [[contravariant]] vectors 
	- *is seen in the Definition above, as the direct sum between V and V*
	- *vector on their own are invariant, only his covector, the components, change*
	- **Real physical objects don't care about your coordinates!**

# Tensor classes 
- $T_0^0$ - number 
- $T^1_0$ - just vector 
- $T^0_1$ - dual vector from [[dual space]] (makese sense, it is the "row")
- $T_1^1$ - matrix 
- $T^0_2$ (or in general of degree (0,2) and (2,0)) - [[biliniear forms]] 