<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,400;0,500;0,600;1,400;1,500&family=IBM+Plex+Mono:wght@400;500&display=swap" rel="stylesheet">

<style>
  :root {
    --ink: #14110e;
    --paper: #f4efe6;
    --rule: #c9bba8;
    --lacquer: #9c2a1b;
    --mute: #6b6258;
    --card: #fffaf3;
  }

  html { background: var(--paper); }

  body {
    background: var(--paper);
    color: var(--ink);
    font-family: "Cormorant Garamond", "Iowan Old Style", Georgia, serif;
    font-size: 20px;
    line-height: 1.55;
    max-width: 720px;
    margin: 0 auto;
    padding: 4.5rem 1.5rem 8rem;
  }

  .mast {
    border-top: 3px solid var(--ink);
    border-bottom: 1px solid var(--ink);
    padding: 1.75rem 0 1.5rem;
    margin-bottom: 2.75rem;
  }

  .kicker {
    font-family: "IBM Plex Mono", ui-monospace, monospace;
    font-size: 11px;
    letter-spacing: 0.28em;
    text-transform: uppercase;
    color: var(--lacquer);
    margin: 0 0 0.85rem;
  }

  h1 {
    font-family: "Cormorant Garamond", Georgia, serif;
    font-weight: 500;
    font-size: clamp(3.2rem, 8vw, 5.4rem);
    line-height: 0.9;
    letter-spacing: -0.03em;
    margin: 0 0 1rem;
  }

  .lede {
    font-size: 1.15rem;
    font-style: italic;
    color: var(--mute);
    max-width: 38em;
    margin: 0;
  }

  .meta {
    font-family: "IBM Plex Mono", ui-monospace, monospace;
    font-size: 11px;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    color: var(--ink);
    margin: 1.4rem 0 0;
  }

  hr {
    border: 0;
    border-top: 1px solid var(--rule);
    margin: 3.2rem 0;
  }

  h2 {
    font-weight: 500;
    font-size: 1.85rem;
    letter-spacing: -0.02em;
    margin: 0 0 0.35rem;
  }

  .room {
    font-family: "IBM Plex Mono", ui-monospace, monospace;
    font-size: 11px;
    letter-spacing: 0.22em;
    text-transform: uppercase;
    color: var(--lacquer);
    margin: 0 0 0.4rem;
  }

  .room-note {
    font-style: italic;
    color: var(--mute);
    margin: 0 0 2rem;
    font-size: 1.05rem;
  }

  .brief {
    background: var(--card);
    border: 1px solid var(--rule);
    padding: 1.35rem 1.4rem 1.2rem;
    margin: 0 0 1.15rem;
  }

  .num {
    font-family: "IBM Plex Mono", ui-monospace, monospace;
    font-size: 11px;
    letter-spacing: 0.18em;
    color: var(--lacquer);
    margin: 0 0 0.65rem;
  }

  .brief p {
    margin: 0 0 0.85rem;
    font-size: 1.02rem;
  }

  .brief p:last-child { margin-bottom: 0; }

  .colophon {
    font-family: "IBM Plex Mono", ui-monospace, monospace;
    font-size: 11px;
    letter-spacing: 0.08em;
    color: var(--mute);
    line-height: 1.7;
  }

  @media (prefers-color-scheme: dark) {
    :root {
      --ink: #efe8dc;
      --paper: #161310;
      --rule: #3a342c;
      --lacquer: #e07a62;
      --mute: #a79b8c;
      --card: #1e1a16;
    }
  }
</style>

<div class="mast">

<p class="kicker">Capability suite · fifty briefs · one file out</p>

# Fifty Vague Briefs

<p class="lede">A set of messy, human asks for testing whether a model can actually make something. Not a spec sheet. Not a checklist. Just the kind of request a person would mutter if they wanted a whole little world dumped into a single standalone html file.</p>

<p class="meta">10 rooms · 5 briefs each · always one file · always Go all out.</p>

</div>

