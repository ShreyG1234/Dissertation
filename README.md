# Dissertation
%Product Rule

from sympy import diff, Symbol
x = Symbol('x')
f = 4 * x ** 2
g = x ** 3
difff = diff(f)
diffg = diff(g)
print('The function h =', f, '*', g)
print('The fuction f =', f)
print('The fuction g =', g)
print('The derivative of the fuction f =', difff)
print('The derivative of the fuction g =', diffg)
print('The product rule is, diff(f) * g + diff(g) * f ')
print('The derivatives of h =', diff(f) * g, '+', diff(g) + f,'=',diff(f) * g + diff(g) * f)

