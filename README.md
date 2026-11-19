# AVALON – Loyndarmálið

Føroyskt web-spæl fyri 5–10 spælarar. Ein Node.js servari við Socket.IO stýrir rúmum, tilvildarligum leiklutum, atkvøðum og ferðum.

## Byrja

1. Legg Node.js 20+ inn.
2. Koyr `npm install` í hesi mappu.
3. Koyr `npm start`.
4. Far á `http://localhost:3000`.
5. Legg servaran á t.d. Render ella Railway, um telefonir á ymiskum netum skulu spæla saman. Deil HTTPS-leinkjuna.

## Avmarkingar í fyrstu útgávu

- Spælarar mugu vera á netinum alla tíðina; endurinnriting eftir sambandsslit er ikki gjørd enn.
- Rúm og spøl verða goymd í minninum á servaranum, ikki í dátugrunni.
- Game Master velur 5–10 spælarar og serleiklutir: Merlin, Bani, Percival, Morgana, Mordred og Oberon.
- PWA kann leggjast á heimaskíggjan eftir at servarin er lagdur á HTTPS-hosting.
- Ein almenn leinkja verður ikki sjálvvirkandi stovnað við at taka ZIP-fíluna niður.
- Ein servari-instansur; skal ikki koyrast á fleiri replicas uttan felags dátugrunn.
