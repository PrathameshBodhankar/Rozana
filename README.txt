ROZANA – LAUNCH FOLDER

GO LIVE (Cloudflare Pages, no GitHub needed)
1. Sign up at dash.cloudflare.com (free).
2. Workers & Pages > Create > Pages > "Upload assets". Name the project "rozana".
3. Drag this whole folder in and click Deploy. You get a rozana.pages.dev link.
4. Custom domains > add your domain (e.g. rozana.in). If the domain was bought
   elsewhere, change its nameservers to the two Cloudflare gives you. HTTPS is automatic.
5. Replace hello@YOUR-DOMAIN.in in about.html and privacy.html with your email.

ADDING A DAILY PAPER
- Each day is one file: papers/YYYY-MM-DD.json (date in IST).
- Copy an existing file, change "paper", "date" and the questions.
- "ans" is the index of the right option: 0=A, 1=B, 2=C, 3=D.
- The site picks today's file automatically at midnight IST.
  If no file exists for today it shows papers/sample.json.
- You can upload a week of papers in advance. Each one appears on its own date.
- Upload the folder again (step 3) after adding papers.

ADS
- Apply for AdSense once you have 2–3 weeks of papers.
- After approval paste Google's script tag where index.html says "AdSense",
  and put Google's line into ads.txt.
