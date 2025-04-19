# GRETIL Verse Extractor

This project extracts verses and their indices from Sanskrit texts hosted on the [GRETIL archive](https://gretil.sub.uni-goettingen.de/).

It processes two texts:
- **Aṣṭāvakragītā** (`sa_aSTAvakragItA.txt`)
- **Nārāyaṇīya** from the Mahābhārata (`sa_nArAyaNIya.txt`)

## Output Format

Each verse is saved in JSON format like:
```json
{
  "verse": "na tvaṃ viprādiko varṇo nāśramī nākṣagocaraḥ\nasaṅgo 'si nirākāro viśvasākṣī sukhī bhava",
  "index": "1.5"
}

