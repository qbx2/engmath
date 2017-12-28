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

$y^{\prime\prime} + y = 0$

$y = e^{cx}, y' = ce^{cx}, y^{\prime\prime} = c^2e^{cx}$

$c^2e^{cx} + e^{cx} = e^{cx}(c^2 + 1) = 0$

$c = \pm i, y_1 = e^{ix}, y_2 = e^{-ix}$

$y = c_1 e^{ix} + c_2 e^{-ix}$

$= c_1(\cos x + i \sin x) + c_2(\cos (-x) + i \sin (-x))$

$= c_1 \cos x + i c_1 \sin x + c_2 \cos x - i c_2 \sin x$

$= (c_1 + c_2) \cos x + i (c_1 - c_2) \sin x$

$= C_1 \cos x + C_2 \sin x$


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

2. $y^3y' + x^3 = 0$

(a) solve

$y^3y' = -x^3$

$y^3 \cdot \mathrm dy = -x^3 \mathrm dx$

$\int y^3 \mathrm dy = \int -x^3 \mathrm dx$

$1/4 y^4 + C_1 = -1/4 x^4 + C_2$

$y^4 = -x^4 + C$

(b) verify

$4y^3 \mathrm dy / \mathrm dx = -4 x^3$

$4y^3y' = -4x^3$

$y^3y' = -x^3$

5. $yy' + 36x = 0$

(a) solve

$y \mathrm dy / \mathrm dx + 36x = 0$

$y \mathrm dy = -36x \mathrm dx$

$1/2 y^2 + C_1 = -36x^2 + C_2$

$y^2 = -36x^2 + C$

(b) verify

$2y y' = -72x$

$y y' = -36x$

* Initial Value Problems: 10, 13

11. $xy' + y = 0, y(4) = 6$

(a) solve

$xy' = -y$

$y'/(-y) = 1/x$

$\mathrm dy / (-y) = 1/x \ \mathrm dx$

$-\int \frac{\mathrm dy}{y} = \int \frac {\mathrm d x} x$

$-\ln|y| = \ln|x|$

$\ln|x| + \ln|y| = 0$

$\ln|xy| = 0$

$xy = C$

$\ln|y| = -\ln|x|$

$e^{\ln|y|} = e^{-\ln|x| + C}$

$y = (C_te^{\ln|x|})^{-1}$

$y = C_t^{-1}x^{-1}$

$xy = C$

(a).1 verify

$y + x\cdot y' = 0$

$xy' = -y$

(b) get c

$xy = C = 24$

(c) particular solution

$xy = 24$

14. $\mathrm dr / \mathrm dt = -2tr, r(0) = r_0$

(a) general solution

$\mathrm dr/r = -2t \ \mathrm dt$

$\ln|r| = -t^2 + C$

$r = Ce^{-t^2}$

(b) verify

$\mathrm dr / \mathrm dt = Ce^{-t^2} * -2t = -2tr$

verified

(b) particular solution

$r_0 = Ce^0 = C$

$r = r_0 e^{-t^2}$

* Modeling & Applications: 17, 18

19. $\mathrm dy/\mathrm dt = ky, y(1 \text{week}) = 2 y(0). y(2)/y(0) = ?, y(4)/y(0) = ?$

$\mathrm dy = ky \ \mathrm dt$

$\mathrm dy / y = k \ \mathrm dt$

$\int \mathrm dy / y = \int k \ \mathrm dt$

$y = Ce^{kt}$

$y(1) = Ce^k = 2 y(0) = 2C$

$e^k = 2$

$k = \ln 2$

$y(2)/y(0) = Ce^{2k}/C = (e^k)^2 = 4$

$y(4)/y(0) = Ce^{4k}/C = (e^k)^4 = 16$

20. 

(a) $\mathrm dy / \mathrm dt = k_1 y - k_2 y$

$\mathrm dy / y = (k_1 - k_2) \ \mathrm dt$

$\ln|y| = t(k_1 - k_2) + C_1$

$y = Ce^{t(k_1 - k_2)}$

(b) when ?


# Problem Set 1.4
* Exact ODEs, Integrating Factors: 5, 15

5. $(x^2 + y^2) \mathrm dx - 2xy\ \mathrm dy = 0$

(a) check for exactness

$P(x, y) = x^2 + y^2, Q(x, y) = -2xy$

$\frac{\partial P}{\partial y} = 2y, \frac{\partial Q}{\partial x} = -2y$

(b) convert to exact ODE

Assume $FP \ \mathrm dx + FQ \ \mathrm dy = 0$ is an exact ODE.

$M(x, y) = FP, N(x, y) = FQ$

$\frac {\partial M} {\partial y} = F_yP + FP_y = \frac {\partial N} {\partial x} = F_xQ + FQ_x$

$= F_y(x^2 + y^2) + 2Fy = F_x(-2xy) - 2Fy$

$4Fy = Fx(-2xy) - Fy(x^2 + y^2)$

$du = M \ \mathrm dx + N \ \mathrm dy = 0$

$= FP \ \mathrm dx + FQ \ \mathrm dy$

미지수가 너무 많아서 못품

(1) Assume $F_x = \frac{\partial F}{\partial x} = 0$

$\frac {\partial M}{\partial y} = F_yP + FP_y = \frac {\partial N}{\partial x} = F_xQ + FQ_x = FQ_x$

$F_yP + FP_y - FQ_x = 0$

