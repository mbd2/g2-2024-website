---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default-full
title: "Home"
subtitle: ""
vega: True
show_sidetoc: true
header_type: hero #base, post, hero,image, splash
header_img: assets/images/Microphone.jpg
header_title: "Youtube e i Podcast: <br>
L'Ascesa nella Nuova Era di Contenuti Digitali"
# subtitle: "Come è cambiato il mondo dei podcast negli ultimi 10 anni?"
---
<!-- Custom width and offset -->
<div class="custom-col custom-offset"> </div>

<style>
    .quote-box {
        border: 2px solid #ccc;
        padding: 35px;
        margin: 35px 0; 
        background-color: #181818;
        font-style: italic;
        position: relative;
        outline: 2px solid #888;
        border-radius: 12px; /* Arrotonda i bordi dell'outline */
        pointer-events: none; /* Assicura che l'elemento non sia cliccabile */
        color: white;
    }
    .quote-box::before {
        content: "“";
        font-size: 4em;
        position: absolute;
        left: 10px;
        top: -10px;
        right: -10px;
        color: #ccc;
    }
    .quote-box::after {
        content: "”";
        font-size: 4em;
        position: absolute;
        right: 25px;
        bottom: 20px;
        color: #ccc;
    }
    .author {
        text-align: right;
        font-weight: bold;
        margin-top: 20px;
        color: white;
    }
    .container {
        position: relative;
        width: 100%;
        max-width: 800px;
        margin: 20px auto;
    }

    .collapsible {
        background: linear-gradient(45deg, 
                                    transparent 0%, 
                                    transparent 47%, 
                                    rgba(255, 255, 255, 0.3) 50%,
                                    rgba(255, 255, 255, 0.35) 51%,
                                    rgba(255, 255, 255, 0.40) 52%,
                                    rgba(255, 255, 255, 0.40) 53%,
                                    rgba(255, 255, 255, 0.35) 54%,
                                    rgba(255, 255, 255, 0.3) 55%, 
                                    transparent 58%, 
                                    transparent 100%);
        background-size: 200% 200%;
        background-position: 0% 100%;
        color: #ffffff;
        cursor: pointer;
        padding: 10px;
        width: auto;
        height: auto;
        border: none;
        text-align: center;
        outline: none;
        font-size: 16px;
        border-radius: 5px;
        transform-origin: right top;
        transform: rotate(0deg);
        transition: transform 0.3s;
        display: inline-block;
        animation: slideBackground 2s infinite linear;
    }

    .collapsible:focus {
        outline: none;
        border: none;
    }

    .collapsible.active {
        transform: rotate(-90deg);
        animation: none; /* Disabilita animazione quando attivo */
    }

    .content {
        padding: 20px;
        display: none;
        overflow: hidden;
        background-color: rgba(24, 24, 24, 0.8); /* nero con 80% di opacità */
        color: #ffffff;
        border-radius: 5px;
        border: 1px solid #ccc;
        margin-top: -50px;
    }

    .header {
        display: flex;
        justify-content: flex-end;
    }

    .anchor-offset {
    scroll-margin-top: 90px; /* Aggiungi uno spazio extra sopra la sezione */
    }


    @keyframes slideBackground {
        0% {
            background-position: 200% 100%;
        }
        100% {
            background-position: 0% 100%;
    }
}
</style>

<script>
    document.addEventListener('DOMContentLoaded', (event) => {
        var coll = document.getElementsByClassName("collapsible");
        for (var i = 0; i < coll.length; i++) {
            coll[i].addEventListener("click", function() {
                this.classList.toggle("active");
                var content = this.parentElement.nextElementSibling;
                if (content.style.display === "block") {
                    content.style.display = "none";
                } else {
                    content.style.display = "block";
                }
            });
        }
    });
</script>

<div id="introduzione" class="anchor-offset" style="text-align: center;">
    <h1 style="color: white; font-size: 48px;">Introduzione</h1>