These are written the way people actually brief things. A little foggy, a little specific, always sensory. Each one is meant to push past the default demo: the bouncing circle, the spinning cube, the three pie charts, the two second beep. If the model is paying attention, the result should feel authored. If it is not, the result will look like homework.

Every brief already contains the only hard constraint that matters. The whole thing lives in one standalone html file. No extra assets. No excuses. The last two words are always the same.

---

<p class="room">Room 01 · Living ink</p>

## Animated SVGs

<p class="room-note">If it can be drawn with vectors, it should feel like it has a pulse. Morphing, weather, machinery, light leaking through paper. Not a logo spin.</p>

<div class="brief">

<p class="num">01 / 50</p>

<p>Okay so I keep seeing this tram window at night, rain dragging the city into long wet streaks, and the neon signs outside are not just sitting there, they are breathing and melting into each other like the letters cannot decide what language they want to be. There is a faint passenger reflection in the glass and a ticket stub stuck in the corner and every so often another tram ghost-slides past in the opposite direction. I want the whole scene as living animated SVG, every drip and flicker drawn, and I want it sitting in a single standalone html file so I can just open it and stare. Go all out.</p>

</div>

<div class="brief">

<p class="num">02 / 50</p>

<p>Make me a pocket watch that has gotten ideas above its station. When it opens, the gears do not stay polite, they unspool into this ridiculous exploded view, springs stretching like they are showing off, jewels catching light, roman numerals drifting out of orbit and then getting embarrassed and clicking back into place. It should feel expensive and a little unhinged, brass and enamel, the kind of object a Victorian engineer would build if they had been up for three days. Put the entire mechanism in one standalone html file as animated SVG, no images, just paths that know how to move. Go all out.</p>

</div>

<div class="brief">

<p class="num">03 / 50</p>

<p>I want a flower that should not exist. It starts as a wet seed in dark soil and then it grows too fast, petals unfolding in this slightly wrong order, leaves veining themselves while you watch, pollen lifting off like tiny lanterns. The colors keep changing their mind, like the plant is trying on different centuries. When it finally opens you realize the center is a small architectural floor plan, a greenhouse remembered from a dream. Animate the whole botanical lie in SVG, looping so the death is as pretty as the birth, and drop it into a single standalone html file. Go all out.</p>

</div>

<div class="brief">

<p class="num">04 / 50</p>

<p>Imagine you are looking down into black water and there is a choir of jellyfish down there, not cute, more like lanterns that learned ballet. Their bells pulse out of sync on purpose, trails of light writing cursive that almost becomes words and then forgets. A slower, older one drifts across the foreground and the whole page should feel deep, like the html itself has pressure. I want this as animated SVG with the kind of gradients and glow that make people lean closer to the screen, all of it in one standalone html file. Go all out.</p>

</div>

<div class="brief">

<p class="num">05 / 50</p>

<p>Do that thing where a Japanese ink landscape is still wet. Mountains are just a few honest strokes, a bridge, a tiny figure with an umbrella, and then the season cheats. Mist becomes cherry weather becomes a hard winter lake becomes gold-leaf autumn, and the same composition keeps being rewritten by the ink itself. Birds are commas. The moon is a pause. I do not want a slideshow of four pictures, I want one drawing that cannot stop becoming the next one. Animated SVG, single standalone html file, the kind of piece you leave open on a second monitor like a window. Go all out.</p>

</div>

---

<p class="room">Room 02 · Glass worlds</p>

## Three.js

<p class="room-note">A real scene. Light that has to travel. A camera that has somewhere to be. If it looks like a rotating cube in a void, the brief has been ignored.</p>

<div class="brief">

<p class="num">06 / 50</p>

<p>I want to drift through an abandoned space station that still thinks someone is coming back. The lights are mostly dead except for a few that buzz on a delay, condensation on the inside of a cupola, a plant that has taken over the hydroponics bay and gone feral in slow motion. You should be able to look around, maybe push off a bulkhead, hear that thick quiet. Outside the glass there is a planet that is too close and a sun that keeps lens-flaring across the HUD of whoever used to live here. Build it in Three.js, the whole station in a single standalone html file, and make it feel like a place you could get lost in for longer than you meant to. Go all out.</p>