$= F_y(x^2 + y^2) + F \cdot 2y - F \cdot (-2y)$

$= F_y(x^2 + y^2) + F \cdot 2y + F \cdot 2y$

$= F_y(x^2 + y^2) + 4Fy = 0$

$F_y/F = -4\frac{y}{x^2 + y^2}$

${\mathrm dF}/ F = -4 \frac {y}{x^2 + y^2}{\mathrm dy}$

아 적분 개어렵네

(2) Assume $F_y = \frac{\partial F}{\partial y} = 0$

$\frac {\partial M}{\partial y} = F_yP + FP_y = FP_y = \frac {\partial N}{\partial x} = F_xQ + FQ_x$

$F \cdot 2y = F_x(-2xy) + F \cdot (-2y)$

$4Fy = F_x(-2xy)$

$4y / (-2xy) = -2 / x = F_x / F$

$-2 / x = \frac{\mathrm dF}{\mathrm dx} / F$

$\because \mathrm dF = \frac{\partial F}{\partial x} \mathrm dx + \frac{\partial F}{\partial y} \mathrm dy = \frac{\partial F}{\partial x} \mathrm dx$

$\iff \frac{\mathrm dF}{\mathrm dx} = \frac{\partial F}{\partial x} = F_x$

$-2/x \ \mathrm dx = \mathrm dF / F$

$-2 \ln |x| + C = \ln |F|$

$\ln |F| + 2 \ln |x| = C$

$\ln |F| + \ln |x^2| = C$

$\ln |Fx^2| = C$

$F = C / x^2$

그러면 

$M = FP = \frac{x^2 + y^2} {x^2} = C \cdot (1 + y^2/x^2), N = FQ = C/x \cdot (-2y)$

$M \ \mathrm dx + N \ \mathrm dy = 0$

$du = (1 + y^2/x^2) \mathrm dx - 2y / x \ \mathrm dy = 0$

$u = (x - y^2/x + C_1) + k(y) = C$

$= x - y^2/x + k(y) = 0 = N = -2y/x$

${\partial u \over \partial y} = -2y/x + k(y)$

$u = x - y^2/x + C = 0$

답 확인해보자

주어진 식 $(x^2 + y^2) \mathrm dx - 2xy\ \mathrm dy = 0$ 성립해야함

$\mathrm du = (1+y^2/x^2) \mathrm dx - 2y/x \ \mathrm dy = 0$

$x^2 \ \mathrm du = (x^2 + y^2) \mathrm dx - 2xy \ \mathrm dy = 0$

#### 13. $e^{-y} \ \mathrm dx + e^{-x}(-e^{-y} + 1)\ \mathrm dy = 0, F = e^{x+y}$

$e^x \ \mathrm dx + (-1 + e^y) \ \mathrm dy = 0$

Check for exactness

${\partial e^x \over \partial y} = 0, {\partial (-1 + e^y) \over \partial x} = 0$

$u = \int e^x \ \mathrm dx + k(y)$

$= e^x + k(y)$

${\partial u \over \partial y} = -1 + e^y = k_y$

$k(y) = e^y - y + C$

$\therefore u = e^x + e^y - y + C$

$du = e^x \ \mathrm dx + (e^y - 1) \ \mathrm dy = 0$



# Problem Set 1.5
* General Solution, Initial Value Problem: 7, 10

7. $xy' = 2y + x^3 e^x$

$y' - 2y/x = x^2 e^x$

$h = -\int 2/x \ \mathrm dx = -2 \ln |x| = \ln |1 / x^2|$

$y = x^2 (\int 1/(x^2) * x^2 e^x \mathrm dx + C)$

$y = x^2 (\int e^x \mathrm dx + C)$

$y = x^2 (e^x + C)$

$y = x^2 e^x + Cx^2$

10. $y' \cos x + (3y - 1) \sec x = 0, y(1/4 \pi) = 4/3$

$y' + (3y - 1) \sec^2 x = 0$

$y' + 3 (\sec^2 x) y - \sec^2 x = 0$

$h = \int 3(\sec^2 x) \mathrm dx = 3 \int \sec^2 x \ \mathrm dx = 3 \tan x$

$y = 1/(e^{3 \tan x})(\int e^{3 \tan x} \sec^2 x  + C)$

$= 1/(e^{3 \tan x})(1/3 e^{3 \tan x} + C) $

$= 1/3 + C / e^{3 \tan x}$

우엑

$my^{\prime\prime} + ky = 0$

$y^{\prime\prime} + k/m\ y = 0$

$\lambda = 1/2(-a \pm \sqrt {a^2 - 4b})$

$= 1/2(0 \pm \sqrt {0 - 4 k/m})$

$= \pm i \sqrt {k/m}$

$y = e^{\lambda x} = e^{\pm ix \sqrt{k/m}}$


* Nonlinear ODEs: 18, 21'

22. $y' + y = y^2, y(0) = -1/3$

$dy/dx = y^2 - y$

$dy/(y^2 - y) = dx$

$= dy/y(y-1) = (1/(y-1) - 1/y)dy = dy/(y-1) - dy/y = dx$

$\ln|y-1| - \ln|y| + C_1$

$= \ln|\frac{y-1}{y}| = x + C_1$

$(y-1)/y = Ce^x$

$y-1 = ce^x y$

$(1-ce^x)y = 1$

$y = \frac{1}{1-ce^x}$
