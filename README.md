# babapionier-model

On-Device-KI-Modell für die **[BABAPionier](https://apps.apple.com/app/id6761618780)** iOS-App.
Die App lädt dieses Modell beim ersten Start einmalig herunter und führt danach die
gesamte KI **offline auf dem iPhone** aus — ohne Server, ohne Cloud, ohne laufende Kosten.

## Modell

| | |
|---|---|
| **Modell** | Qwen2.5-3B-Instruct, 4-bit quantisiert (MLX-Format) |
| **Quelle** | [mlx-community/Qwen2.5-3B-Instruct-4bit](https://huggingface.co/mlx-community/Qwen2.5-3B-Instruct-4bit) |
| **Upstream-Lizenz** | Apache-2.0 |
| **Größe** | ~1,7 GB |
| **Laufzeit** | [Apple MLX](https://github.com/ml-explore/mlx) (iOS 17+, Apple Silicon) |

## Auslieferung

Die Modell-Dateien werden als **GitHub-Release-Assets** bereitgestellt. Eine
`manifest.json` im Release listet alle Dateien mit Größe/Prüfsumme; die App liest das
Manifest, lädt die Dateien per WLAN und cached sie lokal. Ab dem zweiten Start läuft
die App vollständig offline.

**Aktuelles Release:** [`qwen2.5-3b-instruct-4bit-v1`](../../releases/tag/qwen2.5-3b-instruct-4bit-v1)

## Lizenz

Die Modellgewichte stehen unter **Apache-2.0** (siehe [`LICENSE`](LICENSE) und
[`NOTICE`](NOTICE)). Die Quell- und Trainingsrechte liegen bei den jeweiligen
Urhebern (Qwen / Alibaba Cloud, mlx-community). Dieses Repository verteilt die
Gewichte unverändert für die Nutzung in der BABAPionier-App weiter.