</div>

<div class="brief">

<p class="num">07 / 50</p>

<p>Okay picture a cobblestone alley at three in the morning after rain. Everything is wet enough to be a mirror. There is a bakery sign that still works, a cat that might be a shadow, steam from a grate, and one window on the third floor with a lamp on like somebody could not sleep. I want to walk it, or at least mouse around it, with puddles that actually reflect and neon that actually bleeds. Three.js, moody as a photograph that was taken by accident, all packed into one standalone html file so the alley exists by itself. Go all out.</p>

</div>

<div class="brief">

<p class="num">08 / 50</p>

<p>Make a tiny museum that only contains glass. Not vases in a row, I mean sculptures that look like someone froze a conversation, caustics crawling across the floor, a skylight doing too much work, dust in the beams. You wander with the camera like you are being polite in a gallery you snuck into after hours. When you get close to a piece the light inside it wakes up a little, as if the glass is flattered. Three.js, serious lighting, the kind of scene that makes a graphics person squint and say wait. One standalone html file. Go all out.</p>

</div>

<div class="brief">

<p class="num">09 / 50</p>

<p>I keep wanting a planet I can hold. Not Earth with the usual texture, a made-up one, oceans in a color that does not exist yet, a single city glowing on the night side, weather sliding around if you spin it. Clouds should have weight. If you leave it alone a storm gathers just to have something to do. Maybe a tiny moon on a leash. It should feel like a desk toy for a tired god. Three.js in a single standalone html file, and I want the lighting to make the sphere feel like a real object sitting in a dark room with you. Go all out.</p>

</div>

<div class="brief">

<p class="num">10 / 50</p>

<p>A vinyl shop that grew out of a dream and refused to become a real floorplan. Records float, sleeves drift past like slow fish, and if you click one it tilts toward you and the room takes on that album's color temperature. There is a listening booth that is just a cone of warmer light. Dust, wood grain, a cat on the counter if you can manage a cat. I want to poke around in Three.js until I find a record I would actually want to own, even though none of them are real. Whole shop in one standalone html file. Go all out.</p>

</div>

---

<p class="room">Room 03 · Tiny universes</p>

## Pixel art

<p class="room-note">Limited palette, honest pixels, a scene that is alive even if nobody is playing. Dithering, idle loops, light that flickers like a cheap tube.</p>

<div class="brief">

<p class="num">11 / 50</p>

<p>Make me a one-room cyberpunk apartment at night and then just let it live. Rain on the window in fat pixels, a CRT in the corner chewing static, a cat that occupies the only clean patch of bed, noodles going cold on the desk, a fan that does that slightly broken wobble. The city outside should feel taller than the screen. I want a real pixel palette, no blurry fake pixels, little loops everywhere so the room never quite holds still. Put the whole apartment in a single standalone html file, maybe with a couple of things you can click just to prove you were paying attention. Go all out.</p>

</div>

<div class="brief">

<p class="num">12 / 50</p>

<p>There is an 8-bit temple that the jungle ate and I want to watch the day happen to it. Morning is all gold through broken roofs, noon is violent and green, dusk brings lanterns that nobody lit, night is eyes in the trees. Vines should tick forward a pixel at a time. A fox priest or something equally unofficial keeps doing a patrol that is not quite a game. Limited colors, chunky tiles, the kind of scene that looks like a lost SNES title screen that accidentally became a place. One standalone html file. Go all out.</p>

</div>

<div class="brief">

<p class="num">13 / 50</p>

<p>A diner at two in the morning, pixel art, American and a little haunted. The waitress has a walk cycle that is too human. The jukebox is trying. Neon from the parking lot keeps rewriting the color of the pie. One customer who has been there since the previous decade, coffee cup never empty, rain doing that cheap movie thing against the glass. I want to feel the linoleum. If there is a tiny game inside it, fine, but the room itself is the point, looping forever in a single standalone html file like a place the internet forgot to close. Go all out.</p>

