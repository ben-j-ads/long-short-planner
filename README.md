# Long and Short Planner

One flow from budget to plan. Enter your media budget, your market share, an estimate of competitors' media spend and three facts about the category, and get the brand and activation split, your share of voice, the share you should gain or lose, and the budget needed to hold or grow share.

Open `index.html` in any browser. No build step and no dependencies.

- **Split:** the 60/40 long-and-short rule, shifted 10 points each by purchase cycle, brand size and price tier, kept between 30% and 85% brand (same rules as the 60/40 splitter).
- **Share:** share of voice = your spend / (your spend + competitors'), ESOV = SOV minus market share, predicted share change = 0.05 x ESOV a year (same rule as the ESOV explorer).
- **Also shows:** the budget to hold share (share x others / (1 - share)), the budget to grow 1 point a year (ESOV of 20 points), and a table of what changes if competitor spend is a third higher or lower.
- **Verdict:** `budget grows share`, `budget holds share` or `budget loses share`, with the same plus or minus 2 point maintain band as the ESOV explorer.
- **Share:** a paper-ground PNG card, and the URL hash carries your numbers.

Cross-category averages from the IPA Databank. Smaller brands and new launches typically need more excess share of voice. Competitor spend is an estimate, and the table shows how far the answer moves if it is wrong.

## License

Code is MIT licensed ([LICENSE](LICENSE)). The bundled fonts (Bricolage Grotesque, Archivo) are SIL OFL 1.1, with licenses in `fonts/`. The ben.j.ads wordmark and footnote mark in `logo/` are Ben Johnston's brand assets and are not covered by the MIT license.
