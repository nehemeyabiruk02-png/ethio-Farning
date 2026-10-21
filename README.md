# Ethiopia Everyday

Free tools for daily life in Ethiopia, in English and Amharic (አማርኛ). One static page, no build step, no tracking.

- Live Ethiopian date and clock (13 months, 6-hour clock offset)
- Ethiopian and Gregorian date converter
- Monthly salary, income tax and pension estimate (Proclamation 1395/2025 bands)
- Equb planner with payout dates and a copyable schedule
- Upcoming holidays
- Emergency numbers: police 991, ambulance 907, fire 939, traffic police 945

## Put it online with GitHub Pages

1. Create a new repository on GitHub (for example `ethiopia-everyday`), public.
2. Upload every file in this folder, including the hidden `.github` folder, or push with git:
   ```
   git init
   git add .
   git commit -m "First version"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/ethiopia-everyday.git
   git push -u origin main
   ```
3. In the repository open **Settings > Pages**. Under **Build and deployment**, set **Source** to **GitHub Actions**.
4. Open the **Actions** tab and wait for "Deploy to GitHub Pages" to turn green (about a minute).
5. Your site is at `https://YOUR-USERNAME.github.io/ethiopia-everyday/`.

Every later push to `main` updates the live site.

## Edit

Everything is in `index.html`. Text in both languages is in the `T` object in the script. Tax bands are in `BANDS`.

## Notes

Tax and pension figures are estimates. Check them against official sources before relying on them.
