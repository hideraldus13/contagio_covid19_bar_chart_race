# Notebook com Bar Chart Race de Contágio de Covid19 por Estados do Brasil  

Notebook com dados atualizados diariamente e exportação em gif e mp4.

<sub>Diga "Oi" <br> 
    [<img src = "https://img.shields.io/badge/github-black.svg?&style=for-the-badge&logo=github&logoColor=white">](https://github.com/hideraldus13)
    [<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/hideraldoluis/) 
    [<img src = "https://img.shields.io/badge/instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white">](https://www.instagram.com/hideraldojunior/) 
</sub>

## :runner: Fast Track
* Pré requisitos: <b>Python e [ffmpeg*(opcional)](https://ffmpeg.zeranoe.com/builds/ "Página de Download do ffmpeg")</b>
```bash
$ git clone https://github.com/hideraldus13/contagio_covid19_bar_chart_race.git
$ cd ocr_python_fast_track
$ pip install -r requirements.txt

//Comandos para Windows. Linux ou Mac não sei como funciona, mas é por aí.
```

## :candy: Testando a aplicação

- Abrir o notebook <i>covid19_states.ipynb</i> e rodar os comandos. 
- Veja que bar chart race estará disponível para execução. 
- Estarão disponíveis também, no mesmo diretório do código-fonte, as exportações em gif <i>(covid_gif.gif)</i> e mp4 <i>(covid_mp4.mp4)</i>. 

### :boom: Deu erro?
```bash
RuntimeError: Requested MovieWriter (ffmpeg) not available
```

- O ffmpeg deve ser instalado/descompactado e o caminho do diretório bin <i>(ffmpeg\bin)</i> deve estar presente no PATH das variáveis de sistema do Windows


### :smiling_imp: Mais, eu quero mais

Na fonte de dados utilizados para gerar os gráficos há também o número de óbitos, dentre outras informações. 
A utilização dessas outras informações, bem como o incremento dos dados traz uma gama gigantesca de aplicações que podem ser visualizadas de forma de evolução com o bar chart race.
Brinque à vontade. :gift:


#### :floppy_disk: Fonte de dados utlizada:
https://github.com/wcota/covid19br
