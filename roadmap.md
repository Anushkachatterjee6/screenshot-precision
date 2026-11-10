# Polyglot ASR — roadmap

## Done (from earlier work)
- [x] Shared research shell (sidebar + header) and seven page components.
- [x] Typed configurable API client (`VITE_API_BASE_URL`), honest disconnected-backend states, API contract.
- [x] API boundary tests (no fabricated transcripts).

## This pass
- [ ] Routing: real file routes for all seven pages, shell around every page.
- [ ] Restore the dark research-console design tokens (colours, fonts, token colours, surfaces).
- [ ] Shell: mobile navigation drawer, live model/connection status, active states.
- [ ] Shared session state: preferences (persisted) + vocabulary (session).
- [ ] Transcription: real waveform from decoded audio, seekable playback, copy/export (txt/json), sends domain + vocabulary + rescoring.
- [ ] Language analysis: token labels, distribution, code-switch statistics, switch timeline; local script-based estimate clearly labelled when no backend.
- [ ] Context adaptation: custom domains, add/remove terms, session persistence, side-by-side comparison.
- [ ] Model evaluation: WER/CER/LID/Switch-F1/RTF from backend only, experiment comparison table + chart, measured vs unavailable.
- [ ] History: backend records only, search + filter, view dialog, txt/json download.
- [ ] Settings: functional persisted preferences, endpoint + mode display, connection test.
- [ ] Tests for language statistics and preferences; run tests + lint.
