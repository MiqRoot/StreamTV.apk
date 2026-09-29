# StreamTV — APK

Repositório público usado apenas para distribuição do APK do app StreamTV.

**Download direto:**
https://raw.githubusercontent.com/MiqRoot/StreamTV.apk/main/StreamTV.apk

## Instalação

1. Baixe o `StreamTV.apk` pelo link acima (no celular, toque no link).
2. Autorize a instalação de apps de fontes desconhecidas se o Android pedir.
3. Abra o arquivo baixado e instale.

## Como atualizar (para mantenedores)

```bash
# após bump de versão e ./gradlew assembleRelease
cp app/android/app/build/outputs/apk/release/app-release.apk StreamTV.apk
git add StreamTV.apk && git commit -m "StreamTV vX.Y.Z" && git push
```

A URL acima é estável — o app baixa sempre o arquivo mais recente do branch `main`.