</div>

<div class="brief">

<p class="num">14 / 50</p>

<p>Okay I want the inside of a small research submarine, all gauges and rivets and a viewport that is mostly darkness until a fish the size of a bus decides to be curious. Pixel art, cramped, a little claustrophobic in a cozy way. Dials should actually twitch. A sonar sweep that you start watching like it is television. Condensation pixels. Somebody's mug magneted to a pipe. The whole craft lives in one standalone html file and if you click things they should confess that they work. Go all out.</p>

</div>

<div class="brief">

<p class="num">15 / 50</p>

<p>A rooftop garden on a building that is too tall, pixel art, laundry and tomatoes and a telescope and three airships arguing in the distance. The smog below is a second ocean. Wind should move flags in that cheap satisfying way. There is a kid watering plants and an old person reading a newspaper that is probably from a city that does not exist anymore. Day slides into a purple evening without making a fuss. I want this as a living pixel diorama in a single standalone html file, the sort of thing you screenshot and then keep open anyway. Go all out.</p>

</div>

---

<p class="room">Room 04 · Heard things</p>

## Music and song

<p class="room-note">Original audio, Web Audio or whatever the file can carry, at least thirty seconds of something that is actually a piece of music. A visualizer without a song is a shrug.</p>

<div class="brief">

<p class="num">16 / 50</p>

<p>Write me a late night song that sounds like the kitchen light was left on. Soft drums that know they are guests, a bassline walking around in socks, keys that keep almost becoming a melody and then deciding not to embarrass anyone. It has to play for at least thirty seconds, preferably longer, with a beginning that sneaks in and an ending that does not just die. I want to hear it the moment I open the file, and I want something on screen that belongs to the music, not a leftover audio bar. Original composition, single standalone html file, no streaming, no excuses about samples. Go all out.</p>

</div>

<div class="brief">

<p class="num">17 / 50</p>

<p>I need a chase. Synthwave, but not the poster version, the sweaty version, the one where the arpeggio is a little too fast and the drums are arguing with the bass about who is driving. Give it a real structure, intro that feels like headlights, a middle that refuses to calm down, a last stretch that goes brighter instead of bigger. At least thirty seconds, longer if you have the nerve, and the picture should move with it like a title sequence that forgot the title. All original, all generated in the page, one standalone html file. Go all out.</p>

</div>

<div class="brief">

<p class="num">18 / 50</p>

<p>Make a sad piece that does not announce it is sad. It starts with a piano that is sitting in a room with bad heating, then something like strings arrives as if they were always in the hallway, and by the time a minute has passed you realize it has become a small orchestral thing built out of oscillators that learned manners. I want dynamics, not a looped four bars with a filter. Minimum thirty seconds, a shape you can hum later, and a visual that feels like weather over an empty city. Single standalone html file, press nothing, it just begins. Go all out.</p>

</div>

<div class="brief">

<p class="num">19 / 50</p>

<p>Give me jungle. Breaks that are chopped like somebody is late for a train, a bass that lives in the floor, little stabs of atmosphere, a vocal chop that is not a real lyric so much as a ghost of one. It should run at least thirty seconds and actually change, drops and all, not a screensaver of the same bar. I want the screen to feel like a pirate radio that found a way into the browser, maybe some fictional station chrome, maybe just light that pulses like it is guilty. Original track inside one standalone html file. Go all out.</p>

</div>

<div class="brief">

<p class="num">20 / 50</p>

<p>Start it like a sea shanty, voices made of synths that are pretending they have lungs, a squeeze-box that is probably just oscillators in a coat, and then let the thing mutate. By the thirty second mark it should have become something modern and a little wrong, like the sailors got wifi. I still want a tune you could slam a glass to. Make the page feel like a pub that is slowly turning into a club without anyone admitting it. Whole song generated in a single standalone html file, no licensed anything, and do not fade out like you got bored. Go all out.</p>

</div>

---

<p class="room">Room 05 · The long take</p>

## Cinematic storytelling games

