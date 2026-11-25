---
title: "Gemini Gems Are Becoming Skills: Save Yours and Build a Reply Helper"
title_es: "Los Gems de Gemini ahora son Skills: guarda los tuyos y crea un ayudante para responder"
description: "Google is replacing Gems with skills in Gemini, and old Gems disappear on December 17. Save your work and build a free customer-reply skill, step by step."
categories: [ai-tools]
has_spanish: true
---

Maybe you built a Gem in Gemini months ago. A little helper that writes your Instagram captions, or answers customer emails the way you like. And this week you opened it and… you can't use it anymore. You can see it, but you can't chat with it or edit it.

That's not a glitch. Google is changing how custom helpers work in the Gemini app. **Gems are being replaced by something called "skills."** For personal Google accounts, Gems became read-only on **November 17, 2026**, and Google says they'll be **removed on December 17, 2026**.

The good news: Google converts your Gems into skills automatically, and skills can do more. The not-so-good news: some files might not make the trip, and if you never built a helper at all, you're missing one of the most useful free AI tricks for a small business.

This guide covers both. First, how to save what you have. Then, how to build a skill that drafts replies to customer messages in your own voice, with prompts you can copy and paste.

## Why it matters

If you run a small business alone, you write the same kinds of messages over and over: "Yes, we're open Saturday," "Here's how the deposit works," "Sorry for the delay." Each one takes a few minutes. Together they eat your week.

A **skill** is a set of saved instructions (plus files, if you want) that Gemini reuses every time. In plain words: you explain your business, your tone and your rules *once*, and then you just call the skill when you need it. No more pasting the same long prompt into every chat.

Three reasons to care right now:

1. **Deadline.** If you have Gems on a personal account, December 17 is the date Google gives for removal.
2. **Your files.** Google's help page says files that don't transfer need to be downloaded before December 17.
3. **It's free to start.** Google's skills help page lists only two requirements: be 18 or older, and sign in to the Gemini app.

## Who is affected, and when

| Account type | What happens to Gems |
|---|---|
| Personal Google account, 18+ | Read-only since Nov 17, 2026. Removed Dec 17, 2026. |
| Personal account, under 18 | A later date, not announced yet |
| Google Workspace (business, enterprise, non-profit) | Moves to skills in March 2027 |
| Google Workspace (education) | Moves to skills in June 2027 |

If you use Gemini through a **Workspace** business account, you have more time. Skills are only available on personal accounts for now; Google says work and school accounts are coming "soon."

## What it costs

