# Portfolio Project Setup

*A documentation of my setup process, written by 
someone who had never used GitHub before.*

---

## Tools Installed

- **Cursor IDE** — Downloaded from https://cursor.com/ but could not be opened 
  due to macOS version incompatibility on my machine.
- **Claude Code** — This is an extension inside Cursor. Could not be installed 
  because Cursor was unable to run on my system.
- **Codex** — Also an extension inside Cursor. Could not be installed for the 
  same reason.
- **GitHub** — Created an account and repository at https://github.com/
- **Replit** — Used as a browser-based alternative to Cursor. Connected to this 
  GitHub repository at https://replit.com/@aisyaracelly/Portfolio-Project
- **Supadata** — Used as a web-based API tool to collect YouTube transcripts 
  via API at https://supadata.ai/


---

## Steps Completed

1. Downloaded and attempted to install Cursor IDE
2. Created a GitHub account at github.com
3. Created this public repository (portfolio-project)
4. Created and edited this README.md using GitHub's browser editor (github.dev)
5. Committed and pushed this README to GitHub
6. Signed up for Replit and imported this GitHub repository as an alternative 
   development environment
7. Updated this README
8. Identified 10 LinkedIn experts and collected their recent posts manually
9. Attempted to build a YouTube transcript API script via Replit — hit a 
   technical limitation (YouTube blocks cloud server requests)
10. Used Supadata API to successfully collect YouTube transcripts via API
11. Added additional YouTube creators to enrich the research
12. Committed and pushed regularly throughout the process
13. Research all of the contents and trends to find pattern, disagreement, and my own ideas to create the playbook
14. Build the playbook here and put the sources inside
15. Committed and push the process

---

## Issues I Ran Into & How I Fixed Them

### Cursor IDE, Claude Code & Codex — Mac Compatibility Issue

**Issue:** After downloading Cursor, turns out my Mac is too old to run it. 
Which also meant I couldn't install Claude Code and Codex since those live 
inside Cursor.

**What I did:** I first looked into whether I could still pull this off without 
downloading anything. Watched a GitHub beginner playlist but it didn't really 
cover my situation. So I turned to Claude for help and since 
this was literally my first time using GitHub, I asked 
it to walk me through everything step by step all 
the way to committing this README.

For the editor, I used GitHub's built-in browser editor (github.dev) instead of 
Cursor.