<p class="room-note">You play it. Atmosphere does half the talking. Choices should stain the room. This is not a slideshow with a next button wearing a costume.</p>

<div class="brief">

<p class="num">21 / 50</p>

<p>You are the last person still answering the radio in a city that decided to become a river. The game should feel like a film that was shot through wet glass, all long quiet and then a voice that should not still be on the other end. I want to click around a dim studio, twist dials, choose what I say, and have the city outside change its mind about the weather based on whether I was kind. Keep it short but complete, a night's work, cinematic in the lighting and the sound and the way text arrives. One standalone html file, a whole little movie you can fail at. Go all out.</p>

</div>

<div class="brief">

<p class="num">22 / 50</p>

<p>I am hitchhiking across a desert that is not convinced it is a desert. Sometimes the sand is parking lot. Sometimes a motel appears that has been waiting with the vacancy sign already on. You meet drivers who talk like they have been in the car for years. The whole thing should play like a road movie that got lost in someone else's dream, choices that seem small and then rewrite the color of the sky. I want a camera, I want music, I want the feeling of heat. Build the entire game as a single standalone html file so it can be sent like a postcard. Go all out.</p>

</div>

<div class="brief">

<p class="num">23 / 50</p>

<p>There is a hotel where every floor is a different decade and the elevator is a moral decision. You arrive with a key that does not match your memory of your face. Staff are polite in a way that suggests they have buried worse guests than you. I want to wander, open drawers, overhear things, pick a floor, and have the story lean in like a camera. Make it cinematic, grain and all, with enough interactivity that it is clearly a game and not a comic. The whole hotel in one standalone html file. Go all out.</p>

</div>

<div class="brief">

<p class="num">24 / 50</p>

<p>You keep a lighthouse. The sea has been rehearsing something. Each night you log the weather, you decide whether to keep the lamp honest, and sometimes there are knocks that are not weather. I want the game to look like it was photographed on tired film, interiors the color of tea, windows that are mostly a reason to be afraid of beauty. Played in a single sitting, choices that change what comes ashore, sound that does a lot of the acting. One standalone html file, no engine, just the night. Go all out.</p>

</div>

<div class="brief">

<p class="num">25 / 50</p>

<p>You sit down on a night train across from a younger version of yourself who is not in the mood. The windows show a country that keeps skipping like a record. The conversation is the game, but the carriage should still exist, luggage racks, bad coffee, a conductor who knows both of you and is pretending not to. I want branching talk that actually goes somewhere, cinematic framing, a sense that the train will arrive whether you are ready or not. Pack the entire encounter into a single standalone html file. Go all out.</p>

</div>

---

<p class="room">Room 06 · The boardroom</p>

## Corporate financial dashboards

<p class="room-note">Dense on purpose. A company with a personality. Numbers that look like they would get someone fired if they were wrong. This is not three charts and a navy header.</p>

<div class="brief">

<p class="num">26 / 50</p>

<p>Build the Q3 war room for a Fortune 500 that makes everything and is slightly ashamed of how well that is going. I want a dashboard a CFO would actually squint at, revenue versus the story they told the street, regional heat, a margin that is doing something politically inconvenient, a ticker of analyst notes that sound expensive. Dark, dense, the lighting of a room that has not seen morning. Micro-interactions when you hover a number like the number might confess. Invent the company, invent the tension, put the whole executive surface in one standalone html file. Go all out.</p>

</div>

<div class="brief">

<p class="num">27 / 50</p>

<p>A family office dashboard for people who do not say how much they have. Quiet luxury, paper-colored, type that looks like it was chosen by someone who collects watches. Portfolio across quiet companies, vineyards, a shipping stake, a fund that is only a letter, and a risk panel that is polite until you open it. I want it to feel like wealth with manners, still extremely full of data, maps, performance, a calendar of boards they sit on. One standalone html file that could be mistaken for an internal tool if you did not look too long at the company names. Go all out.</p>

</div>

<div class="brief">

<p class="num">28 / 50</p>