</div>

<div style="position: relative; width: 100%; padding-right: 200px; padding-left: 200px;">
    <div class="row">
        <div class="col-md-3 col-md-offset-3">
        </div>
        <div class="col-md-6">
            <hr>
            <p>Negli ultimi anni, i podcast si sono conquistati uno spazio sempre più importante all'interno delle nostre quotidianità.</p>
            <p>Il termine nacque quando l'uso dei feed RSS divenne popolare per lo scambio di registrazioni audio su computer, palmari, lettori di musica digitale e anche telefoni cellulari. L'origine più accreditata del termine podcasting è un articolo apparso sul quotidiano britannico The Guardian a firma di Ben Hammersley, Audible Revolution, in cui l'articolista, per definire il nuovo fenomeno di file audio in formato MP3 disponibili su supporti facilmente trasportabili come l'iPod e la possibilità di costruire un palinsesto completamente digitale senza passare per l'etere, cercava di trovare un termine-ombrello che definisse il tutto.</p>
            <p>La semplicità di fruizione dello streaming, la crescente domanda di contenuti digitali da parte dei consumatori finali e il proliferare di nuove piattaforme distributive come Spotify inizialmente, e Youtube poi, hanno contribuito a renderli uno dei prodotti principali della nostra “dieta mediatica”.</p>   
            <p>Secondo la ricerca IPSOS 2023, il 39% degli italiani ha ascoltato podcast nell’ultimo mese. In numeri assoluti, tutto ciò si traduce in circa 11.9 milioni di ascoltatori mensili di podcast in Italia.</p>
            <div class="container">
                <div class="header">
                    <button type="button" class="collapsible">Technical analysis</button>
                </div>
                <div class="content">
                    <p>"Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?"
                    Traduzione del 1914 di H. Rackham</p>
                </div>
            </div>
            <p>Daria Corrias, autrice e documentarista radiofonica che abbiamo avuto il piacere di intervistare, si esprime così riguardo all'avvento dei Podcast nel nostro paese:</p>
            <div class="quote-box">
                Da Serial sono passati 10 anni. Oggi nel 2024 abbiamo visto che il Podcast non è solo questo.
                <div class="author">- Daria Corrias</div>
            </div>
            <p>Come ci conferma anche la nostra intervistata, quindi, i podcast erano strutturati in maniera orizzontale, vuol dire che per comprendere appieno ogni episodio era necessario aver ascoltato quello precedente. Questo requisito, divenne via via sempre meno importante, fino al punto che oggi, la maggior parte dei Podcast, offrono un tipo di contenuto verticale.  
            Infatti, i canali che abbiamo preso in considerazione per la nostra analisi, offrono questo tipo di contenuto.</p>
            <div class="quote-box">
                Da Serial sono passati 10 anni. Oggi nel 2024 abbiamo visto che il Podcast non è solo questo.
                <div class="author">- Daria Corrias</div>
            </div>
            <p>Per effettuare le nostre analisi, ci siamo focalizzati sugli Stati Uniti e abbiamo preso in considerazione 24 tra i più seguiti canali Podcast sulla piattaforma YouTube nel mese di Maggio 2024, a questo <a title="Link" href="https://rephonic.com/charts/youtube/united-states/popular-podcasts">Link</a></p>
            <vegachart schema-url="{{site.baseurl}}/assets/charts/views_pub_chart_BLACK_VERO 2.json" style="width: 100%; display: flex; justify-content: center;"></vegachart>                 
            <br>
            <vegachart schema-url="{{site.baseurl}}/assets/charts/frequency_PDF_CDF_chart.json" style="width: 100%; display: flex; justify-content: center;"></vegachart>
            <br>
            <vegachart schema-url="{{site.baseurl}}/assets/charts/beeswarm_chart.json" style="width: 100%; display: flex; justify-content: center;"></vegachart> 
            <br>
            <vegachart schema-url="{{site.baseurl}}/assets/charts/temporal_chart 2.json" style="width: 80%; height: 100vh;"></vegachart>
            </p>
            <hr>
        </div>
    </div>
