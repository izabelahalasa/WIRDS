# WIRDS

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/izabelahalasa/WIRDS/main?urlpath=rstudio)

Aby binder działał potrzeba następującego pliku:

1. 'runtime.txt' -- określamy z jakiej wersji R będziemy korzystać oraz z jakiego dnia mają buć pakiety

Możemy założyć jakie pakiety mają być w ramach tego obrazu. w takim razie powinniśmy utworzyć plik o nazwie install.R, który będzie zaweirał skrypt R do instalacji pakietów. Na przykład:
  
install.packages("tidyverse")
install.packages("data.table")
install.packages("sf")
install.packages("rio")