- **Gemini app with skills:** 🆓 Free with limits. You need a Google account and must be 18+. Free Gemini has usage limits that can change, and you can have up to **100 active skills** with up to **100 MB of files per skill**.
- **Google AI Pro:** 💳 Paid, $19.99/month in the US (checked today on Google's Gemini business page). It gives higher usage limits. You don't need it to build skills.
- **Free alternative outside Google:** 🆓 **Claude Projects** on Claude's free plan. Anthropic's help center says free users can create up to 5 projects, each with its own instructions and uploaded documents.

## Step 1: Rescue your old Gems (10 minutes)

Even though Google converts Gems automatically, don't trust a migration you didn't check. Here's a safe routine:

1. Go to **gemini.google.com** and find your Gems in the sidebar.
2. Open each one. They're read-only now, but you can still **see** them.
3. **Copy the instructions** into a Google Doc or a note. Title the note with the Gem's name.
4. If you uploaded files to the Gem, make sure you still have the originals on your computer or in Drive. If not, download them now.
5. After the conversion, open **Customize → Skills** and check that your helper is there and works the way you expect.

> **Tip:** Files that live in Google Drive stay linked to the skill, so if you update the Drive file, the skill sees the new version. Files you uploaded from your computer don't update on their own.

## Step 2: Write your "voice notes" (15 minutes)

Before you build a reply helper, collect what it needs to know. Open a blank document and fill in this checklist:

- **Business basics:** name, what you sell, where you work, hours.
- **Top 10 questions** customers ask, with your real answers.
- **Policies:** deposits, cancellations, refunds, delivery or travel.
- **Tone:** three words that describe how you sound (for example: warm, short, direct).
- **Things you never say:** for example, "never promise a delivery date," "never give a discount without asking me."
- **Languages:** which languages you reply in.
- **Two or three real replies** you were happy with (remove customer names first).

> **Privacy rule:** Leave out client names, phone numbers, addresses, health details and payment information. After 20 years as a medical and legal interpreter, I treat this as non-negotiable. Your skill needs to know your *business*, not your *clients*.

Save this as a Google Doc or a .docx or .pdf file. Google's help page lists those formats as supported. Older formats like .doc are not.

## Step 3: Create the skill (10 minutes)

1. Go to **gemini.google.com** and sign in.
2. In the sidebar, click **Customize** (if you don't see it, click **More** first).
3. At the top, click **Skills**, then **Create**.
4. Choose **Create manually**.
5. Enter a **name**. Skill names use lowercase letters and hyphens, like `customer-replies`.
6. Write a short **description**, such as: *Drafts replies to customer messages in my voice, using my policies.*
7. Paste the **instructions** below (fill in the brackets).
8. Click **Add** to attach your "voice notes" document from your computer or Google Drive, then click **Upload**.
9. Click **Create**.

Copy-paste instructions for the skill:

```
You help me reply to customer messages for my business, [business name].
I sell [product or service] in [city or online].

Use the attached document as the source of truth for prices,
hours and policies. If the answer isn't in the document, write
[CHECK] in the draft instead of guessing.

My tone: [warm, short, direct]. Use short sentences. No emojis
unless the customer used one. Sign off as [your name].

Never promise dates, discounts or refunds. If a customer asks for
one, write a polite reply that says I'll confirm personally.

Reply in the same language the customer wrote in. If it's Spanish,
use natural Latin American Spanish, not a word-for-word translation.

Give me ONE draft, then a one-line note on anything I should check.
```

## Step 4: Use it and test it (10 minutes)

In any Gemini chat, type **/** followed by the skill name (Google says this will soon change to **@**), then paste the customer's message:

```
/customer-replies
Customer wrote: "Hi! Do you work Saturdays? And how much is the
deposit if I book for December?"
```

Gemini can also pick up a relevant skill on its own, but calling it by name is more predictable.

Test it with five real (anonymous) messages, including one it *shouldn't* be able to answer. A good result says **[CHECK]** instead of inventing a price. If it guesses, add a stricter line to the instructions: *"If you're not 100% sure, write [CHECK]."*

To change the instructions later: **Customize → Skills →** click your skill, edit, and click **Save**.

## What skills can't do (yet)

Google's help page lists some limits worth knowing:

- Skills don't work with **Canvas** or **Deep Research**.
- Several tools Gems had, like video or music creation, don't work with skills.
- Sharing a skill only works on the web version, and a skill with a notebook attached can't be shared.
- You can't turn skills on or off from inside a chat; you do it in **Customize → Skills**.

## The honest truth

A reply skill saves typing. It does not replace your judgment. Read every draft before you send it, especially anything about money, dates or a complaint. AI tools can still sound confident and be wrong, even with your documents attached.

Also, this change is a reminder that tools change. That's why your "voice notes" document matters more than any single app: keep it in your own files, and you can rebuild your helper in Gemini, Claude or anything that comes next in about ten minutes.

I answer questions like this every day in my free community, [Plugin & Progress](https://community.mainentry.net). Bring your skill instructions and we'll improve them together.

## Your one action for today

Open gemini.google.com and check for old Gems. If you have any, copy their instructions into a document before December 17. If you have none, write your "voice notes" checklist from Step 2. That one document is the foundation for every AI helper you'll build.

<hr>

<h2 id="espanol">🇪🇸 Español</h2>

Tal vez creaste un Gem en Gemini hace unos meses. Un pequeño ayudante que escribe tus textos para Instagram o responde correos de clientes como a ti te gusta. Y esta semana lo abriste y… ya no puedes usarlo. Lo ves, pero no puedes chatear con él ni editarlo.

No es un error. Google está cambiando cómo funcionan los ayudantes personalizados en la app de Gemini. **Los Gems se están reemplazando por algo llamado "skills" (habilidades).** En las cuentas personales de Google, los Gems pasaron a ser de solo lectura el **17 de noviembre de 2026**, y Google dice que se **eliminarán el 17 de diciembre de 2026**.

La buena noticia: Google convierte tus Gems en skills automáticamente. La no tan buena: algunos archivos podrían no pasar. Y si nunca creaste un ayudante, te pierdes uno de los trucos gratuitos de IA más útiles para un negocio pequeño.

Esta guía cubre las dos cosas. Primero, cómo guardar lo que tienes. Después, cómo crear una skill que redacte respuestas a tus clientes con tu propia voz, con instrucciones que puedes copiar y pegar.

## Por qué importa

Si llevas tu negocio sin equipo, escribes los mismos mensajes una y otra vez: "Sí, abrimos el sábado", "Así funciona el anticipo". Cada uno toma minutos. Juntos se comen tu semana.

Una **skill** es un conjunto de instrucciones guardadas (y archivos, si quieres) que Gemini reutiliza cada vez. En palabras sencillas: explicas tu negocio, tu tono y tus reglas *una sola vez*, y luego solo llamas a la skill cuando la necesitas. Ya no tienes que pegar el mismo mensaje largo en cada chat.

Tres razones para prestarle atención ahora:

1. **Fecha límite.** Si tienes Gems en una cuenta personal, el 17 de diciembre es la fecha que da Google para eliminarlos.
2. **Tus archivos.** La página de ayuda de Google dice que los archivos que no se transfieran deben descargarse antes del 17 de diciembre.
3. **Empezar es gratis.** La página de ayuda de skills de Google menciona solo dos requisitos: tener 18 años o más e iniciar sesión en la app de Gemini.

## A quién afecta y cuándo

| Tipo de cuenta | Qué pasa con los Gems |
|---|---|
| Cuenta personal de Google, 18+ | Solo lectura desde el 17 nov 2026. Se eliminan el 17 dic 2026. |
| Cuenta personal, menores de 18 | Una fecha posterior, aún sin anunciar |
| Google Workspace (empresas, organizaciones sin fines de lucro) | Pasan a skills en marzo de 2027 |
| Google Workspace (educación) | Pasan a skills en junio de 2027 |

Si usas Gemini con una cuenta de **Workspace** de empresa, tienes más tiempo. Por ahora las skills solo están disponibles en cuentas personales; Google dice que llegarán "pronto" a cuentas de trabajo y escuela.

## Cuánto cuesta

- **App de Gemini con skills:** 🆓 Gratis con límites. Necesitas una cuenta de Google y tener 18 años o más. Gemini gratis tiene límites de uso que pueden cambiar, y puedes tener hasta **100 skills activas** con hasta **100 MB de archivos por skill**.
- **Google AI Pro:** 💳 De pago, $19.99 USD al mes en EE. UU. (verificado hoy en la página de Gemini para negocios). Da límites de uso más altos. No lo necesitas para crear skills.
- **Alternativa gratis fuera de Google:** 🆓 **Proyectos de Claude** en el plan gratuito de Claude. El centro de ayuda de Anthropic dice que los usuarios gratuitos pueden crear hasta 5 proyectos, cada uno con sus propias instrucciones y documentos.

## Paso 1: Rescata tus Gems antiguos (10 minutos)

Aunque Google convierte los Gems automáticamente, no confíes en una migración que no revisaste. Esta es una rutina segura:

1. Entra a **gemini.google.com** y busca tus Gems en la barra lateral.
2. Abre cada uno. Ahora son de solo lectura, pero todavía puedes **verlos**.
3. **Copia las instrucciones** en un documento de Google o una nota. Ponle el nombre del Gem.
4. Si subiste archivos al Gem, asegúrate de tener los originales en tu computadora o en Drive. Si no, descárgalos ahora.
5. Después de la conversión, abre **Personalizar → Skills** (en inglés: *Customize → Skills*) y comprueba que tu ayudante esté ahí y funcione como esperas.

> **Consejo:** Los archivos de Google Drive siguen conectados a la skill: si actualizas el archivo en Drive, la skill ve la versión nueva. Los que subiste desde tu computadora no se actualizan solos.

## Paso 2: Escribe tus "notas de voz" (15 minutos)

Antes de crear un ayudante para responder, reúne lo que necesita saber. Abre un documento en blanco y completa esta lista:

- **Datos básicos:** nombre del negocio, qué vendes, dónde trabajas, horario.
- **Las 10 preguntas más comunes** de tus clientes, con tus respuestas reales.
- **Políticas:** anticipos, cancelaciones, reembolsos, entregas o traslados.
- **Tono:** tres palabras que describan cómo hablas (por ejemplo: cálida, breve, directa).
- **Lo que nunca dices:** por ejemplo, "nunca prometo fecha de entrega", "nunca doy descuentos sin consultarme".
- **Idiomas:** en qué idiomas respondes.
- **Dos o tres respuestas reales** que te gustaron (quita los nombres de los clientes).

> **Regla de privacidad:** No incluyas nombres de clientes, teléfonos, direcciones, datos de salud ni información de pago. Después de 20 años como intérprete médica y legal, para mí esto no es negociable. Tu skill necesita conocer tu *negocio*, no a tus *clientes*.

Guárdalo como documento de Google, .docx o .pdf. La página de ayuda de Google los menciona como formatos compatibles. Los formatos antiguos como .doc no lo son.

## Paso 3: Crea la skill (10 minutos)

1. Entra a **gemini.google.com** e inicia sesión.
2. En la barra lateral, haz clic en **Personalizar** (si no lo ves, haz clic primero en **Más**).
3. Arriba, haz clic en **Skills** y luego en **Crear**.
4. Elige **Crear manualmente**.
5. Escribe un **nombre**. Los nombres de skills usan minúsculas y guiones, como `respuestas-clientes`.
6. Escribe una **descripción** corta, por ejemplo: *Redacta respuestas a mensajes de clientes con mi voz, usando mis políticas.*
7. Pega las **instrucciones** de abajo (completa lo que está entre corchetes).
8. Haz clic en **Agregar** para adjuntar tu documento de "notas de voz" desde tu computadora o Google Drive, y luego en **Subir**.
9. Haz clic en **Crear**.

Instrucciones para copiar y pegar en la skill:

```
Me ayudas a responder mensajes de clientes de mi negocio, [nombre].
Vendo [producto o servicio] en [ciudad o en línea].

Usa el documento adjunto como fuente oficial de precios, horarios
y políticas. Si la respuesta no está en el documento, escribe
[REVISAR] en el borrador en lugar de adivinar.

Mi tono: [cálido, breve, directo]. Usa frases cortas. Sin emojis
a menos que el cliente haya usado uno. Firma como [tu nombre].

Nunca prometas fechas, descuentos ni reembolsos. Si un cliente pide
alguno, escribe una respuesta amable diciendo que lo confirmaré
personalmente.

Responde en el mismo idioma en que escribió el cliente. Si es
español, usa un español latinoamericano natural, no una traducción
palabra por palabra.

Dame UN solo borrador y luego una nota de una línea con lo que
debo revisar.
```

## Paso 4: Úsala y pruébala (10 minutos)

En cualquier chat de Gemini, escribe **/** seguido del nombre de la skill (Google dice que pronto cambiará a **@**) y pega el mensaje del cliente:

```
/respuestas-clientes
El cliente escribió: "¡Hola! ¿Trabajan los sábados? ¿Y cuánto es
el anticipo si reservo para diciembre?"
```

Pruébala con cinco mensajes reales (sin datos personales), incluido uno que *no* debería poder responder. Un buen resultado dice **[REVISAR]** en lugar de inventar un precio. Si adivina, agrega una línea más estricta: *"Si no estás 100 % segura, escribe [REVISAR]."*

Para cambiar las instrucciones después: **Personalizar → Skills →** haz clic en tu skill, edita y haz clic en **Guardar**.

## Lo que las skills todavía no pueden hacer

La página de ayuda de Google menciona algunos límites que conviene conocer:

- Las skills no funcionan con **Canvas** ni con **Deep Research**.
- Varias herramientas que tenían los Gems, como crear video o música, no funcionan con skills.
- Compartir una skill solo funciona en la versión web, y una skill con un cuaderno (notebook) adjunto no se puede compartir.
- No puedes activar o desactivar skills desde un chat; se hace en **Personalizar → Skills**.

## La verdad honesta

Una skill para responder te ahorra escribir. No reemplaza tu criterio. Lee cada borrador antes de enviarlo, sobre todo si trata de dinero, fechas o una queja. Las herramientas de IA pueden sonar muy seguras y aun así equivocarse, incluso con tus documentos adjuntos.

Además, este cambio nos recuerda que las herramientas cambian. Por eso tu documento de "notas de voz" vale más que cualquier app: guárdalo en tus propios archivos y podrás reconstruir tu ayudante en Gemini, en Claude o en lo que venga después en unos diez minutos.

Respondo preguntas como esta todos los días en mi comunidad gratuita, [Plugin & Progress](https://community.mainentry.net). Trae las instrucciones de tu skill y las mejoramos juntos.

## Tu única acción para hoy

Entra a gemini.google.com y revisa si tienes Gems antiguos. Si tienes, copia sus instrucciones en un documento antes del 17 de diciembre. Si no tienes ninguno, escribe tu lista de "notas de voz" del Paso 2. Ese documento es la base de cualquier ayudante de IA que vayas a crear.
