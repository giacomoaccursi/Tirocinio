# Introduzione

Camminare è una delle attività più svolte quotidianamente. Una normale camminata richiede la coordinazione del sistema nervoso, muscoloelettrico e cardiorespiratorio. 
La camminata è influenzata dall'età, dall'umore e persino da fattori socioculturali. 
I disturbi dell'andatura portano ad una perdita della libertà personale, a cadute, seguite da possibili lesioni, e in generale ad una riduzione nella qualità della vita.[[1]](#1)
Negli anziani, la velocità è un potente predittore della mortalità.
L'attrezzatura e le metodologie utilizzate per l'analisi della camminata hanno fatto sostanziali progressi negli ultimi anni. Gli strumenti utilizzati permettono di diagnostiare in modo più efficiente e accurato coloro che hanno subito una lesione che influisce sulla loro capacità di camminare.  

Il campo della ricerca sull'andatura umana è ampio. Nel campo sanitario, poichè le anomalie nella camminata colpiscono un'alta percentuale della popolazione, l'andatura viene studiata per diagnosticare malattie neurodegenerative come il morbo di Parkinson, mielopatia, amiotrofia spinale, sclerosi multipla, atassia celebrale, tumori celebrali, alcuni tipi di demenza, malattie neuromusclari ecc..[[6]](#6)

