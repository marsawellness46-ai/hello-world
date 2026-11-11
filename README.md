Build a single-page Arabic (RTL) web app called "LOVE YOURSELF" about expressing feelings through clothing.

Flow:
1. Short intro in warm Egyptian Arabic: "فيه كلام صعب يتقال… خلّي هدومك تقوله".
2. Step 1: user picks who the message is for: نفسي / أمي / أبويا / صاحبي / حد بحبه.
3. Step 2: user picks the feeling: امتنان / اعتذار / فخر / طمأنة / اشتياق / تشجيع.
4. Step 3 (optional): one sentence about the situation, free text.
5. Using Gemini, generate 3 options. Each option has: a short t-shirt phrase (max 8 words, not a cliché, real and specific), the idea behind it in one sentence, and a personal gift-card message of 3-4 lines. Return them as structured JSON and render them as cards.
6. Each card has buttons: "اختار ده" and "جيب غيره". Choosing shows a preview of the phrase on a t-shirt mockup plus the card.
7. Email capture: "سيب إيميلك أو رقمك ونبلغك لما التصميم ينزل" with a simple form (stored in local state, with CSV export).

Tone rules for the AI: Egyptian colloquial Arabic, warm, no preaching, no clichés, no medical or therapy claims.
Design: soft warm palette (cream, terracotta, deep green), rounded cards, mobile-first, Cairo or Tajawal font.# hello-world
This repository is for practicing the GitHub Flow."
