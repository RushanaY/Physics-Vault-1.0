**Main charaketeristics of telescopes**:
- Lichsammevermögen/Sensitivität 
- Auflösungsvermögen
- Spektrabereich
- Blickfeldgröße 


**Types of telescopes**
- Linsen T. = Refraktor
	- Vergrößert Bild (nichts für Auflösung)
	- Nachteil: chromatische Abberation
	- Vorteil: 
		- leichte Montage, da Linse nur am Rand gehalten wird
		- wenig Verformung wegen großem Durchmesser
- Spegel T. = Reflektor 
	- Nachteile (bei sphärischen Spiegeln):
		- sphärische Abberation
		- Astigmatismus 
		- chromatische Abberation
		- Kome 



**Auflösungsvermögen**/ angular resolution:
$$\alpha = 1.22 \frac{\lambda}{D}$$

-> is the [[Rayleight criterion]] 

**Atmospheric seeing**
- idea that looking through the atmosphere gives a lot of inconsistencies and tubulenses in the picture 
- Reasons are the depth of the atmosphere and pressure and temperature fluctuations, that are impossible to predict
- Soution: **Adaptive Optics** 
	- Intresting: telescope uses a think layer of natrium, exited by a natrium laer, in the atmosphere as a guide star


**Detectors**:
- Quantenkedector - Photoplatte
	- creates a negativ by having a chemical reaction between the light and silver on the plate 
	- big view field 
	- small differtiation of different lights
- Photomultiplier 
	- detects just if ther was a Photon, but not what kind 
- CCDs: charged coupled devices 
- Bolometer 
	- absorbed radiation leads to temperature growth, which can be very precisly measured 
- Phohtometrie
- Spectroscopy 
- Interferometry 
- Tscherenkowdetector
- Neutrinodetector
- gravitational waves detector 

---------------------------------------- 
**Sheet 4** 
1. **Angular resolution/ Resolution power** 
	Use [[Rayleight criterion]] => Important: angle is in **[[radians]]**
	using astronomical units of ![[arg minutes and seconds]] to degrees 
	
2. **Black holw in M87**
	a.) calculate [[escape velocity#$$v = sqrt{ frac{2GM}{R}}$$]] as usual
	b.) use [[Rayleight criterion]] with given data
	,. 
	c.)![[Pasted image 20250606103937.jpg]]
	$tan \frac{\alpha}{2} = \frac{r}{2a} \to r = 2 \cdot a \cdot tan \frac{\alpha}{2}$
	where $a$ is the distance from the black hole to earth (given in describtion in 1pc)
	
	**Diameter of the light ring** $R_C$ (seen on the photo) -> *the last distance at which photons can escape. Therfore we can see the light*
	$d = 2r = 2 \cdot R_C$  
	$R_c = 2.6 \cdot R_S$ -> given in the describtion 
	
	**Schwarzschild radius** $R_S$  -> *ist the distance, where the mass of the black hole makes the escape velocity equal to light speed*
	$R_S = \frac{R_C}{2.6} = \frac{r}{2.6} tan \frac{\alpha}{2} = 319.5 km = 2.13 \cdot 10^{-6} au$
	$M = \frac{R_S c^2}{2G} = 7.2 \cdot 10^{23} kg$  -> *it is quite a tad smaller than it should be. general formular is correct and is derived from the ecsape velocity*
	
	solution from tutor :
	$R_C = \alpha \cdot d = 1.3966 \cdot 10^{-10} Rad \cdot 206264 au  470au$
		$\alpha$ comes from the radial resolution
		$d$ is the distance to earth
	$M = ... = 1.989 \cdot 10^{30} kg = 21 \cdot 10^6 \space solar \space masses$ 
	

3. **Photon energy**
	a.) 
	$L = \frac{energy}{time} = \frac{E_{Phtoton} \cdot N_{Photon}}{time}$ with 	$Energy = (Energy \space of \space photon) \cdot N_{Photon}$
	
	$\frac{N_{Photon}}{time} = \frac{L}{E_{Photon}} = L \frac{\lambda}{hc} = 2.78 \cdot 10^{52} \frac{1}{s}$ -> energy of the whole sun, not just our earth
	
	solution from tutor: 
	-> is more accurate, because if is more specifically the amount of photons, that hit the earth, instead of just being emittet from the sun:	$$\Gamma_{earth} = \frac{S}{E_{\lambda, max}} = 3.5. \cdot 10^{17} ph/cm^2/s$$
	b.) $\frac{1}{r^2} = \frac{2.78 \cdot 10^{52} \frac{1}{s}}140^2 \frac{1}{pc^2} = 1.4 \cdot 10^{48}\frac{1}{pc^2s}$ -> inverted squares law (every meter if distance leads to quadratic donwfall of intensity)
	
	solution from tutor:
	
	$\lambda_{max} = \frac{hc}{5 k_B T} = 2.9 mm (\frac{T}{K})' \approx 500nm$ 
	$E_{\lambda, max} = \frac{hc}{ \lambda_{max}} = 4 \cdot 10^{-12}erg$  
	$= \frac{L}{4 \pi d^2} = 1.4 \cdot 10^6 erg/sm^2/s$
	$\Gamma = \frac{L}{4 \pi E_{\lambda, max}} \frac{1}{14^20pc^2} = 420 ph/cm^2/s$
	or $= \Gamma_{Earth} (\frac{d}{1 au})^{-2}$ 
	
	c.) 
	![[Pasted image 20250606110749.jpg]]
		
	 $P = \frac{F}{A} = \Gamma \frac{h}{\lambda} = \frac{L}{4 \pi c} \frac{1}{R^2} [erg/cm^3] = \frac{rate \space of \space work}{area}$ 
	 	
	d.) $F_{grac} = \frac{GMm}{d^2} = \frac{\frac{4}{3} \pi a^3 \rho MG}{d^2}$ 
	$F_{photon} = P \pi a^3 = \frac{L}{4\pi c} \frac{1}{d^2} \pi a^2$ 
	$F_{grac} = F_{photon}$
	=> $a = 0.6 \mu m$ к





	 