I also connected this repository to Replit (https://replit.com) as a 
browser-based alternative to Cursor for future development. I can 
write and run code directly from the browser without needing a local IDE and 
it already has AI built in, similar to how Cursor works with Claude Code.


### YouTube Transcript API — Cloud Server Restriction

**Issue:** I built a working Python script in Replit using the YouTube Transcript 
API to automatically fetch transcripts. However, YouTube blocks requests coming 
from cloud servers like Replit. Their IPs are blocked to prevent automated 
scraping at scale. The script itself was correct and functional, just unable to 
run in a cloud environment.

**What I did:** I used Supadata (supadata.ai). By pasting YouTube video URLs into Supadata's 
Playground, I was able to fetch transcripts via API without needing a local 
development environment. This achieved the same outcome, API-based content 
collection, through a legitimate alternative tool.

### Note on Claude Code and Codex

The original instruction intended for Claude Code or Codex to handle the entire API workflow automatically: 
writing the code, running it, calling the API, and saving results directly into the repo files in one step. 
Because Cursor wasn't compatible with my Mac, I couldn't use this automated 
workflow. Instead, I replicated the same outcome manually: using Supadata's 
web-based API to fetch YouTube transcripts and saving them into the correct repo 
folders myself. The end result is the same: content collected via API, organized 
in the repo, just without the automation layer that Claude Code would have provided.

---

## Research: LinkedIn Organic Content Strategy for B2B SaaS

### Why I chose this topic
LinkedIn organic content strategy is a topic I have direct experience with from 
my B2B marketing background. I understand some of the audience who are skeptical professionals 
who don't respond to generic content, and I have some instincts about what works 
and what doesn't. This made it the strongest choice for building a research-backed 
playbook later.

### How I approached the research

I started by identifying 10 active **LinkedIn authors** as my primary sources. 
The reasoning: since my topic is LinkedIn organic content strategy, 
LinkedIn authors are the most direct and credible reference. They're actively 
practicing what they post about on the platform itself. A YouTube creator who 
talks about LinkedIn can still be active on LinkedIn, but I personally think the primary source still should be LinkedIn because that's the proof of concept. 

From there, I looked for YouTube videos from the same experts. But not all of 
them had relevant YouTube content. Some are LinkedIn-first creators who rarely 
post on YouTube. So I added additional YouTube creators who cover LinkedIn 
strategy, B2B marketing, and content-led growth to enrich the research further.

In hindsight, I could have looked for 10 experts who had strong presence on both 
platforms. But I stand by the decision to prioritize LinkedIn authors. At the 
end of the day, the playbook is about LinkedIn and the people practicing it on 
LinkedIn daily are the strongest signal of what actually works.

### Collection method

**LinkedIn posts** — Look for the 10 experts using Claude and visit the profiles one by one to see whether the profile is a perfect match. Then manually collected the posts by filtering by posts and selecting 3-5 recent teaching posts per expert. Manual collection was the right call here: LinkedIn's API is heavily restricted and 
doesn't allow pulling personal post content at scale. More importantly, manual 
selection meant I was curating quality over quantity, choosing posts that were 
genuinely useful rather than just scraping everything.

**YouTube transcripts** — Initially attempted to automate this using a Python 
script built in Replit with the YouTube Transcript API. Hit a technical wall 
when YouTube blocked requests from cloud server IPs. Pivoted to Supadata 
(supadata.ai) to fetch transcripts directly from YouTube URLs. This worked well and achieved the goal of API-based collection.

### What I collected

- 10 LinkedIn experts with 3-5 posts each → `/research/linkedin-posts/`
- YouTube transcripts from 10 creators → `/research/youtube-transcripts/`
- Full source list with annotations → `/research/sources.md`

### Why these experts

Each person was chosen for a specific reason,
either because of what they practice, what they teach, or what their content 
style demonstrates. Here's the thinking behind each one:

---

**1. Pierre Herubel**
Pierre is one of the clearest examples of someone who built a real business 
purely through LinkedIn content. He went from $0 to $1M in agency revenue in 
14 months with just content. What makes him particularly 
valuable for this research is that he doesn't just teach LinkedIn strategy 
theoretically. He built his own proof of concept first, then turned that into 
a framework he now teaches to 600+ B2B brands. His posts cover content 
positioning, content ecosystems, and B2B buyer behavior in a way that is 
immediately applicable to building a playbook. His YouTube channel adds an 
extra layer especially his 2026 video on team-led content, which argues that 
single-founder personal brands are no longer enough and that coordinated 
multi-voice content is the real winning strategy now.

**2. Lara Acosta**
Lara is one of the fastest growing LinkedIn creators with 300K+ followers, and 
she built that audience while simultaneously running multiple businesses. What 
sets her apart from most LinkedIn coaches is that she teaches from lived 
experience rather than observation. Her frameworks: the SLAY framework, the 
4-3-2-1 system, and the IFP vs ICP distinction, are specific, repeatable, and 
designed for people who want to use LinkedIn to actually generate revenue. 
She's also one of the few creators who openly talks about the 
LinkedIn algorithm changes and what they mean for content strategy in 2026, 
which makes her research both current and actionable.

**3. Richard van der Blom**
Richard is a data-driven voice in the LinkedIn space. Every year he 
publishes an Algorithm Report based on millions of analyzed posts and in 2026 
that report covers 2.5M+ posts. While most LinkedIn advice is based on 
observation and personal experience, Richard backs his recommendations with 
actual numbers. His research on metrics that matter (DM conversations vs 
impressions), the TOFU/MOFU/BOFU framework for LinkedIn, and the performance gap 
between different content types gives this research a factual foundation that 
the other sources can't provide on their own. For a playbook to be credible, it 
needs data and Richard is where that data comes from.

**4. Amanda Natividad**
Amanda's angle is different from the others. As VP Marketing at SparkToro, she 
thinks about content from a distribution and demand generation perspective rather 
than a personal brand perspective. Her zero-click marketing framework, the idea 
that most searches now end without a click anywhere and that brands need to 
build recognition before the visit rather than just optimize for traffic, is 
directly relevant to LinkedIn organic strategy. LinkedIn is inherently a 
zero-click platform. People consume content without ever leaving the feed. Amanda 
helps explain why that's actually an opportunity rather than a limitation and 
her thinking on building a brand that people and machines recognize by name is 
useful for shaping the positioning layer of the playbook.

**5. Katelyn Bourgoin**
Katelyn's value is in buyer psychology. Known as the "Customer Whisperer," she 
specializes in understanding why buyers make decisions and she translates that 
into content strategy in a way that most LinkedIn coaches don't. Her 8-tier proof 
framework is a perfect example: most B2B content stays at the lowest tiers of 
credibility (borrowed proof, self-reported results) when the content that actually 
converts buyers sits at the higher tiers (demonstrated results, trusted 
endorsements). Her Joshua Bell analogy about how world-class expertise becomes 
invisible without the right packaging is one of the most useful frameworks in 
this entire research for understanding why good content sometimes fails to land. 
For a LinkedIn playbook targeting B2B buyers, understanding buyer psychology is essential.

**6. Ross Simmonds**
Ross was included for two reasons. First, he generated over $2M in direct revenue 
from LinkedIn which makes him a legitimate practitioner, not just a teacher. 
Second, his "create once, distribute forever" philosophy adds a dimension that 
most LinkedIn-focused creators don't cover: distribution strategy. Most LinkedIn 
advice stops at "post good content." Ross thinks about where content goes after 
it's published, how to get it in front of the right people, and how to build 
systems that compound over time. His posts on B2B content distribution and his 
thinking on how AI is changing content discovery add a strategic layer to the 
research that goes beyond just LinkedIn tactics. His posts were also studied for 
their structure and posting style. He's a strong example of data-backed B2B 
content done well.

**7. Tim Soulo**
Tim was included as a live case study rather than a strategy teacher. As CMO of 
Ahrefs, one of the most respected B2B SaaS brands in the world, his LinkedIn 
presence shows what consistent, data-backed, product-led content looks like in 
practice. He doesn't post about LinkedIn strategy. He posts about SEO, AI search, 
and Ahrefs research. But the way he does it, grounding every post in original 
data, tying product features to market trends, and writing in a way that educates 
without being generic, is an education in B2B SaaS LinkedIn content. His 
posts were studied for tone, structure, and the relationship between content and 
product positioning rather than for explicit strategy advice.

**8. Devin Reed**
Devin is one of the most directly relevant experts on this list. He actively 
posts about LinkedIn content strategy, the creator economy, and how B2B content 
connects to pipeline and he does it from the perspective of someone who has 
both built content strategies for major B2B SaaS companies and grown his own 
LinkedIn presence significantly. His post on LinkedIn's new Creator Marketplace, 
his frameworks for different post types (Save This, Trend-Spotter, Scar Tissue, 
Bold POV), and his data on why company LinkedIn pages matter for deal conversion 
all feed directly into the playbook. He's also one of the few people who talks 
openly about using AI in his content process without pretending to write 
everything from scratch which is a more honest and useful perspective for 
anyone building a scalable content system.

**9. Jasmin Alić**
Jasmin is the most LinkedIn-native expert on this list. He built 360K+ followers 
by being deeply, consistently present on the platform. Spending hours daily in 
comments, giving away advice for free, and refusing shortcuts like engagement 
pods or automation. What makes him valuable for this research is that he 
challenges a lot of conventional LinkedIn wisdom from a place of real experience. 
His post on breaking LinkedIn "rules" is a useful counterbalance to the more formulaic advice 
from other experts. A playbook needs voices that push back 
on the received wisdom, and Jasmin provides that. His community building approach 
also adds a dimension that pure content strategy advice often misses.

**10. Ruben Hassid**
Ruben was included specifically to study high-performing LinkedIn content 
structure rather than topic. With 500K+ followers, his posts about AI tools 
consistently generate massive engagement and the reason is 
the format. Short punchy sentences, strong numbered lists, clear hooks, specific 
CTAs. His content is a live example of what structurally effective LinkedIn posts 
look like at scale. Studying his posts alongside the more strategy-focused experts 
helps bridge the gap between knowing what to say and knowing how to say it
which is ultimately what a content playbook needs to answer.

---

### Why additional YouTube creators were added

Not all of the primary LinkedIn authors had relevant YouTube content. Rather than 
leaving the YouTube transcripts folder empty and not full, additional creators were brought in 
who cover LinkedIn strategy, B2B marketing, and content-led growth from different 
angles:

- **Michelle J Raymond** her entire 
  channel is dedicated to LinkedIn strategy for B2B, covering company pages, 
  employee advocacy, algorithm changes, and content frameworks without hacks or 
  shortcuts. Her channel description says it best: "B2B Growth. No hacks. Strategy 
  over shortcuts."

- **Diandra Escobar and Tommy Clark** both cover content-led growth on LinkedIn 
  with a personal brand angle. While not strictly B2B focused, their frameworks 
  on building audience, creating consistent content, and converting followers into 
  clients are transferable to B2B LinkedIn strategy.

- **Angelique Rewers** covers B2B marketing broadly. Her angle on selling to 
  corporate clients and understanding enterprise buyer behavior adds useful context 
  for the B2B side of the playbook.

- **Chris Prouty** covers LinkedIn alongside other social platforms. His tactical 
  approach to profile optimization and lead generation on LinkedIn provides 
  additional practical reference points.

- **Mark Firth** covers LinkedIn strategy broadly including content. A useful 
  supplementary reference for understanding LinkedIn growth tactics from a 
  practitioner's perspective.

---

## What I Learned

I came into this knowing nothing about GitHub, APIs, or developer tools. Going 
through this process taught me what a repository is, how version control works, 
how to commit and push files, and how APIs work in practice including what 
happens when they don't work and how to find alternatives.

More than that, I learned that not having the "right" tools doesn't have to stop 
you. There's almost always a workaround if you're willing to look for one and 
documenting that process clearly is just as valuable as getting it perfect the 
first time.

---

*Built with GitHub + Replit + Supadata | github.com/aisyaracelly*
