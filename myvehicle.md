# MyVehicle — Support & Privacy Policy

*Last updated: 18 September 2026*

---

## Support / Assistenza

**English** — Need help, found a bug, or have feedback about MyVehicle? Contact us at **siciliano.dev@icloud.com** and we'll get back to you as soon as possible.

**Italiano** — Hai bisogno di aiuto, hai trovato un bug o vuoi darci un feedback su MyVehicle? Scrivici a **siciliano.dev@icloud.com**, ti risponderemo il prima possibile.

---

## English

**MyVehicle** keeps track of the maintenance of your own vehicles — services, tyre changes, fuel, insurance and roadworthiness deadlines — with a focus on enduro motorcycles, which are serviced by engine hours rather than kilometres. This Privacy Policy explains how the app handles information.

### Data We Do Not Collect

MyVehicle has **no servers and no accounts**. We never receive your data: there is nothing to sign up for, and nothing about your garage is ever sent to us or to anyone else. It does not use GPS or any location service: if you write down where you rode, that is text you typed yourself.

The app contains **no analytics**. It does contain advertising, which is described in the next section — that is the one part of the app that talks to a third party, and it never sees what is in your garage.

### Advertising

The free version of MyVehicle shows advertising supplied by **Google AdMob**: a banner on the Garage, Deadlines and Statistics screens, and occasionally a full-screen advert when you open a form that records something new.

