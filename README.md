# My_first_Repository
##Excersise 1 - Code
> ?mtcars
starting httpd help server ... done
> dat=mtcars
> pmatrix=scale(dat)
> d=dist(pmatrix)
> c=hclust(d,method="ward.D2")
> plot(c)
> rect.hclust(c,k=4)
> groups<-cutree(c,k=4)
> table(mtcars$species,groups) *Thank You*
