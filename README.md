# রাবিনা AI 🌸 — Personal Assistant

তোমার পার্সোনাল AI অ্যাসিস্ট্যান্ট — পড়াশোনা, প্রশ্ন-উত্তর, লেখালেখি, কোড আর দৈনন্দিন সব কাজে সাহায্য করে।

- 🇧🇩 বাংলা-ফার্স্ট চ্যাট (ইংরেজিতেও উত্তর দেয়)
- 🎙️ ভয়েস ইনপুট + ভয়েস আউটপুট
- 🆓 কোনো API key লাগে না — ফ্রি, keyless সার্ভার
- 🔄 Multi-server failover — একটা সার্ভার down হলেও চ্যাট থামে না
- 📲 ফোনে ইন্সটল করা যায় (PWA)

## Live
Deploy on Vercel — `index.html` serves at root.

## Tech
Single-file `index.html`. AI engines (client-side fetch, all keyless):
1. OVHcloud AI Endpoints (OpenAI-compatible, 4 rotating models)
2. Pollinations `/openai`
3. Pollinations legacy GET
4. AI Horde (async crowd GPU, last resort)
