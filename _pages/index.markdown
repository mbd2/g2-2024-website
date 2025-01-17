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
            <p>Daria Corrias, autrice e documentarista radiofonica che abbiamo avuto il piacere di intervistare, si esprime così riguardo all'avvento dei Podcast nel nostro paese:</p>
            <div class="quote-box">
                "Ricordo che c'erano moltissimi interrogativi e infinite discussioni su come questo 'Podcast' potesse rappresentare effettivamente un formato valido. Siamo partiti tutti da 'Serial', che ha dato poi la forma al Podcast. E quindi inizialmente si pensava che il PodCast dovesse essere seriale, true crime e con un host molto presente. Quindi con una narrazione molto presente in primo piano. Il Podcast era quella roba là."
                <div class="author">- Daria Corrias</div>
            </div>
            <p>Come ci conferma anche la nostra intervistata, quindi, i podcast erano strutturati in maniera orizzontale, vuol dire che per comprendere appieno ogni episodio era necessario aver ascoltato quello precedente. Questo requisito, divenne via via sempre meno importante, fino al punto che oggi, la maggior parte dei Podcast, offrono un tipo di contenuto verticale.  
            Infatti, i canali che abbiamo preso in considerazione per la nostra analisi, offrono questo tipo di contenuto.</p>
            <div class="quote-box">
                Da Serial sono passati 10 anni. Oggi nel 2024 abbiamo visto che il Podcast non è solo questo.
                <div class="author">- Daria Corrias</div>
            </div>
            <p>Per effettuare le nostre analisi, ci siamo focalizzati sugli Stati Uniti e abbiamo preso in considerazione 24 tra i più seguiti canali Podcast sulla piattaforma YouTube nel mese di Maggio 2024, a <a title="Link" href="https://rephonic.com/charts/youtube/united-states/popular-podcasts" target="blank">questo link</a>.</p>
            <br>
            <h4 style="text-align: center;">Grafico 1: Statistiche descrittive sui Podcast analizzati</h4>
            <p style="text-align: center;">Dalla visualizzazione incrociata dei grafici a seguire si evidenzia come i canali con il numero di visualizzazioni media più alte non siano necessariamente quelli con più podcast, ma potrebbero seguire altre metriche, quali la durata media o il numero di iscritti per canale.</p>
            <vegachart schema-url="{{site.baseurl}}/assets/charts/combined_chart_ulteriore.json" style="width: 100%; display: flex; justify-content: center;"></vegachart>
            <br>
            <br>
            <br>
            <h4 style="text-align: center;">Grafico 2: Distribuzione percentuale dei Podcast nel dataset</h4>
            <p style="text-align: center;">Di seguito, viene invece, riportato, in base alla data di pubblicazione del podcast, il numero di visualizzazioni totali e il numero di pubblicazioni per mese. Il mese a cui appartengono i podcast con più visualizzazione risulta Gennaio, quello con meno visualizzazioni Luglio. Nel mese precedente, ovvero a Giugno, si riscontra il numero minore di pubblicazioni, mentre quello maggiore si registra a Marzo.</p>
            <vegachart schema-url="{{site.baseurl}}/assets/charts/area_chart_podcast_distribution_dataset_black.json" style="width: 100%; display: flex; justify-content: center;"></vegachart>
            <br>
            <br>
            <h4 style="text-align: center;">Grafico 3: Distribuzione delle log-visualizzazioni per canale</h4>
            <p style="text-align: center;">Il grafico riporta su una scala logaritmica, le puntate di maggior e minor successo per ciascun canale.</p> 
            <vegachart schema-url="{{site.baseurl}}/assets/charts/std_views_podcast_chart_leggero.json" style="width: 100%; display: flex; justify-content: center;"></vegachart>
            <br>
            <br>
            <h4 style="text-align: center;">Grafico 4: Visualizzazioni per canale</h4>
            <p style="text-align: center;">Nel grafico, per ciascun canale, vengono mostrati, in ordine temporale, i podcast, nonché le relative visualizzazioni evidenziate dalla dimensione del pallino.</p> 
            <vegachart schema-url="{{site.baseurl}}/assets/charts/beeswarm_chart_leggero.json" style="width: 100%; display: flex; justify-content: center;"></vegachart> 
            <br>
            <br>
            <h4 style="text-align: center;">Grafico 5: Numero di views e contenuti pubblicati per mese di pubblicazione</h4>
            <p style="text-align: center;">Di seguito, viene invece, riportato, in base alla data di pubblicazione del podcast, il numero di visualizzazioni totali e il numero di pubblicazioni per mese. Il mese a cui appartengono i podcast con più visualizzazione risulta Gennaio, quello con meno visualizzazioni Luglio. Nel mese precedente, ovvero a Giugno, si riscontra il numero minore di pubblicazioni, mentre quello maggiore si registra a Marzo.</p> 
            <vegachart schema-url="{{site.baseurl}}/assets/charts/views_pub_chart_BLACK_VERO 2.json" style="width: 100%; display: flex; justify-content: center;"></vegachart>                
            <br>
            <br>
            <h4 style="text-align: center;">Grafico 6: Numero medio di Podcast</h4>
            <p style="text-align: center;">Il grafico riporta l'andamento temporale medio del numero di podcast pubblicati. Nel cordo del tempo il fenomeno dei podcast ha riscontrato un particolare successo sempre crescente, con un numero medio di podcast pubblicati che al 2024 si attesta a circa 13.</p> 
            <vegachart schema-url="{{site.baseurl}}/assets/charts/temporal_chart 2.json" style="width: 80%; height: 100vh;"></vegachart>
            <h4 style="text-align: center; margin-top: -80px;">Grafico 7: Frequenza di pubblicazione</h4>
            <p style="text-align: center;">Nel grafico vengono riportate le probabilità di osservare una specifica frequenza di pubblicazione e la probabilità di osservare al più una determinata frequenza di pubblicazione, calcolata come l'inverso della differenza temporale tra le pubblicazioni in mesi (per cui se un canale pubblica ogni 30 giorni, la frequenza di pubblicazione sarà 1). In generale l'80% dei canali ha una frequenza di pubblicazione molto alte, pari a 18 pubblicazioni al mese. Rileva la bassa rilevanza di frequenze di pubblicazione comprese fra 18 e 26 pubblicazioni mensili, nonché i canali che pubblicano con cadenza giornaliera fra le 26 e le 30 pubblicazioni al mese.</p> 
            <vegachart schema-url="{{site.baseurl}}/assets/charts/frequency_PDF_CDF_chart_leggero.json" style="width: 100%; display: flex; justify-content: center;"></vegachart>
            <br>
            <br>
            <div class="container">
                <div class="header">
                    <button type="button" class="collapsible">Technical analysis</button>
                </div>
                <div class="content">
                    <p>Avevamo un obiettivo ben preciso: raccogliere dati da YouTube da un totale di 25 canali. Tuttavia, abbiamo dovuto ridurre il numero a 24, poiché uno dei canali non rispettava i criteri di un podcast. Per raccogliere i metadati che ci interessavano, come il titolo dell’episodio, il numero di visualizzazioni, la descrizione dell’episodio, la data di pubblicazione, il numero di “mi piace”, la durata e il numero di commenti, abbiamo utilizzato la libreria Selenium. Questo ci ha permesso di ottenere dati da 13.756 episodi.</p>
                    <p>Per raccogliere informazioni sui commenti, abbiamo fatto ricorso a Google Console. Creando diversi token, siamo riusciti a utilizzare le API di YouTube per scaricare i metadati di primo livello relativi ai commenti. Questi metadati includevano l’autore del commento, il testo del commento e la data di pubblicazione.</p>
                    <p>Abbiamo anche utilizzato le API di YouTube per ottenere le trascrizioni di questi video, riuscendo a ottenere circa 13.218 documenti. Per ottenere gli audio, abbiamo utilizzato una serie di librerie, tra cui Librosa, Pytube, Pydub e FFmpeg, che ci hanno permesso di ottenere circa 7500 file audio. Abbiamo utilizzato la libreria Requests per ottenere le miniature dei video e le librerie CV2 e Pytube per ottenere i frame dei video.</p>
                    <p>Le caratteristiche che abbiamo ottenuto per il nostro dataset includono il nome del canale, l’URL, le visualizzazioni, la descrizione, la data di pubblicazione, i “mi piace”, la durata, i commenti, gli iscritti, la data di creazione del canale e le visualizzazioni del canale. Inoltre, abbiamo creato file CSV separati per gestire le trascrizioni e un file JSON per gestire i commenti, che contenevano più di 18.000.000 di commenti. Questo ci ha permesso di avere una visione completa e dettagliata dei podcast che abbiamo analizzato.</p>
                </div>
            </div>
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
            <p>I temi trattati nel tempo sono stati estratti dalle trascrizioni di vari episodi di podcast presenti su YouTube. Abbiamo identificato i seguenti argomenti "politics", "sports", "economy", "health", "technology", "culture", "education", "environment", "crime", "entertainment" e "music".</p>
            <p>È importante precisare che la categoria ‘crime’ può includere non solo episodi di True Crime, ma anche crimini di guerra, crimini politici, ecc. Inoltre, ‘education’ non si riferisce solo all’educazione scolastica, ma anche a temi che riguardano la formazione lavorativa, la crescita personale, temi che possono riguardare il razzismo, quindi tutti i temi che hanno a che fare con la crescita personale degli individui o dell’intervistato.</p>
            <p>Nel tempo abbiamo visto quale è stata l’evoluzione dei temi nei podcast:</p> 
            <br>
            <vegachart schema-url="{{site.baseurl}}/assets/charts/TOPIC_PROJECT_BLACK_VERO_3.json" style="width: 100%; display: flex; justify-content: center;"></vegachart> 
            <br>
            <p>Dal 2013 i temi ricorrenti per gli episodi podcast da noi analizzati erano tecnologia, con una preponderanza maggiore di questo tema sugli altri e poi altri temi come crime, health e entertainment. Particolarmente interessante è vedere come il tema politics compaia nel 2017 per poi arrivare ad essere uno dei temi principali dal 2022 fino al 2024. C’è da sottolinerare però che il canale podcast MedaisTouch e il canale di Brian Tyler Cohen Podcast (che trattano principalmente di temi politici) sono quelli con il maggior numero di episodi sul complessivo rispetto a questi anni.</p>
            <p>Un altro aspetto interessante che emerge è come l’argomento crime sia ancora molto utilizzato dentro i podcast, anche in questo caso va fatto però presente che nel nostro dataset ci sono diversi Canali che sono meramente True Crime come Let’s Read e Law&crimeNetwork e Baley Sarian, confermando che alcuni podcaster preferiscono utilizzare questo topic perché di maggiore appeal, come in precedenza detto da Daria Corrias.</p>
            <p>Di seguito invece abbiamo un grafico a bolle sui quali sono i temi principalmente tratti rispetto ai canali Podcast. Se cliccate dentro la bolla è possibile visualizzare tutti i temi principalmente discussi all’interno dei diversi canali podcast.</p>
            <br>
            <div class="flourish-embed flourish-hierarchy" data-src="visualisation/18816599"><script src="https://public.flourish.studio/resources/embed.js"></script>
            </div>
            <br>
            <div class="container">
                <div class="header">
                    <button type="button" class="collapsible">Technical analysis</button>
                </div>
                <div class="content">
                    <p>L'obiettivo di questo progetto è estrarre i topic prevalenti all'interno di un dataset di podcast. Per raggiungere questo scopo, sono stati eseguiti diversi passaggi, inclusi il preprocessing dei dati, la classificazione basata su embedding e la valutazione della qualità dei topic identificati.</p>
                    <p>Preprocessing delle Trascrizioni: Abbiamo rimosso annotazioni come "[music]", "[laughing]" usando espressioni regolari.</p>
                    <p>Tokenizzazione e Pulizia: Il testo è stato tokenizzato in singole parole, sono stati rimossi numeri e punteggiatura, e tutte le parole sono state convertite in minuscolo.</p>
                    <p>Abbiamo utilizzato il modello Word2Vec di Google-news-300, un modello pre-addestrato su un vasto corpus di notizie. Questo modello rappresenta ogni parola come un vettore di 300 dimensioni. Per ciascuna parola nella trascrizione, abbiamo ottenuto il vettore di embedding usando Word2Vec e calcolato la media di questi vettori per ottenere il vettore rappresentativo della trascrizione.</p>
                    <p>Successivamente, abbiamo definito un dizionario con diversi temi, tra cui: "politics", "sports", "economy", "health", "technology", "culture", "education", "environment", "crime" e "entertainment". Per ciascun tema, abbiamo calcolato il vettore di embedding come media dei vettori delle parole chiave associate. Per ogni trascrizione, abbiamo calcolato la Cosine Similarity tra il vettore della trascrizione e il vettore di ciascun topic. Abbiamo assegnato il topic con la Cosine Similarity più alta a ciascuna trascrizione.</p>
                    <p>Infine,  abbiamo effettuato un  analisi qualitativa su 90 dei video analizzati e abbiamo riscontrato che su 25 URL l'assegnazione del topic era errata.</p>
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
            <br>
            <div style="text-align: center;">
                <h2 style="color: white; font-size: 28px;">Frame</h2>
            </div>
            <br>
            <p>Molto spesso gli Youtuber, e nella nostra fattispecie i Podcaster, non considerano, o mettono in secondo piano, la scelta dei colori preponderanti all’interno delle loro inquadrature. Anche i fruitori stessi credono che i colori che partecipano alla creazione dell’ambiente virtuale all’interno del quale si svolge il podcast non influenzi il loro engagement.</p>
            <p>In realtà, la scelta dei colori e conseguentemente l’ambient che viene a crearsi all’interno di un podcast, risulta essere una variabile di primaria importanza, che innesca nel fruitore un senso di comfort e cattura involontariamente l’attenzione. Questo comporta un vantaggio enorme per il podcaster che mira ad ottenere un forte coinvolgimento del pubblico e alla sua fidelizzazione nel tempo.</p>
            <p>Consapevoli dell’importanza di questa variabile, è stato condotto uno studio sulla totalità dei podcast presi in analisi per individuare quali fossero i colori principali più utilizzati dai podcaster statunitensi di successo.</p>
            <p>Dato che nel tempo, vuoi per moda, per cultura o aspettativa degli utenti, i colori più attraenti possono aver subito delle modifiche, lo studio è stato condotto su uno span temporale il più largo possibile, così da capirne la sua tendenza nel tempo.</p>
            <p>Estrapolando diversi frame da ogni podcast in analisi, ed estrapolando i colori più rilevanti per ogni podcast, è emersa la seguente evoluzione dell’utilizzo dei colori di scena.</p>
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
                    <p>Per effettuare l’analisi sui frame sono stati necessari diversi passaggi tecnici che vanno dalla raccolta dei frame stessi fino all’estrapolazione dei colori e quindi dei risultati.</p>
                    <p><strong>Estrazione Frame</strong></p>
                    <p>L’estrazione dei frame è avvenuta per mezzo della libreria pytube per scaricare video e cv2 per l'elaborazione delle immagini. Grazie a quest’ultima libreria è stato possibile esaminare i singoli fotogrammi, estraendo i più rilevanti. Essendo l’obiettivo dell’analisi quello di rilevare tutti i colori utilizzati in scena, la logica costruita per mezzo del codice è stata quella di rilevare ogni cambiamento di inquadratura e catturare un frame per ogni inquadratura. Per fare questo, ogni fotogramma del video è stato convertito in scala di grigi e calcolato l’istogramma dei livelli di grigio. Gli istogrammi dei fotogrammi consecutivi sono stati poi confrontati utilizzando la correlazione. Qualora la correlazione fosse risultata al di sotto di una certa soglia (“threshold”), veniva identificato un cambio di scena e quindi veniva salvato il fotogramma corrispondente.
                    Inoltre, è stata anche implementata una logica grazie alla quale, in caso di stessa inquadratura ripetuta, il frame catturato veniva ignorato (per evitare double counting). Per fare questo è stato calcolato un hash delle immagini (usando “imagehash.phash”) per i fotogrammi individuati come cambio di scena. Gli hash dei fotogrammi sono stati confrontati con una soglia di somiglianza (hash_similarity_threshold) e solo i fotogrammi con hash sufficientemente diversi sono stati considerati cambi di scena unici con conseguente salvataggio del fotogramma.
                    Man mano che i video venivano scaricati ed analizzati, il codice li eliminava automaticamente al termine dell’analisi per preservare lo spazio su disco.</p>
                    <p><strong>Estrazione colore dai frame</strong></p>
                    <p>L’analisi dei frame invece è avvenuta utilizzando la libreria PIL per la manipolazione delle immagini e sklearn per il clustering dei colori. Ogni immagine viene ridimensionata per velocizzare l'elaborazione, convertita in un array numpy e aggregata in un’unica immagine. Viene poi applicato il K-means clustering sui pixel aggregati per identificare il colore dominante principale. Per ogni colore dominante trovato, vengono calcolati diversi valori di identificazione univoca del colore, come HSV, HSL e Luma, oltre a RGB. I valori HSL (“Hue Saturation Lightness”) risulteranno poi fondamentali per rimuovere la luminosità e la saturazione dai fotogrammi e ottenere così il colore reale. A questo punto per ogni video sono stati salvati in un JSON i colori principali.</p>
                    <p><strong>Analisi colori</strong></p>
                    <p>L’analisi del colore è consistita nel creare un dataframe con tutti i video associati al proprio colore principale e alla data di pubblicazione del video.
                    Durante lo studio è emerso come la maggior parte dei colori fossero su scale di grigio e, per ottenere il colore principale, è stato necessario rimuovere la saturazione e luminosità da ogni colore. Per questo motivo l’analisi è stata effettuata partendo dai valori HSL e prendendo come riferimento solo il valore “H”, ossia la Hue. Ottenuta la Hue, questa è stata tramutata in rgb. A questo punto, avrebbe avuto poco senso rappresentare ogni singolo colore dello spettro rgb, e quindi è stato effettuato un K-means clustering, raggruppando i colori in 10 macrocategorie che non erano altro che la sintesi di tutti colori dello spettro raggruppati per similarità. A questo punto, grazie all’utilizzo di un bar chart dinamico, è stata rappresentata la presenza nel tempo di determinati colori, ordinati per data di pubblicazione. I risultati sono stati quelli esposti nel sito di riferimento.</p>
                    <p>Il procedimento per le thumbnails è stato il medesimo.</p>
                </div>
            </div>
            <hr>
        </div>
    </div>
