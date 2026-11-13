# Changelog

Each version in English, then in Spanish. *Cada versión en inglés y luego en español.*

## 0.3.11 · 2026-11-13

**EN**
- **Who reveals first.** Your panel now says who reveals first this round, "Reveal: you" or
  "Reveal: rival", beside the combat direction: the game's own sign can end up under a panel.
- **The combat direction is easier to read.** It moved from the header to the row of the hearts,
  with its word: "Combat" and the arrow.
- **Counters at the side.** A new option in the tray's menu puts both panels' counters in a column
  beside the cards instead of under them: the panel is a row shorter and a little wider.
- **No hand counter.** The game already shows both hands, so the footer is down to five counters:
  deck, destroyed, spells cast, discarded and created.
- **Lists open upwards again.** With a panel at the top of the screen, hovering a counter opened
  its list downwards, away from the panel. It now opens over the cards, from the footer up.

**ES**
- **Quién revela primero.** Tu panel ahora dice quién revela primero esta ronda, "Revela: tú" o
  "Revela: rival", al lado de la dirección del combate: el cartel del juego puede quedar debajo
  de un panel.
- **La dirección del combate se lee mejor.** Pasó del encabezado a la fila de los corazones, con
  su palabra: "Combate" y la flecha.
- **Contadores al costado.** Una opción nueva en el menú de la bandeja pone los contadores de los
  dos paneles en una columna al lado de las cartas en vez de debajo: el panel queda una fila más
  bajo y un poco más ancho.
- **Sin contador de la mano.** El juego ya muestra las dos manos, así que el footer queda en cinco
  contadores: mazo, destruidas, hechizos lanzados, descartadas y creadas.
- **Las listas vuelven a abrirse hacia arriba.** Con un panel en lo alto de la pantalla, pasar el
  cursor por un contador abría su lista hacia abajo, fuera del panel. Ahora se abre sobre las
  cartas, desde el footer hacia arriba.

## 0.3.10 · 2026-11-12

**EN**
- **Discarded cards have their own counter.** A card sent from the hand to the graveyard without
  being played used to count as destroyed or as a spell cast. The footer now counts discards apart,
  and hovering yours lists them; the opponent's are a number only. In your deck, a discarded card
  has an amber edge.
- **Discards in the dashboard.** A match shows how many cards each side discarded and which of
  yours, in matches played from this version on.
- **Your panel can be moved.** Drag it by its header, as the opponent's: it stays where you leave
  it, and the tray's "Your panel" menu puts it back at its edge.

**ES**
- **Las cartas descartadas tienen su propio contador.** Una carta que iba de la mano al cementerio
  sin jugarse contaba como destruida o como hechizo lanzado. Ahora el footer cuenta los descartes
  aparte, y al pasar el cursor por el tuyo las lista; del rival solo el número. En tu mazo, una
  carta descartada lleva el borde ámbar.
- **Descartes en el dashboard.** Una partida muestra cuántas cartas descartó cada lado y cuáles de
  las tuyas, en las partidas jugadas desde esta versión.
- **Tu panel se puede mover.** Arrástralo por su encabezado, como el del rival: se queda donde lo
  dejes, y el menú "Tu panel" de la bandeja lo devuelve a su borde.

## 0.3.9 · 2026-11-10

**EN**
- **Cards no longer lose their names and art after a game update.** Starting after an update, Origins
  takes a few seconds to write its new card data, and a tracker opened at the same time read it half
  written: some cards showed as codes with no picture until you reopened the tracker. It now notices
  when the game has finished and reads the cards again by itself.

**ES**
- **Las cartas ya no pierden su nombre y su arte tras una actualización del juego.** Al arrancar después
  de una actualización, Origins tarda unos segundos en escribir los datos nuevos de sus cartas, y un
  tracker abierto a la vez los leía a medio escribir: algunas cartas salían como códigos y sin imagen
  hasta reabrirlo. Ahora se da cuenta de cuándo el juego terminó y vuelve a leer las cartas solo.

## 0.3.8 · 2026-11-04

**EN**
- **Community stats keep balance changes apart.** Origins can change cards without a Steam update, as
  it did with today's Dr. Frank update, so the game's version alone no longer said which cards a match
  was played with. Each shared match now says so, and origins.lytra.app/stats counts each set of
  cards on its own.
- **Boss fights are no longer kept.** Like practice and tutorial matches, they stop counting in your
  win rate, streak and decks, and the ones already kept are removed when you update. Ranked matches
  are untouched.

