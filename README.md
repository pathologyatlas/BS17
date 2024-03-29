





```
r language BS17, echo=FALSE, include=TRUE
source("./R/language.R")
output_type <- knitr::opts_knit$get("rmarkdown.pandoc.to")
```


```
asis CMV hepatiti, karaciğer TR, echo = (language == "TR")
## BS17 - CMV hepatiti, karaciğer {#sec-BS17 }
```


```
asis CMV hepatitis, liver EN, echo = (language == "EN")
## BS17 - CMV hepatitis, liver {#sec-BS17 }
```






```
r BS17 screenshot HE, eval=TRUE, include=FALSE
if (!file.exists("./screenshots/BS17-HE_screenshot.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/BS17/HE.html",
  file = "./screenshots/BS17-HE_screenshot.png"
)
}
```





::::: panel-tabset


### WSI - Link










[https://images.patolojiatlasi.com/BS17/HE.html](https://images.patolojiatlasi.com/BS17/HE.html)





```
asis, echo = (language == "TR")

**CMV hepatiti, karaciğer**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/BS17-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS17/HE.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/BS17/HE.html)
```

```
asis, echo = (language == "EN")

**CMV hepatitis, liver**

[![Click for Full Screen WSI](./screenshots/BS17-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS17/HE.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/BS17/HE.html)

```





### WSI








```
asis, echo = ((language=="TR") & (output_type=="html"))
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/BS17/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





```
asis, echo = ((language == "EN") & (output_type=="html"))

See Microscopy with viewer:

<iframe src="https://images.patolojiatlasi.com/BS17/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





### Diagnosis


```
asis, echo = (language == "TR")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Tanı için tıklayın

CMV hepatiti, karaciğer

:::


```


```
asis, echo = (language == "EN")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Click for Diagnosis

CMV hepatitis, liver

:::

```









:::::











