# Come contribuire

Grazie per voler dare una mano. Il kit cresce con quello che le community condividono: un wapuu nuovo, un gradiente, un template per un formato che ancora manca. Qui trovi come mandarci il tuo contributo e cosa ci serve sapere per inserirlo.

🇬🇧 *A short English version is at the [end of this page](#in-english).*

## Come proporre qualcosa

### Se usi GitHub

1. Fai un **fork** della repository.
2. Crea un ramo con un nome che dica cosa aggiungi, per esempio `aggiungi-wapuu-torre`.
3. Metti i file nella cartella giusta, con i nomi descritti più sotto.
4. Apri una **pull request** e compila la checklist che trovi già pronta.

### Se non usi git

Apri una [issue](../../issues/new/choose) con il modulo **Proponi una risorsa** e trascina i file nel campo dedicato. Ti basta un account GitHub. Se un formato non viene accettato, comprimi i file in uno `.zip`.

## Cosa accettiamo

| Risorsa | Cartella | Formato preferito |
|---|---|---|
| Wapuu | `assets/wapuus/` | SVG, oppure PNG con trasparenza |
| Gradienti e sfondi | `assets/gradienti/` | PNG, oppure JPG per i gradienti fotografici |
| Forme e decorazioni | `assets/forme/` | SVG |
| Font | `assets/font/` | TTF o OTF, con il file di licenza originale |
| Template | `pdf/` e `template-affinity/` | PDF più il file sorgente Affinity, e il link al modello Canva se c'è |
| Loghi e identità | `assets/brand/` | SVG, PNG |

## Nomi dei file

Usa solo lettere minuscole senza accenti, numeri e trattini, senza spazi.

I template seguono lo schema `categoria_formato`, con il trattino basso tra le due parti:

```
save-the-date_post-4x5.pdf
promemoria_stories-9x16.pdf
locandina_a3.pdf
```

I formati si scrivono con la `x` (`4x5`, `9x16`), perché i due punti non sono ammessi nei nomi dei file. Le versioni dello stesso template, per esempio con foto e solo tipografica, vanno come pagine dello stesso file. Lo stesso nome vale per il PDF, per il sorgente Affinity e per l'anteprima in `anteprime/`.

Per le altre risorse basta un nome che descriva il file, per esempio `wapuu-torre-pendente.svg` o `gradiente-giallo-tramonto.png`.

## Licenza dei contributi

Quando mandi un contributo dichiari che il lavoro è tuo, oppure che hai il permesso di condividerlo, e accetti che venga distribuito con la licenza del kit ([CC BY 4.0](LICENSE)).

Se aggiungi un wapuu, un font o una foto di qualcun altro, scrivi nella pull request o nella issue chi l'ha fatto, con quale licenza e dove l'hai trovato. Riportiamo tutto nella sezione [Licenza del README](README.md#-licenza).

## Cosa non possiamo accettare

- elementi con una licenza che non permette di modificarli e ridistribuirli
- foto, illustrazioni e font della libreria Canva Pro o di banche immagini a pagamento
- loghi e marchi di terzi
- font commerciali, anche se ne hai comprato la licenza

## Cosa succede dopo

Le proposte le guardiamo noi, Gabriele ed Elisa. Possiamo inserirle così come sono, chiederti qualche modifica oppure dirti di no, e in quel caso ti spieghiamo il motivo. Ti rispondiamo nella pull request o nella issue.

## Comportamento

Tratta chi partecipa come lo tratteresti a un meetup, con rispetto e un po' di pazienza. Commenti offensivi, discriminatori o aggressivi vengono rimossi.

---

## In English

Thanks for helping the kit grow.

- **With GitHub:** fork the repository, add your files to the right folder and open a pull request. The checklist is already there.
- **Without git:** open an [issue](../../issues/new/choose) with the **Proponi una risorsa** form and drag your files into it.
- **File names:** lowercase, no spaces, no accents, words joined by hyphens. Templates follow `category_format`, for example `save-the-date_post-4x5.pdf`, with each version as a page of the same file.
- **License:** by contributing you confirm the work is yours or that you have permission to share it, and you agree to release it under CC BY 4.0. For third party wapuus, fonts or photos, tell us the author, license and source.
- **We can't accept** Canva Pro or paid stock assets, third party logos, or commercial fonts.
