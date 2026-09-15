# Cartella samples

Metti qui i tuoi file audio (.wav, .mp3, .m4a...).

Poi apri "samples.json" in questa cartella e aggiungi il nome di ogni file
all'elenco, ad esempio:

["kick.wav", "snare.wav", "vocal_chop.mp3"]

Dopo aver salvato samples.json e ricaricato l'app, i file compariranno
nel menu SOUND sotto la voce "Samples" e potrai selezionarli come un
qualsiasi synth: verranno intonati automaticamente in base al Pitch
di ogni step (nota di riferimento: C4).

Nota: se apri index.html direttamente come file locale (senza un
piccolo server/hosting), il browser potrebbe bloccare il caricamento
di samples.json e dei file audio per motivi di sicurezza (CORS).
In quel caso resta comunque disponibile il pulsante "Load sample..."
nel menu SOUND, che carica un file scelto al momento senza questa
limitazione.
