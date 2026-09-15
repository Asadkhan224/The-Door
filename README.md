# The Door ❤️

Ek chhota romantic interactive website — name enter karne par special surprise video chalti hai.

## Files
- `index.html` — pura website (HTML + CSS + JS ek hi file me)
- `Asad.mp4` — surprise video (jab special name detect ho)

## Kaise kaam karta hai
1. User apna naam likhta hai.
2. Agar naam me `sehar / sahar / saher / sher / shar / shr / seher / sehri / saira` in me se koi bhi lafz aaye (shuru me, beech me, ya akela) — to romantic message ke sath `Asad.mp4` khud-ba-khud chalne ki koshish karta hai, aur ek bada "▶ Play Video" button bhi dikhta hai (kyunke browsers kabhi kabhi auto-play block kar dete hain, ye button manually chala deta hai).

## GitHub par upload kaise karein

### Option A — Website se (sabse aasan, bina terminal ke)
1. https://github.com par jayein aur naya repository banayein (e.g. `the-door`).
2. Us repo page par "Add file" -> "Upload files" par click karein.
3. Is folder ki files (`index.html`, `Asad.mp4`) ko drag-drop karein.
4. "Commit changes" dabayein.
5. Agar chahein to website live dekhne ke liye: repo Settings -> Pages -> Branch = `main` -> Save. Kuch second baad `https://<username>.github.io/<repo-name>/` par live ho jayegi.

### Option B — Terminal se (git installed hona chahiye)
```bash
cd path/to/The-Door-main
git init
git add .
git commit -m "Door website"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```
