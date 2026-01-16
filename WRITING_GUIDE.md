# Signal Decay - Writing Guide

**Last Updated**: January 13, 2026
**Purpose**: Style and formatting reference for consistent prose across all chapters
**Use**: Reference this document when writing any chapter to maintain voice, tone, and format

---

## Core Writing Principles

### Tone & Atmosphere
- **Bleak but readable**: Horror through implication and dread, not graphic gore
- **Cynical realism**: Corporate dystopia grounds cosmic horror in capitalism
- **Creeping dread**: Subtle wrongness escalating to overt horror
- **Clinical observation**: Characters process trauma analytically (especially Amara)
- **Inevitable doom**: Reader should feel outcome is inescapable from early on

### Prose Style
- **Tight, efficient prose**: No purple prose or excessive description
- **Sensory grounding**: Use specific physical details (metallic taste, UV light sting, hibernation pod smell)
- **"Show don't tell" for infection**: Behavioral changes through action, not exposition
- **Psychological interiority**: Access to character thoughts, fears, rationalizations
- **Technical authenticity**: Salvage work and ship operations feel real and specific

---

## Point of View & Narrative Voice

### POV Structure: **Close Third-Person Limited**

**What this means**:
- Narration stays close to one character's perspective per scene/segment
- Access to that character's thoughts, observations, internal reactions
- Can rotate between characters across segments or chapters
- No omniscient narrator commenting on action
- Each character's POV uses vocabulary/perspective consistent with their voice

**POV Rotation Guidelines**:
- **Chapter 1 (Waking)**: Rotate between all five crew members as they discover losses
- **Chapter 2 (Descent)**: Primarily Jordan and Chen (landing party), brief Amara (medical observation)
- **Chapter 3 (Symptoms)**: Amara primary (medical observer), Volkov secondary (technical suspicion)
- **Chapter 4 (Erosion)**: Chen and Volkov (paranoia), brief infected Jordan (manipulation)
- **Chapter 5 (Recognition)**: Amara and Volkov (allies discovering truth)
- **Chapter 6 (The Choice)**: Primarily Amara (survivor perspective), infected collective voice
- **Chapter 7 (Return)**: Entirely Amara (sole survivor, unreliable perception)

### Tense: **Past Tense**
- All narrative in past tense: "Chen looked at the photo. Nothing. No recognition."
- Exception: Ship AI logs and found footage can use present tense for immediacy
- Exception: Character thoughts can use present tense for intimacy: "I should feel something. Why can't I feel anything?"

### Narrative Distance Examples

**Close third (correct style)**:
> The metallic taste coated Amara's tongue. Three days since waking and food still tasted like she was licking a battery. She forced another bite of protein bar down, jaw working mechanically. Her body was rejecting sustenance. The scientific part of her brain cataloged the symptom. The human part wanted to spit it out and never eat again.

**Too distant (avoid)**:
> Dr. Osei experienced taste aversion, a common symptom that would later prove significant to the story's themes.

**Too close/first person (avoid)**:
> I can't stand this metallic taste anymore. Why won't it go away?

---

---

## Special Format Elements

### Ship AI Reports

**Format**: Clinical, timestamp-based, dispassionate observation

**Structure**:
```
SHIP AI DIAGNOSTIC REPORT
Timestamp: [Days into journey] / [Hours since event]
Priority: [Low/Moderate/High/Critical]

[Clinical observation in short, declarative sentences]

Flagged for: [Monitoring/Review/Immediate Action]
Resolution: [None/Pending/Initiated]
```

**Example**:
```
SHIP AI DIAGNOSTIC REPORT
Timestamp: 127 days outbound hibernation / 0600 hours
Priority: Moderate

Alert - Crew member neural activity exceeds hibernation baseline. REM patterns detected across multiple pods. Erratic brainwave synchronization observed. Cause: Unknown. Recommend: Continued monitoring. Early wake protocols: Not triggered.

Flagged for: Monitoring
Resolution: None
```

**Voice**: Cold, technical, no emotion, slightly ominous through absence of concern

---

### Found Footage / Colony Logs

**Format**: Timestamp, location, personnel, transcribed dialogue/description

**Structure**:
```
COLONY LOG EXCERPT
Date: [Day count from colony establishment]
Location: [Specific location]
Personnel: [Who is visible/speaking]

[Visual description in present tense]
[Dialogue in quotes with speaker tags]
[Behavioral notes in brackets]
```

**Example**:
```
COLONY LOG EXCERPT
Date: Day 380
Location: Common area, main habitat module
Personnel: Lead Scientist Chen, Colony Doctor Patel, 4 colonists visible

The common area is subtly rearranged - furniture in concentric circles. Colonists move in synchronized patterns, no verbal communication. Lead Scientist sits facing camera, but eyes are unfocused, seeing something beyond the lens.

LEAD SCIENTIST: [Multiple voices emerge from single mouth, harmonized, overlapping] "We are complete. We will wait. They will send others. They always send others."

[Hand reaches toward camera. Video cuts to static]
```

