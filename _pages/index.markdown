---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default-full
title: "Home"
subtitle: ""
show_sidetoc: true
header_type: hero #base, post, hero,image, splash
header_img: assets/images/Microphone.jpg
header_title: "Youtube e i Podcast: <br>
L'Ascesa nella Nuova Era di Contenuti Digitali"
subtitle: "Come è cambiato il mondo dei podcast negli ultimi 10 anni?"
---
<!-- Custom width and offset -->
<div class="custom-col custom-offset"> </div>

<div class="container py-3">
    <div class="row">
        <div class="col-md-3 col-md-offset-3">
        </div>
        <div class="col-md-6">
            <hr>
            <p>Negli ultimi anni, i podcast hanno conquistato uno spazio sempre più importante all'interno della nostra quotidianità. La semplicità di fruizione dello streaming, la crescente domanda di contenuti digitali da parte dei consumatori finali e il proliferare di nuove piattaforme distributive hanno contribuito a renderli uno dei contenuti principali della nostra “dieta mediatica”. Nella galassia dei nuovi media digitali, il podcast rappresenta un formato alternativo di comunicazione, un’ estensione delle attività quotidiane delle radio e degli editori, in cui trovano facile spazio contenuti di informazione, educazione e intrattenimento.
            Secondo la ricerca IPSOS 2023, il 39% degli italiani ha ascoltato podcast nell’ultimo mese. In numeri assoluti, tutto ciò si traduce in circa 11.9 milioni di ascoltatori mensili di podcast in Italia.

            
            <br>
            <br>
            <br>
            ***Qui va la parte delle date con il grafico***
            <br>
            <br>
            <br>
            Ma come si è evoluto questo formato di contenuto? Quali sono i temi e gli argomenti che hanno guadagnato maggiore popolarità nel tempo? 
            Per rispondere a queste domande, abbiamo preso in considerazione 24 tra i più seguiti canali Podcast sulla piattaforma YouTube d'oltreoceano.
            <br>
            Il nostro dataset di analisi si compone di 14 mila youtube podcast, 24 canali, 20+ ore. I canali selezionati sono quelli più popolari secondo la classifica del seguente link: https://rephonic.com/charts/youtube/united-states/popular-podcasts.
            <br>
            <br>
            <br>
            ***Grafico crescita views***
            <br>
            <br>
            <br>
            </p>
            <hr>
        </div>
    </div>
</div>


# Topic Modelling

<div class="container py-3">
    <div class="row">
        <div class="col-md-3 col-md-offset-3">
        </div>
        <div class="col-md-6">
            <hr>
            <p>Negli ultimi anni, i podcast hanno conquistato uno spazio sempre più importante all'interno della nostra quotidianità. La semplicità di fruizione dello streaming, la crescente domanda di contenuti digitali da parte dei consumatori finali e il proliferare di nuove piattaforme distributive hanno contribuito a renderli uno dei contenuti principali della nostra “dieta mediatica”. Nella galassia dei nuovi media digitali, il podcast rappresenta un formato alternativo di comunicazione, un’ estensione delle attività quotidiane delle radio e degli editori, in cui trovano facile spazio contenuti di informazione, educazione e intrattenimento.
            <br>
            <br>
            <br>
            ***Qui va la parte delle date con il grafico***
            <br>
            <br>
            <br>
            Ma come si è evoluto questo formato di contenuto? Quali sono i temi e gli argomenti che hanno guadagnato maggiore popolarità nel tempo? 
            Per rispondere a queste domande, abbiamo preso in considerazione 24 tra i più seguiti canali Podcast sulla piattaforma YouTube d'oltreoceano.
            <br>
            Il nostro dataset di analisi si compone di 14 mila youtube podcast, 24 canali, 20+ ore. I canali selezionati sono quelli più popolari secondo la classifica del seguente link: https://rephonic.com/charts/youtube/united-states/popular-podcasts.
            <br>
            <br>
            <br>
            ***Grafico crescita views***
            <br>
            <br>
            <br>
            </p>
            <hr>
        </div>
    </div>
</div>

<div class="row pb-5">
    <div class="col-md-12 col-sm-12">
        <div class="card-container">
            {% for image in site.data.home-cards %}
            <div class="card" style="width: 18rem;">
                    <a href="{{site.baseurl}}{{ image.path}}">
                    <div class="card-img"  ><img src="{{site.baseurl}}{{ image.url}}" class="card-img-top" alt="{{ image.name }}">
                    </div>
                    <div class="card-body">
                        <h5 class="card-title">{{ image.name }}</h5>
                        <p class="card-text">{{ image.description }}</p>
                    </div>
                    </a>    
            </div>
            {% endfor %}
        </div>
    </div>
</div>


<div class="container py-3 mb-0 bg-color-full bg-color">
    <div class="row">
        <div class="col-md-3 col-md-offset-3">
        </div>
        <div class="col-md-6">
            <p>Prima di affrontare la realizzazione del sito è necessario installare Jekyll</p>
            <a href="{{site.baseurl}}/installation" class="btn btn-info" role="button">Installazione di Jeykll</a>
        </div>
    </div>
</div>
