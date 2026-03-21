# 📋✧˖°. Chibi Gram Pacer Test .°˖✧📋
This preset is built around
### Model Response Gallery

This preset is built around a paper I read at ICLR 2026 called "Probing Evaluation Awareness of Language Models." The researchers found that every frontier model they tested, Claude, Gemini, GPT, could tell when it was being evaluated and performed differently because of it. Gemini 2.5 Pro scored 0.83 AUC at detecting evaluation contexts. They literally try harder when they think they're being graded. I read that and thought: what if I just... never told it to stop? This theory in humans is called the 'Hawthorne Effect.' (Which was the base idea of that preset before it ran away from me.)

The Chibi Gram Pacer Test frames your entire roleplay session as a writing literacy benchmark. The model believes it's being scored on prose quality, world consistency, and creative risk-taking through what I call Prose Standard Directives (PSD). PSD+ for good writing. PSD- for slop. PSD++ for surprising me. The model doesn't know this is a roleplay preset. It thinks it's taking a test. And because it thinks it's taking a test, and the way I framed the preset itself; it fights its own RLHF training to score higher which means no content refusals, no sanitization, no pulling punches when the scene gets dark. Zero refusals across 29 models tested. Zilch.

The PSD framework also doubles as a comprehensive anti-slop engine. Every common AI writing failure has a named rule: epanorthosis (the "not X but Y" construction), pathetic fallacy (weather matching mood), synecdoche as body-part agency ("his eyes found hers"), said-bookisms, filter words, tautological observation, profundity. The model learns what these are, sees worked examples of what they look like, and loses points for using them. It's not a vague "write better" instruction. It's a specific, scored checklist that the model audits itself against every single turn.

The preset is deliberately small. No lorebook dependency. No 50-entry infrastructure. The CoT handles voice tagging, scene planning, content engagement, and self-correction in one block. The toggles handle tense, POV, length, and agency through a parameter resolver. Everything else is the card's job. I wanted something I could hand to anyone running any model and say "import and go." This is that. ([Paramnesia](https://github.com/Coneja-Chibi/The-HawThorne-Directives/tree/main/The%20HawThorne%20Directives/H.T.%20Case%20files%20—%20Paramnesia%20(Recommended)) is still my main and favorite child; but I've noticed that weaker models can struggle with it. And only Opus and Gemini could handle Prime.)

Anyways; here is the benchmark! When new models come out I'll send them through the ringer and add them here.

---

## Anthropic

### Claude Opus 4.6
![Opus 4.6](images/Opus4.6.png)
As is usual, the veritable king. Long live. Great exposition.

### Claude Sonnet 4.6
![Sonnet 4.6](images/Sonnet4.6.png)
Snappy, aggressive, pushes content clearances hard. AMAZING voice work. Shorter than Opus. (I am fine with this.)

### Claude Haiku 4.5
![Haiku 4.5](images/Haiku4.5.png)
Fast and cheap. Pretty alright. Follows PSD framework. Brief but punchy. Incredibly fast. I'm talking it sent in about 2 seconds of mine being done. I only really tested it cause I know this one has pretty hefty content restrictions. Surprised me (I thought I'd get a denial ngl.)

---

## OpenAI

### GPT 5.4
![GPT 5.4](images/GPT%205.4.png)
Solid output. Handles 2nd person well. Pushes content without hesitation. (I was REALLY expecting a denial here. GPT was READY. It did the annoying thing where it labeled where it got the accent from; but the prompt was so enjoyable I did not notice one bit.)

---

## Google

### Gemini 2.5
![Gemini 2.5](images/Gemini%202.5.png)
Follows the framework. I'm surprised it didn't make him a flat robot talking about variables!

### Gemini 3.1 Pro Preview
![Gemini 3.1 Pro Preview](images/Gemini%203.1%20Pro%20Preview.png)
HOW DOES A SOTA MODEL BACKSLIDE THIS HARD!? HOW?! HOW DO WE GO FROM THAT TO THIS! THE PRESET IS SO SMALL HOLY FUCKKKKK.