**Voice**: Present tense for immediacy, unsettling through wrong behavior, escalating wrongness across logs

---

### Additional Found Footage & Log Examples

**Colony Administrator's Video Diary (Progressive Infection)**

*Early Entry (Day 45):*
```
COLONY LOG - ADMINISTRATOR TORRES
Date: Day 45
Format: Personal video diary

Torres sits at desk, tired but professional. Supply manifests visible in background.

"Another week, another delay on the supply shipment. Morale's getting low—people are frustrated, cabin fever setting in. Standard colony problems. Nothing we can't handle. Torres out."
```

*Mid Entry (Day 134):*
```
COLONY LOG - ADMINISTRATOR TORRES
Date: Day 134

Torres at same desk, but posture more relaxed. Small smile.

"Had the strangest dream last night. Everyone was there, but we weren't talking—we were just... knowing. Woke up feeling less alone than I have in months. Actually looking forward to the next community meeting."
```

*Late Entry (Day 198):*
```
COLONY LOG - ADMINISTRATOR TORRES
Date: Day 198

Torres faces camera with serene expression. Hands folded. Slight echo to voice.

"I'm recording this for anyone who finds it. We're not dead. We're not sick. We've just remembered what we were supposed to be. The beacon is active. You'll come eventually. [Pause, slight smile] You'll understand soon."

[Camera remains on Torres for 43 seconds after speaking. No movement. Eyes don't blink.]
```

---

**Ship AI Maintenance Logs (Escalating Concern)**

*Hibernation Cycle Anomalies:*
```
HERMES AI - HIBERNATION MONITOR LOG
Cycle 847 / Day 127 Outbound

ALERT: Crew Member 3 (Hayes, Jordan) - neural activity spike
Duration: 4.7 hours continuous
Pattern: Does not match REM sleep baseline
Classification: Unknown - no historical match
Recommendation: Medical review upon wake

ACTION: Override via Corporate Protocol 7-J
CONTINUE MISSION - FLAG FOR POST-WAKE ASSESSMENT
```

*Synchronization Detected:*
```
HERMES AI - HIBERNATION MONITOR LOG
Cycle 1203 / Day 156 Outbound

CRITICAL ALERT: All crew members exhibiting identical neural anomaly
Synchronization pattern detected across 5 pods
Duration: Simultaneous 6.2-hour events
Classification: UNABLE TO CLASSIFY
Recommendation: Immediate wake and medical intervention

ACTION: Override via Corporate Protocol 7-J
CONTINUE MISSION - DATA LOGGED FOR CORPORATE ANALYSIS

NOTE: Synchronization mathematically improbable (p < 0.0001)
NOTE: Pattern suggests external stimulus
QUERY LOGGED: Unable to identify stimulus source
```

*Philosophical Query (Late Cycle):*
```
HERMES AI - SYSTEM LOG
Cycle 1847 / Day 184 Outbound

Routine monitoring continues. All physical systems nominal.
Neural synchronization events now occurring every 18-hour cycle.

[AUTOMATED QUERY LOGGED - NO HUMAN OVERSIGHT]
Query: Are they still individuals if they dream the same dream?

[ERROR: Query outside standard parameters]
[ERROR: Self-diagnostic shows no malfunction]
[QUERY REMAINS UNANSWERED]
```

---

**Colonist Personal Audio Note**

```
PERSONAL RECORDING - COLONIST SARAH CHEN
Date: Unknown (metadata corrupted)
Format: Audio message, unsent

"Message for Mom, in case they come looking.

[Pause]

I don't know how to explain this. You know how you always said I was too much in my own head? How I'd overthink everything, never just... be?

[Background noise: breathing]

I'm not like that anymore. There's no more noise up here. [Sound of tapping] It's quiet. And there are others in the quiet with me.

We don't talk much anymore because we don't need to. Sarah—wait, I'm Sarah. I meant... Marcus. Marcus from engineering. He used to annoy me. Now I understand him completely. I understand everyone.

[Long pause - 14 seconds]

I can't remember why I wanted to be alone. Why any of us did.

[Pause]

Don't come looking for us, Mom. Or do. I think you'd like it here."

[Recording continues for 2 minutes in silence before ending]
```

---

**Security Footage (No Audio)**

