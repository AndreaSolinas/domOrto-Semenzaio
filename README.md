# Semenzaio Domotico per ortaggi

## Dimensioni
Le dimensioni **interne** dovrebbero rispettare la figura sottostante, questa è la dimensione (con gioco) di una cassetta di vaschette di piantine.

             ____________________________________________________  ---
            /                                                   / |
           /                                                   /  |
          /                                                   /   | 32 cm
         /                                                   /    | (spessore)
        /                                                   /     |
       /___________________________________________________/      ---
       |                                                   |     /
       |                                                   |    /
       |                                                   |   / 
       |                                                   |  / 32 cm
       |                                                   | / (altezza)
       |                                                   |/
       |___________________________________________________|

       |<--------------------- 52 cm --------------------->|
                            (lunghezza)

> [!IMPORTANT]
> Questo progetto deve essere il più possibile scalare.

## Dati di base

per la germinazione delle semenze sono necessarie le seguenti:
- temperatura (20°C)
- umidità relativa (70%-90% per la gerinazione. 50%-70% post germinazione)

## sensori
È necessario avere dei sensori di **umidità** garantendo la costanza settando l'umidità generale a **90%** per il primo tempo (da seme a germoglio) per poi abbasssarsi a **50%**, in maniera scalare, per evitare la formazione di muffa.

Per questo di devono avere dei **servo** per poter aprire delle feritoie garantendo la circolazione di aria, (opzionale una **ventola** per velocizzare il tutto), un **nebulizzatore** per aumentare e bagnare i germogli, una **camera** che visualizzi quando io germoglio esce dalla terra e abbassare l'umidità.

Per finire un sensore di **temperatura** che deve monitorare lo sbalzo mantendendo il più possibile i 20°


#### Lista

- [ ] sensore di umidità
- [ ] sensore di temperatura (interno/esterno)
- [ ] sensore visivo (camera / infrarossi)
- [ ] servo motori
- [ ] nebilizzatore
- [ ] pompa di calore / piasta riscaldante 

Opzionali
- [ ] ventola
- [ ] (de)umidificatore

![Heat Index](https://image.3bmeteo.com/images/newarticles/w_1280/summer-simmer-index-blog-gcwizard-net-3bmeteo-133040.png "3b Meteo")
