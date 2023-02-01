---
title: "Introducción a R"
output: learnr::tutorial
runtime: shiny_prerendered
---
```{r setup, include=FALSE}
library(learnr)
knitr::opts_chunk$set(echo = FALSE)
```

## Instalación

### ¿Que es R?
R es un lenguaje de programación que es utilizado principalmente para los análisis estadísticos. Sin embargo, ultimamente se han desarrollado paqueterías que permiten, desde el desarrollo de modelos de inteligencia artificial hasta aplicaciones interactivas, principalmente SHINY. 

- Es un leguaje de programación que interatúa con muchos otros como Python, Java y Javascript.  
- Es licencia libre y código abierto
- Trabaja en distitntas plataformas como Linux, Windows, MacOS
- Su uso principal es para el análsis estadísticos y realiza gráficos de alta calidad

Su instalación en windows es muy fácil e intuitiva, se descarga e intala como cualquier otro programa. A continuación se muestran los links de descarga: 

##### Descargar R en su versión más reciente
**<http://cran.r-project.org/bin/windows/base/>**

##### Descargar RStudio
**<http://www.rstudio.com/ide/download/>**

### Video tutorial de intalación
![](https://www.youtube.com/watch?v=E5KzCLn1EsI)



## Topic 1

### Exercise 

*Here's a simple exercise with an empty code chunk provided for entering the answer.*

Write the R code required to add two plus two:

```{r two-plus-two, exercise=TRUE}

```

### Exercise with Code

*Here's an exercise with some prepopulated code as well as `exercise.lines = 5` to provide a bit more initial room to work.*

Now write a function that adds any two numbers and then call it:

```{r add-function, exercise=TRUE, exercise.lines = 5}
add <- function() {
  
}
```

## Topic 2

### Exercise with Hint

*Here's an exercise where the chunk is pre-evaluated via the `exercise.eval` option (so the user can see the default output we'd like them to customize). We also add a "hint" to the correct solution via the chunk immediate below labeled `print-limit-hint`.*

Modify the following code to limit the number of rows printed to 5:

```{r print-limit, exercise=TRUE, exercise.eval=TRUE}
mtcars
```

```{r print-limit-hint}
head(mtcars)
```

### Quiz

*You can include any number of single or multiple choice questions as a quiz. Use the `question` function to define a question and the `quiz` function for grouping multiple questions together.*

Some questions to verify that you understand the purposes of various base and recommended R packages:

```{r quiz}
quiz(
  question("Which package contains functions for installing other R packages?",
    answer("base"),
    answer("tools"),
    answer("utils", correct = TRUE),
    answer("codetools")
  ),
  question("Which of the R packages listed below are used to create plots?",
    answer("lattice", correct = TRUE),
    answer("tools"),
    answer("stats"),
    answer("grid", correct = TRUE)
  )
)
```