I sistemi tradizionali per la valutazione della camminata sono semi-soggettivi perchè sono svolti da specialisti che ne osservano la qualità facendo camminare il paziente. I risultati non si basano su rilevazioni oggettive ma su valutazioni soggettive. [[2]](#2)
Le nuove tecnologie hanno permesso agli specialisti di estrarre informazioni oggettive dalle diagnosi, riducendo quindi il margine di errore. 
I dispositivi utilizzati possono essere basati sia su sensori indossabili che non indossabili. 
I dispositivi basati su sensori non indossabili richiedono l'uso di strutture dedicate , il paziente cammina all'interno di una stanza e i suoi passi sono misurati attraverso sensori da pavimento. Uno dei problemi di questi sensori è il limitato numero di passi che possono essere compiuti e l'impossibilità di poterli usare durante le attività quotidiane. 
I dispositivi basati su sensori indossabili consentono invece di rilevare la camminata durante le attività quotidiane della persona, tuttavia, in alcuni casi possono risultare invasivi, alterando l'andatura e producendo misurazioni imprecise. 



# Sistemi attuali per l'analisi della camminata

Ad oggi i sensori indossabili costituiscono una alternativa meno complessa e costosa rispetto ai laboratori specializzati, in quanto il loro utilizzo non è limitato ad un ambiente controllato.  
Questi sensori sono attaccati a varie parti del corpo del paziente, ad esempio ai piedi o alla vita. Le caratteristiche temporali dell'andatura vengono raccolte e stimate da accelerometri e sensori di pressione all'interno delle scarpe, i segnali e i movimenti registrati possono essere utilizzati per l'analisi della camminata. 

### Goniometri

Vengono utilizzati per calcolare la rotazione fra due segmenti del corpo umano. Il goniometro basato su estensimetri lavora con una resistenza che cambia a seconda di quanto è flesso il sensore. Nel momento il cui viene flesso, la corrente al suo interno avrà un percorso più lungo e di conseguenza aumenterà la resistenza al suo interno proporzionalmente all'angolo di flessione. In generale questi dispositivi sono poco invasivi, facili da utilizzare e operano indipendentemente dall'asse sul quale ruotano le articolazioni. 

### Sensori Inerziali

Sono dispositivi che, attraverso accelerometri, giroscopi e qualche volta magnetometri, misurano la velocità di un oggetto, la sua accelerazione e l'orientamento. L'accelerometro usa i fondamenti delle leggi di Newton le quali dicono che l'accelerazione di un corpo è proporzionale alla forza netta che agisce su esso, quindi conoscendo il quoziente di proporzionalità (massa dell'oggetto) e tutte le forze misurate dai sensori, si riesce a calcolare l'accelerazione. Con l'integrazione dell'accelerazione troviamo la velocità, e integrandola otteniamo la posizione riferita ai 3 assi. Integrando la velocità angolare otteniamo l'angolo di flessione e attraverso algoritmi di filtraggio e classificazione possiamo estrarre il numero di passi fatti. [[2]](#2)
I vantaggi di tale sistema risiedono nella sua intrinseca portabilità, affidabilità e accuratezza. 
A differenza degli elettrogoniometri sono complessi e costosi, ma sono capaci di analizzare il movimento tridimensionale del cammino umano. 

### Sensori ad Ultrasuoni

I sensori ad ultrasuoni vengono utilizzati per calcolare il passo corto, la lunghezza della falcata e la distanza fra i piedi. Le onde sonore emesse sono onde ad alta frequenza, al di sopra dello spettro udibile umano. 
Un sensore ad ultrasuoni calcola il tempo che intercorre tra l'invio e il ritorno dell'onda riflessa da un oggetto e, conoscendo la velocità con cui il suono viaggia nell'aria, calcola la distanza da esso. 
Qi et al [[3]](#3) ha proposto un metodo a basso costo, basato su questa tecnologia, per estrarre i parametri spazio-temporali dell'andatura, tra cui la velcità della falcata e la cadenza della falcata. Le prestazioni sono state valutate confrontando il sistema con un altro basato su una telecamera in laboratorio. I risultati mostrano la fattibilità della soluzione proposta, con un errore medio del 2.7%.  (aggiungere immagine del paper di riferimento)

### Sensori di forza e pressione

Entrambi i sensori si occupano di misurare la Ground Reaction Force (GRF), ovvero la forza di reazione esercitata dal suolo all'appoggio del piede. 
I sensori di pressione misurano solo le GRF verticali, mentre i sensori di forza misurano le GRF su ogni asse. 
L'uso più frequente che viene fatto di questi dispostivi è l'integrazione nelle scarpe. 
Alcuni studi, come quello di Howell et al [[4]](#4) hanno dimostrato che le misure ottenute da una soletta contenente 12 sensori capacitivi, mostrano un'alta correlazione con le misurazioni simultanee di un laboratorio di analisi del movimento. 
Esistono più scelte per quanto riguarda il tipo di sensore da utilizzare, la scelta dipende dalla pressione sopportata e dalla sensibilità: 

+ Sensori resistivi: la resistenza elettrica diminuisce all'aumentare del peso ai quali sono sottoposti. 
+ Sensori piezoelettrici: sono composti da 3 misuratori di deformazione, posti in 3 direzioni ortogonali. I misuratori sono collocati su un gel di silicone. Quando il gel sotto pressione si deforma, i misuratori ne misurano la deformazione e, conoscendo le caratteristiche del gel, può essere calcolata la pressione totale. 
+ Sensori capacitivi: si basano sul principio che la capacità del condensatore cambia in funzione di diversi parametri, la cui la distanza tra i due elettrodi.

### Sensori a pavimento

In questi sistemi i sensori sono collocati lungo il pavimento sulle "piattaforme di forza" [[3]](#3) dove l'andatura è misurata da sensori di forza o pressione.
Lo svantaggio principale di questi strumenti è la loro dimensione ridotta, che limita il numero di passi che si possono misurare. 
Leusmann et al [[5]](#5) hanno proposto il primo sensore integrabile nel pavimento di casa con l'obbiettivo di assistere le persone anziane e più fragili che vivono da soli. Il sensore funziona grazie ad una fitta rete di sensori piezoelettrici. L'algoritmo sviluppato raccoglie dati con il fine di valutare la camminata della persona, ma è in grado di rilevare anche eventuali cadute o situazioni di emergenza. 

### Sistemi commerciali

Esistono aziende che hanno sviluppato strutture per l'analisi dell'andatura ad alta precisione. I sistemi utilizzati sono basati su una varietà di sensori sia indossabili che non. Molti di essi utilizzano un alto numero di telecamere per riprendere l'andatura del paziente da più angolazioni. 
A differenza delle soluzioni citate finora, i sistemi in questione richiedono una grande quantità di attrezzatura e procedure di calibrazione che li rendono costosi sia in termini di tempo che di denaro e non sono applicabili alle situazioni della vita quotidiana. 
Nonostante queste limitazioni, per via della loro grande precisione, sono considerati i gold standard per le valutazioni cliniche e le nuove tecnologie proposte sono valutate confrontandole con questi sistemi. 



### Deep Learning

Deep learning(DL) è una branca del Machine learning(ML) che a sua volta è una branca dell'Intelligenza Artificiale(AI). La figura in basso mostra la relazione esistente fra AI, ML e DL.

Il modo più semplice per pensare all'Intelligenza Artificiale, al Machine Learning, alle Reti Neurali Artificiali e al Deep Learning è quello di pensare alle matrioske: ogni termine è un componente del termine precedente. 
Le reti neurali sono una branca del Machine learning(ML) che a sua volta è una branca dell'Intelligenza Artificiale(AI). 
Quando una rete neurale ha più di 3 layer, si parla di Deep Learning(DL). 

#### Perceptron

Il primo modello matematico per un neurone artificiale è stato il Threshold Logic Unit proposto da Warren S.McCulloch e Walter H.Pitts Jr nel 1943.[[10]](#10).
Il modello presentato può essere descritto attraverso le seguenti regole: 

+ Un output binario y $\in$​​ {0, 1}, dove y = 1 inica che il neurone si attiva e y = 0 che il neurone è a riposo. 
+ Ha un numero N di ingressi binari eccitatori $X_k$ $\in$ {0, 1}
+ Ha un solo ingresso i. Se questo è acceso, il neurone non può attivarsi. 
+ Ha un valore di soglia $\Theta$. Se la somma dei suoi ingressi è maggiore di questo valore critico. Il neurone si attiva, altrimenti rimane a riposo. 

Dato l'input X = $[X_1, X-2, X_3,...,X_n]$​, l'input $i$​, e il valore di soglia $\Theta$​, l'output è calolato come segue. 

$f(x)$​ = $\left\{ \begin{array}{rcl} {1} & se \sum X_k > \Theta & e &i = 0, \\ 0 & altrimenti \end{array}\right.$​

15 anni dopo il neurone di McCulloch e Pitts, Frank Rosemblat (MPC), ideo il perceptron, un miglioramento rispetto al MPC. 
Il principale di Rosemblatt è stato quello di dimostrare che, rilassando alcune delle vecchie regole, in particolare l'uguale contributo di tutti gli ingressi e la loro natura intera, i neuroni artificiali potevano effettivamente imparare dai dati. 
Rosemblatt ha anche ideato un primo algortmo che ha permesso al neurone artificiale di capire da solo i pesi corretti direttamente dai dati dati di addestramento. L'algoritmo può gestire solo classificazioni per classi linearmente separabili.

(Figura: separabili_nonseparabili, didascalia: si noti come in realtà l'esempio a destra possa essere trattato dal perceptron dopo una fase di preprocessing che lo riconduca ad un problema linearmente separabile)

(Figura: perceptron)

Nel 1969 Marvin Minsky e Seymour Papert pubblicarono il famoso libro Perceptrons: an introduction to computational geometry nel quale dimostravano quanto fosse limitato il perceptron di Rosemblat e qualsiasi altro perceptron a singolo strato, e in particolare, mostravano come non fosse in grado di imparare la semplice funzione logica XOR. 

#### Reti neurali Artificiale

Una rete neurale artificiale è un paradigma di elaborazione ispirato al cervello umano. Una rete neurale artificiale è in grado di imparare e generalizzare dall'esperienza. Una delle principali aree nel quale è utilizzata è la previsione, ma trova spazio anche nella classificazione e nel riconoscimento di modelli. 
A differenza dei metodi statistici tradizionali, ha forme più generali e flessibili ed è in grado di eseguire una modellazione non lineare senza una conoscenza delle relazioni tra le variabili di input e di output. 
Una rete neurale con un singolo strato è un Perceptron. Un perceptron multi-strato è una rete neurale artificiale. 
Il ciclo di vita di una Rete Neurale Artificiale è divisa in due fasi, la prima è la fase di addestramento e l'altra la fase di predizione. 
Nella fase di addestramento si cercano i valori dei pesi e del bias. Nella fase di predizione invece, la rete neurale elabora l'input al fine di produrre previsioni. 
Il processo di apprendimento di una rete neurale è composto da una fase di andata e una di ritorno, rispettivamente chiamate Forward Propagation e Backward Propagation

#### Forward Propagation

Come suggerisce il nome, i dati input vengono elaborati in avanti attraverso la rete. Ogni strato nascosto accetta i dati in input, li elabora a seconda della propria funzione di attivazione e li passa allo strato successivo. 
Per generare un output, i dati devono obbligatoriamente fluire solo in avanti. Se fluissero anche all'indietro si formerebbe un ciclo e nessun output sarebbe generato. 
In ogni neurone dello strato nascosto o di uscita, l'elaborazione avviene in due fasi: 

1. Preattivazione: viene effettuata una somma pesata di tutti i valori in input e viene aggiunto un bias. 
2. Attivazione: la somma pesata degli input è passata alla funzione di attivazione. La funzione di attivazione aggiunge non linearità alla rete. 

Sulla base del risultato ottenuto, il neurone decide se inoltrare le informazioni al neurone successivo. 

#### Activation functions

#### Backward Proagation

E' probabilmente una delle colonne portanti delle reti neurali. E' stata introdotta per la prima volta nel 1970 e poi riscoperta nel 1989 da Rumelhart, Hinton and Williams [[11]](#11). 
E' un algoritmo per il supervised learning di reti neurali artificiali che utilizza la discesa del gradiente. 
Data una rete neurale artificiale e una funzione di errore, viene calcolato il gradiente della funzione di errore rispetto ai pesi della rete. 
Il calcolo del gradiente viene fatto procedendo all'indietro nei nodi della rete. I calcoli parziali del gradiente in uno strato sono riutilizzati nel calcolo per lo strato precedente. Questo flusso all'indietro ne permette un calcolo efficiente. 

#### Recurrent Neural Network

#### Convolutional neural network

#### Layer più importanti

I layer più importanti per comporre una rete sono: i layer convoluzionali, i pooling layer e i layer dense. Il dropout layer si è rivelato un layer importante nella regolarizzazione. 

##### Dense layer

Utilizza un insieme lineare di connessioni tra l'input e l'output. Tutti i neuroni di uno dense layer sono connessi a tutti i neuroni dello strato successivo. In questo modo ogni unità prende l'input da tutte le unità precedenti e lo trasferisce a quelle successive. 
Questo porta a un calcolo matrice-vettore molto semplice, ma anche ad un insieme molto grande di parametri addestrabili. 
Reti neurali composte da layer densi sono utili per dati a bassa dimensione, mentre i calcoli possono diventare molto onerosi nei casi in cui i dati sono ad alta dimensione, come nel caso delle immagini. 

##### Convolutional layer

Uno strato convoluzionale contiene un insieme di filtri i cui parametri devono essere appresi. L'altezza e il peso dei filtri sono più piccoli di quelli del volume di input. Il filtro viene fatto scorrere attraverso la larghezza e l'altezza dell'input e in ogni posizione viene calcolato il prodotto scalare fra l'input e il filtro per creare una mappa di attivazione fatta di neuroni. L'output di uno strato convoluzionale è ottenuto impilando le mappe di attivazione di tutti i filtri. 
Poichè la larghezza e l'altezza di ogni filtro è progettata er essere più piccola dell'input, ogni neurone nella mappa di attivazione è collegato solo ad una piccola regione locale dell'input [[12]](#12).
Questa soluzione è ispirata alla corteccia visiva animale, dove i campi recettivi delle cellule sono molto piccoli. 
La connettività locale dello strato convoluzionale, consente alla rete di imparare filtri che corrispondono a una regione locale dell'input, questa possibilità è molto importante dal momento che data un'immagine in input, un pixel è più correlato ai pixel vicini rispetto a quelli lontani. 

##### Pooling Layer

Simile allo strato convoluzionale, il pooling layer è responsabile della riduzione della dimensione spaziale, utile per diminuire la potenza di calcolo richiesta per elaborare i dati. Esistono due tipi di pooling: Max Pooling e Average Pooling. 
Il Max Pooling restituisce il valore massimo dalla porzione di immmagine coperta dal filtro. 
L'Average Pooling restituisce la media di tutti i valori della porzione di immagine coperta dal filtro. 
Average Pooling si limita ad eseguire una riduzione della dimensionalità, mentre Max Pooling funziona anche come soppressore del rumore, scartando del tutto le attivazioni rumorose.
Il Pooling Layer è spesso incorporato fra due strati convoluzionali successivi. 

##### Dropout Layer

Dropout è un metodo per la regolarizzazione nelle reti neurali artificiali. L'idea chiave è quella di disabilitare alcune unità di input in modo totalmente casuale durante la fase di training. 
In ogni fase dell'addestramento, i singoli nodi vengono eliminati dalla rete con probabilità 1 - p o mantenuti con probabilità p. Anche i nodi di input e output possono essere rimossi. 
Questa tecnica riduce significativamente l'overfitting e fornisce miglioramenti significativi rispetto ad altri metodi di regolarizzazione. 
Qualche considerazione sul dropout: 

1. Il dropout costringe una rete neurale ad apprendere caratteristiche più robuste che sono utili in combinazione con molti sottoinsiemi casuali diversi degli altri neuroni
2. Il dropout raddoppia approssimativamente il numero di iterazioni richieste per convergere. Tuttavia il tempo di addestramento per ogni epoca è inferiore. 
3. Con H unità nascoste che possono essere eliminate, abbiamo $2^H$​​ ​modelli possibili. 

##### Flatten Layer

Lo strato flatten serve a rimuovere tutte le dimensionalità eccetto una. In altre parole, partendo da una matrice, viene creato un array unidimensionale. 
Se l'ultimo strato convoluzionale restituisse in output un tensore (28, 28, 3), applicando il flattening avremmo un tensore (2532, 1). 

#### Overfitting e Underfitting

Un algoritmo di successo deve performare bene anche su dati di input mai analizzati dello stesso tipo di quelli proposti nel training set e validation set. Le performance di un algoritmo non devono essere valutate solo sulla capacità nel minimizzare l'errore nel training, ma anche nel minimizzare la differenza tra gli errori di training e validation. Quest'ultima differenza viene anche chiamata errore di generalizzazione. 
L'errore di generalizzazione e l'errore sul training dipendono dalla capacità di rappresentazione, la quale è una misura di quanto l'algoritmo è in grado di adattarsi a una gamma di ouput. 

In teoria, se la capacità di rappresentazione può essere arbitrariamente alta, l'algoritmo si adatterà perfettamente ad ogni insieme finito di eventi, ma questo limiterà la sua capacità di funzionare bene su nuovi dati, poichè si sarà eccessivamente specializzato sui dati di addestramento. 

Quando un algoritmo è in grado di rendere piccolo l'errore sui dati di addestramento ma perde la capacità di generalizzare, siamo di fronte ad overfitting.
Viceversa, quando un algoritmo è caratterizzato da un'alto bias e una bassa varianza, non riesce a minimizzare l'errore nei dati di addestramento, siamo di conseguenza di fronte ad underfitting. 
(figura: underfitting_overfitting, didascalia: nella parte sinistra dell'immagine possiamo notare come l'erorre nel training e l'errore di generalizzazione siano entrambi alti, siamo infatti nella zona di underfitting. Incrementando la capacità, l'errore sul training diminuisce, ma aumenta il gap fra errore di training e di generalizzazione. Spostandosi verso destra, il divario aumenta e si entra nella zona di overfitting, dove a capacità è troppo grande, al di sopra della capacità ottimale [[8]](#8))



# Acquisizione dei dati 

### OpenPose

OpenPose è una libreria opensource per la stima della posizione umana. Propone un metodo basato su una rappresentazione non parametrica, chiamata Part Affinity Fields (PAFs), per imparare ad associare parti del corpo con gli individui nell'immagine [[7]](#7).  A differenza delle altre soluzioni, OpenPose utilizza un approccio bottom-up, prima rileva tutte le parti del corpo presenti nell'immagine e poi le associa agli individui.

L'input è una immagine RGB. L'architettura multi-stage delle Reti Neurali Convoluzionali (CNN) predice prima l'insieme di PAFs, i campi vettoriali 2D, e le mappe di confidenza di rilevamento, che indicano la probabilità che una particolare parte del corpo possa essere localizzata in un determinato pixel. La figura mostra il procedimento seguito. 

Il tool è disponibile gratuitamente e può essre utilizzato su differenti piattaforme hardware e software. E' possibile personalizzare alcune impostazioni come la sorgente di input, che può essere una immagine, un video oppure la webcam. 
Una volta che il video è stato acquisito, OpenPose restituisce un file in formato JSON per ogni frame del video, contenente le coordinate 2D di ogni keypoint rilevato e la rispettiva confidenza nell'affermare che quel keypoint sia in quell'esatto pixel. 

Nel paper di riferimento, viene dimostrato come un algoritmo di parsing greedy è sufficiente per produrre una rappresentazione della posa di alta qualità, conservando l'efficienza indipendentemente dal numero di persone.

# Analisi dell'andatura proposto

# Risultati

# Conclusioni e lavori futuri

###### 

## References

<a id="1">[1]</a> Gait disorders in adults and the elderly
<a id="2">[2]</a> Gait Analysis Methods: An Overview of Wearable and Non-Wearable Systems, Highlighting Clinical Applications
<a id="3">[3]</a> Estimation of Spatial-Temporal Gait Parameters Using a Low-Cost Ultrasonic Motion Analysis System
<a id="4">[4]</a> Kinetic gait analysis using a low-cost insole
<a id="5">[5]</a> Your Floor Knows Where You Are: Sensing and Acquisition of Movement Data
<a id="6">[6]</a> Deep Learning for Monitoring of Human Gait: A Review
<a id="7">[7]</a> OpenPose
<a id="8">[8]</a> I. Goodfellow, Y. Bengio, and A. Courville, Deep Learning. MIT Press, 2016, http: //www.deeplearningbook.org
<a id="9">[9]</a> Rosenblatt, F. 1957. The Perceptron — a perceiving and recognizing automaton.
<a id="10">[10]</a> McCulloch, W. S., and Pitts, W. 1943. A logical calculus of the ideas immanent in nervous activity. 
<a id="11">[11]</a> Learning representations by back-propagating errors
<a id="12">[12]</a> Computer Vision for Assistive Healthcare, chapter 5.
<a id="13">[13]</a> Dropout: A simple way to prevent neural networks from overfitting

