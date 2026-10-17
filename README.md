# A Little World of Us — Dreamy Photo Book

A free, static, mobile-friendly birthday photo book. No framework, backend, database, or paid service is required.

## 1. Personalize it
1. Open `index.html` in a code editor (VS Code is a good free option).
2. Search for `const memories = [` and replace the sample titles and notes with your own words.
3. Add 5–8 photos to the `photos` folder named `photo-1.jpg`, `photo-2.jpg`, ... `photo-8.jpg`.
   - If you have fewer than 8 photos, either duplicate a photo temporarily or remove extra entries from the `memories` array.
   - JPG, PNG, and WebP can work, but if you change the extension, also change the matching `image` path in the array.
4. Search for `const personalLetter =` and write your own ending letter.
5. Optional music: add an audio file you are allowed to use at `music/our-song.mp3`. The site won't autoplay it; she clicks the music button.

## 2. Preview locally
Double-click `index.html` to open it in your browser. Test the cover, next/previous buttons, last page, ending letter, and music. Test on a phone too.

## 3. Publish free with GitHub Pages
1. Create a GitHub repository. For privacy of the source, you may choose a private repo, but check the current GitHub Pages plan/support before relying on that; public pages should be treated as accessible to anyone with the URL.
2. Upload `index.html`, the `photos` folder, and the `music` folder (if used).
3. In repository Settings → Pages, choose the deployment source/branch as GitHub Pages instructs, then wait for the published URL.
4. Open the URL on your phone using mobile data, not only your own Wi-Fi, to verify the live version.
5. Remember: a public URL is not real access control. Avoid uploading intimate/private images or sensitive information.

## 4. Birthday-in-24-hours checklist
- [ ] Choose 5–8 photos with different moods/memories.
- [ ] Write a specific 2–4 sentence note for each one.
- [ ] Personalize the ending letter.
- [ ] Test on mobile and desktop.
- [ ] Verify every photo and audio file loads from the hosted URL.
- [ ] Send the link with a short personal birthday message.

## Notes
- This is a starter template. It includes sample copy; replace it before gifting so the website sounds like you.
- The page-turn animation is a lightweight CSS effect on desktop and a softer transition on mobile. A full simulated book-flip library can be added later, but this keeps the build fast and reliable.
