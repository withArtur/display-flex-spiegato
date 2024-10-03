1. mostro il base:
   1. mostro prima la condizione in cui sono abbiamo messo il **flex basis** -> differenza *tra impostare il flex-basis e la width qual è*?
   2. aggiungiamo il gro e prende lo spazio, lo vedremo bene dopo
   3. se aggiung il margin, rimaniamo sempre nei limiti del box ma si crea spazio a sinistra
2. flex direction:
   1. qual è il comportamento di *default*?
   2. mostro le quattro direzioni
   3. modifico il basis 
   4. faccio notare che col reverse si spostano alla fine e sono anche invertite
3. wrap:
   1. qual è il comportamento di default? 
   2. nel momento in cui non wrappa, non prende in considerazione il flex basis, ma punta a far stare tutto su una stessa riga
4. justify content
   1. Gestione degli elementi sul main axis
   2. Il comportamento di default è stare all' inizio quindi il flex-start
   3. Se metto flex end, si spostano tutti alla fine, ma a differenza del column reverse qui mantengo tutte lo stesso ordine 
   4. mostro gli altri
   5. differenza tra **space around e space evenly, che con evenly lo spazio intorno e interno è uguale**
5. align items:
   1. Gestione degli elementi sul cross axis
   2. comportamento di default:.... ? **stretch**
   3. mostro tutti gli altri
   4. baseline che fa? Allinea in base al testo
6. Flex-grow:
   1. Cosa fa? *vediamo che dicono*
   2. il primo con flex grow 1 prende tutto lo spazio
   3. In realtà è un po più complesso; cerchiamo di capirlo ->ragionamento dietro la **divisione dello spazio per il flex-grow**
   4. far notate il calcolo quando attivo entrambi, il totale della grandezza e anche come viene rappresentato nell'inspector, con l'area e la freccetta
7. Flex-shring
   1. Cosa fa? stesso di grow ma al contrario
   2. quindi se d 3 shrinka di più rispetto a uno
   3. Notate che va anche oltre il bordo del box, perché ho impostato per l'esemepio **flex-shrink:0**, questo perché di default  flex fa in modo di far entrare tutto nel contenitore
   4. shrink: 0 impedisce a flex di restringere l'elemento
   5. notare anche qui le freccine
8. Order
   1. faccio vedere l'order normale
   2. inizio aggiungendo order a uno e faccio vedere che qualsiasi cosa metto va alla fine, perché gli altri non hanno ordine
   3. se non è impostato ordine, allora è considerato 0
   4. mostrare anche con ordine negativo 
   5. Ricordate di riflettere su **quanto vi serve** e ha senso fare così o se serve fare con html
9. float
   1.  rivediamo andiamo a sinistra e a desta
   2.  ricordare ancora una volta id usare il clearfix, mostrare se lo rompo che succede col bordo
   3.  ricordare che il clearfix va dato ai genitori di elementi float, non serve altrove
   4.  il genitore non è più influenzato dall'altezza del figlio flottante, se non ci sta il clearfix
10. inline- inline block
    1.  Attivo le varie proprietà sul block e funziona tutto
    2.  le attibo su inline. mostro che il **margin funziona solo in orizzontale**, mentre il **padding** funziona in **tutte** le direzioni. **witdh e height** nada
    3.  inline-block  prende tuttecose