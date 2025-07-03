# Exterior cerivative and tensor 
$$\frac{\partial}{\partial x^{\mu}} A_{\nu} := \partial_{\mu} A_{\nu} := A_{\mu, \nu}$$

$$dx^{\mu} \land dx^{\nu} = dx^{\mu} \otimes dx^{\nu} - dx^{\nu} \otimes dx^{\mu} = \epsilon^{\mu \nu}_{\alpha \beta} dx^{\alpha} \otimes dx^{\beta}$$
Definition of ext. derivative for:
- function $$df = (\partial_{\mu} f) dx^{\mu}$$
- tensor $$d \overline A = \partial_{\nu} A_{\mu} dx^{\nu} \land dx^{\mu} = (A{\mu, \nu} - A_{\nu, \mu}) dx^{\nu} \otimes dx^{\mu}$$
- p - form $$dw = (dw_{i_1 ... i_p} \land dx^{i_1} \land ... \land dx^{i_p} = (\partial_k w_{i_1 ... i_p}) dx^k \land dx^{i_1} \land ... \land dx^{i_p}$$

Good to know realtions:
- $\overline F = \vec E \cdot (dx_0 \land d \vec x ) - \vec B d \vec \sigma$ 
- $F_{o, i} = \partial_0 A_i - \partial_i A_0 = \frac{- E_i}{c}$
- $F_{ij} = \vec \triangledown \times A$ 


# Exterior derivative trafos
$$\partial_j = \frac{\partial r}{\partial_j} \partial_r + \frac{1}{r} \frac{\partial \theta}{\partial_j} \partial_{\theta}+ \frac{\partial \phi}{\partial_j} \partial_{\phi} $$
Gradiant on [[spherical coordinates]]$$\vec \triangledown f = \frac{\partial f}{\partial r} \hat e_r + \frac{1}{r} \frac{\partial f}{\partial \theta} \hat e_{\theta} + \frac{1}{r \sin \theta} \frac{\partial f}{\partial \phi} \hat e_{\phi}$$
Gradiant in [[cylindrical coordinates]] $$\vec \triangledown f = \partial_{\rho} f \hat \rho + \frac{1}{\rho} \partial_{\phi} f \hat \phi + \partial_z f \hat z $$


# Hodge 
$$\star (dx^{\mu_1} \land ... \land dx^{\mu_p}) = \frac{\sqrt{|g|}}{(n-p)!} g^{\mu_i  \nu_i} ... g^{\mu_p \nu_p} \epsilon_{\nu_1 ... \nu_p \nu_{p+1} ... \nu_n} dx^{v_{p+1}} \land ... \land dx^n$$
- normal space $$\det \delta =1$$
- [[Minkowski]] space $$\det \eta = -1$$

$$\star \star w = (-1)^{k(n-k)} s w$$
	with $s = \det g$ 