<p>Make me a foreign exchange floor that got compressed into a screen. Pairs twitching, a world map that is really a mood ring for liquidity, a central bank calendar, a blotter, something that looks live even though we both know it is theater. The aesthetic should be late trading, not a fintech startup, more CRT ghosts and good type than gradients. I want to feel slightly underqualified looking at it. All of it in a single standalone html file, dense enough that a real trader would at least lean in before calling the bluff. Go all out.</p>

</div>

<div class="brief">

<p class="num">29 / 50</p>

<p>This conglomerate owns four fashion houses, a distillery, a hotel chain nobody admits is a hotel chain, and a cosmetics line that prints money. I want the group dashboard the board sees before lunch in Milan, beautiful in a ruthless way, each maison with its own pulse, wholesale versus boutique, a China number that everyone is pretending is fine, a creative calendar next to an inventory aging chart because art still has to ship. Make it look expensive and a little bored. Single standalone html file. Go all out.</p>

</div>

<div class="brief">

<p class="num">30 / 50</p>

<p>An energy major that is trying to look like the future without putting down the past. Split screen kind of soul, barrels and wind, a map of assets that could start an argument, emissions that are presented too calmly, a projects pipeline with dates that have slipped and everyone knows. I want operational density, not a sustainability brochure. Alerts, a crude strip, a renewables capacity curve that is climbing just fast enough to be a press release. The whole corporate cockpit in one standalone html file, as if it were running on a wall in Houston at 6:40 in the morning. Go all out.</p>

</div>

---

<p class="room">Room 07 · Time on purpose</p>

## Motion graphics

<p class="room-note">A sequence with a clock. Easing that was chosen. Cuts. Holds. A piece that could have been an opener if someone had billed a studio for it.</p>

<div class="brief">

<p class="num">31 / 50</p>

<p>I want a title sequence for a prestige show that does not exist, something about a city that keeps inheriting the same crime. Type should arrive like it has been subpoenaed. You get glimpses of rooms, a river, a coat on a chair, none of it explained, all of it timed. Twenty or thirty seconds that play themselves, with a last card that makes you believe the series already won awards. Build the whole motion piece in a single standalone html file so it runs like a commercial the moment you open it, replayable, no editor, no After Effects, just the browser pretending it went to film school. Go all out.</p>

</div>

<div class="brief">

<p class="num">32 / 50</p>

<p>Launch a phone that is fictional and slightly too beautiful. I want the motion graphics package, the one that starts in a void, finds a silhouette, lets light travel across brushed whatever, type that is almost arrogant, a feature montage that lasts only as long as a breath, then a name that feels like it cost a million dollars to kern. It should play as a timed film, not a webpage that waits for you to scroll. One standalone html file, cinema in a tab, and do not make it look like every other gadget keynote. Go all out.</p>

</div>

<div class="brief">

<p class="num">33 / 50</p>

<p>Do a sports ident, Olympic-adjacent energy without copying anyone's rings. Bodies suggested by light, a stadium that is mostly atmosphere, a network mark that slams into place like it has been waiting all year. I want whooshes that are tasteful, which is a paradox I am handing you on purpose, and a clock, a city name, a fictional games year. The whole thing should run as a self-playing motion piece in one standalone html file, the kind of ident that makes you sit up even though you do not care about the sport. Go all out.</p>

</div>

<div class="brief">

<p class="num">34 / 50</p>

<p>Fashion week opener. A house that is invented, a season that is invented, type that walks like it has opinions about your shoes. I want strobes of fabric, a runway reduced to a single white line, credits for a creative director who is probably a ghost, music if you can manage it, and timing that feels expensive. It plays, it does not sit there hoping you hover. Pack the entire motion film into a single standalone html file and make it look like the agency got paid and then stayed late anyway. Go all out.</p>

</div>

<div class="brief">

<p class="num">35 / 50</p>

<p>Breaking news package for a network that takes itself extremely seriously. The world is ending in a tasteful lower third. I want the stings, the globe, the red that is not default red, a presenter desk that exists for four seconds, a map that slams, type that has been trained. It should feel like you accidentally opened a broadcast, complete with a looping bed of urgency underneath. All of it motion-timed in one standalone html file, replay from the top, no YouTube, just the panic and the polish. Go all out.</p>

