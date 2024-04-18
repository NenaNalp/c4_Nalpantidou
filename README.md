# Example of README.md
## Dendogram Exercise
?mtcars
dat=mtcars
pmatrix=scale(dat)
d=dist(pmatrix)
c=hclust(d, method="ward.D2")
plot(c)
rect.hclust(c, k=4)
