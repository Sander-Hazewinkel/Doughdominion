# Lessen (werkgeheugen)

Door Claude bijgehouden. Eén les per blok, nieuwste onderaan. Formaat:

```
## <korte titel>
- Datum: JJJJ-MM-DD · Sessie: <link>
- Les: <wat de volgende sessie anders moet doen>
- Bewijs: <wat er gebeurde, foutmelding, of Sanders correctie>
- Status: actief | verouderd (reden)
```

Verouderde lessen niet stil verwijderen: zet de status op `verouderd`; de
droom-ronde ruimt ze op.

---

## X/Twitter-links lezen
- Datum: 2026-11-04 · Sessie: https://claude.ai/code/session_016hwgo6o76wxbrPioGER3xh
- Les: WebFetch op x.com geeft HTTP 402. Haal posttekst en video-URL's op via
  `https://api.fxtwitter.com/<user>/status/<id>`. Video's: mp4 downloaden,
  `ffmpeg -ac 1 -ar 16000` naar wav, transcriberen met `faster-whisper` (base.en,
  ~5 min voor 30 min audio op 4 cores). Geef faster-whisper een numpy-array, niet
  het pad: de geïnstalleerde PyAV-versie crasht op `metadata_errors`.
- Bewijs: in deze sessie zo de presentatie over context engineering getranscribeerd.
- Status: actief