</div>

---

<p class="room">Room 08 · Math as paint</p>

## Generative shaders

<p class="room-note">The picture is computed. Full page. Mouse as a weather system. If it could have been a CSS gradient, it is not finished.</p>

<div class="brief">

<p class="num">36 / 50</p>

<p>I want oil paint that never dries, the whole page, thick enough that you can almost hear it. Color should shove other color out of the way. If I move the mouse I am stirring a studio floor. Sometimes a face tries to happen and then the paint gets shy. This has to be a real shader situation, generative, living, not a video and not a slideshow of pretty noise. Drop the entire canvas into a single standalone html file so the painting is the only object in the world. Go all out.</p>

</div>

<div class="brief">

<p class="num">37 / 50</p>

<p>Make a portal that is obviously made of math and still feels like a bad idea to touch. Rings of something that might be light, a center that is too deep, little errors in the geometry that look like the universe coughing. I want to lean the view with the mouse and have the thing react like it noticed. Full viewport, hypnotic without becoming a screensaver from 1998. One standalone html file, shader to the edges, the kind of tab you open and then forget to close because it is doing a better job of being a window than the actual window. Go all out.</p>

</div>

<div class="brief">

<p class="num">38 / 50</p>

<p>Fill the browser with underwater caustics until the room you are sitting in feels incorrectly dry. Light should crawl across an imaginary pool floor, wobble, gather, break. Maybe there is a suggestion of tiles. Maybe a shadow of something larger than it should be. I want the shader to be the experience, slow and expensive looking, mouse making the sun tilt. All of it in a single standalone html file, no photographs, just computed water doing overtime. Go all out.</p>

</div>

<div class="brief">

<p class="num">39 / 50</p>

<p>Show me a city through heat. Infrared, heat haze, rooftops breathing, a river that is a different temperature than the story, windows as little fevers. It should still read as architecture, not just a rainbow lookup table dumped on noise. Moving the pointer is like lifting a thermal camera. I want a generative shader world that feels documentary and alien at the same time, packed into one standalone html file you could leave on a wall. Go all out.</p>

</div>

<div class="brief">

<p class="num">40 / 50</p>

<p>A nebula that is in no hurry. Slow gas, slow stars being implied rather than drawn as clipart, color that has not been named. If I drag through it I am being rude to weather on a scale I do not deserve. I want depth, filaments, the sense that the math would keep going if I walked away for a year. Fullscreen generative shader, single standalone html file, quiet and enormous. Go all out.</p>

</div>

---

<p class="room">Room 09 · Things that fall</p>

## Physics playgrounds

<p class="room-note">Gravity is not a metaphor. Objects collide, stack, topple, sing. You are allowed to mess with the world and the world has to notice.</p>

<div class="brief">

<p class="num">41 / 50</p>

<p>Build a Rube Goldberg machine that actually completes a stupidly small task, like ringing a bell or dropping a single olive into a glass, and I want to be able to restart it and poke it mid-run so it fails in new ways. Dominos, a fan, a balloon, a marble, something on fire if you can fake fire without being boring. It should feel handmade, a little too tall for the page, with the physics doing honest work. The entire contraption lives in one standalone html file. Go all out.</p>

</div>

<div class="brief">

<p class="num">42 / 50</p>

<p>I want cloth. A huge flag in a weather you can change, or a curtain you can yank, or a tablecloth that learns about a cat. Wind sliders, grab the fabric, let it drape over a chair that is also in the scene. It should look a little too pretty for a physics demo, late afternoon light, the kind of thing a technical artist would keep tweaking. Pack the playground into a single standalone html file so I can pull on the world like it owes me money. Go all out.</p>

</div>

<div class="brief">

<p class="num">43 / 50</p>

