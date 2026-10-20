# Jordan Bones & Stones Clinic — عيادة العظام والحصى الأردنية

Website of the Hazem Bilbeisi Endocrine Clinic (عيادة الدكتور حازم البلبيسي للغدد الصم), Basma Medical Complex, Amman.

Static site for GitHub Pages:

- `index.html` — the whole site (Arabic, RTL), including the World Osteoporosis Day article tab (`#wod`)
- `news.json` — news posts; edit this file to add or remove news
- `assets/logo.png` — combined clinic logo

## Adding a news post

Edit `news.json` on GitHub (pencil icon) and add an entry at the top:

```json
{
  "id": "unique-id",
  "date": "2026-11-20",
  "title": "العنوان",
  "body": "النص",
  "link": "#wod",
  "linkText": "اقرأ المزيد"
}
```

`link` and `linkText` are optional. Posts are sorted by date automatically. Commit, and the site updates within a minute or two.

## Publishing

Settings → Pages → Source: *Deploy from a branch* → `main` / `(root)`.
