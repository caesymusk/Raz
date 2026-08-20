DROP YOUR AUDIO FILES HERE
===========================

The site looks for exactly these four filenames in this folder.
Keep the site's HTML file, this "assets" folder, and everything inside it
together in the same place (e.g. all inside one project folder) — the
site links to them using a relative path, so it just needs to be next
to the HTML file, not anywhere in particular on your computer.

  ambient.mp3   /Users/caesymusk/Documents/GitHub/RAZ/assets/ambient.mp3Soft looping background pad. Plays continuously once
                the intro is dismissed. Keep this one subtle and seamless
                for looping — no hard start/end transient.

  whoosh.mp3    Short (under ~1.5s) rush/swell sound. Plays the moment
                a/Users/caesymusk/Documents/GitHub/RAZ/assets/enter.mp3 constellation opens into its solar system.

  chime.mp3     Short (under ~1s) bell/pluck/hit. Plays when a planet
                or the sun finishes zooming into close-up focus.

  enter.mp3     A deeper, more resonant one-shot (~1-2s). Plays the
                moment you step "inside" a planet.

If a file is missing, nothing breaks — that cue just stays silent until
you add it. mp3, wav, and ogg all work; just keep the filenames above
(only change the extension in SOUND_FILES near the top of the <script>
in index.html if you're not using mp3).