</div>



<div id="topic-extraction" class="anchor-offset" style="text-align: center;">
    <h1 style="color: white; font-size: 48px;">Topic Extraction</h1>
</div>

<div style="position: relative; width: 100%; padding-right: 200px; padding-left: 200px;">
    <div class="row">
        <div class="col-md-3 col-md-offset-3">
        </div>
        <div class="col-md-6">
            <hr>
            <p>Quali sono i temi e quali argomenti sono stati trattati nel tempo?</p> 
            <p>Dalle trascrizioni ottenute dai diversi episodi dei Podcast presenti in YouTube abbiamo estratto. i topic definiti sono 11 e sono sono: politics', 'sports', 'economy', 'health', 'technology', 'culture', 'education','environment','crime' e 'entertainment'. </p>
            <p>Specifichiamo che nella categoria crime possono rientrare non sono episodi True Crime ma anche crimini di guerra, crimini politici ecc. Education viene intesa invece non solo come educazione scolastica ma anche temi che riguardano la formazione lavorativa, la crescita personale, temi che possono riguardare il razzismo, quindi tutti temi che hanno a che fare con la crescita personale degli individui o dell’intervistato.</p>
            <p>Nel tempo abbiamo visto quale è stata l’evoluzione dei temi nei podcast:</p> 
            <br>
            <vegachart schema-url="{{site.baseurl}}/assets/charts/TOPIC_PROJECT_BLACK_VERO_3.json" style="width: 100%; display: flex; justify-content: center;"></vegachart> 
            <br>
            <p>Dal 2013 i temi ricorrenti per gli episodi podcast da noi analizzati erano tecnologia, con una preponderanza maggiore di questo tema sugli altri  e poi altri temi come crime, health e entertainment. Particolarmente interessante è vedere come il tema politics compaia nel 2017 per poi arrivare ad essere uno dei temi principali dal 2022 fino al 2024. C’è da sottolinerare però che il canale podcast MedaisTouch e il canale di Brian Tyler Cohen Podcast (che trattano principalmente di temi politici)sono quelli con il maggior numero di episodi sul complessivo rispetto a questi anni.</p>
            <br>
            <p>Di seguito invece abbiamo un grafico a bolle su quali sono i temi principalmente tratti rispetto agli argomenti. Se cliccate dentro la bolla è possibile visualizzare tutti i temi principalmente discussi all’interno dei diversi canali podcast.</p>
            <br>
            <div class="flourish-embed flourish-hierarchy" data-src="visualisation/18816599"><script src="https://public.flourish.studio/resources/embed.js"></script>
            </div>
            <br>
            <div class="container">
                <div class="header">
                    <button type="button" class="collapsible">Technical analysis</button>
                </div>
                <div class="content">
                    <p>Tramite le API di Google siamo riusciti a scaricare circa 13.218 documenti complessivi. Per il preprocessing, abbiamo rimosso le annotazioni come [music], [laughing], ecc., utilizzando un’espressione regolare. Abbiamo tokenizzato il testo in parole singole, rimosso le stopword e i numeri, eliminato la punteggiatura e convertito tutte le parole in minuscolo.</p>
                    <p>Abbiamo utilizzato il modello Word2Vec di Google-news-300 per creare un sistema di classificazione non supervisionato basato su embedding. Questo ci ha permesso di ottenere il vettore di embedding per ciascuna parola nel testo preprocessato utilizzando il modello Word2Vec, e di restituire la media di questi vettori.</p>
                    <p>Successivamente, abbiamo definito un dizionario con diversi temi, quali: ‘politics’, ‘sports’, ‘economy’, ‘health’, ‘technology’, ‘culture’, ‘education’, ‘environment’, ‘crime’ e ‘entertainment’. Abbiamo calcolato la media dei vettori di embedding per le parole chiave di ciascun argomento.</p>
                    <p>Una volta ottenuto il vettore dei topic, abbiamo calcolato la similarità del coseno tra quest’ultimo e il vettore delle trascrizioni, e abbiamo salvato per ciascun URL il topic con la similarità del coseno più alta.</p>
                    <p>Da un punto di vista qualitativo, abbiamo controllato che i topic assegnati fossero corretti rispetto all’argomento trattato nel video. Su 90 video analizzati, abbiamo riscontrato un’assegnazione errata dei topic per 25 URL.</p>
                </div>
            </div>
            </p>
            <hr>
        </div>
    </div>
