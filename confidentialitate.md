# Politica de Confidențialitate pentru RazAgent Video Publisher

**Ultima actualizare:** 23 Iulie 2026

## 1. Informații Generale
Această Politică de Confidențialitate explică modul în care "RazAgent Video Publisher" (Aplicația) colectează, utilizează și protejează datele obținute prin intermediul integrării cu TikTok API. 

## 2. Ce date colectăm
Aplicația este un sistem de automatizare cu circuit închis (uz intern). Prin autentificarea OAuth2 (Composio), colectăm doar strictul necesar:
- **Date de profil de bază:** Pentru a identifica și confirma contul pe care se va face postarea (user.info.basic).
- **Token-uri de acces:** Stocate securizat, local, exclusiv pentru a autoriza acțiunea de încărcare și publicare video (video.upload, video.publish).

## 3. Cum utilizăm datele
Datele sunt utilizate EXCLUSIV de către scripturile de automatizare din `RazAgent_Enterprise_vNext` pentru a rula webhook-urile de încărcare a videoclipurilor generate de AI pe contul de TikTok asociat.

## 4. Partajarea datelor
**NU vindem, NU închiriem și NU transferăm** nicio informație către terțe părți. Datele rămân strict în arhitectura locală a agentului și sunt folosite doar în comunicarea directă cu serverele TikTok.

## 5. Securitatea datelor
Token-urile de acces sunt stocate local, izolate de accesul public. Accesul la agent este restricționat doar administratorului sistemului.

## 6. Drepturile utilizatorilor
Deoarece aplicația gestionează doar conturile proprii ale dezvoltatorului, revocarea accesului se poate face oricând direct din setările de securitate ale contului de TikTok (Secțiunea: Aplicații autorizate).
 
