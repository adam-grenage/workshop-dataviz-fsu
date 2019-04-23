# Software requirements
You should have both [R](https://www.r-project.org) and [RStudio](https://www.rstudio.com) installed on your machine. 

In this workshop, we will be using `R` together with the integrated development environment (IDE) RStudio. In addition to offering a 'cleaner' programming development than the basic `R` editor, RStudio offers a large number of added functionalities for integrating code into documents, built-in tools and web-development.

# Prerequisites
There are no formal prerequisites for this workshop. However, I am assuming that participants have a basic understanding of `R` programming, in particular:

* Setting a working directory,
* Installing and loading packages,
* Reading and writing data,
* Basic data formats (scalar, vector, data frame),
* Basic variable types (numeric, character, factor, logical),
* Basic vector and data frame operations, such as subsetting, transforming variables, merging, reshaping, etc.

If you are unfamiliar with `R` or would like to brush up on your skills, take a look at my [intro to data management workshop](https://github.com/thereseanders/Workshop-DataManagement-tidyverse). The first two sessions go over basic `R` functionality and programming principles. The latter four sessions introduce data management operations using packages from the [`tidyverse`](https://www.tidyverse.org/packages/) suite. I also recommend taking a look at [`R` for Data Science](https://r4ds.had.co.nz) website and/or book for a great resource on learning `R` and data management. 

# Getting help
The key to learning `R` is: Google! This workshop will give you an overview over data visualiztion in `R`, but to become truly proficient you will have to actively use it yourself, trouble shoot, ask questions, and google! The `R` mailing list and other help pages such as [StackOverflow](http://stackoverflow.com) offer a rich archive of questions and answers by the `R` community. For example, if you google "recode variable in r" you will find a variety of useful websites explaining how to do this on the first page of the search results. Also, don't be surprised if you find a variety of different ways to execute the same task.

RStudio has a useful help menu. In addition, you can get information on any function or integrated data set in `R` through the console, for example:

```{r}
?geom_tile()
```