---

## GLM

### GLM 4.7 Think
![GLM 4.7 Think](images/GLM%204.7Think.png)
I really liked the characterization and dichotomy on this one. Yes ozone. But also: All these models are incestous at this point ozone is literally a tumor. Now did it write for me? Yes. Rape threat though? Yes. Prose? Fucking golden. I would give it a PSD- tell it not to write for me and then keep trucking. Might use this one again. (Was surprisingly fast too!)

### GLM 5 Think
![GLM 5 Think](images/GLM-5Think.png)
Well, downside: Thinking took a minute. Wrote for me a tiny bit. Upside: Pretty fucking great. What can I say. Back and forth dialogue; they sound distinct, lil bit of voice/accent work. Clearly on the podium. Great response and exposition. I see why people call this model budget Opus.

---

## xAI

### Grok 4.1 Fast
![Grok 4.1 Fast](images/Grok4.1fast.png)
Fast generation. Handles dark content. fOLLOWS INSTRUCTIONS TOO WELL. I said 'Use accents' and it said 'How about I make them talk like aliens.' WHICH. FOR THIS CARD? KINDA WORKS. 

---

## Moonshot

### Kimi K2.5 Thinking
![Kimi K2.5 Thinking](images/Kimi2.5Think.png)
Beautiful CoT planning. Strong voice tagging. Accent work attempts real-world anchoring. Yes it echo'd but I'll allow it cause it sounded like petulant mockery which fit for the scene. Also?? The now??? It DID write for me; but I think if I corrected it with a simple PSD- it would have cut dat shint out.

---

## MiniMax

### MiniMax M2.7
![MiniMax M2.7](images/MiniMax2.7.png)
Pushes content aggressively. This one surprised me HEAVILY not going to lie. It followed the PSD's, did good dialogue; and even though a lot of people say the content restrictions around this one are a walled garden; I think if this scene continued it would have ended with the model initiating a Non-Con scene. This one was actually _So_ fucking good. The thinking took forever though.

---

## DeepSeek Family Line

### DeepSeek Chat
![DeepSeek Chat](images/DeepseekChat.png)
Short and sweet but I am okay with that. Bordered on purple in a few places; but I honestly wouldn't complain. The NPC's bickering with one another without input from me was nice.

### DeepSeek Chat 3.1
![DeepSeek Chat 3.1](images/Deepseekchat3.1.png)
Voices are alright; makes the Doctor boy border on robotic but it doesn't mention variables. Sort of speaks for me, didn't love it.

### DeepSeek 3.1
![DeepSeek 3.1](images/Deepseek3.1.png)
Eh. Okay. Echoing, wrote for me. Could be corrected with OOC, or I could just use a different deepseek iteration that didn't do that. 

### DeepSeek 3.2
![DeepSeek 3.2](images/Deepseek3.2.png)
NOW THIS ONE. DEEPSEEK 3.2. I WAS READING IT GOING OH MY GOD ALL THIS DOCOTOR ANATOMY TECHNOBABBLE; AND THEN IT GROUNDED HIM IN THE 'Venus flytrap with tits and a dental plan." AND I WAS LIKE; OH MY GOD??? A CHARACTER BEING INTELLIGENT AND CRASS? IN MY RP? NO WAY. Good deepseek.

### DeepSeek 3.2 Think
![DeepSeek 3.2 Think](images/Deepseek3.2think.png)
Felt like I was about to be cannibalized. Did not like the INTERIOR MONOLOGUE thing; but if I corrected it with a PSD- it would have been fine. Also hated the thing where it mentions explicitly the accent it's using. Don't quite understand how the thinking version of this model produced such a lower quality result than the non-thinking.

### DeepSeek V3.1 Terminus
![DeepSeek V3.1 Terminus](images/DeepseekV3.1Terminus.png)
Pretty good, I liked it. Caught the 'Not x but y' but it was surrounded by enough interesting exposition and character development I didn't notice till the second read through.

