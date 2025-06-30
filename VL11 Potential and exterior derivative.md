Helmholz: $$\vec F = - \triangledown U + \vec \triangledown \times \vec W$$ possible $U, \vec W$ $$U ( \vec r) - \frac{1}{4 \pi} \int \frac{D (\vec r) } { |\vec r - \vec r'|} d^3 r$$$$\vec W (\vec r) = \frac{1}{4 \pi} \int \frac{\vec C (\vec R)}{|\vec r - \vec r'|}d^3r$$
	with $D = \vec \triangledown \cdot \vec F$ and $\vec C = \vec  \triangledown  \times \vec F$ 
but they aren't really definite = Eindeutig => soemhow not really important but can look different

**magnetostatic vector potential** $\vec \triangledown \times \vec B = \mu_0 \vec j$
	$$\vec A (\vec r) = \frac{\mu_0}{4 \pi} \int \frac{\vec j (\vec r)}{|\vec r - \vec r'|} d^3r'$$ - is Uneindeutig $$\vec A = \vec A + \vec \triangledown \lambda$$
		with $\lambda (\vec r)$ 
		$$\vec B' = \vec \triangledown \times \vec A' = \vec \triangledown \times \vec A + \vec \triangledown \times \vec \triangledown \lambda = \vec B$$
			where $\vec \triangledown \times \vec \triangledown \lambda = 0$ is   

**Ampere law**
$$\mu_0 \vec j = \vec \triangledown \times \vec B = \vec \triangledown \times (\vec \triangledown \times \vec A) = \vec \triangledown (\vec \triangledown \cdot \vec A) - \vec \triangledown^2 \vec A$$
	- needed: ein... so that $\vec \triangledown \cdot \vec A = 0$ 
	- that would mean that $\vec \triangledown (\vec A' + \vec v \lambda) =0$ 
	- and therefore : $$- \vec \triangledown \vec A = \triangle \lambda$$ being the Poisson equation 



