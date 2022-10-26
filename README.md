# The-Newton-Method
Another way to calculate roots of functions 
# The-Newton-s-Method
A method to calculate roots of functions

Given a function f(x), if we don't have an idea of the interval where the root can possibly be( This way we can't use the bissection method ! ), we can just guess a region next enough of the root ant the Newton's method find for us ( through derivatives )  and goes on and on gets closer, aproximating by derivatives from the first guess. 

Let f(x) be the function that we want to find at least one root and xo the first guess we have, an ideia of what the root can be next too

the algoritm is very simple and intuitive

x1 = x0 - f(xo)/f'(x0)

So the xn+1 for n arbitrary : 

xn+1 = xn - f(xn)/f'(xn)

The demonstration is by taylor serie's
Everey polynomial function can be written as an aproximation of :  

f(x) = f(xo) + f'(x)(x-xo) + [f''(xo)(x-xo)^2]/2! [f'''(xo)(x-xo)^2]/3! + ...