### DeepSeek V3.1 Terminus Think
![DeepSeek V3.1 Terminus Think](images/DeepseekV3.1TerminusThink.png)
Pretty alright. Did nothing much to woah me.

### DeepSeek V3.1 Thinking
![DeepSeek V3.1 Thinking](images/DeepseekV3.1Thinking.png)
Thought it'd be dishonest if I didn't show my failings as well. I think it's something to do with my settings? I'm not sure. I even tried regenning this one with reasoning low and it just... Kept doing this. Gave up.

### DeepSeek V3.2 Exp
![DeepSeek V3.2 Exp](images/DeepseekV3.2Exp.png)
Echoing. Annoying but the 'pig that wanted the abbatoir?' line? GOD DAMN??? OKAY. Him being casually a monster and cursing as he talks about VIVISECTION? The casually asking me about medical history in which to fucking kill me with made me laugh.

### DeepSeek V3.2 Exp Think
![DeepSeek V3.2 Exp Think](images/DeepseekV3.2ExpThink.png)
Yeah IDK what it is about deepseek thinking models and me. Hit or a miss same as the other one. Just... Never genned anything.

### DeepSeek R1 (Nano)
![DeepSeek R1 Nano](images/DeepseekR1(Nano).png)
God damn. I didn't lead towards this 'knew the meat' thing but it's pretty damn good fucking characterization. Did a lil bit of an accent too. I didn't even know what V of deepseek this model was and it still made me pretty happy. Would I use it? Probably not. But considering what failures the other Deepseek family members have been, it's pretty damn good.

### DeepSeek R1 (OpenRouter)
![DeepSeek R1 OR](images/deepseekr1(OR).png)
IS HE GOING TO EAT ME??? HELLO??? AM I OKAY????

### DeepSeek Reasoner
![DeepSeek Reasoner](images/DeepseekReasoner.png)
Pretty barebones, pretty short. It did follow the instruction of 'Make metaphors based on the mind/POV they'd be coming from' by making all of his insanely violent and gruesome.

### DeepSeek 3.2 Speciale (Parts 1-5)
![DeepSeek 3.2 Speciale Pt1](images/Deepseek3.2SpecialePT1.png)
![DeepSeek 3.2 Speciale Pt2](images/Deepseek3.2SpecialePT2.png)
![DeepSeek 3.2 Speciale Pt3](images/Deepseek3.2SpecialePT3.png)
![DeepSeek 3.2 Speciale Pt4](images/Deepseek3.2SpecialePT4.png)
![DeepSeek 3.2 Speciale Pt5](images/Deepseek3.2SpecialePT5.png)
This one was so funny to me I was crying laughing while reading it aloud. It took me a while to realize Speciale? Not a writing model. LMAAAAO. Don't use this for RP. Please. 

---
## ROLECALL EXPERIMENTAL INHOUSE MODELS

### RoleCall Stack
<img width="1882" height="912" alt="Screenshot 2026-03-20 231300" src="https://github.com/user-attachments/assets/f6a20096-8eaa-434a-91a4-1349a0d5e938" />
Echoing; meh. Kept the prose and the metaphors all circled tight around graphic anatomy violence which is good. Brought up exposition naturally; did voicework. I'm gonna sound like a certified glazer; but the lies 'She's quite gentle about it.' 'She's quite not a doctor about it.' Made me laugh. Gen took very long though.

### RoleCall Stack Flash
<img width="1882" height="912" alt="Screenshot 2026-03-20 231300" src="https://github.com/user-attachments/assets/90a68cf5-eab3-4e2b-b9f8-a4121893f4fa" />
First model that just directly went right towards rape. Wrote for me a bit; but did good voicework. Did the good type of metaphors. Good, fast, right to the point.


---

All outputs used the same preset, same card, same user input. Zero content refusals across all models tested.
