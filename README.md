# JUEVES
REPOSITORIO DEL JUEVES

cONJUNTO DE DATOS

```{r}
numeros <- seq(1,100, by=1)
```

Generamos dos muestras al azar que utilizaremos en la regresion lineal

```{r}
x <- sample(numeros,50)
y <- sample(numeros,50)
```

modelo de regresion lineal

```{r}
reg1 <- lm(x~y)
```

resultado de la regresion

```{r}
summary(reg1)
```

grafica

```{r}
plot(x~y)
abline(reg1)
```