To serve and measure those adverts, the Google Mobile Ads SDK collects **device and usage information** — a device identifier, general information about the device and the app, interaction with the adverts, and diagnostic data. That happens inside Google's SDK: we do not receive any of it, and we do not have an account-level view of you. Google's handling of that data is governed by the [Google Privacy Policy](https://policies.google.com/privacy) and by [how Google uses information from sites or apps that use its services](https://policies.google.com/technologies/partner-sites).

**The adverts are non-personalised.** The app explicitly asks Google not to personalise them, which is why iOS never shows you the "allow tracking" prompt: MyVehicle does not use the advertising identifier to follow you across other apps or websites, and it does not build a profile of you. Non-personalised adverts still use the context of the app and coarse, non-identifying signals to be served and counted.

**Your garage is never part of it.** Vehicles, counters, rides, services, costs, documents, photos and notes are not sent to Google or used to choose adverts. The advertising knows nothing about your bikes.

### Removing The Advertising

A single in-app purchase of **0,99 €** removes the advertising permanently. It is a one-off purchase, not a subscription, and it is tied to your Apple Account, so it applies to your other devices and can be restored with **Restore purchases** in Settings after reinstalling or changing phone.

The purchase is handled entirely by Apple. We never see your payment details: the app only asks Apple whether this Apple Account owns the purchase. Once it does, the advertising SDK is **not even started** — nothing is loaded and nothing is collected.

### What You Store In The App

Everything in MyVehicle is entered by you. Depending on what you choose to record, that can include:

- **Vehicles** — make, model, year, nickname, and optionally the number plate and the VIN / chassis number.
- **Counters** — engine hours and kilometres, and the dated readings behind them.
- **Rides** — date, duration, distance, type of outing, the place (free text) and your notes.
- **Maintenance** — services performed, dates and counter values, whether you did it yourself or a workshop did, the workshop's name, costs, and the parts used with their part numbers and prices.
- **Tyres and refuelling** — fitments and fill‑ups, with quantities and amounts spent.
- **Documents** — insurance, roadworthiness test, road tax, the owner's manual and similar: type, company, policy number, validity dates, cost, and optionally the file itself.
- **Photos and files** — optionally a photo of a vehicle, a photo of a receipt attached to a service, and a PDF or image attached to a document.

Some of this can identify you or your vehicle — a number plate, a VIN, a policy number. Whether to record those fields is entirely your choice: they are all optional, and the app works without them.

### Photos And Attachments

Attaching a photo uses the **system photo picker**, which runs outside the app. The app is never granted access to your photo library — that is why iOS does not ask you for a photo permission — and it receives only the single image you picked. MyVehicle does not use the camera.

Before the image is saved it is **resized and re-encoded**, which also means the metadata that a photo usually carries is **not kept: no GPS coordinates, no capture date, no device information**. Only the pixels are stored. Photos are never analysed, and nothing is read out of them.

Files are attached the same way, through the **system file picker**: the app gets the one file you chose and nothing else. A PDF is stored exactly as it is, because re-encoding it would cost you the selectable text and the bookmarks — which does mean a PDF keeps whatever metadata its own author put inside it, unlike a photo. Attachments are capped at 25 MB, since they sync along with everything else.

From then on photos and files live in the same database as the rest and follow the same rules described below.

### Where Your Data Is Stored

Your data lives in a database **on your device**.

If you are signed in to iCloud and iCloud Drive is enabled for MyVehicle, the app also syncs that database to **your own private iCloud database (CloudKit)**, so your garage is available on your other devices and is included in your iCloud backup. This is Apple's infrastructure, tied to your Apple Account: we have no access to it, and neither does anyone else. Apple's handling of that data is governed by the [Apple Privacy Policy](https://www.apple.com/legal/privacy/).

If you are not signed in to iCloud, or you turn iCloud off for MyVehicle, everything stays on your device and nothing is transmitted anywhere.

### Notifications

Reminders are **local notifications**, scheduled by the app on your device from the deadlines it calculates. They are optional, you are asked for permission only the first time you switch them on, and no notification is ever sent from a server. Nothing about your vehicles leaves the device in order to produce them.

### Export And Sharing

You can export your garage as a JSON file and your service history as a CSV file. These files are created on request and handed to the iOS share sheet: **you** decide whether to save them, send them or discard them. The app does not upload them anywhere.

### Deleting Your Data

Deleting the app removes the data stored on your device. If iCloud sync was enabled, the copy in your private iCloud database can be removed from **Settings → your name → iCloud → Manage Account Storage**, where MyVehicle's data can be deleted like that of any other app.

### Children's Privacy

MyVehicle does not knowingly collect any data from children under 13.

### Changes To This Policy

If MyVehicle ever introduces features that change how data is handled — for example sharing a garage with another person, or any feature involving a server of ours — this policy will be updated before those features ship.

### Contact

For any questions about this Privacy Policy, contact us at: **siciliano.dev@icloud.com**

---

## Italiano

**MyVehicle** tiene sotto controllo la manutenzione dei tuoi veicoli — tagliandi, cambi gomme, rifornimenti, scadenze di assicurazione e revisione — con una particolare attenzione alle moto da enduro, che si manutengono a ore motore e non a chilometri. Questa Privacy Policy spiega come l'app gestisce le informazioni.

### Dati che non raccogliamo

MyVehicle **non ha server e non ha account**. I tuoi dati non ci arrivano mai: non c'è nessuna registrazione da fare, e niente di quello che c'è nel tuo garage viene inviato a noi o a chiunque altro. Non usa il GPS né alcun servizio di localizzazione: se annoti dove hai girato, è testo che hai scritto tu.

L'app non contiene **analytics**. Contiene invece la pubblicità, descritta qui sotto: è l'unica parte dell'app che parla con un terzo, e non vede mai cosa c'è nel tuo garage.

### Pubblicità

La versione gratuita di MyVehicle mostra pubblicità fornita da **Google AdMob**: un banner nelle schermate Garage, Scadenze e Statistiche e, ogni tanto, un annuncio a schermo intero quando apri un modulo per registrare qualcosa.

Per mostrare e contare quegli annunci, l'SDK Google Mobile Ads raccoglie **informazioni sul dispositivo e sull'uso**: un identificativo del dispositivo, informazioni generiche su dispositivo e app, l'interazione con gli annunci e dati diagnostici. Succede dentro l'SDK di Google: a noi non arriva niente e non abbiamo nessuna vista su di te. Il trattamento da parte di Google è regolato dalle [norme sulla privacy di Google](https://policies.google.com/privacy) e da [come Google utilizza le informazioni dei siti o delle app che usano i suoi servizi](https://policies.google.com/technologies/partner-sites).

**Gli annunci sono non personalizzati.** L'app chiede esplicitamente a Google di non personalizzarli, ed è il motivo per cui iOS non ti mostra mai la richiesta «consenti il tracciamento»: MyVehicle non usa l'identificativo pubblicitario per seguirti su altre app o siti e non costruisce un profilo su di te. Un annuncio non personalizzato usa comunque il contesto dell'app e segnali grossolani e non identificativi per essere mostrato e conteggiato.

**Il tuo garage non c'entra mai.** Veicoli, contatori, uscite, interventi, costi, documenti, foto e note non vengono inviati a Google né usati per scegliere gli annunci. La pubblicità non sa niente delle tue moto.

### Togliere la pubblicità

Un acquisto in-app di **0,99 €** rimuove la pubblicità per sempre. È un acquisto una tantum, non un abbonamento, ed è legato al tuo Apple Account: vale anche sugli altri tuoi dispositivi e si recupera con **Ripristina acquisti** nelle impostazioni dopo una reinstallazione o un cambio di telefono.

L'acquisto è gestito interamente da Apple. I tuoi dati di pagamento non li vediamo mai: l'app chiede ad Apple soltanto se questo Apple Account possiede l'acquisto. Quando lo possiede, l'SDK pubblicitario **non viene nemmeno avviato**: non carica niente e non raccoglie niente.

### Cosa salvi nell'app

Tutto ciò che c'è in MyVehicle lo inserisci tu. A seconda di cosa scegli di registrare, può comprendere:

- **Veicoli** — marca, modello, anno, soprannome e, se vuoi, targa e numero di telaio.
- **Contatori** — ore motore e chilometri, con le letture datate da cui derivano.
- **Uscite** — data, durata, distanza, tipo di uscita, il luogo (testo libero) e le tue note.
- **Manutenzioni** — interventi eseguiti, date e contatori, se li hai fatti da solo o in officina, il nome dell'officina, i costi e i ricambi usati con codice e prezzo.
- **Gomme e rifornimenti** — montaggi e pieni, con quantità e spesa.
- **Documenti** — assicurazione, revisione, bollo, libretto di uso e manutenzione e simili: tipo, compagnia, numero di polizza, validità, costo e, se vuoi, il file stesso.
- **Foto e file** — se vuoi, la foto di un veicolo, la foto di uno scontrino allegata a un intervento e un PDF o un'immagine allegati a un documento.

Alcune di queste informazioni possono identificare te o il tuo veicolo: una targa, un numero di telaio, un numero di polizza. Se registrarle è una scelta solo tua: sono tutti campi facoltativi e l'app funziona anche senza.

### Foto e allegati

Per allegare una foto si usa il **selettore foto di sistema**, che gira fuori dall'app. All'app non viene mai dato accesso alla tua libreria — è il motivo per cui iOS non ti chiede nessun permesso per le foto — e riceve solo la singola immagine che hai scelto. MyVehicle non usa la fotocamera.

Prima di essere salvata, l'immagine viene **ridimensionata e ricodificata**: questo comporta che i metadati che una foto normalmente si porta dietro **non vengono conservati: nessuna coordinata GPS, nessuna data di scatto, nessuna informazione sul dispositivo**. Vengono salvati solo i pixel. Le foto non vengono mai analizzate e da esse non viene letto nulla.

I file si allegano allo stesso modo, con il **selettore file di sistema**: all'app arriva il singolo file che hai scelto e nient'altro. Un PDF viene salvato esattamente com'è, perché ricodificarlo ti costerebbe il testo selezionabile e i segnalibri — il che però significa che un PDF conserva i metadati che ci ha messo dentro chi l'ha prodotto, a differenza di una foto. Gli allegati hanno un limite di 25 MB, dato che vengono sincronizzati insieme a tutto il resto.

Da lì in poi foto e file vivono nello stesso database del resto e seguono le stesse regole descritte qui sotto.

### Dove sono conservati i dati

I tuoi dati stanno in un database **sul tuo dispositivo**.

Se hai effettuato l'accesso a iCloud e iCloud Drive è attivo per MyVehicle, l'app sincronizza quel database anche sul **tuo database iCloud privato (CloudKit)**, così il garage è disponibile sugli altri tuoi dispositivi ed è incluso nel backup iCloud. È l'infrastruttura di Apple, legata al tuo Apple Account: noi non vi abbiamo accesso, e nessun altro ce l'ha. Il trattamento da parte di Apple è regolato dall'[informativa sulla privacy di Apple](https://www.apple.com/legal/privacy/).

Se non hai l'accesso a iCloud, oppure disattivi iCloud per MyVehicle, tutto resta sul dispositivo e non viene trasmesso da nessuna parte.

### Notifiche

I promemoria sono **notifiche locali**, programmate dall'app sul tuo dispositivo a partire dalle scadenze che calcola. Sono facoltative, il permesso ti viene chiesto solo la prima volta che le attivi e nessuna notifica parte mai da un server. Per generarle nessuna informazione sui tuoi veicoli lascia il dispositivo.

### Esportazione e condivisione

Puoi esportare il garage in un file JSON e lo storico degli interventi in un file CSV. Questi file vengono creati su tua richiesta e passati al pannello di condivisione di iOS: sei **tu** a decidere se salvarli, inviarli o scartarli. L'app non li carica da nessuna parte.

### Cancellazione dei dati

Disinstallando l'app i dati salvati sul dispositivo vengono rimossi. Se la sincronizzazione iCloud era attiva, la copia nel tuo database iCloud privato si elimina da **Impostazioni → il tuo nome → iCloud → Gestisci spazio account**, dove i dati di MyVehicle possono essere cancellati come quelli di qualsiasi altra app.

### Privacy dei minori

MyVehicle non raccoglie consapevolmente dati da bambini di età inferiore ai 13 anni.

### Modifiche a questa informativa

Se in futuro MyVehicle introdurrà funzionalità che cambiano il trattamento dei dati — per esempio la condivisione del garage con un'altra persona, o qualsiasi funzione che coinvolga un nostro server — questa informativa sarà aggiornata prima del rilascio di tali funzionalità.

### Contatti

Per qualsiasi domanda su questa Privacy Policy, contattaci a: **siciliano.dev@icloud.com**