**ES**
- **Las estadísticas de la comunidad separan los cambios de balance.** Origins puede cambiar cartas sin
  una actualización de Steam, como hizo hoy con la de Dr. Frank, así que la versión del juego ya no
  decía con qué cartas se jugó una partida. Ahora cada partida compartida lo dice, y
  origins.lytra.app/stats cuenta cada conjunto de cartas por separado.
- **Las peleas contra jefes ya no se guardan.** Igual que las de práctica y tutorial, dejan de contar en
  tu porcentaje de victorias, tu racha y tus mazos, y las ya guardadas se borran al actualizar. Las
  ranked no cambian.

## 0.3.7 · 2026-11-03

**EN**
- **Your statistics are your real matches.** Practice and tutorial matches are no longer kept, and
  the ones already kept are removed when you update, so they no longer count in your win rate,
  streak or decks. The dashboard's filters for them are gone too. Ranked matches against bots still
  count.
- **Your decks go by their names.** The dashboard now reads your decks' names from the game's own
  files, so a deck shows the name you gave it even if you have only played it in ranked. A renamed
  deck catches up when the next match ends or the app opens.
- The overlay and the dashboard no longer mark an opponent as a bot.

**ES**
- **Tus estadísticas son tus partidas reales.** Las partidas de práctica y de tutorial ya no se
  guardan, y las ya guardadas se borran al actualizar, así que dejan de contar en tu porcentaje de
  victorias, tu racha y tus mazos. También se van los filtros del dashboard para ellas. Las ranked
  contra bots siguen contando.
- **Tus mazos con su nombre.** El dashboard ahora lee los nombres de tus mazos desde los archivos del
  propio juego, así que un mazo muestra el nombre que le pusiste aunque solo lo hayas jugado en ranked.
  Si renombras uno, se actualiza al terminar la siguiente partida o al abrir la app.
- El overlay y el dashboard ya no marcan a un rival como bot.

## 0.3.6 · 2026-11-02

**EN**
- **The overlay gets out of your way.** It now opens hidden, with only the eye at the edge of your
  screen. It comes out by itself when a match starts, and puts itself away when the match ends or
  the game closes. Hiding or folding a panel during a match still holds, and the eye still brings
  it back whenever you want.
- While the cards' art is being made, the first time or after a patch, your panel stays open to
  show the progress.
- The notice about anonymous stats now shows when your panel opens, and comes back until you answer
  it.
- In the dashboard's round by round, a tower that was healed now shows in **green** rather than red.
- A round with no cards standing as its combat began, after a board wipe for example, now shows its
  empty board rather than saying it could not be read.

**ES**
- **El overlay ya no estorba.** Ahora se abre oculto, solo con el ojo en el borde de tu pantalla. Sale
  solo cuando empieza una partida, y se guarda solo cuando termina o se cierra el juego. Ocultar o
  plegar un panel durante la partida se sigue respetando, y el ojo lo trae de vuelta cuando quieras.
- Mientras se genera el arte de las cartas, la primera vez o después de un parche, tu panel queda
  abierto para mostrar el progreso.
- El aviso de las estadísticas anónimas ahora aparece cuando se abre tu panel, y vuelve hasta que lo
  respondas.
- En la ronda a ronda del dashboard, una torre que se curó ahora sale en **verde** y no en rojo.
- Una ronda sin cartas en pie al empezar su combate, por ejemplo después de limpiar el tablero, ahora
  muestra su tablero vacío en vez de decir que no se pudo leer.

## 0.3.5 · 2026-11-02

**EN**
- **A match's cards are the game's own.** In the dashboard, a match's board and decks now draw each
  card in the game's frame, as the deck builder does.
- **Attack and health on the card.** On the round-by-round board, each card shows them on its own
  frame: **red** when below the card's own, **green** when above.
- The cards listed under the board, and the ones a match made, are larger, so you can read them.

**ES**
- **Las cartas de una partida son las del juego.** En el dashboard, el tablero y los mazos de una
  partida ahora dibujan cada carta con el marco del juego, como en el creador de mazos.
- **Ataque y vida sobre la carta.** En el tablero de la ronda a ronda, cada carta los muestra en su
  propio marco: en **rojo** si están bajo lo de la carta, en **verde** si están sobre lo de la carta.
- Las cartas que aparecen bajo el tablero, y las que generó la partida, son más grandes para que se
  puedan leer.

## 0.3.4 · 2026-11-02

**EN**
- **Each panel its own.** The tray now has **Your panel** and **Opponent's panel**, each with its
  own grid and size: yours normal and your opponent's small, four by three and six by two.
