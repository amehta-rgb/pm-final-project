# Strategic Discovery Map (Module 1)

## Responses
- **Write one feature from the map that, if an engineer asked “why is this a priority for our 12-week roadmap?”, you honestly could not give a strategic answer for.:** Wearables (under Sync).

If an engineer asked why it’s on a 12-week roadmap, I’d have nothing strategic to say. It ended up on the map because water trackers usually have it, not because I reasoned it would move a metric.

Cost is high and ongoing. Each platform (Apple Watch, Wear OS, Garmin, Fitbit) has its own SDK, review process, and quirks. The maintenance never really ends.
The benefit is unclear. Wearables mostly track activity and heart rate, and neither measures water intake. The plausible value is a goal adjustment based on workout data, or a wrist shortcut for logging. Health-app sync already covers the first, and quick-add on the phone covers most of the second.
It reaches a minority of users. Most people in an early-stage hydration app won’t own a compatible device or want to configure it.
It does nothing for the core loop. Logging, reminders, and streaks are what decide whether someone is still using the app in week 4. Wearables only polish that loop for a few people.

I’d defer it until two things are true. First, retention data should show the core loop works and that users want logging closer to hand. Second, there should be a concrete signal such as user requests or a cohort of watch owners who churn faster. Until then, the 12 weeks are better spent on logging speed and reminder quality.
- **Write one feature that looks “correct” for the app but has zero strategic weight, you have no idea if it helps the company make money or whether a single user actually asked for it.:** Feature: Droplet Companion

A small animated water droplet lives on the home screen and reacts to your intake. It looks sleepy at 0%, perks up at 50%, and does a little dance at 100%. Users can unlock seasonal outfits, like a scarf in winter or sunglasses in summer.

Why it looks right: It sounds like gamification, and gamification is a known retention tactic. It fits the “stay motivated” branch of the mindmap, it demos well, and nobody in a roadmap review would object to it.

What’s missing:

No user asked for it. I have no interviews, support tickets, or survey responses mentioning a mascot, and I don’t know if the target users would find it charming or childish.
No link to revenue. It isn’t tied to a subscription tier, an ad placement, or a conversion step. I can’t say whether outfits would be paid, free, or ignored.
No evidence it moves retention. Streaks and reminders have at least some track record. I’d be guessing that a cartoon droplet keeps anyone past week 2.
No success metric. If we shipped it, I wouldn’t know what number to check to decide whether it worked.
It has real costs. It needs design and animation work, ongoing seasonal content, and extra testing across devices, and it would compete for the same sprint as the quick-add flow, which does address a known risk.

Features like this tend to ship because they’re easy to picture and hard to argue against. Before building it, I’d ask for one piece of evidence: a user quote, a test result, or a revenue hypothesis. If none exists, it goes to the bottom of the backlog
- **Compare V3 to your Step 1 baseline. What changed, and is the output objectively better, did the AI get smarter, or did your added PM knowledge (JTBD, effort/impact, retention) force it to be useful?:** _(not filled in)_
- **Key takeaway: how does this prove the PM’s role is to think while the AI’s role is to execute?:** _(not filled in)_
