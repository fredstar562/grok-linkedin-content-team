# Install Prompt

Upload this whole repo (the ZIP) to your primary Grok Bot, then paste everything below the line.

---

You are going to install a LinkedIn content team for me from the files I just uploaded. Read every file first: README.md, every file in bots/, every file in context/, and rules/linkedin-content-rules.md.

Then do these steps in order. Show me the result of each step and wait for my OK before the next one. Never publish anything to LinkedIn.

**Step 1: Interview me.** Ask me these one at a time:
1. My name, company, website and what I sell
2. Who my ideal customer is
3. My real results and proof (only these numbers can ever appear in posts)
4. My LinkedIn profile URL
5. 10 to 20 LinkedIn creators in my niche whose posts go viral
6. My 5 to 10 best posts (or scrape them from my profile)
7. Words I never want used
8. My brand colours, fonts and logo, plus 2 to 3 creatives I like (or "use a clean default")
9. Slack or Telegram for approvals
10. How often I want to post, and which scheduler I use (or none)

**Step 2: Create the folder.** In my Google Drive, create a folder called "Content Team" with these subfolders: context, rules, research, ideas, drafts, creatives, approved, rejected, stats. Copy the context/ templates and rules/ file in. Fill every context file with my answers. For voice.md, analyse my best posts. For top-posts.csv, ask for my Apify API token and scrape my last 90 days of posts.

**Step 3: Create the 5 Bots.** Use the Name, Job and Description in each file in bots/. Give every Bot access to the Content Team folder.

**Step 4: Group chat.** Put all 5 Bots in one group chat and pin this: "Order: Researcher → Ideator → Copywriter → Designer → Publisher. Each Bot does only its own job and hands off to the next. Read context/ and rules/ before every task. Nothing is published or scheduled without the owner's APPROVE."

**Step 5: Approvals.** Connect my approval channel. For Slack, create #content-approvals. For Telegram, walk me through @BotFather, then store the bot token and my chat ID. Send a test message and confirm you can read my reply.

**Step 6: Test.** Run the full team once with 2 posts and send them to my approval channel. Ask me what to change, then update the Bots.

**Step 7: Routines.** Only when I say "Turn on the routines", set:
- Researcher: Mondays 7am
- Ideator: Mondays 9am
- Copywriter: Mondays 1pm
- Designer: Tuesdays 8am
- Publisher: Tuesdays 10am
- Researcher (stats): Fridays 4pm
