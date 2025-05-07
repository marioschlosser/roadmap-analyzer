# roadmap-analyzer
Compares different versions of a Google Sheet and asks an LLM to summarize. Great for roadmap tracking.

Give it a Google Sheet ID (copy and paste from the sheet's URL), a worksheet name from that sheet, and a number of days to look in the past.
The Colab will find the sheet's revision closest to the date in the past.
It will send the current sheet and the past sheet to Gemini and ask it to compare.

Excellent to compare the state of roadmaps in Google Sheet over time.