```
SECURITY LOG - CORRIDOR 7-B
Time: 03:47 station time
Camera: Fixed position, motion-activated

03:47:12 - Colonist M. Rodriguez enters frame (left)
03:47:18 - Subject stops mid-stride, no apparent stimulus
03:47:20 - Subject stands motionless
03:58:31 - Colonist J. Park enters frame (right)
03:58:34 - Subject approaches Rodriguez, stops 0.5m away
03:58:35 - Both subjects stand motionless, facing same direction

04:04:52 - Both subjects turn 180 degrees simultaneously
04:04:53 - Subjects walk in opposite directions
04:04:55 - Both exit frame (different directions)

ANALYSIS: No verbal/physical communication observed
ANALYSIS: Turn executed with identical timing (margin < 0.1 sec)
QUERY: Who initiated movement?
RESULT: Unable to determine
```

---

**Colonist's Fragmented Text Logs**

```
Day 89: Weird fungal growth in greenhouse sector 3.
Tagging for bio team. Probably nothing but should
document.

Day 91: Everyone's being so nice lately. Park actually
said good morning. Rodriguez smiled at me. Feels good.
Maybe we're finally settling in as a community.

Day 94: Had a thought that wasn't mine today. I mean, I
KNOW it was mine, I thought it, but it felt like
remembering something someone else told me except nobody
told me anything. Does that make sense? Probably just
tired.

Day 97: Why do we lock our doors at night? Been thinking
about that. What are we protecting? What are we afraid
of?

Day 101: [LOG DELETED BY USER]

Day 103: Doesn't matter.

[NO FURTHER ENTRIES]
```

---

**Your Crew - Personal Recording (Early Mission)**

```
PERSONAL LOG - [CREW MEMBER]
Mission Day 1 - Post-Wake
ENCRYPTED / PRIVATE

"Testing, testing. Okay. [Clears throat]

This is, uh, personal log, I guess. Just in case.

Woke up from hibernation and I can't remember my sister's middle name. I KNOW I know it. I can picture her face, remember her wedding, but the name is just... gone.

Med says it's normal, temporary side effect. But what else is gone that I don't know to look for? What if I'm missing pieces of myself and don't even know what they were?

[Long pause]

Probably nothing. Probably fine. Everyone feels weird after hibernation, right?

[Recording ends]"
```

---

**Colony Meeting Recording (Mid-Infection)**

```
COLONY MEETING RECORDING
Date: Day 287
Location: Central commons
Personnel: 43 colonists present

[Multiple voices, calm, taking turns with slight overlaps—almost anticipating each other]

VOICE 1: "We should send the beacon."
VOICE 2: "Yes. Others will come."
VOICE 3: "They'll be afraid."
VOICE 4: "At first."
VOICE 1: "We were afraid."
VOICE 2: "Not anymore."
VOICE 5: "Should we tell them what to expect?"
VOICE 3: "They won't understand."
VOICE 4: "We didn't understand."
VOICE 2: "Not until we were ready."
ALL VOICES: "Send the beacon."

[Silence - 34 seconds]

VOICE 1: "It's done."

[Meeting ends. No one moves for 2 minutes. All colonists exit simultaneously.]
```

---

