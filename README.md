# Meesho CoD Trust Analysis

## The Question
Meesho has 75–88% Cash on Delivery orders.
Prepaid success rate is 97%. CoD success rate is 77%.
**Why do customers choose the less reliable option?**

## The Finding
CoD is not a payment preference.
It is rational self-protection by customers who lost money
to prepaid failures and received no resolution.

> *"maine is pr trust Kiya online payment karke...
> hamara payment aur trust dono hi gaye"*
> — Real Meesho customer review

## Data Sources
| Source | What it provided |
|--------|-----------------|
| Meesho Pre-Filed DRHP · SEBI | CoD %, success rates, platform outages |
| Redseer Industry Report 2025 | Customer profile, UPI transaction data |
| Google Play Store · Self-scraped | 133,300 reviews · Oct 2025 – May 2026 |

## Key Numbers
- **23,149** negative reviews analysed
- **23.5%** mention financial issues — 2nd highest complaint category
- **480** reviews cite fraud specifically alongside payment or refund failure
- **20 point gap** between prepaid and CoD success rate — unchanged in 4 years

## Visuals
[Gap Chart](<img width="2126" height="1260" alt="visual1_gap_chart" src="https://github.com/user-attachments/assets/7b9b9fb7-d4a2-4a56-9d92-8c9f1b58c589" />
)
[Keyword Chart](<img width="2142" height="1440" alt="visual2_keywordchart" src="https://github.com/user-attachments/assets/74c1f26f-8c1e-4df3-bb19-67c8ba5d7d47" />
)
[Escalation](<img width="3150" height="6445" alt="visual3_chain_reaction" src="https://github.com/user-attachments/assets/12682e19-216d-4db5-a034-3d4b8874c980" />
)

## Files
- `meesho_scrape2.ipynb` — Full scraping and analysis code
- `visual1_gap_chart.png` — Prepaid vs CoD success rate gap
- `visual2_keyword_chart.png` — What 23,149 negative reviews are saying
- `visual3_doom_loop.png` — Six step escalation from payment failure to CoD dependency

## Tools Used
Python · google-play-scraper · pandas · datetime

## Author
Vishal Yadav | BS Data Science · IIT Madras
LinkedIn:-https://www.linkedin.com/in/vizz-yadav/
