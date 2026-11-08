# CV di Alessio Pecilli

Il CV e' scritto in LaTeX. La versione pronta per la consultazione e' [CVPecilliAlessio.pdf](CVPecilliAlessio.pdf).

## Modifiche

- La descrizione personale si trova in `src/personal-description.tex`. Sostituisci il testo segnaposto con una presentazione di 2-3 righe.
- La foto usata nell'intestazione e' `foto-alessio-pecilli.jpg`. Per cambiarla, sostituisci il file e ricompila il PDF.
- Dopo ogni modifica, verifica che il PDF resti su una pagina.

Per ricompilare con MiKTeX:

```powershell
pdflatex -interaction=nonstopmode -halt-on-error -jobname=CVPecilliAlessio resume.tex
pdflatex -interaction=nonstopmode -halt-on-error -jobname=CVPecilliAlessio resume.tex
```

Il workflow GitHub Pages pubblica il PDF gia' compilato. Dopo averlo modificato, includi nel commit anche `CVPecilliAlessio.pdf`.