- **Move your opponent's panel** by dragging its header, for example across the top of the board.
  It stays where you leave it, your stream follows, and **Back to its place** in the tray returns
  it to its edge.
- The odds over your panel now say **Draw odds**: "Next draw" could read as the card that comes next.
- The dashboard's deck builder starts empty each time, and asks before you leave a deck you are
  building.

**ES**
- **Cada panel con lo suyo.** La bandeja ahora tiene **Tu panel** y **Panel del rival**, cada uno con
  su cuadrícula y su tamaño: el tuyo normal y el del rival pequeño, cuatro por tres y seis por dos.
- **Mueve el panel de tu rival** arrastrando su cabecera, por ejemplo sobre la parte de arriba del
  tablero. Se queda donde lo dejes, tu stream lo sigue, y **Volver a su lugar** en la bandeja lo
  devuelve a su borde.
- La probabilidad sobre tu panel ahora dice **Prob. de robo**: "Próximo robo" podía entenderse como la
  carta que viene.
- El creador de mazos del dashboard parte vacío cada vez, y pregunta antes de salir de un mazo que
  estás armando.

## 0.3.3 · 2026-11-02

**EN**
- **Community stats.** Your Ranked matches now help build public deck and card stats for
  origins.lytra.app, anonymously: your deck, the result and what your opponent showed, never a
  name, an account or the hour. The overlay tells you before anything goes, and only matches
  played after that count, never your history. In the EU, the EEA and the UK it stays off until
  you say yes.
- One click turns it off: in the tray, or on the dashboard's new **Profile** page, which also shows
  your last Ranked match exactly as it goes.
- The terms now say all this.

**ES**
- **Estadísticas de la comunidad.** Tus partidas ranked ahora ayudan a armar estadísticas públicas
  de mazos y cartas para origins.lytra.app, de forma anónima: tu mazo, el resultado y lo que mostró
  tu rival, nunca un nombre, una cuenta ni la hora. El overlay te avisa antes de enviar nada, y solo
  cuentan las partidas jugadas después, nunca tu historial. En la UE, el EEE y el Reino Unido queda
  desactivado hasta que digas que sí.
- Un clic lo desactiva: en la bandeja, o en la nueva página **Perfil** del dashboard, que además
  muestra tu última partida ranked tal como se envía.
- Las condiciones ahora dicen todo esto.

## 0.3.2 · 2026-11-01

**EN**
- The dashboard's **Card by card** draws each card in the game's own frame, as the deck
  builder does; a card never out in a match stays dimmed. Click one — there or in the deck
  above it — to open it large, with the cards it makes behind it.
- In the overlay, your opponent's cards not shown yet carry Lytra's mark, faint, in their
  dashed slots.

**ES**
- **Carta a carta** del dashboard dibuja cada carta con el marco del propio juego, como el
  creador de mazos; una carta que no salió en ninguna partida sigue apagada. Haz clic en una —
  ahí o en el mazo de arriba — para abrirla en grande, con las cartas que genera detrás.
- En el overlay, las cartas de tu rival que aún no muestra llevan la marca de Lytra, tenue, en
  sus espacios punteados.

## 0.3.1 · 2026-11-01

**EN**
- **The cards a card makes**, everywhere it shows: Legion of the Dead's Zombie, Three Not So
  Little Pigs' pigs, Van Helsing's Tools and his four tools, Three Blind Mice's Mouse… — 26
  cards, read from the game's own data. In the overlay, hovering a card shows what it makes
  beside it.
- The deck builder, in the dashboard and online: the magnifier on a card opens it large, the
  cards it makes fanned behind it — click one to bring it forward, with its own text and
  numbers —; ← and → step through the cards, Esc closes. The Art view shows the cost alone, as
  the picture it is.

**ES**
- **Las cartas que genera una carta**, en todos lados donde aparece: el Zombie de Legion of the
  Dead, los cerdos de Three Not So Little Pigs, las Tools de Van Helsing y sus cuatro
  herramientas, el Mouse de Three Blind Mice… — 26 cartas, leídas de los datos del propio
  juego. En el overlay, al pasar el ratón por una carta se ve lo que genera a su lado.
- El creador de mazos, en el dashboard y en línea: la lupa de una carta la abre en grande, con
  las cartas que genera en abanico detrás — toca una para traerla adelante, con su propio texto
  y sus números —; ← y → recorren las cartas, Esc cierra. La vista Arte muestra solo el coste,
  como la imagen que es.

## 0.3.0 · 2026-11-01

