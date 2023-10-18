
# Typescript #4: React & Typescript
👋 Se föreläsningen i tisdags och onsdags ✅ 

**Syftet med denna workshop:** Få testa på att använda Typescript i React och avgöra vad det finns för fördelar.


### Skapa Reactprojekt med Typescript i Vite

```
npm create vite@latest
```
och välj tillval (React, Typescript)

### Migrera React JS-projekt till Typescript i Vite

1. npm install @types/react @types/react-dom
1. Om man har externa bibliotek som kräver types så installera dem med
1. npx tsc --init
1. tsconfig => jsx": "react-jsx"
1. Byt alla .js/.jsx-filer till .tsx
1. Använd // @ts-no-check högst upp i en fil för att ignorera  ts-fel - så att du kan fokusera på vissa filer
1. Rätta alla ts-fel eller inför typer där det behövs
1. Jobba utifrån och in (alltså i komponenter som inte har beroenden, och sedan dem som importerar)
1. Testkör! Obs! Du behöver ändra entrypoint main.jsx till main.tsx i index.html


### Bra att veta

Alla uppgifter + extrauppgifter är framåtsyftande mot provet i Typescript i v 44.

Förutom övningen finns även extrauppgifter på externa sidor. Gör dessa för att repetera, få djupare förståelse. För att relatera tll kommande prov anger jag G-nivå eller VG-nivå.

På provet kommer man få använda sig av Typescriptdokumentationen, så börja bli vän med den redan nu :-)

[https://www.typescriptlang.org/docs/](https://www.typescriptlang.org/docs/)

# 👩🏽‍💻 Övning : Migrera valfri Reactapp till Typescript


Välj ut en redan befintlig Reactapp och migrera till Typescript! Lagom omfång :-)
Det går också bra att skapa en Reactapp från grunden med Typescript.


# 🏃🏽‍♂️ Extrauppgifter

[https://www.totaltypescript.com/tutorials/react-with-typescript](https://www.totaltypescript.com/tutorials/react-with-typescript)




# ✅ Redovisning:
* Du redovisar minst uppgiften för övningen. 
* ***Om du inte kan delta på workshopen, redovisar du ovanstående nästkommande workshop***







