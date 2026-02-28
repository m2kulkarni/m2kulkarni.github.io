---
layout: post
title: "India's AI Infrastructure — Part 1: Compute"
subtitle: "Understanding where India stands in the AI race — and why the next few years matter more than we think."
date: 2026-02-28
---

I've been spending a lot of time lately thinking about India's position in the AI race, in terms of model capabilities, but also in terms of the physical infrastructure underneath it all. This blogpost is my attempt to understand the current landscape. Its less about what India lacks or the issues, but to put numbers to where we stand, what's being built, and what it means.

I have broken down this into three parts.

First, Compute — I've been hearing about new AI datacenter buildouts in India and also the recent tax break. I wanted to understand this in detail. particularly, what capabilities we have right now, what is planned and what are the implications.

Second, Energy — I wanted to put a number to the energy capabilities, both AI-specific and otherwise. How much of the energy infra is coal, solar, wind etc and who are the key players.

Third, Model Capabilities — India for sure needs to keep on developing its model capabilities. Here i will talk about model companies in India, their bets and what I would like to see happen in the ecosystem.

My goal is to understand the geopolitical and practical implications behind all of this. The world is in a brittle place, and understanding specific policies will give us a better idea on how to navigate this uncertainty ahead.

This blogpost is also not about what capabilities AI models will have in the near future, nor their implications on the economy. For that, I'd point to a few sources. Note that all these sources are super bullish about progress in AI capabilities, and you may choose to believe otherwise. Personally, I am very scale-pilled and have chosen to write everything under this assumption. Rich Sutton's [The Bitter Lesson](http://www.incompleteideas.net/IncIdeas/BitterLesson.html) is worth reading if you want to understand why.

1. [AI 2027](https://ai-2027.com/)
2. [Dario Amodei — Machines of Loving Grace](https://darioamodei.com/machines-of-loving-grace)
3. [Leopold Aschenbrenner — Situational Awareness](https://situational-awareness.ai/)

This is bigger than the industrial revolution, and every nation and individual needs to tread this path carefully. Throughout this essay I will focus on US and China as the main players (competitors if you like) in this race and what it probably means for India.

## Compute

When i say datacenter compute, i mean total capacity — AI and non-AI combined.

### How much AI compute does India actually have today?

India has roughly 1.5 GW of total datacenter capacity. There are no specific figures for GPU compute within this, but estimates place it around 200–400 MW. For perspective, the United States has over 50 GW and China has around 30 GW. India thus represents about 3% of US datacenter capacity.

Zooming into AI specifically, India has an estimated 80,000 GPUs across public and private infrastructure. Meta — a single company, albeit a large one — has about 1 million. Meta's infrastructure spending this year alone exceeds the combined near-term datacenter investment of every Indian company put together.

I think we need to internalize what these numbers mean for India's future. With the recent Sarvam release, there's a growing idea that India can "leapfrog" in AI by building great models, and fostering startups. All of this matters, but none of it matters if we don't have the physical infrastructure, or are dependent on other nation-state, to run AI at scale.

Models are truly important, and I'll talk about this in Part 3. But they are essentially software, and open-source has been about 3–6 months behind frontier. Assuming this gap continues to hold, its very likely that the real bottleneck will be the machines you run them on. These machines require huge buildings, gigawatts of power, millions of litres of water for cooling, and years to build. These are as essential as power plants. As Mark Carney puts it, if you're not at the table, you're on the menu. We can't rent our intelligence from someone else, atleast not for long.

All of this might sound gloomy, but things are moving. Datacenter investment has been growing, and its growing rapidly. India announced more than $277B in AI investment commitments at the 2026 AI Impact Summit. That's huge. The IndiaAI mission has deployed over 38,000 GPUs at heavily subsidized rates, averaging about ₹65–116 per GPU-hour versus Rs 330 on AWS.

The recent 2026 budget introduced a tax holiday for foreign cloud operators extending through 2047, essentially exempting them from tax on income from global operations routed through Indian datacenters. I don't understand the exact implications of this policy, but it's an incredibly aggressive incentive and a step in the right direction. A few notable projects worth highlighting:

- Reliance has pledged about $110B over seven years, with a 3 GW campus being built in Jamnagar.
- Adani committed about $100B by 2035 for 5 GW of capacity.
- TCS's HyperVault signed OpenAI as its first datacenter customer, part of the broader Stargate project, whose progress has been contentious.
- Microsoft, Google, AWS are all building in India, with commitments from $10–20B each.

This is all good. But it takes time, and these commitments are spread across 5–10 years. The projected datacenter capacity by 2030, even in an optimistic scenarios is around 6–8 GW. The US will be at 80–100 GW. China at 50+ GW.

While these numbers tell a story, the geopolitical risks are what make these numbers truly urgent.

The major players in AI chipmaking business are NVIDIA, AMD and Huawei. India essentially is limited to NVIDIA and AMD, both of whom must abide by US regulations regarding chip export. India currently has unrestricted access to these chips, but we shouldn't assume this will always be the case. In late 2024, the Biden administration drafted the AI Diffusion policy which essentially limited India to 50,000 of the most advanced GPUs. The Trump administration has rescinded this, but the situation remains fluid. India's advanced AI chip fabrication capabilities are pretty much zero, however there has been movement recently, and I hope this changes.

If this chip window closes, either through of export controls, geopolitical shifts, or supply chain disruptions, we kinda have no fallback. What happens if US-India relations deteriorate? And then there's the Taiwan question. TSMC fabricates over 90% of the world's most advanced semiconductors. If that supply chain breaks down for any reason, and the US needs to ration chip supply to the world, where does India stand in the queue? The implications are massive across energy, defense, telecommunications and the broader economy.

The next 3–5 years are the window. After which the geopolitical landscape around chips might look very different. Capabilities will have grown massively, the competitive dynamics will have hardened and renting intelligence will not sound like such a good anymore.

Compute however, isn't the whole picture. With compute, we will need to scale power behind it, and scaling that is a beast on its own. In the next part, I'll explore India's energy capabilities, the demands AI infrastructure will place on them, and how this connects to the token economy.

---

*This is Part 1 of a 3-part series on India's AI Infrastructure.*

- *Part 2: Energy — Coming soon*
- *Part 3: Model Capabilities — Coming soon*
