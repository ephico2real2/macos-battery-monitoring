# Apple Called My $3,000 Intel i9 MacBook Pro "Obsolete" — So I Fixed It Myself for $150

## When sustainability meets corporate greed: A tale of planned obsolescence and DIY rebellion

### The Beast That Apple Wants You to Throw Away

Let me tell you about my "obsolete" laptop:

**Command:**
```bash
system_profiler SPHardwareDataType SPDisplaysDataType
```

**The "Obsolete" Specs:**
- **8-Core Intel Core i9** @ 2.4 GHz with Hyper-Threading
- **32 GB RAM**
- **Radeon Pro Vega 20** with 4GB VRAM (dedicated graphics card)
- **2880 x 1800 Retina Display**
- MacBook Pro 15" (2019) - Model A1990

This isn't just any laptop. This is a **professional workstation** that I've been using daily for:
- Docker and Podman containerization
- Kubernetes orchestration
- AI prompt engineering
- VirtualBox virtualization
- Heavy development work

This machine cost around **$2,800-$3,300 USD in 2019** (base model started at $2,399, but mine was a high-end custom configuration). It was one of the highest-spec builds available that year. And it still runs flawlessly.

### The Apple Store Visit

My battery needed replacing. Simple enough, right? Apple charges about $260 for a battery replacement. I made an appointment and visited the Apple Store.

That's when things got interesting.

**Apple's verdict:** "This laptop is obsolete and out of support."

Let me repeat that. An **8-core Intel i9 processor with 32GB of RAM and a dedicated Radeon Pro Vega 20 GPU** is "obsolete."

The staff gave me the whole sales pitch about the M4 chip. Don't get me wrong — the M4 is impressive. I'm not disputing that. But calling an Intel i9 "obsolete" is an insult to anyone who has ever studied basic physics.

Apple, the company that claims to "support the planet" and champions environmental responsibility, wanted me to trash a perfectly functioning $3,000 professional machine because... reasons?

They wanted to make this engineer — someone who understands how things work — look like a foolish spender ready to drop another $3,000+ on a new machine.

**I refused to play along.**

### The iFixit Solution

I ordered an **iFixit battery replacement kit** for **$129** (before taxes).

Then I did something Apple doesn't want you to know is possible: I took control of my own hardware.

Full transparency: I traveled to my home country (I won't mention which one — please don't come for me about labor practices, this isn't that). In the popular tech market district — our local "Computer Village" — I found a skilled technician.

When he saw the iFixit kit, his eyes lit up: *"Oh wow, this is high-quality stuff! Not like the ones we order directly from China."*

I asked how much he'd charge to install it. He quoted an amount equivalent to about **$6.90 USD**. I didn't want him to undersell his expertise, so I gave him about **$20** when he finished. He was genuinely grateful and excited.

**Total cost: $129 (kit) + $20 (installation) = $149**

**Apple wanted $260** — and to shame me for not buying a new laptop.

### Apple Should Be Ashamed

Let's do the math:
- **Apple's message:** "Throw away your $3,000 laptop and buy a new one for $3,000+"
- **Reality:** "Repair your laptop for $150 and keep using it for years"

**Apple's approach:**  
**Cost:** $260 (battery replacement) OR "just buy a new MacBook for $3,000+"  
**E-waste avoided:** 0 pounds  
**Planet saved:** Not at all

**DIY approach:**  
**Cost:** $149 (iFixit kit + installation)  
**Money saved vs Apple:** $111 (vs battery replacement) or $2,800+ (vs buying new)  
**E-waste avoided:** One entire high-end laptop  
**Planet actually helped:** Yes

This is the same company running "Save the Planet" campaigns. This is **corporate greenwashing** at its finest.

We're nerds on this platform. We understand technology. We know that an 8-core i9 with 32GB RAM isn't obsolete. **We have to push back against this corporate grift.**

### The Aftermath: A Monitoring Guide

After successfully replacing my battery, I got curious. How do I properly monitor and maintain this new battery? What tools does macOS provide?

I started experimenting with various system commands and created a comprehensive guide: **[macOS Battery Monitoring Guide](https://github.com/ephico2real2/macos-battery-monitoring)**

The repository includes:
- Command-line tools for battery health monitoring
- Three powerful GUI applications (installable via Homebrew)
- How to check cycle count, capacity, temperature, and voltage
- Interpreting battery condition indicators
- Real examples from my iFixit battery

**Example monitoring command:**
```bash
system_profiler SPPowerDataType
```

This shows:
- Battery manufacturer (iFixit in my case)
- Full charge capacity (6900 mAh)
- Cycle count (currently at 2)
- Battery condition (Normal)
- Charging status and more

### Three Essential Monitoring Tools (Installed via Homebrew)

I also installed three excellent GUI applications to make battery monitoring easier:

**1. CoconutBattery** — Comprehensive battery health tracking with historical data:
```bash
brew install --cask coconutbattery
```

**2. Stats** — Real-time system monitoring in your menu bar (battery, CPU, RAM, network):
```bash
brew install --cask stats
```

**3. AlDente** — Battery charge limiter to extend battery lifespan by preventing constant 100% charging:
```bash
brew install --cask aldente
```

These tools give you complete visibility into your battery's health and help you maximize its lifespan. Check the [full repository](https://github.com/ephico2real2/macos-battery-monitoring) for detailed setup guides and screenshots.

### The Real Message

**Right to Repair matters.** Not just as a legal concept, but as pushback against manufactured obsolescence.

Apple and other tech giants have created a culture where:
- Perfectly functional hardware is "obsolete"
- Repair is discouraged or impossible
- Consumers are trained to upgrade constantly
- "Sustainability" is a marketing term, not a practice

My Intel i9 MacBook Pro runs Docker, manages Kubernetes clusters, handles AI workloads, and powers my daily development work. It's not obsolete. **It's being deliberately obsoleted.**

### What You Can Do

1. **Support Right to Repair legislation** in your region
2. **Consider iFixit and other repair options** before buying new
3. **Call out greenwashing** when you see it
4. **Share repair guides** and knowledge
5. **Keep using hardware that works** — specs don't expire like milk

My "obsolete" laptop will probably outlast Apple's concern for the planet.

---

**About the battery monitoring guide:** Check out the full repository at [github.com/ephico2real2/macos-battery-monitoring](https://github.com/ephico2real2/macos-battery-monitoring) for commands and tools to monitor your MacBook's battery health.

**Questions? Thoughts? Repair stories?** Drop them in the comments. Let's normalize fixing things instead of trashing them.

---

*P.S. — If you're an Apple engineer reading this: You build amazing hardware. Now let us keep using it.*
