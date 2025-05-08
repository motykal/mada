# Emergency Medical Trivia – 60 Multiple‑Choice Questions 🇮🇱

This repository contains a ready‑to‑import trivia bank for EMT/First‑Responder training apps.

## Files

| File | Format | Notes |
|------|--------|-------|
| **`emergency_trivia_60_full.csv`** | UTF‑8‑BOM CSV | 6 columns: `Question, A, B, C, D, Correct` |
| **`emergency_trivia_60_full.json`** | JSON array | Same structure in JSON |
| **`emergency_trivia_60_full.xlsx`** | Excel (`.xlsx`) | Single sheet **Questions** |
| **`emergency_trivia_60_full.pdf`** | PDF | Human‑readable table (60 Qs) |

All files are encoded in UTF‑8 so Hebrew text is preserved.

## Column definitions

| Column | Description |
|--------|-------------|
| `Question` | Full scenario or direct question |
| `A`‑`D` | Four answer options (Hebrew) |
| `Correct` | Letter of the right option (`A`/`B`/`C`/`D`) |

## Quick preview

```markdown
| Question                                                                                                         | A                 | B                                               | C                   | D                            | Correct   |
|:-----------------------------------------------------------------------------------------------------------------|:------------------|:------------------------------------------------|:--------------------|:-----------------------------|:----------|
| בעת שימוש במסכת חמצן עם שקית העשרה (Non‑Rebreather) במטופל מבוגר, מהו טווח זרימת החמצן המומלץ לקבלת 90–100 % O₂? | 2 ליטר/דקה        | 4 ליטר/דקה                                      | 10–15 ליטר/דקה      | 20 ליטר/דקה                  | C         |
| לאחר שה‑AED סיפק שוק למטופל מחוסר דופק, איזו פעולה יש לבצע מיד?                                                  | בדיקת דופק מיידית | חידוש עיסויי חזה למשך כשתי דקות לפני הערכה מחדש | שתי הנשמות ואז דופק | השמת מנתב אוויר ובדיקת נשימה | B         |
| מיכל חמצן 20 ל׳ בלחץ 750 PSI, זרימה 10 LPM. לכמה דקות יספיק החמצן?                                               | ≈ 40 דק׳          | ≈ 60 דק׳                                        | ≈ 100 דק׳           | ≈ 200 דק׳                    | C         |
| ילד בן 6 ללא דופק ונשימה, שני מטפלים מבצעים החייאה. מה יחס העיסויים‑הנשמות?                                      | 30 : 2            | 15 : 2                                          | 5 : 1               | 3 : 1                        | B         |
| תינוק בן 9 חודשים, מטפל יחיד מבצע החייאה. איזה יחס עיסויים‑הנשמות יש לבצע?                                       | 15 : 2            | 30 : 2                                          | 2 : 30              | 3 : 1                        | B         |
```

## How to use

1. **Clone / download** this repo:
   ```bash
   git clone https://github.com/your‑org/emergency‑trivia.git
   ```
2. **Import** the `CSV` or `Excel` file into Lovebole / Base44:
   - Lovebole ➜ *Data ➜ Import ➜ Upload CSV/Excel ➜ Map columns exactly as above*.
   - Base44 ➜ *Datasets ➜ New ➜ Upload*.

If your platform doesn’t detect Hebrew correctly, make sure to choose **UTF‑8** (or simply use the Excel file).

## License

CC‑BY 4.0 – Feel free to adapt, share and improve. Please credit the original author.