</div>


<div id="sentimenti-analysis" class="anchor-offset" style="text-align: center;">
    <h1 style="color: white; font-size: 48px;">Sentiment analysis</h1>
</div>

<div style="position: relative; width: 100%; padding-right: 200px; padding-left: 200px;">
    <div class="row">
        <div class="col-md-3 col-md-offset-3">
        </div>
        <div class="col-md-6">
            <hr>
            <p>Nell'era digitale, il successo dei podcast dipende fortemente dall'engagement con il pubblico. La nostra analisi ha esaminato il sentiment dei commenti ai video per capire come si evolvono le percezioni degli ascoltatori nel tempo.</p>
            <p>I risultati sono chiari: negli anni analizzati, i commenti positivi rappresentano una porzione significativa delle interazioni, indicando una prevalenza di sentimenti favorevoli. Tuttavia, un fenomeno degno di nota è emerso: i commenti negativi sono in aumento rispetto agli anni precedenti. </p>
            <br>
            <br>
            <vegachart schema-url="{{site.baseurl}}/assets/charts/Polarity_Comments 2.json" style="width: 100%; display: flex; justify-content: center;"></vegachart>
            <br>
            <br>
            <p>Questo trend solleva interrogativi importanti. Cosa sta alimentando l'incremento dei feedback negativi? È un fenomeno isolato o si verifica su tutte le piattaforme social? </p> 
            <p>Capire le ragioni dietro l'aumento dei commenti negativi è cruciale per i creatori di contenuti. In un mondo sempre più connesso, mantenere un rapporto positivo con il proprio pubblico è una sfida complessa. Se da un lato, i commenti negativi possono indicare aree di miglioramento, dall'altro, potrebbero anche contribuire ad accrescere la visibilità e il dibattito attorno ai contenuti. </p>
            </p>
            <div class="container">
                <div class="header">
                    <button type="button" class="collapsible">Technical analysis</button>
                </div>
                <div class="content">
                    <p>Si è effettuata una sentiment analysis sui commenti ai video utilizzando VADER per determinare la polarità dei sentimenti espressi, sia positivi che negativi.</p>
                    <p>VADER è uno strumento di analisi del sentimento che assegna punteggi di positività o negatività a oltre 7.000 parole ed emoticon, basandosi su lessici di sentimenti noti.</p>
                    <p>Inoltre, utilizza una serie di regole di corrispondenza dei modelli scritte a mano, come le negazioni e gli intensificatori, per modificare il contributo dei punteggi delle parole originali al sentimento generale del testo.</p>
                    <p>Si sono utilizzati strumenti per pulire e preparare testi da commenti. Si sono utilizzati due funzioni di pulizia:
                    una per rimuovere caratteri non alfanumerici e accenti,
                    l'altra per gestire specifici elementi dei commenti di YouTube come URL, hashtag e menzioni.</p>
                    <p>I risultati restituiti dal modell Vader sono i seguenti:
                    {‘neg’: 0,125, ‘neu’: 0.595, ‘pos’: 0.28, ‘compound’: 0.604}.</p>
                    <p>Per migliorare la qualità dei dati, sono stati selezionati solo i record con un valore di compound superiore a 0,6. Questo filtro ha ridotto il numero di record a circa 6 milioni, rispetto ai 18 milioni iniziali.</p>
                </div>
            </div>
            <hr>
        </div>
    </div>
