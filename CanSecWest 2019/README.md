# Danger of Using Fully Homomorphic Encryption，a Look at Microsoft SEAL - CanSecWest 2019



This is my slides for CanSecWest 2019


Fully homomorphic encryption is a promising crypto primitive to encrypt your data while allowing others to compute on the encrypted data. But there are many well-known problems with fully homomorphic encryption such as CCA security and circuit privacy problem. Despite these problems, there are still many companies are currently using or preparing to use fully homomorphic encryption to build data security applications. It seems that the full homomorphic encryption is very close to practicality and these problems can be easily mitigated in implementation. Although the those problems are well known in theory, there is no public discussion of their actual impact on real application. Our research shows that there are many security pitfalls in fully homomorphic encryption from the perspective of practical application. The security problems of a fully homomorphic encryption in a real application is more severe than imagined.  We will take Microsoft SEAL as an examples to introduce the security pitfalls of fully homomorphic encryption from the perspective of implementation and practical application
