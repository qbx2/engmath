\mathrm{d}

# Report #1: Chapter 1
# Problem Set 1.1
* Calculus: 1, 3

1. $y' + 2 \sin 2\pi x = 0$

$\frac{\mathrm{d}y}{\mathrm{d}x} = -2 \sin 2\pi x$

$\mathrm{d}y = -2 \sin 2 \pi x \ \mathrm{d}x$

$y = -2 \int \sin 2 \pi x \ \mathrm{d}x$

$y = -2 (-\cos 2 \pi x) / 2\pi + C$

$y = \frac{\cos 2 \pi x}{\pi} + C$

3. $y' = y$

$\mathrm{d}y / \mathrm{d}x = y$

$\mathrm{d}y = y \ \mathrm{d}x$

$\frac{\mathrm{d}y}{y} = \mathrm{d}x$

$\ln |y| = x + C$

$y = \pm e^{x + C}$

$y = \pm Ce^x$

$y = Ce^x$

* Verification of Solution: 5, 8

5. $y' = 4e^{-x} \cos x$

$\mathrm{d}y = 4e^{-x} \cos x \ \mathrm{d}x$

$y = 4 \int{e^{-x} \cos x\  \mathrm{d}x}$, $e^{-x} \ \mathrm{d}x = \mathrm{d}(-e^{-x})$

$1/4 y = \int{\cos x \ \mathrm{d}(-e^{-x})}$

$ = \cos x \cdot \left(-e^{-x}\right) - \int{-e^{-x} \ \mathrm{d}(\cos x)}$

$ = \cos x \cdot \left(-e^{-x}\right) - \int{(-e^{-x}) (-\sin x) \ \mathrm{d}x}$

$\int(-e^{-x})(- \sin x) \ \mathrm{d}x$

$= \int(e^{-x})(\sin x) \ \mathrm{d}x$

$= \int{\sin x \ \mathrm{d}(-e^{-x})}$

$= \sin x \cdot (-e^{-x}) - \int(-e^{-x})\ \mathrm{d}(\sin x)$

$= \sin x \cdot (-e^{-x}) - \int(-e^{-x})\ \mathrm{d}x \cdot (\cos x)$

$1/4 y = \int{\cos x \ \mathrm{d}(-e^{-x})}$

$= \int{\cos x \cdot e^{-x} \ \mathrm{d}x}$

$= \cos x \cdot (-e^{-x}) - (\sin x \cdot (-e^{-x}) - \int{(-e^{-x}) \cos x \ \mathrm{d}x})$

$= \cos x \cdot (-e^{-x}) - \sin x \cdot (-e^{-x}) + \int{(-e^{-x}) \cos x \ \mathrm{d}x}$

$2 \int{\cos x \cdot e^{-x} \ \mathrm{d}x} = 1/2 y = -e^{-x} \cdot (\cos x - \sin x) + C$

$\therefore y = 2e^{-x} \cdot (\sin x - \cos x) + C$

8. $y^{\prime\prime\prime} = e^{-0.2x}$

Let $u = y^{\prime\prime}, $ so $ u' = e^{-0.2x}$

$\mathrm{d}u = e^{-0.2x} \mathrm{d}x$

$u = -5e^{-1/5x} + C_1$

$y^{\prime\prime} = -5e^{-1/5x} + C_1$

Let $v = y'$, so $v' = y^{\prime\prime}$

$v' = -5e^{-1/5x} + C_1$

$v = 25e^{-1/5x} + C_1x + C_2$

$y' = 25e^{-1/5x} + C_1x + C_2$

$y = -125e^{-1/5x} + C_1x^2 + C_2 + C_3$

* Initial Value Problems: 12, 13
* Modeling & Applications: 17, 18
# Problem Set 1.3
* General Solution: 2, 5
* Initial Value Problems: 10, 13
* Modeling & Applications: 17, 18
# Problem Set 1.4
* Exact ODEs, Integrating Factors: 5, 15
# Problem Set 1.5
* General Solution, Initial Value Problem: 7, 10
* Nonlinear ODEs: 18, 21'