</div>


<div id="audio" class="anchor-offset" style="text-align: center;">
    <h1 style="color: white; font-size: 48px;">Analisi tracce audio</h1>
</div>

<div style="position: relative; width: 100%; padding-right: 200px; padding-left: 200px;">
    <div class="row">
        <div class="col-md-3 col-md-offset-3">
        </div>
        <div class="col-md-6">
            <hr>
            <p>Ma come si è evoluto il suono dei podcast nel corso degli ultimi anni? Per rispondere a questa domanda abbiamo esaminato alcune caratteristiche audio dei 24 podcast, analizzando oltre 7500 episodi. </p>
            <p>Le variabili chiave oggetto di studio sono state l’energia RMS (rms_energy) che misura l’intensità media del segnale, il primo coefficiente cepstrale Mel (mfcc_1_mean) che cattura informazioni sulla “qualità” o il “colore” della voce ed è influenzato dall’energia dello spettro, il ritmo (tempo) del parlato, la frequenza media del pitch (pitch_mean), utile nel determinare quanto “alta” o “bassa” sia la voce in media in termini di frequenze, il tasso di attraversamento dello zero (zero_crossings_rate), il centroide spettrale medio (spectral_centroid_mean) e il roll-off spettrale medio (spectral_rolloff_mean).</p>
            <br>
            <br>
            <vegachart schema-url="{{site.baseurl}}/assets/charts/chart_audio3.json" style="width: 100%; display: flex; justify-content: center;"></vegachart>
            <br>
            <br>
            <p>Uno dei risultati riscontrati è stato un marcato cambiamento nelle audio features intorno alla fine del 2019. Abbiamo osservato un picco significativo sia per quanto riguarda l’energia espressa (rms_energy) che le caratteristiche del timbro vocale (mfcc_1_mean), seguito da un declino nell’andamento delle stesse variabili. Un’ipotesi è che, in una prima fase, a seguito dell’aumento della popolarità dei podcast i creatori potrebbero aver sperimentato stili più energici e dal ritmo più serrato per distinguersi e tenere alta l’attenzione degli ascoltatori.  </p> 
            <p>Dopo il 2020 emergono tendenze interessanti nel complesso paesaggio sonoro dei podcast. Possiamo notare una diminuzione dell’intensità e del ritmo percepito, così come del primo coefficiente MFCC. Al contrario, le variabili pitch_mean (altezza della voce), zero_crossings_rate (presenza di suoni acuti) e spectral_centroid_mean (brillantezza del suono) mostrano un andamento crescente. I podcaster sembrano aver optato per uno stile di presentazione più rilassato ma con una maggiore enfasi sulla definizione del suono. I cambiamenti nello stile vocale potrebbero essere legati all’esperienza di fruizione del medium degli utenti: voci più acute e brillanti possono risultare maggiormente intelligibili, soprattutto in ambienti di ascolto non ideali (ad esempio, durante gli spostamenti e in presenza di rumore di fondo). Inoltre, sempre in riferimento all’adattamento tecnologico, le preferenze inerenti ai meccanismi diffusivi potrebbero essersi indirizzate verso suoni che vengono meglio riprodotti su dispositivi mobili e auricolari wireless, e la combinazione di suoni più chiari ma meno intensi potrebbe rendere l’ascolto più confortevole se protratto per lunghi periodi. </p>
            </p>
            <div class="container">
                <div class="header">
                    <button type="button" class="collapsible">Technical analysis</button>
                </div>
                <div class="content">
                    <p>Per l'estrazione delle variabili relative all'audio abbiamo implementato un sistema basato sulle librerie Librosa e Pydub, ottimizzato per l'elaborazione parallela su 32 core tramite Dask. Il processo ha previsto l'utilizzo di Pydub per la manipolazione dei file audio applicando una normalizzazione del volume per ottenere una coerenza sonora tra i diversi file. Successivamente, quando necessario, è stato effettuato un ricampionamento a 44100 Hz utilizzando Librosa, assicurando così una frequenza di campionamento uniforme per tutte le analisi successive. La durata complessiva dell'audio processato ammonta all'incirca a 2765 ore. </p>
                    <p>Le variabili estratte comprendono il tasso di attraversamento dello zero, l'energia RMS e la sua deviazione standard, la media e la deviazione standard del segnale, altre statistiche generali come la curtosi e l’asimmetria, il pitch medio e la sua deviazione standard, i primi 7 coefficienti MFCC, il centroide spettrale e la sua deviazione standard, il roll-off spettrale e la sua deviazione standard, e il tempo. Queste features sono state calcolate utilizzando le funzioni di Librosa, che offrono algoritmi ottimizzati per l'analisi del segnale audio. I risultati sono stati salvati in CSV e poi convogliati in un dataset unitamente ai metadati e altre variabili di interesse. </p>
                    <p>Quanto alla visualizzazione dei dati, dopo la rimozione degli outlier, abbiamo applicato tecniche di raggruppamento mensile, standardizzazione delle variabili e media mobile. Per creare il grafico interattivo che mostra l'evoluzione temporale delle variabili audio standardizzate abbiamo utilizzato Altair. </p>
                </div>
            </div>
            <hr>
        </div>
    </div>
