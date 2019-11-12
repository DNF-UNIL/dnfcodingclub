# 06 11 19 Session


### Server Connection
http://130.223.196.101:8080

### Github
https://github.com/

### Bash
https://explainshell.com/

#### Download image script

```
#/bin/bash

for i in {0..100}
do

echo $i
wget https://spainweather.es/webcams/malaga/current.jpg
sleep 3

done
```

### Jupyter Notebooks
https://jupyter.org/

#### Binder
https://mybinder.org/

### Docker
https://www.docker.com/

https://hub.docker.com/

### R
by L. Telley

https://juba.github.io/tidyverse/02-prise_en_main.html

#### EBImage

Is necesary to install in the terminal this dependency before

```bash
sudo apt-get update
sudo apt-get install libfftw3-3 libfftw3-dev libtiff5-dev
sudo conda install -c eumetsat fftw3
```

```R
if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")

BiocManager::install("EBImage")
```

### Shiny

by Adrian

![](06_11_19_img/Slide1.JPG)
![](06_11_19_img/Slide2.JPG)
![](06_11_19_img/Slide4.JPG)
![](06_11_19_img/Slide5.JPG)
![](06_11_19_img/Slide6.JPG)
![](06_11_19_img/Slide7.JPG)
![](06_11_19_img/Slide8.JPG)
![](06_11_19_img/Slide9.JPG)
![](06_11_19_img/Slide10.JPG)
![](06_11_19_img/Slide11.JPG)
![](06_11_19_img/Slide12.JPG)
![](06_11_19_img/Slide13.JPG)

## How to install Docker

https://docs.docker.com/install/linux/docker-ce/ubuntu/

```
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -

sudo add-apt-repository \
   "deb [arch=amd64] https://download.docker.com/linux/ubuntu \
   $(lsb_release -cs) \
   stable"

sudo apt-get update
sudo apt-get install docker-ce docker-ce-cli containerd.io

```