**EN**
- The deck builder draws every card in **the game's own frame**, taken from your installation:
  characters with their rounded frame and the tray for attack and health, spells with their
  cut corners, the game's cost hexagon (winged for a legendary), sword, heart and alignment
  ribbons, and the game's proportions.
- Online, at origins.lytra.app/referral: turn your referral code into a card to share. Pick a
  card, get a link and a picture; your friend copies the code into the game's Referrals tab, and
  after 5 bosses you both get a Collector Pack.

**ES**
- El creador de mazos dibuja cada carta con **el marco del propio juego**, sacado de tu
  instalación: los personajes con su marco redondeado y la bandeja para ataque y vida, los
  hechizos con sus esquinas cortadas, el hexágono del coste del juego (con alas en una
  legendaria), la espada, el corazón y las cintas de alineamiento, y las proporciones del juego.
- En línea, en origins.lytra.app/referral: convierte tu código de referido en una carta para
  compartir. Elige una carta y obtén un link y una imagen; tu amigo copia el código en la
  pestaña Referidos del juego y, tras 5 jefes, los dos reciben un sobre de coleccionista.

## 0.2.0 · 2026-10-31

**EN**
- **Language** in the tray: System, English or Español. Everything follows it — the tray's
  menu, the overlay, the dashboard and the cards' texts, which in Spanish are the game's own
  translation (its Latin American Spanish). Card names stay as the game keeps them.
- The deck builder, in the dashboard and online: a card already in your deck goes grey with a
  check; hover a card in your deck to see it large with its text; a wider deck column; new
  controls; its filters in Spanish say what the game's deck creator says.
- Online, at origins.lytra.app/decks: save your decks with a Lytra account (the same one as
  tournaments.lytra.app), share them, like them, keep favorites, and add a YouTube video of
  you playing one.

**ES**
- **Idioma** en la bandeja: Sistema, English o Español. Todo lo sigue: el menú de la bandeja,
  el overlay, el dashboard y los textos de las cartas, que en español son la traducción del
  propio juego (su español latinoamericano). Los nombres de las cartas quedan como el juego
  los deja.
- El creador de mazos, en el dashboard y en línea: una carta que ya está en tu mazo se pone
  gris con un ✓; pasa el mouse por una carta de tu mazo para verla en grande con su texto;
  una columna del mazo más ancha; controles nuevos; sus filtros en español dicen lo mismo que
  el creador de mazos del juego.
- En línea, en origins.lytra.app/decks: guarda tus mazos con una cuenta de Lytra (la misma de
  tournaments.lytra.app), compártelos, dales me gusta, ten favoritos y agrega un video de
  YouTube tuyo jugando uno.

## 0.1.0 · 2026-10-31

**EN**
- The first version of Lytra · Origins, a deck tracker for Origins TCG from the makers of
  Lytra, the tracker for MARVEL SNAP.
- An overlay beside the board: your deck on the left, with what is left in it, what you have
  drawn and played, the cards made during the match and your odds of drawing each one; your
  opponent's cards on the right as they reveal them, with how many they swapped at the
  mulligan and how many are left in their deck.
- A dashboard in your browser: every match you play while it runs, round by round, with the
  board, the lives and the towers, and your decks, each with the game's code to share it.
  Click **YOU** on the overlay, or *Open dashboard* in the tray.
- A deck builder with the game's filters, in the dashboard and online at
  origins.lytra.app/deck-builder: copy a deck's code and the game imports it.
- For your stream: the overlay as an OBS browser source, at `http://127.0.0.1:47750/obs/`.
- From now on it updates itself when it opens.

**ES**
- La primera versión de Lytra · Origins, un tracker de mazos para Origins TCG de quien hace
  Lytra, el tracker de MARVEL SNAP.
- Un overlay junto al tablero: tu mazo a la izquierda, con lo que te queda, lo que has robado
  y jugado, las cartas creadas durante la partida y la probabilidad de robar cada una; las
  cartas de tu rival a la derecha a medida que las revela, con cuántas cambió en el mulligan
  y cuántas le quedan en el mazo.
- Un dashboard en tu navegador: cada partida que juegues con la app abierta, ronda a ronda,
  con el tablero, las vidas y las torres, y tus mazos, cada uno con el código del juego para
  compartirlo. Haz clic en **YOU** en el overlay, o en *Open dashboard* en la bandeja.
- Un constructor de mazos con los filtros del juego, en el dashboard y en línea en
  origins.lytra.app/deck-builder: copia el código de un mazo y el juego lo importa.
- Para tu stream: el overlay como fuente de navegador de OBS, en
  `http://127.0.0.1:47750/obs/`.
- Desde ahora se actualiza solo al abrirse.
