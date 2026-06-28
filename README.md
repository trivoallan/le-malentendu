# Le Malentendu

> « La musique qui n'a jamais existé. »
> **non = malentendu**

Une **méthode ouverte** pour fusionner les genres musicaux. Le produit, c'est la
**méthode** — une représentation *model-agnostic* d'une fusion + un compilateur —
pas l'audio, pas le prompt. Les modèles (Suno, Udio, MusicGen, un musicien) sont
des **backends interchangeables**.

Libre, sous **AGPLv3**.

## Ce dépôt

| | |
|---|---|
| [`process/methode.md`](process/methode.md) | la spec : 2 couches (son + texte), 3 registres (musicologie / ressenti / politique), atomes vs molécules, vision politique |
| [`process/rfc/`](process/rfc/) | les RFC — la méthode mise en débat. **La discussion se fait sur les Pull Requests.** |
| [`poc/`](poc/) | la preuve : `python3 poc/compile.py` compile une fusion vers un prompt Suno **et** un brief humain (deux backends, une source) |
| [`catalogue/`](catalogue/) | les *malentendus trouvés* — les beaux accidents qu'on garde |
| [`GENESIS.md`](GENESIS.md) | comment le projet est né, à découvert |

## Participer

Lis la RFC ouverte et **commente la Pull Request**. Indique ton registre :
🎼 musicologie (un fait) · 👂 ressenti (subjectif) · ✊ politique (valeurs).
Le désaccord est le sujet.

## Lancer la preuve

```bash
python3 poc/compile.py          # compile les fusions -> Suno + brief
python3 poc/compile.py --check  # self-check
```

---

*non = malentendu*
