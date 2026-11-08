# Mind Reel

Mind Reel is a personal app for practicing rapid image cycling, a technique developed by William Bengston and known as Image Cycling®. To learn the method from the source, visit [bengstonresearch.com](https://bengstonresearch.com/).

## What it does

- **Watch them flash.** Add a picture or a short phrase for each goal. The app plays them in order for as long as you choose.
- **Practice in your head.** Six levels show you fewer pictures each time, until you can run the whole list with your eyes closed. An order check lets you test yourself.
- **More than one list.** Keep separate lists, such as business goals and personal goals, and switch between them.
- **Session notes.** After a session, jot down what came up. Notes are saved with the date, the session type, and the list.
- **Backup reminder.** If you haven't saved a backup in 7 days, the app reminds you. A backup file holds every list, your pictures, your notes, and your progress.

## Safety

- A flashing warning appears the first time the app opens.
- The top speed is 3 pictures per second unless you unlock faster speeds and confirm a warning. Faster speeds are never turned on from a backup file.
- If Reduce Motion is on for your device, the top speed is 1 picture per second.
- Text cards use dark colors only, so nothing bright flashes.

## Privacy

Your pictures, lists, and notes stay in your browser on your device. Nothing is uploaded. The fonts are stored inside the app. There is no tracking.

## Running it

This is a plain static site with no build step. Serve the folder over HTTP, or host it on GitHub Pages. When you change the app, update `VERSION` in `sw.js` so installed copies load the new files.

## Credits and license

Mind Reel is built from [Flipbook Mind](https://github.com/kostas564/flipbook-mind) by kostas564, which is shared under the MIT License. That license is in [LICENSE](LICENSE) and still applies to the code.

The fonts, Calistoga and Poppins, are shared under the SIL Open Font License 1.1. See the `fonts/` folder.

This is a personal, unofficial project. William Bengston, Bengston Research, and L & B Consulting, Inc. did not make it and do not endorse it. "Image Cycling" and "The Bengston Energy Healing Method" are registered trademarks of L & B Consulting, Inc. Nothing here is medical advice.
