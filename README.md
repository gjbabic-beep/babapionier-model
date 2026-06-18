# babapionier-model

On-Device-KI-Modell fuer die **BABAPionier** iOS-App.

- **Modell:** Qwen2.5-3B-Instruct, 4-bit quantisiert (MLX-Format)
- **Quelle:** [mlx-community/Qwen2.5-3B-Instruct-4bit](https://huggingface.co/mlx-community/Qwen2.5-3B-Instruct-4bit) (Apache-2.0)
- **Groesse:** ~1.7 GB

Die Modell-Dateien werden als **Release-Assets** bereitgestellt und von der App
beim ersten Start heruntergeladen (`manifest.json` listet alle Dateien). So
laeuft die App vollstaendig auf dem Geraet — ohne Server, ohne laufende Kosten.

## Release

Tag: `qwen2.5-3b-instruct-4bit-v1`