</div>

<div id="conclusioni" class="anchor-offset" style="text-align: center;">
    <h1 style="color: white; font-size: 48px;">Conclusioni</h1>
</div>

<div style="position: relative; width: 100%; padding-right: 200px; padding-left: 200px;">
    <div class="row">
        <div class="col-md-3 col-md-offset-3">
        </div>
        <div class="col-md-6">
            <hr>
            <p>Ritornando al punto focale, cosa influenza le visualizzazioni, i like e il numero di commenti di un podcast?</p>
            <p>Dalle nostre analisi emergono diverse evidenze significative in relazione a ciascuna di queste variabili.</p>
            <br>
            <h4 style="text-align: center;">Numero di Visualizzazioni del podcast</h4>
            <p>Con riferimento all’audio del podcast, <strong>i suoni con un pitch minore, ovvero meno acuti e più gravi tendono a catturare più attenzione</strong> e generare un maggior numero di visualizzazioni. Alcune caratteristiche specifiche dell'audio, come i coefficienti MFCC 1, 6 e 7, sono associate a un loro aumento, mentre altri coefficienti, come MFCC 4 e 5, sembrano avere un effetto negativo.</p>
            <p><strong>Colori più vivaci e saturi</strong> generalmente attraggono più spettatori e visualizzazioni. Tuttavia, in modo piuttosto inaspettato, anche i video con <strong>tonalità più scure comportano un aumento del numero di visualizzazioni.</strong></p>
            <p>Per quanto riguarda la durata del video e le caratteristiche del canale, i <strong>video più lunghi</strong> tendono ad accumulare più visualizzazioni. Canali con un numero maggiore di iscritti tendono ad avere una maggiore visibilità in termini di visualizzazioni. In modo scontato, video più vecchi sono legati a maggiori più visualizzazioni, in virtù della loro permanenza nel tempo.</p>
            <br>
            <vegachart schema-url="{{site.baseurl}}/assets/charts/regression_views_3.json" style="width: 100%; display: flex; justify-content: center;"></vegachart>
            <br>
            <h4 style="text-align: center;">Numero di Mi Piace del podcast</h4>
            <p>Si conferma che <strong>suoni meno acuti</strong> e alcune caratteristiche audio più specifiche (come i coefficienti MFCC 1 e 5) <strong>tendano ad avere più mi piace</strong>. Esiste una relazione positiva tra la "frequenza media" del contenuto audio del video e il numero di likes che il video riceve, ovvero in altri termini, podcast che hanno una <strong>maggiore concentrazione di energia nelle frequenze alte</strong> tendono a essere più apprezzati dagli spettatori, indicando una preferenza per audio chiari e caratterizzati da frequenze alte. Inoltre a incidere sul numero dei mi piace, diversamente da quanto accadeva per le visualizzazioni, incide positivamente la distribuzione delle ampiezze sonore: <strong>quando le ampiezze sonore più alte sono più frequenti di quelle basse si riscontra un aumento del numero di likes</strong>, pertanto “timbri” o “picchi di volume” più frequenti potrebbero indurre l’ascoltatore a mettere mi piace più frequentemente.</p>
            <p>Per l’immagine, a determinare i likes al video, non è più, differentemente dalle visualizzazioni,l’intensità del colore o la sua luminosità, bensì la tonalità del colore. <strong>Tonalità più elevate nei frame</strong> del video sono associate in modo positivo a un maggior numero di likes.</p>
            <p>Inoltre, le caratteristiche della <strong>miniatura del podcast</strong>, elemento di “prima interazione” con l’utente, influenzano positivamente il numero dei mi piace messi al video: in particolare, sia immagini caratterizzate da <strong>colori più intensi che immagini maggiormente luminose</strong>, sono associate ad un maggior numero di likes.</p>
            <p>Contrariamente a quanto accade per le visualizzazioni, <strong>la durata del video influisce negativamente sui mi piace</strong>: video più lunghi tendono a ricevere meno mi piace. Infine, <strong>video con un numero maggiore di persone nella miniatura ricevono tendenzialmente più mi piace</strong></p>
            <br>
            <vegachart schema-url="{{site.baseurl}}/assets/charts/regression_likes_3.json" style="width: 100%; display: flex; justify-content: center;"></vegachart>
            <br>
            <h4 style="text-align: center;">Numero di Commenti del podcast</h4>
            <p>Un ritmo più veloce e caratteristiche audio specifiche (MFCC 1 e 5) sono associati a un maggiore numero di commenti, mentre alcune caratteristiche audio (MFCC 4 e 7) hanno l'effetto opposto.</p>
            <p>Con riferimento all’immagine, si evidenzia che <strong>tonalità più elevate e colori più intensi</strong> siano correlati a più commenti, mentre, diversamente, la luminosità non sembra avere un grande impatto. Le <strong>miniature con immagini luminose e tonalità più vivaci</strong> permettono di riscontrare un aumento del numero di commenti.</p>
            <p><strong>I video più lunghi e quelli più datati tendono ad avere meno commenti</strong>, probabilmente per un declino dell’interesse e dell’attenzione degli utenti nel tempo. In ultima istanza, la presenza di più persone nella miniatura sembra essere legata ad un maggior numero di commenti.</p>
            <br>
            <vegachart schema-url="{{site.baseurl}}/assets/charts/regression_comments_3.json" style="width: 100%; display: flex; justify-content: center;"></vegachart>           
            <br>
            <div class="container">
                <div class="header">
                    <button type="button" class="collapsible">Technical analysis</button>
                </div>
                <div class="content">
                    <p>Ai fini dell'analisi di regressione sono state prese in considerazione diverse variabili dipendenti (views, likes e comments) contro un panel di regressori, composto dalle variabili legate all'immagine, all'audio e intrinsecamente al canale del podcast.</p>
                    <p>Il dataset originale conteneva per le variabili sull'immagine, le scale RGB, HSL ,HSV e LUMA, nonché il conteggio delle persone nella miniatura.</p>
                    <p>Sono stati rimosse dal dataset tutti i record con data di pubblicazione assente, in quanto necessaria per creare la variabile dei "giorni trascorsi dalla data di pubblicazione".</p>
                    <p>Il dataset finale prevede l'assenza di missing values sulle feature audio. Il campionamento di un minor numero di audio rispetto alle caratteristiche video ha comportato una consistente riduzione del dataset in termini di record. Nonostante il tentativo d'uso di tecniche per risolvere l'assenza di bilanciamento nel dataset (sottocampionamento, sovracampionamento e SMOTE), è stato preferito mantenere inalterato il dataset originale rispetto alla presenza di dati sintetici, mirando a includere features che permettano di superare le differenze individuali esplicando le variabili dipendenti.</p>
                    <p>Al fine di ottenere misure direttamente interpretabili, le variabili audio sono state standardizzate dividendo la rispettiva media per la standard deviation.</p>
                    <p>Dall'analisi di correlazione è emerso che i colori della scala RGB risultano altamente correlati fra loro, essendo i colori finali combinazioni fra questi. La scala HSL presenta le minori correlazioni e una maggior esplicabilità. Sono state in seguito rimosse le seguenti variabili altamente correlate:  standardized_mfcc_3, standardized_spectral_rolloff,  standardized_rms_energy e Total_Videos.</p>
                    <p>La matrice di correlazione finale presenta correlazione massima di +0.64 (fra lo standardized_mfcc_2 e lo standardized_spectral_centroid) e minima di -0.44 (fra lo standardized_mfcc_1 e audio_kurtosis).</p>
                    <p>Segue in seguito l'outlier detection: se, in prima battuta è stato deciso di eseguirla su tutte le variabili, si è riscontrato che, stante la perdita di troppi record, un buon risultato di compromesso risultava dall'applicare l'outlier detection alle variabili dipendenti, non risultati da elaborazioni proprie ma oggetto di acquisizione esterna.</p>
                    <p>Passando all'analisi di regressione, per le variabili dipendenti in oggetto è stato, in prima battuta, adoperato un modello di regressione adatto a variabili di conteggio, ovvero un modello di tipo Poisson. Tale processo richiederebbe che la relativa media e varianza, denotate come lambda, coincidano: sui dati tale ipotesi non è riscontrata, pertanto si è proceduto alla stima di un modello adatto a dati di conteggio sovradispersi, in cui la varianza del processo è superiore alla relativa media, quale il modello Binomiale Negativo.</p>
                    <p>La stima è stata effettuata con la specificazione di un tipo di matrice di covarianza robusta per tenere conto di eventuali problemi sulla matrice di correlazione.</p>
                    <p>L'interpretazione dei coefficienti non è diretta, in quanto il link fra la variabile risposta e il predittore lineare è dato dal logaritmo. Segue che prendere l'esponente dei coefficienti può riportare misure più comprensibili, ovvero, se al di sopra di 1, la percentuale in eccesso prodotta grazie ad un aumento di un regressore, viceversa se inferiore a 1, la percentuale in difetto prodotta dall'aumento di un regressore. In termini esplicativi risulta più conveniente applicare l'esponenziale e sottrarre 1, in modo tale da riportare le differenze sulla rispettiva scala positivi/negativi (anziché solo positivi).</p>
                    <p>Limitazioni relative all'analisi potrebbero essere probabilmente superabili con l'uso di un dataset più esteso (la riduzione al 40% degli audio potrebbe aver ridotto l'ampiezza dell'analisi e influenzato le relative variabili).</p>
                </div>
            </div>
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