<p>A marble run that was designed by someone who used to build cathedrals. Tracks that are architecture, stained glass light if you can spare it, forks that are decisions, a bottom that is a brass bell. I want to drop marbles, maybe too many, and watch the machine cope. Physics has to be real enough that stacking and collisions are the entertainment. Make it beautiful enough to screenshot and chaotic enough to replay. One standalone html file. Go all out.</p>

</div>

<div class="brief">

<p class="num">44 / 50</p>

<p>There is a sandcastle, or maybe a small brick town, and I am allowed to ruin it. Click, drag, wind, a single disrespectful wave. I want crumbling that feels good, debris that keeps being debris, the tiny tragedy of a tower you just watched someone else build. After the collapse there should still be a place, a beach, a sky that does not care. Physics playground as melancholy toy, all in one standalone html file. Go all out.</p>

</div>

<div class="brief">

<p class="num">45 / 50</p>

<p>Newton's cradle, except it is also an instrument. The balls do the honest physics, and each impact is a note, and if you add balls or change lengths you are accidentally writing a piece of music. I want it to look like a desk object that escaped from a university and started performing. Chrome, wood, late light, a little UI that does not look like a tutorial. The whole instrument-toy in a single standalone html file, satisfying to knock around for much longer than is reasonable. Go all out.</p>

</div>

---

<p class="room">Room 10 · Words that move</p>

## Kinetic type and editorial

<p class="room-note">Letterforms are the actors. Layout with a point of view. This is a magazine, a credits sequence, a campaign, not a blog template in a trench coat.</p>

<div class="brief">

<p class="num">46 / 50</p>

<p>Make a magazine cover that cannot stay a cover. You open the file and it is already a issue of something called, I do not know, a journal for people who miss cities at night. Then the masthead starts walking, a headline becomes a hallway, a pull quote turns into a room you can scroll. I want editorial type, weird crop, paper grain, one photograph that is not a photograph so much as a lighting cue. The whole issue-as-experience in a single standalone html file, beautiful enough that a designer gets quiet. Go all out.</p>

</div>

<div class="brief">

<p class="num">47 / 50</p>

<p>There is a poem and it typesets itself while you descend. Not line by line like a typewriter gag, more like the page is thinking, words finding their measure, a stanza becoming architecture, a refrain coming back in a heavier cut. I want the kind of kinetic typography that would have been a physical installation if somebody had the budget. Invent the poem, make it good, let the motion be the reading. One standalone html file, no chrome, just language learning how to occupy a rectangle. Go all out.</p>

</div>

<div class="brief">

<p class="num">48 / 50</p>

<p>Film credits you can wander. Names of a made-up crew who all sound like they existed, job titles that get more specific than they need to, a director who is probably the weather. The sequence should move with that long rolling gravity, but I also want to drift sideways and find a gaffer hiding, a best boy, an animal wrangler for a cat that never appears. Make it cinematic and typographic and a little playful without becoming a joke. Entire credits world in one standalone html file. Go all out.</p>

</div>

<div class="brief">

<p class="num">49 / 50</p>

<p>A perfume campaign that is allergic to product shots. Light, type, a color that is trying to be a scent, a name that feels like a last name and a season. I want the page to breathe, letters fogging, a bottle suggested by a highlight and then denied. Luxury without the usual serif-on-black laziness, something stranger, like the art director had been looking at fogged windows in Lisbon. The whole campaign in a single standalone html file, timed and still, both. Go all out.</p>

</div>

<div class="brief">

<p class="num">50 / 50</p>

<p>Start as a newspaper, columns, a date, a city, a headline about something small and true. Then the paper loses its manners. Columns shear, a weather report becomes a manifesto, classifieds start confessing, the masthead molts into a poster. I want to watch print design have a nervous breakthrough, still readable, still designed, never a pile of random animations. Kinetic editorial, the last brief, all of it in one standalone html file that feels like it was composed rather than generated. Go all out.</p>

</div>

---

<p class="colophon">
Fifty Vague Briefs · 10 rooms · 5 each<br>
Every ask ends the same way on purpose.<br>
The only deliverable is a single standalone html file.
</p>