</div>



<div id="frame-color" class="anchor-offset" style="text-align: center;">
    <h1 style="color: white; font-size: 48px;">Frame color analysis</h1>
</div>

<div style="position: relative; width: 100%; padding-right: 200px; padding-left: 200px;">
    <div class="row">
        <div class="col-md-3 col-md-offset-3">
        </div>
        <div class="col-md-6">
            <hr>
            <div style="text-align: center;">
                <h2 style="color: white; font-size: 28px;">Frame</h2>
            </div>
            <br>
            <p>Molto spesso gli Youtuber, e nella nostra fattispecie i Podcaster, non considerano, o mettono in secondo piano, la scelta dei colori preponderanti all’interno delle loro inquadrature. Anche i fruitori stessi credono che i colori che partecipano alla creazione dell’ambiente virtuale all’interno del quale si svolge il podcast non influenzi il loro engagement.</p>
            <p>In realtà, la scelta dei colori e conseguentemente l’ambient che viene a crearsi all’interno di un podcast, risulta essere una variabile di primaria importanza, che innesca nel fruitore un senso di comfort e cattura involontariamente l’attenzione. Questo comporta un vantaggio enorme per il podcaster che mira ad ottenere un forte coinvolgimento del pubblico e alla sua fidelizzazione nel tempo.</p>
            <p>Consapevoli dell’importanza di questa variabile, è stato condotto uno studio sulla totalità dei podcast presi in analisi per individuare quali fossero i colori principali più utilizzati dai podcaster statunitensi di successo.</p>
            <p>Dato che nel tempo, vuoi per moda, per cultura o aspettativa degli utenti, i colori più attraenti posso aver subito delle modifiche, lo studio è stato condotto su uno span temporale il più largo possibile, così da capirne la sua tendenza nel tempo.</p>
            <p>Estrapolando diversi frame da ogni podcast in analisi, ed estrapolando i colori più rilevanti per ogni podcast, è emersa la seguente evoluzione dell’utilizzo dei colori di scena.</p>
            <br>
            <br>
            <br>
            <div class="flourish-embed flourish-bar-chart-race" data-src="visualisation/18803566"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
            <br>
            <br>
            <br>
            <p>Prima di trarre delle conclusioni da quanto mostra il grafico, è necessario precisare che i colori riportati sono i colori utilizzati in scena al netto della loro luminosità e saturazione. Difatti dai frame sono stati estrapolati i valori “HSL”, ossia Hue Saturation Lightness, e sono stati rimossi i valori di Saturation e Lightness, in modo tale da ottenere i colori reali utilizzati in scena senza l’influenza della loro esposizione. Considerare la loro esposizione, avrebbe portato la nostra analisi all’individuazione di una mera scala di grigi. Questo perché, anticipando leggermente le conclusioni, l’illuminazione della scena, nella stragrande maggioranza dei casi, mira a creare un ambiente “caldo e accogliente”. L’eliminazione di questa variabile ci fornisce una rappresentazione reale del colore degli oggetti portati in scena.</p>
            <p>Precisato questo, risulta evidente come nel corso degli anni, partendo da una scelta di colori prettamente freddi, vi sia stato un trend di avvicinamento ai colori caldi. Questo perché, è noto come i colori caldi tendono a creare rilassatezza e comfort in chi guarda e trasmettono una sensazione di calore umano, familiarità e vicinanza, cruciali per tenere l’utente incollato allo schermo. L’utilizzo di questa tipologia di colori in dei contenuti audio-visivi molto lunghi che possono durare anche ore, come i podcast, risulta essere una variabile tutt’altro che trascurabile. Naturalmente generalizzare in toto non è corretto. Vi sono delle eccezioni dovute anche alla scelta stilistica, necessità di contestualizzazione della scena in base all’argomento trattato e volontà di differenziazione, ma il trend generale tende proprio ai colori caldi.</p>
            <br>
            <br>
            <div style="text-align: center;">
                <h2 style="color: white; font-size: 28px;">Thumbnails</h2>
            </div>
            <br>
            <p>La medesima analisi è stata condotta anche sulle thumbnails. Le thumbnails sono le immagini di copertina che vediamo ad esempio nella Homepage di Youtube. Le immagini di copertina svolgono un ruolo cruciale per il successo di un determinato video. Esse sono, a primo impatto, ciò che per prime catturano l’attenzione dell’utente e, contrariamente a quanto si pensi, possono essere il principale driver che porta l’utente a scegliere di visualizzare o meno un determinato video.</p>
            <br>
            <br>
            <br>
            <div class="flourish-embed flourish-bar-chart-race" data-src="visualisation/18803719"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
            <br>
            <br>
            <p>Per estrapolare i risultati sulle thumbnails è stata usata la stessa identica logica utilizzata per i frame.</p>
            <p>Non stupisce affatto come i risultati ottenuti per le thumbnails siano quasi sovrapponibili a quelli dei frame, ma questa volta non c’è spazio per le eccezioni. La scelta dei colori qui è dettata quasi totalmente dalla necessità di attirare gli utenti e si lascia molto meno spazio a scelte stilistiche personali.</p>
            <p>Qui siamo nella fase della scelta. Una delle più importanti. L’utente deve decidere se guardare o meno un determinato contenuto. Nel momento della scelta, l’utente deve sentirsi catturato e invogliato a cliccare. Il click deve essere quasi una scelta impulsiva e difatti i colori caldi tramettono anche sensazioni di vitalità, energia, entusiasmo e gioia. Inoltre, inutile nascondersi dietro a un dito, le copertine, per sfruttare al massimo il loro potenziale, devono anche tendere al “clickbaiting”, ossia creare una sensazione di stupore, attesa e curiosità sproporzionate rispetto al reale contenuto del video. Non è un caso che i segnali di allerta o pericolo che per natura devono richiamare l’attenzione, siano di colore rosso, giallo o arancione… ossia colori caldi (che sono anche quelli più frequenti nei grafici mostrati dallo studio condotto).</p>
            </p>
            <div class="container">
                <div class="header">
                    <button type="button" class="collapsible">Technical analysis</button>
                </div>
                <div class="content">
                    <p></p>
                </div>
            </div>
            <hr>
        </div>
    </div>
</div>


<!--
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
-->