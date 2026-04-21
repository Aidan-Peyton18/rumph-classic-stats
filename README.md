# rumph-classic-stats
The Danny Rumph Classic is an annual basketball tournament held in Philadelphia to raise awareness for heart disease in athletes. A few years ago, I was asked to modernize the spreadsheet used to track player statistics throughout the tournament. The original workflow relied heavily on manual calculations, with very few formulas or automated processes. Statisticians had to compute player averages by hand after every game, which slowed down reporting and introduced opportunities for error.

When I took over, I redesigned the entire system to reduce manual work and improve accuracy. I introduced structured formulas, created a centralized Master Stats sheet, and built automated calculations that update in real time. This allowed tournament staff to instantly see leaders in points, rebounds, assists, shooting efficiency, and other key metrics.

To take the system further, I developed a Google Apps Script that runs after every edit. The script extracts data from each game sheet, aggregates player statistics, calculates per‑game averages and shooting percentages, and writes the results directly into the Master Stats tab. Each team also has its own roster page, where player stats are pulled dynamically using VLOOKUPs to ensure consistency across the entire workbook.

The result is a fully automated, reliable, and scalable stat‑tracking system that significantly reduces manual entry time and improves the accuracy of tournament reporting.