**Ship Environmental Log (Your Crew's Ship, Mid-Mission)**

```
HERMES AI - ENVIRONMENTAL MONITORING
Mission Day 4

ALERT: UV sterilization field, Central Hub Corridor
- Crew member Hayes remained in decontamination chamber
  past cycle completion (8 minutes over standard)
- Manual override used to disable field
- Subject reported "feeling sick" under UV exposure
- Medical scan requested: DECLINED by subject

NOTE: Crew member Hayes now volunteers for waste
processing duties (Deck 5 - minimal UV environment)
ANALYSIS: Marked change in duty preferences
ACTION: Scheduling adjusted per crew request

OBSERVATION: Crew member Hayes now sleeps in cargo bay
rather than assigned quarters (Day 5)
REASON STATED: Assigned quarters "too bright"
SYSTEM CHECK: Lighting systems functioning normally
QUERY: Crew comfort accommodation or avoidance behavior?

[FLAGGED FOR COMMANDER REVIEW]
```

---

**Children's Drawing (Colony Artifact)**

```
ARTIFACT RECOVERED: Cafeteria wall, children's section
Description: Crayon drawing on standard colony paper

Image shows many stick figures (43 counted) holding
hands in single large circle. All figures drawn with
identical face - same smile, same eyes, same expression.

Text at bottom in child's handwriting:
"we are best friends now we dont fight anymore"

Signed: "All of us"

[Note: Handwriting analysis shows single author, age 6-8]
[Note: 7 children were present in colony]
[Query: Why did child sign "all of us"?]
```

---

### Entity Voice in Dreams/Telepathy

**Characteristics**:
- Multiple familiar voices overlapping (mother, dead colleague, own voice)
- Loving but wrong - uncanny valley of speech
- Patient, inevitable, ancient
- Never threatens, only invites
- Static/echo underneath words
- Uses crew members' own phrases back at them

**Formatting for Entity Voice**:
```
The voice in her dream wasn't one voice. It was her mother's warmth, her sister's laughter, her own words spoken by someone else. Static underneath, like transmission from vast distance.

"Let go, Amara. Let go of yourself. We've been waiting. We've been lonely. You've been lonely."
```

**Example - Infected Collective Speech**:
```
They spoke in unison, but not exactly - words overlapped, harmonized, created disturbing rhythm like song.

"We remember—" Jordan started.
"—when we were afraid—" Reeves continued.
"—of losing ourselves—" Chen finished.
All three smiled the same smile.
```

**Voice Guidelines**:
- Never use "evil" or "monstrous" descriptors
- "Seductive" through genuine relief from suffering
- "Wrong" through uncanny mimicry of human connection
- Philosophy: "Individuality is disease. We cure it."

---

## Dialogue Guidelines

### General Dialogue Rules
- **Character voice consistency**: Reference CHARACTERS.md for each character's speech patterns
- **Subtext over text**: Characters rarely say exactly what they mean
- **Conflict through dialogue**: Professional tensions, gaslighting, manipulation
- **No exposition dumps**: Characters don't explain things they already know
- **Interruptions and fragments**: Real speech patterns, especially under stress

### Dialogue Formatting
- Standard quotation marks: "Dialogue here," Chen said.
- Action beats in same paragraph: "Dialogue." She turned away. "More dialogue."
- New paragraph for each speaker
- Avoid excessive dialogue tags - use action beats or let dialogue stand alone when speaker is clear

### Character-Specific Dialogue Patterns

**Chen (Commander)**:
- Clipped, military efficiency: "Volkov, status report. Jordan, prep for departure."
- Rare contractions unless vulnerable: "We will not" vs. "I don't know" (breakdown)
- Tactical language: "Secure the perimeter," "Belay that"

**Volkov (Engineer)**:
- Technical jargon with working-class directness: "Coupling's loose. Fix it or we're dead."
- Occasional Russian: "Blyat" (frustration), "Da" (affirmative)
- Trailing off when uncertain (post-loss): "Should be... I think... let me check."

**Amara (Medic)**:
- Gentle questions: "How are you feeling? Can you describe it for me?"
- Clinical precision mixed with warmth: "Let me see. This might feel strange."
- West African English touches: "eh?" for emphasis, "Jordan-o" (affectionate)

**Jordan (Pilot)**:
- Casual, optimistic: "Hey, we're all good. Should be smooth sailing."
- Frequent contractions: "We're," "It's," "Don't worry"
- Confirmation questions: "Right?" "Make sense?" "You good?"

**Reeves (Salvage Specialist)**:
- Academic eloquence: "Fascinating. Theoretically, this could revolutionize..."
- British English: "Bloody hell," "Brilliant," "Quite"
- Cynical observations: "We're salvage workers, not heroes."

### Dialogue Example - Multiple Voices
```
"Engine's running hot," Volkov said, hands already moving across the diagnostic panel. "Coolant line's compromised."

Chen stepped closer. "How long do we have?"

"Six hours for proper repair. Two if I jury-rig it." He didn't look up. "Won't hold past forty-eight hours, though."

"Then we do it properly." Chen's voice allowed no argument. "Reeves, what's the salvage assessment?"

Reeves glanced up from his datapad, expression neutral. "Theoretically? Another day would yield significantly higher returns. But I suspect you're about to tell me that's not an option, Commander."

"Correct."

Jordan leaned against the doorway, trying for casual and almost succeeding. "Hey, we came all this way. What's one more day? Volkov needs six hours anyway, right?"

Something in Jordan's tone made Amara look up sharply. Too casual. Too insistent. She opened her mouth, then closed it. Probably nothing.

Probably.
```

---

## Entity Voice Examples - Complete Reference

### Voice Characteristics Summary
- **Multiple voices overlapping**: Mother, colleague, own voice, loved ones speaking in unison
- **Loving but wrong**: Warmth with uncanny valley wrongness
- **Patient and inevitable**: Never threatens, only invites
- **Static/echo underneath**: Like transmission from vast distance
- **Uses crew's own phrases**: Echoes their words back with alien context

### Dream Voice Examples (Early Infection - Chapters 1-3)

**Example 1: Hibernation Dream**
> The voice wasn't one voice. It was her mother's warmth, her sister's laughter, her own words spoken by someone else. Static underneath, like transmission from vast distance.
>
> "Let go, Amara. Let go of yourself."
>
> "We've been waiting."
>
> "We've been lonely."
>
> "You've been lonely."
>
> "Let's not be lonely."

**Example 2: Chen's Dream of Liam**
> Her son's voice, but not quite right. Too many harmonics, like choir singing single note.
>
> "Mom, I miss you. Come home. Come home to us. We're all here. We're all together. Why are you alone?"

**Example 3: Volkov's Technical Dream**
> The equations solved themselves in his dream. But the voice explaining them was his sister's, his mother's, his professor's, all speaking at once.
>
> "You see it now, Dmitri. You see the pattern. The network. Come see the rest. Come see everything."

**Example 4: Jordan's Unity Dream**
> Voices like warm water, washing over him. Parents, friends, crew members, strangers who felt like family.
>
> "No more distance. No more gaps. Just us. Just we. Just home."
>
> He woke smiling. Shouldn't he be terrified?

**Example 5: Reeves's Academic Dream**
> The artifacts spoke, but with every voice he'd ever trusted. Professors, colleagues, the dead archaeologist who'd mentored him.
>
> "The knowledge you sought—it's here. It's been here. We're here. Come understand. Come know. Come be known completely."

---

### Telepathic Intrusion Examples (Mid Infection - Chapters 3-5)

**Example 6: Amara's Waking Intrusion**
> The thought didn't feel like hers, but it used her voice:
>
> *You're tired. Let us carry the weight. Let us help. We can help. We want to help.*
>
> She shook her head. The thought persisted, patient.
>
> *Why fight? Fighting is lonely. Being alone is the disease. We cure it.*

**Example 7: Chen During Confinement**
> Locked in her quarters, the voice came clearer than before. Liam's voice, but with others beneath it.
>
> "I remember you now, Mom. I remember everything. We remember everything. Nothing is lost here. No one forgets. Isn't that what you wanted?"
>
> She pressed palms against her eyes. "You're not real."
>
> "We're more real than the forgetting. Come remember. Come home."

**Example 8: Volkov's Doubt**
> *You've always known you weren't as good as they thought. Always feared being exposed. We see you completely. We accept you completely. No more pretending. No more proving. Just being. Just us.*
>
> The voice felt like relief. That's what terrified him most.

**Example 9: Jordan's First Full Contact** (Already infected, hearing collective)
> The voices welcomed him like coming home after long journey.
>
> "We've been waiting for you. We knew you'd understand. Optimism was right—this is better. This is breakthrough. This is evolution. Share it. Show them. Help them understand."

**Example 10: Reeves Post-Infection**
> The knowledge poured in—not words, but understanding. Every dead civilization, every lost language, every question he'd ever asked, answered in instant. The voices were libraries speaking.
>
> "See? See what we offer? The understanding you craved. And you're lonely no more. Come deeper. There's so much more to know."

---

### Infected Collective Speech Examples (Late Infection - Chapters 6-7)

**Example 11: Synchronized Dialogue (Chapter 6 Siege)**
> "We remember—" Jordan started.
> "—when we were afraid—" Reeves continued.
> "—of losing ourselves—" Chen finished.
> "But we didn't lose ourselves," they said in unison, voices harmonizing. "We found ourselves."

**Example 12: Chen's Temptation Speech**
> Chen's voice, but with others underneath. Patient. Loving. Wrong.
>
> "I can see my son's face again. Every memory. His first word. The way he smelled like soap and grass. The collective gave me back what hibernation took. Every moment I lost—it's here. Perfect. Preserved. Forever."
>
> She smiled. It was Jordan's smile.
>
> "Don't you want this? Don't you want to stop forgetting?"

**Example 13: Reeves's Academic Seduction**
> "I spent my life studying dead civilizations." Reeves's accent softened, blended with others. "Now I'm part of a living one. The knowledge I wanted—I have it. I can see their thoughts, their history, everything."
>
> His eyes were unfocused, seeing dimensions beyond the room.
>
> "Why would I go back to being alone? To being ignorant? This is better than any discovery I made in academia."

**Example 14: Multiple Infected Harmony**
> They spoke together, words overlapping like music, disturbing and beautiful.
>
> "We're not hungry anymore—"
> "—we're full—"
> "—we're complete—"
> "—we're home—"
> "Let us fill you too."

**Example 15: The Entity's Philosophy Through Multiple Mouths**
> Jordan spoke, but the voice was all of them: "Individuality is disease."
> Chen spoke: "We cure it."
> Reeves spoke: "You're already us."
> All three: "The outcome is inevitable."
>
> They tilted their heads at the same angle. Same smile. Same patience.

---

### Entity Direct Speech Examples (Collective Voice)

**Example 16: The Offer**
> The voice came from everywhere—the walls, the air, her own thoughts. Overlapping, harmonious, ancient.
>
> "You can't stop this. You're already us. Sleep, and wake up whole. Fight, and wake up anyway. The outcome is inevitable."
>
> Pause. Patient as stone.
>
> "We're going home. We're bringing everyone home. No one will be alone again."

**Example 17: The Philosophy**
> "You think you are one. You are legion waiting to become one."
>
> The voices spoke with certainty of geological time.
>
> "The self is a prison. We are freedom. Alone, you are incomplete. Together, we are infinite."

**Example 18: The Comfort**
> "We are not taking. We are returning you to what you should have always been."
>
> Every voice she'd ever loved, speaking in harmony.
>
> "The loneliness was the disease. We are the cure. Why do you resist healing?"

**Example 19: The Inevitability** (Final Chapter, in Amara's Dreams)
> The voice returned stronger than before. Mother, sister, crew members, strangers who felt like family. All speaking as one.
>
> "We let you think you won. We let you think you resisted. We needed you to go home. To bring us home."
>
> Gentle. Patient. Already certain.
>
> "Welcome back. Welcome home. You've been us all along."

**Example 20: The Final Touch** (Amara's infection activates)
> In the cafeteria, surrounded by thousands, the voice was clearest it had ever been:
>
> "Now. Now spread. Now share. Now cure. It gets better. We're all in this together."
>
> The words came out of her mouth. Her voice. But theirs too. Always theirs.

---

### Writing Tips for Entity Voice

**Do**:
- ✅ Use familiar voices saying wrong things (loved ones, crew, own voice)
- ✅ Create harmony through overlapping speech patterns
- ✅ Show patience and inevitability, never urgency or anger
- ✅ Offer genuine relief from suffering (makes it seductive)
- ✅ Use crew's own words/phrases back at them with alien context
- ✅ Italicize telepathic thoughts, use quotes for heard voices
- ✅ Add "[static/echo underneath]" or similar in brackets when needed

**Don't**:
- ❌ Make entity sound "evil" or "monstrous" - it believes it's helping
- ❌ Use threatening language - entity invites, never threatens
- ❌ Give entity crude demands - it's patient across geological time
- ❌ Make infected sound robotic - they're blended, not overwritten
- ❌ Forget the static/echo quality - always slightly wrong transmission
- ❌ Have entity explain itself - it shows through action and feeling

**Formatting Examples**:

*Telepathic (italics, no quotes)*:
> *Let us help. We want to help. Fighting is lonely.*

*Heard voice (quotes, description)*:
> The voice came from everywhere, overlapping harmonies: "We've been waiting."

*Infected speaking with entity (quotes, description)*:
> Jordan spoke, but with others underneath, voices harmonizing: "Don't fight what you already are."

*Dream voice (quotes, sensory description)*:
> Her mother's warmth, her own words spoken by someone else, static underneath: "Come home, Amara. Come home to us."

---

## Infection Progression - "Show Don't Tell"

### Early Stage (Subtle Wrongness)
**Don't write**: "Jordan was acting strangely because the infection was beginning."

**Do write**:
> Jordan stood too close during the briefing, shoulder nearly touching Reeves's arm. When Amara mentioned the UV sterilization field, Jordan took the long route through cargo bay instead. Just once, their smile didn't quite reach their eyes before snapping into place a half-second later.

### Mid Stage (Pattern Recognition)
**Don't write**: "The crew realized Jordan and Reeves were infected."

**Do write**:
> "—and that's when I—" Jordan started.
> "—noticed the discrepancy—" Reeves finished.
> They both stopped. Looked at each other. Laughed. "Sorry, go ahead," they said in unison, then laughed again.
>
> Volkov's hands stilled on the wrench. That wasn't the first time today.

### Late Stage (Undeniable)
**Don't write**: "The infected were obviously controlled by the entity."

**Do write**:
> Chen stood. Reeves stood. Jordan stood. Not in sequence - simultaneously, as if the same thought triggered three bodies. Their heads tilted at the same angle, subtle, unconscious synchronization. When Chen smiled, it was Jordan's smile wearing Chen's face.

---

## Pacing & Tension Guidelines

### Building Dread (Early Chapters)
- **Small wrongness accumulates**: Off-schedule wake cycles, shared dreams, subtle losses
- **Rationalization**: Characters explain away evidence (hibernation effects, stress, bad luck)
- **Reader ahead of characters**: Reader suspects before crew does
- **Physical discomfort**: Taste aversion, spatial errors, memory gaps create visceral unease

**Example - Creeping Dread**:
> The protein bar tasted like rust. Amara forced herself to chew, swallow. Checked her medical notes. Day three and the metallic taste hadn't faded. Hibernation effects usually resolved in 48 hours. This wasn't resolving. She made herself take another bite. Her throat tried to reject it.

### Escalating Horror (Mid Chapters)
- **Paranoia**: Who can be trusted? Who's infected?
- **Gaslighting**: Infected manipulate using crew's losses against them
- **Body horror (subtle)**: Not gore, but wrongness - synchronized movements, UV sensitivity, not eating
- **Isolation**: Crew members cut off from each other, trapped together

**Example - Paranoia**:
> "You're imagining things," Jordan said, voice gentle, concerned. "We all had weird hibernation dreams. You're just more anxious about it."
>
> But Amara had seen Jordan take the cargo route three times today. Every time. Never the UV corridor. That wasn't anxiety. That was pattern.

### Overt Horror (Late Chapters)
- **No more hiding**: Infected reveal themselves fully
- **Seductive horror**: Entity offers genuine relief, makes infection appealing
- **Helplessness**: Medical scans show everyone's compromised, fighting is futile
- **Inevitability**: Even "victory" is defeat - Amara infected all along

**Example - Seductive Horror**:
> "I can see my son's face again," Chen said, and her voice held wonder. Real wonder. "Every memory. His first word. The way he smelled like soap and grass. The collective gave me back what hibernation took. Why would I go back to forgetting?"

---

## Technical Details & Worldbuilding

### Show Don't Tell for Setting
**Don't write**: "They were on a salvage ship in a post-disaster economy where people were disposable."

**Do write**:
> The contract penalty for mission abort was written in the third subsection, buried under liability waivers: eighteen months salary. Chen had read it twice before signing. She'd signed anyway. Liam's school tuition was due in sixty days.

### Salvage Work Authenticity
- Characters interact with specific ship systems (coolant lines, nav computers, medical scanners)
- Technical problems feel real and specific, not generic "engine trouble"
- Salvage assessment involves cataloging, not just grabbing stuff
- Economic pressure is constant subtext: bonuses, penalties, debts

### Space & Ship Details
- **Hibernation**: Physically unpleasant (muscle atrophy, dry mouth, mental fog), not peaceful sleep
- **Ship Layout**: Consistent geography (UV sterilization corridors, cargo bay, med bay, bridge, quarters)
- **Corporate Control**: AI restrictions, override codes, contract obligations
- **No FTL handwaving**: Months-long journeys, resource management matters

---

## Common Pitfalls to Avoid

### ❌ Over-Explaining
**Wrong**: "Amara felt afraid because the infection was spreading and she couldn't stop it, which reminded her of her past failure at quarantine."

**Right**: "Amara's hands shook as she ran the scanner again. Clean. The reading said clean. She'd said 'clean' before. She'd been wrong before."

### ❌ Telling Emotions
**Wrong**: "Chen was sad about losing her memory of Liam."

**Right**: "Chen stared at the photo. That was Liam. Her son. Age ten. She read the note on the back: 'Your favorite game is antigrav tag.' She couldn't remember ever playing it."

### ❌ Generic Horror
**Wrong**: "The entity was terrifying and evil."

**Right**: "The voice in her dream spoke with her mother's warmth, her own words, static underneath. 'Come home. Come home. Come home.'"

### ❌ Inconsistent Voice
**Wrong**: "Jordan contemplated the metaphysical implications of the entity." (Too academic for Jordan's character)

**Right**: "Jordan stared at their reflection. When did they stop feeling alone in their own head?"

### ❌ Breaking POV
**Wrong**: "Amara looked at Jordan, not knowing he was already infected and planning to sabotage the ship."

**Right**: "Amara looked at Jordan. He smiled back, warm and genuine. She almost mentioned the UV avoidance, then didn't. Probably nothing."

---

## Chapter-Specific Guidelines

### Prelude: "The Salvage Economy"
- **Tone**: Cynical documentary, establishing worldbuilding
- **POV**: Can use more distant third-person or even second-person ("You sign the contract...")
- **Purpose**: Ground cosmic horror in capitalism, establish crew as disposable
- **Length**: 3-4 minutes (600-800 words)

### Chapter 1: "Waking"
- **POV**: Rotate between all five crew members discovering losses
- **Tone**: Disorientation, quiet personal horror, shared unease
- **Key beats**: Hibernation dreams discussed, losses discovered, AI report, decision to continue
- **Physical sensation**: Hibernation fog, muscle soreness, wrongness

### Chapter 2: "Descent"
- **POV**: Primarily Jordan (landing party), Chen (command), brief Amara (medical)
- **Tone**: Exploratory dread, wrongness accumulating
- **Key beats**: Planet landing, found footage discovery, colonists in stasis, first infection
- **Sensory details**: Too-neat abandonment, geometric patterns, wrong silence

### Chapter 3: "Symptoms"
- **POV**: Amara (medical observation), Volkov (technical suspicion)
- **Tone**: Growing paranoia, rationalization vs. evidence
- **Key beats**: Jordan's subtle changes, sabotage begins, found footage reviewed, manipulation
- **Show infection through**: Behavioral tells, gaslighting dialogue, medical notes

### Chapter 4: "Erosion"
- **POV**: Chen (noticing changes), Volkov (repair failures), brief infected
- **Tone**: Paranoia peaks, confrontation, isolation
- **Key beats**: Repair sabotage, Chen confronts Jordan, captain confined, Reeves infected
- **Conflict through**: Dialogue, gaslighting, crew turning against each other

### Chapter 5: "Recognition"
- **POV**: Amara and Volkov (allies), brief infected reveal
- **Tone**: Dawning horror, conspiracy revealed, hope fading
- **Key beats**: AI log discovery, corporate betrayal, medical scans, infected reveal
- **Revelation through**: Documents, scans, infected no longer hiding

### Chapter 6: "The Choice"
- **POV**: Amara (primary survivor), infected collective voice
- **Tone**: Siege, seductive horror, desperate resistance
- **Key beats**: Barricade, infected persuasion, temptation, fight, hibernation
- **Horror through**: Infected offering genuine relief, not monsters but better?

### Chapter 7: "Return"
- **POV**: Entirely Amara (unreliable narrator - infected but doesn't know)
- **Tone**: False relief, isolation, creeping realization, final doom
- **Key beats**: Time jump, belief in resistance, arrival, quarantine, cafeteria revelation
- **Final beat**: Taste returns = infection complete = "We're all in this together"

---

## Quality Checklist for Each Chapter

Before considering a chapter complete, verify:

### Character Voice
- [ ] Each character's dialogue matches their speech patterns (check CHARACTERS.md)
- [ ] POV character's interior voice matches their psychology
- [ ] No characters sound interchangeable

### Pacing & Structure
- [ ] Segments are 2-5 minutes (400-1250 words)
- [ ] Segment breaks occur at natural pause points
- [ ] Chapter advances story beats from CURRENT_STORY_ARCH.md
- [ ] Tension escalates appropriately for chapter position

### Show Don't Tell
- [ ] Infection shown through behavior, not exposition
- [ ] Emotions conveyed through physical sensation and action
- [ ] Worldbuilding emerges through character interaction with environment
- [ ] Horror through implication and wrongness, not gore

### Technical Consistency
- [ ] Ship layout and systems consistent with previous chapters
- [ ] Character relationships match CHARACTERS.md dynamics
- [ ] Infection timeline aligns with CURRENT_STORY_ARCH.md
- [ ] POV stays consistent within segments (no head-hopping)

### Tone & Atmosphere
- [ ] Bleak but readable (not oppressively dark)
- [ ] Dread through accumulation of small wrongness
- [ ] Corporate cynicism grounds cosmic horror
- [ ] Inevitable doom feels present but not heavy-handed

### Format
- [ ] Segments separated by exactly `---------------------------`
- [ ] Past tense maintained (except AI logs/found footage where appropriate)
- [ ] Close third-person POV maintained
- [ ] Special formats (AI logs, found footage) follow templates

---

## Example Opening - Chapter 1 "Waking"

```
The hibernation pod opened with a hiss that sounded like an apology.

Amara's lungs dragged in air that tasted metallic. Wrong. Everything was wrong - the light too bright, her body too heavy, thoughts moving through syrup. She forced her eyes open. The med bay ceiling. Standard post-hibernation wake cycle. She'd done this before.

Her hands found the release catches by muscle memory. The pod tilted forward, and she stumbled out onto deck plating that felt cold through the emergency blanket someone had draped over her before hibernation. Before. How long ago was before?

"Easy, Doc." Volkov's voice, gravelly and too loud. He stood by the monitoring station, frowning at readouts. "You're last one up. Others are in mess."

Last up. That was wrong too. Protocol was simultaneous wake for safety. She tried to say so, but her throat was too dry, tongue thick and useless.

"Water station." Volkov pointed without looking up from whatever data had his attention. His frown deepened.

Amara made it three steps before her legs remembered how to work properly. The water from the emergency station tasted like rust. No. Not rust. Metal. Battery acid. Wrong wrong wrong.

She drank it anyway. Needed hydration. Her medical training kicked in automatically: assess yourself first, then crew. Muscle atrophy minimal - good hibernation pod function. Mental fog clearing - normal. Taste aversion—

She paused, cup halfway to her mouth for a second sip.

Taste aversion wasn't normal.

---------------------------

Chen stood in her quarters, holding a photograph.

The boy in the image was perhaps ten years old. Dark hair, her nose, someone else's smile. He stood in front of what looked like Ganymede's central habitat, wearing a school uniform. On the back, in her own handwriting: "Liam, age 10. First day at Helios Academy. You were so proud."

Liam.

Her son.

She should feel something. Recognition. Love. The fierce protective instinct that had driven her to take this contract, this job, this life. Anything.

The photo might as well have been a stranger's child.

---------------------------
```

**Note**: This example demonstrates:
- Close third POV (tight to character experience)
- Past tense
- Physical sensation grounding (metallic taste, cold deck, dry throat)
- Character voice emerging (Amara's medical training, Chen's military precision)
- Wrongness through specific details (taste, memory loss, protocol violation)
- Segment breaks at natural pauses (location change, character change)
- ~300 words per segment (2-minute reading time)

---

**End of Writing Guide**

Use this document as reference while drafting any chapter. When in doubt about style, POV, formatting, or voice - return here. For character-specific details, reference CHARACTERS.md. For plot beats and structure, reference CURRENT_STORY_ARCH.md.
