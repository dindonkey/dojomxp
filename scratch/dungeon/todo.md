# Dungeon - step 2
* aggiungere nuovi costumi livello 2 a stage e muri
* sprite "change level" (da mettere dopo la porta)
  * inizializza variabile "livello"
  * fantasma 100%
  * quando tocca il player
    * livello+1
    * manda messaggio "next level" 
* tutti reagiscono a "next level"
  * assicurarsi che tutti abbiamo una posizione iniziale
  * stage e muri passano al costume successivo
  * gli altri oggetti si ricollocano o resettano il proprio stato sotto condizione se livello = 1
  * il player si ricolloca
  * la porta:
    * si chiude
    * si ricolloca
  * la chiave 
    * resetta il suo stato
    * si ricolloca
  * il mostro si ricolloca
  * il next level si ricolloca
  

# Tiled
* new map
* scratch screen size: 480 x 360
  * quante tileset da 32x32 devo fare ?
* tileset cutter: https://0x72.itch.io/tilesetssplitter