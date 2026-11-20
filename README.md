# Happy Birthday Shyama 💗

A personalized, mobile-friendly birthday experience for Shyama, with a midnight rose-and-lavender theme, animated hero, virtual cake, candle wish reveal, confetti, music controls, and a guestbook. The special cake message is from Pawan.

## Run locally on Android (Termux)

1. Install Termux from F-Droid: https://f-droid.org/packages/com.termux/
2. Put `birthday-shyama.zip` in your phone's Downloads folder and extract it, or extract it with your file manager.
3. In Termux run:

```bash
pkg update -y
pkg install nodejs-lts -y
termux-setup-storage
cd ~/storage/downloads/birthday-main
npm install
npm run dev -- --host 127.0.0.1
```

4. Open Chrome on the same phone and visit `http://localhost:5173`. Keep Termux running while viewing the site.

If you extracted the folder somewhere else, change the `cd` path to that folder.

## Desktop

```bash
npm install
npm run dev
```

Then open the local URL printed by Vite.
