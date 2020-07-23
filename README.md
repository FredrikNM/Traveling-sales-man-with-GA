Traveling Sales Man with diffrent algos :

1. Exhaustive
2. Hill
3. Genetic

With example as showned in jupyter nootbook, Algos_ex_hill_ga


Traveling sales man ( https://en.wikipedia.org/wiki/Travelling_salesman_problem ):
Imagine a sales man that has to travel through different cities and then back home, and you are tasked with finding the shortes route. 
If the cities are London, Paris, Rome and he travel from Brussel (H for home), then it would be pretty easy to check
what the shortest route is, since there are just a few options : 

H -> London -> Paris -> Rome -> H
H -> London -> Rome -> Paris -> H
H -> Rome -> London -> Paris -> H
H -> Rome -> Paris -> London -> H
H -> Paris -> Rome -> London -> H
H -> Paris -> London -> Rome -> H

As we can see that was pretty okay to do, but you see it cleary, that to check all route when there is a lot of cities, will be a thought.
If we have: 
n cities including Home, the number of all possible routes is :

(n-1)! = (n-1) * (n-2) * (n-3) * ... * 2 * 1

This is called permutation = ( https://en.wikipedia.org/wiki/Permutation )

After that we even have to calculate the distances between each city in every route!


