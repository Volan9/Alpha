# Demo prompts

Use these prompts to try the assistants in The Alpha Family.

## Alpha

Add [Alpha_Instructions.md](Alpha_Instructions.md) to your AI project. In the chat, ask the assistant to follow the file and then try this prompt.

**Prompt:** Yesterday's API load reported success, but bookings for one property dropped to zero in today's Power BI report. Where should I start?

**Example response:** Start with **Rio**. Check whether yesterday's raw API data contains bookings for that property. A successful run tells you the pipeline finished. The raw records can show whether the property was included.

**Brief for Rio:** Compare the affected property's raw booking records for yesterday's load and the most recent load that showed bookings. Share the property ID, load dates, record counts and any relevant API errors or pagination gaps.

If the raw records are present, ask **Newt** to check whether the property ID was mapped correctly and the records reached the curated table. If the curated records are present, ask **Argon** to check the report's filters and booking measure.
