# MUUVIN V1 — 1.6.11

## 🎛️ Rack de FX completo: de 14 para 23 efeitos

A aba FX ganhou **9 novos processadores**. Cada um é reordenável, tem seletor de tipo, três presets de partida e um visualizador ao vivo:

- **Phaser** — de 2 a 12 estágios all-pass varridos por um LFO, com feedback (ressonância), spread estéreo e centro.
- **Equalizador de 3 bandas** — low shelf, médio sino (freq + Q) e high shelf (±12 dB), com vozes CLEAN/WARM.
- **Bitcrusher / Decimator** — profundidade de bits (1–16) + redução de sample rate com jitter, drive de entrada e filtro de tom; modos DIGITAL ou LO-FI.
- **Ring Mod / AM** — portadora senoidal/triangular/quadrada, modos RING e AM, frequência, fine e spread estéreo.
- **Stereo Widener** — mid-side (graves mono + brilho nos lados, até 2× de largura) ou Haas, com trim de saída.
- **Auto-Wah** — filtro que segue o envelope, lowpass ou bandpass, com sensibilidade, alcance e velocidade.
- **Formant** — três formantes vocálicos ressonantes que fazem morph entre pares (A-E / E-I / O-U / I-A), com deslocamento de gênero.
- **Pitch Shifter / Harmonizer** — ±24 semitons + fine, com feedback, detune estéreo e modos SHIFT ou HARMONY.
- **Vocoder** — análise de 8/12/16 bandas do seu sinal modulando uma portadora interna (serra ou ruído), com tom, ressonância e deslocamento de formante.

Com isso, **todos os 9 efeitos que faltavam no rack foram concluídos**.

## 🌊 Wavetables direto dos osciladores

Os osciladores **A** e **B** agora têm um **menu ☰** no cabeçalho para importar wavetables externas (WAV/MP3) ou escolher uma da lista — a wavetable é carregada na camada correspondente.

## 🧊 Fim do travamento ao excluir banco

Excluir um banco ou pasta agora roda em segundo plano. A interface continua fluida e responsiva mesmo com bibliotecas grandes, sem travar ao deletar, carregar ou instalar bancos.

## ✅ Qualidade

Validado com **pluginval em nível de rigor 10** (sem falhas): processamento de áudio a 44.1/48/96 kHz, automação, thread-safety, restauração de estado e fuzzing.

---

**Plataforma:** Windows (VST3, 64-bit).
**Instalação:** rode o `MUUVIN V1 Installer.exe` (ou descompacte o ZIP "VST3 plugin only" na sua pasta de plugins VST3). Feche a DAW antes de instalar.
