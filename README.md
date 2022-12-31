Title: An Introduction to Elliptic Curves and Applications in Cryptography

Author: Josh Klein Valente

Advisors: Jerry Shurman Adam Groce

A Thesis Presented to The Established Interdisciplinary Committee for Mathematics and Computer Science at Reed College, May 2022

## Abstract: 
In this thesis we explain the fundamentals of modern cryptography with a focus
on elliptic curves, detailing the elliptic curve group that is extremely important to
modern cryptography. We build a foundation in modern cryptography which we use
to construct and implement elliptic curve versions of common applications such as
Elliptic Curve Diffie-Hellman and Elliptic Curve El Gamal. We also analyze and
implement the Baby Step Giant Step and Pollard’s Rho algorithms which compute
discrete logarithms on elliptic curves. We explain how these algorithms are better
than a brute force search and explore ways to improve them further with some ideas
from modern cryptography research.

## Preface: 
I began this thesis after a summer where I spent the little time that I wasn’t shooting
pool, working on the old linux machines that the people in the pool hall know as
“The Jukebox”. During that time, a friend named Tucker Twomey introduced me to
many new ideas in computer science, one of which was the marvel of elliptic curve
cryptography. Tucker enthusiastically explained that by using elliptic curves, we
achieve a similar level of security as RSA, but with a much shorter key length. At the
time, I was just beginning my exploration into cryptography and would soon learn
all about the formal theories of modern cryptography in a class here at Reed.
While thinking about ideas for my thesis, I pondered many topics, but cryptography, though I had not done much formal study yet, was always the most interesting
to me. It is just one of those things that we depend upon so often in our daily lives,
yet when asked what makes our online payments secure, few could say more than
magic.
For these reasons, this thesis is a journey into the world of cryptography, specifically exploring elliptic curves which are a major part of modern cryptography. This
thesis is written for an undergraduate student of mathematics and computer science
who wants to begin exploring cryptography and may use this work as a jumping off
point to access higher level concepts and read current literature on the subject.
In the first chapter, we will review concepts from group theory, introduce elliptic
curves, and explain the creation of the elliptic curve group, with special care for the
associativity condition.
In the second chapter we introduce some foundational ideas from cryptography,
and then apply them to the elliptic curve group that we have constructed.
In the third and final chapter we introduce two fundamental algorithms for computing discrete logarithms on elliptic curves, touching on a few modern improvements
and current ideas in cryptography research.
