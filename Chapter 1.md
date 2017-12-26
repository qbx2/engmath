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

6. $y^{\prime\prime} = -y$

### 패스


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

12. $yy' = 4x, y^2 - 4x^2 = c (y > 0), y(1) = 4$

(a) Verify

$2y * dy/dx - 8x = 0$

$2yy' - 8x = 0$

$yy' - 4x = 0$

$yy' = 4x$

*Verified*

(b) Determine from y the particular solution of the IVP

$4^2 - 4 \cdot 1^2 = c = 12$

$y^2 - 4x^2 = 12$

13. $y' = y - y^2, y= \frac{1}{1 + ce^{-x}}, y(0) = 0.25$

(a) Verify

$y' = -\frac{1}{(1+ce^{-x})^2} \cdot (-ce^{-x}) = \frac{ce^{-x}}{(1+ce^{-x})}$

$y - y^2 = \frac{1+ce^{-x} - 1}{(1+ce^{-x})^2}$

$= \frac{ce^{-x}}{(1+ce^{-x})^2}$

*Verified*

(b) Determine ...

$0.25 = \frac{1}{1 + ce^{-0}}$

$= \frac{1}{1+c} = 1/4$

$\therefore c=3$

* Modeling & Applications: 17, 18

17. Half-life where $k = 1.4 \cdot 10^{-11} \sec^{-1} \text{ for } ^{228}_{88}\text{Ra}$?

$\mathrm{d}y/\mathrm{d}t = -ky$

$\mathrm{d}y/y = -k \mathrm{d}t$

$\ln|y| + C_1 = -kt + C_2$

$y = Ce^{-kt}$

$y(0) = C, y(x) = 1/2 C = Ce^{-kx}$

$1/2 = e^{-kx}$

$\ln 1/2 = - \ln 2 = -kx$

$x = \ln 2 / k = \ln 2 / (1.4 \cdot 10^{-11} \sec^{-1}) = 1,568.92699 \text{ years}$

18. Radium $^{224}_{88}\text{Ra}$ has a half-life of about 3.6 days.

(a) Given 1 gram, how much will still be present after 1 day?

$y = Ce^{-kt}, y(0) = 1 = C, y = e^{-kt}$

$0.5 = e^{-3.6k}$

$k = \frac{\ln 2}{3.6}$

$y(1) = e^{-k} = e^{-\frac{\ln 2}{3.6}} = (e^{-\ln 2})^{\frac{1}{3.6}} = (0.5)^{(1/3.6)} = 0.824860594$

(b) After 1 year?

$y(365) = e^{-365k} = (e^{-k})^{365} = y(1)^{365} = 3.01233465 \times 10^{-31}$

# Problem Set 1.3
* General Solution: 2, 5
* Initial Value Problems: 10, 13
* Modeling & Applications: 17, 18

# Problem Set 1.4
* Exact ODEs, Integrating Factors: 5, 15

# Problem Set 1.5
* General Solution, Initial Value Problem: 7, 10
* Nonlinear ODEs: 18, 21'

