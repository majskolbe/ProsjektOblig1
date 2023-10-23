# ProsjektOblig1
Individuell del

#definerer alle delene av flagget som verdier
red = rectangle(352, 256, "solid", "red")
blueH = rectangle(352, 32, "solid", "darkblue")
blueV = rectangle(32, 256, "solid", "darkblue")
whiteH = rectangle(352, 64, "solid", "white")
whiteV = rectangle(64, 256, "solid", "white")

#setter sammen verdiene i riktig rekkefølge slik at riktig farge kommer øverst.
norway = 
  put-image(blueH, 176, 128,
    put-image(blueV, 128, 128,
      put-image(whiteH, 176, 128,
        put-image(whiteV, 128, 128,
          red))))

#skriver ut bildet
norway

#for å finne ut hvor delene skulle settes regna jeg meg bare frem ved hjelp av forholdene 22:16, som er forholdet til hele flagget og 6:1:2:1:12 og 6:1:2:1:6 till fargene.

