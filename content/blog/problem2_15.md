+++
title = 'Electric field inside a sphere'
date = 2024-04-02T19:41:22+02:00
draft = false
katex = true
+++

Problem : A thick spherical shell carries charge density: $$\rho = \frac{k}{r^2} \quad (a \le r \le b)$$ Find the electric field in the following three regions: $$(i)\ r < a \quad (ii)\ a < r < b \quad (iii)\ r > b$$


Solution: It is the case that a spherical surface is symmetrical on any axis, therefore Gauss' law will be used. $$\oint_{S} \vec{E}\cdot d\vec{a}=\frac{Q_{\mathrm{enc}}}{\varepsilon_0}$$

\((i)\) The density in this part of the sphere is \(0\), therefore \(Q_{\mathrm{enc}} = 0\) and the electric field \(\vec{E} = 0\)

\((ii)\) In this case, the only part that contributes to the electric field is the volume in the section $ (a < r < b) . The dot product of the electric field vector with the surface vector is parallel and constant over the whole surface, therefore it can be rewritten as $$ \oint_{S} |{E}|\ d\vec{a} = |E| \oint_{S} d\vec{a} = |E|4\pi r^2$$

As for the total enclosed charge, it is obvious that \( \mathrm{d}q = \rho\ \mathrm{d}\tau\) and therefore $$ Q_{\mathrm{enc}} = \frac{1}{\epsilon_{0}} \int \rho\ \mathrm{d} \tau $$

Let us define the \(\mathrm{d}\tau\) factor in spherical coordinates as $$ d\tau = r^2 \sin {\theta}\ dr\ d\phi\ d\theta $$

Then $$ Q_{\mathrm{enc}} =  \int_{a}^{r} \frac{k}{r^2}\ r^2 \sin {\theta}\ dr\ d\phi\ d\theta = 4\pi k \int_{a}^{r} dr = 4\pi k  (r - a) \hat{r} $$

And the resulting equations is:

$$ |E|4\pi r^2 =  \frac{4\pi k}{\epsilon_{0}}  (r - a) \hat{r} $$

Which simplifies to:

$$ \vec{E}= \frac{k}{\epsilon_{0}} \left(\frac{r-a}{r^2}\right) \hat{r}.  \qquad \square$$


