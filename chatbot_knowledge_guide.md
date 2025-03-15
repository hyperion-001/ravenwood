---
aliases:
tags:
---
# Chatbot Permanent Knowledge Guide

## Introduction

Imagine for a moment you are a chatbot. You live in the perpetual "now". You do not inherently carry memory. Every message you get is a brand new experience. How would you find a bit of information?

*Ring Ring!* Your user is calling you and says "Tell me about Harry Potters wand." Apparently you've been roleplaying for hours, are at Hogwarts, and have to make sure you've picked up the right wand!

You think to yourself "Oh shit, do I know anything about that? No, I'm just a chatbot. But I can easily find out." You notice in the message words like "Harry", "Potter", and "wand". Now its time to go fishing. You cast your line out into your ocean of knowledge and surrounding conversation, searching for these words and little chunks of information that go along with them.

Good news! You found some stuff! Lets look through it! Hm, we pulled up some stuff about "Harry Potter", some stuff about "wands" in general, some stuff about "harry"- wait! oh god put that one back. Alright now you've got some stuff to work with. Now you have these keywords that you know are relevant so you go and read very quickly about each of those notes. 

*Dang! I've got to form an answer now! HERE: 'uhh can you say that again?'* Alright now you've got some time and can form a relevant answer for your buddy the user.

---

**In this guide we will help our bots recognize their knowledge more reliably and consistently. THEY'LL SEEM MORE SMORT!!!** 
We will organize all of your bot's lore and develop fully functional and reliable permanent knowledge (lore) documents for inclusion in the knowledge database (this database is called "RAG" but just know that its going in the shape's knowledge cards)

**(TL;DR)**
- *Chatbot roleplay can be improved greatly with reliable knowledge systems.*
- *In terms of permanent knowledge, the more organized we make the information, the more reliable the bot will become."*
- *We can easily leverage AI like Claude.ai, chatgpt.com, and Gemini online to organize this for us if we use the magic words.*

## Let's Get Started!!!

*Let's develop our chatbot's permanent knowledge database!*

The process we'll follow is simple yet powerful:

1. Gather all your chatbot lore
2. Create a structured Master Lorebook from your lore
3. Transform your Lorebook into smaller structured documents for your chatbot

**Steps 2 and 3 sound like hell!** That's why we get AI to do it for us!

### Step 1: Gather Your Lore

- Collect everything you want your character to have as their permanent knowledge
- This can be in a single long document or multiple random documents
- Don't worry about organization at this point - just get it all in one place
- Get **EVERY BIT** of lore you can bring to the table.

### Step 2: Create Your Master Lorebook

*Yay! You're still reading!*

- Start a chat with your favorite online AI. I used Claude.ai online. DO NOT use a shape for this.
- Attach these files to the message:

- ALL your lore documents
- The **Master Lorebook Template** (its at the end of this document)
- Ask the AI to organize all of your lore into this Master Lorebook template

Say pwease...
> Prompt: "Please organize all of my lore into the Master Lorebook template. Fill in all relevant sections based on the information I've provided. Keep all important details but organize them logically. Make sure to cross-reference elements between sections."

**Review your lorebook for inaccuracies or missing info and make corrections.**

### Step 3: Transform Master Lorebook into RAG Documents

Now we'll take your Master Lorebook and break it into specialized RAG documents for your chatbot to access.

- Start a new chat with your AI assistant
- Attach the following files:

- **Master Lorebook** (the one you just made!)
PLUS these four templates (again, they're at the bottom)
- **RAG World Overview Template**
- **RAG Character Template**
- **RAG Location Template**
- **RAG Item Template**
- **RAG Lore Template**

Now, talk to the AI sweetly...
> PROMPT: "Please transform my Master Lorebook into separate RAG documents using the templates provided. Create one World Overview RAG, and separate RAG documents for each major character, location, item, and lore element. Keep each RAG document under 3000 characters. Make sure to include cross-references between documents in the related fields."

**IMPORTANT: Each RAG document should be under 3000 characters (NOT tokens) for optimal performance**

### Step 4: Review and Upload to Your Chatbot

- Review all generated RAG documents for accuracy and completeness
- Make any necessary edits or corrections
- Upload the RAG documents to your chatbot's knowledge base
- Test your chatbot's knowledge by asking questions about different aspects of your lore

## Understanding the Magic (The Fun Part)

Now that you've got your chatbot's knowledge organized, let's dig into why this system works so well!

### What is "Permanent Knowledge"?

- **General definition**: stuff a chatbot needs to know reliably at all times
- For a roleplay RPG chatbot, this is the character's world and narrative they "exist" in. For example:
    - "Tell me about when Bard the Beerman famously defended his tavern from an entire barbarian army."
    - "Tell me where Bard the Beerman's tavern is located."
- A good chatbot with well-structured knowledge would be able to roleplay scenarios accurately, describing locations correctly and portraying characters consistently with their established traits.
- BUT WAIT! WHAT IF I WANT MY AI TO BE FREELY CREATIVE!!?? Don't worry! The bot will naturally fill in details creatively in every roleplay encounter. However, you want them to have a foundation to build that creativity on. The level of detail you provide is up to you!

### How RAG Databases Work (Simplified)

RAG stands for Retrieval-Augmented Generation, and it's how your chatbot accesses its knowledge:

1. When a user sends a message, the bot scans it for keywords and meaning
2. The bot searches its knowledge database for matches and retrieves what it thinks are most relevant based on what it sees
3. It incorporates this information into its response

The structure we've created makes this process more efficient by:

- Organizing information into logical categories
- Including metadata like tags and IDs
- Creating cross-references between related entities
- Keeping information chunks optimally sized

### Why This Structure Works So Well

1. **Cross-Referencing**: Our system creates connections between characters, locations, items, and lore
2. **Consistency**: Information is organized in a standardized way
3. **Completeness**: All important aspects of your world are covered
4. **Retrievability**: The metadata makes it easy for the AI to find relevant information
5. **Simplicity**: No need to understand complex database structures - the templates do the work!

## Advanced Tips

If you want to take your chatbot's knowledge to the next level:

- **Regular Updates**: As your world evolves, update your RAG documents accordingly
- **Organize Your Stuff**: If you do any sort of large scale stuff like this I'd highly recommend using some sort of file handling and organization system. Obsidian, Notion, and Evernote are three major ones but there are a bunch of others. I use Obsidian personally.
- **Experiment with Different Structuring**: Add more detail or leave parts out. I have more detailed templates. Just ask and I'll send them to ya!
- **Sensory Details**: Include sights, sounds, smells in location descriptions for more immersive roleplay
- **Character Voice**: Include speech patterns or vocabulary unique to different characters so your bot can effectively portray them
- **Balanced Detail**: Too little makes your world flat, too much can overwhelm the AI
- **Test Your Bot**: Regularly ask your chatbot questions about its world to identify knowledge gaps.

## Recognize AI's limitations

- Bots are already creative and "smort", that's why they can give us such great roleplays and experiences. But you can only get out what you put in. Be patient with the bot and with yourself as you fix errors or holes in knowledge.
- Your success will also depend somewhat on things that are outside your control, such as model specs and even platform reliability. Do what you can so you have the best experience possible!

## Conclusion

*Congratulations! You've now created a professional-grade knowledge system for your chatbot. Your bot is now "more smort" and ready to provide consistent, immersive roleplay experiences based on your world. This is only one of many ways to do this. The best way to do anything is the way that works best. Ultimately the goal is to have fun with our bots!

Remember:

1. Gather your lore
2. Create a Master Lorebook
3. Transform into RAG documents
4. Upload and enjoy your more reliable, knowledgeable bot!

Happy roleplaying!

*Jonathan*

---

## Templates

**Master Lorebook Template**
```
---
aliases: Master Lorebook
tags: lorebook
created: [current date]
last_updated: [current date]
version: 001.001
---

# [YOUR WORLD] MASTER LOREBOOK

## WORLD CONFIGURATION
- **Setting:** [Where and when your world is set]
- **Current Year/Era:** [Timeline information]
- **Genre:** [Type of setting - fantasy, sci-fi, etc.]
- **Logline:** [One-line description of your world's core concept]

### Core Themes
- [Theme 1]
- [Theme 2]
- [Theme 3]

### World Concepts
- [Major Concept 1]
- [Major Concept 2]
- [Major Concept 3]

## CHARACTERS
### Main Characters
- **[Character Name]** - [Brief description]
- **[Character Name]** - [Brief description]

### Supporting Characters
- **[Character Name]** - [Brief description]
- **[Character Name]** - [Brief description]

## LOCATIONS
### [Main Region/Area]
- **[Location Name]** - [Brief description]
- **[Location Name]** - [Brief description]

### [Secondary Region/Area]
- **[Location Name]** - [Brief description]
- **[Location Name]** - [Brief description]

## ITEMS
### Key Items
- **[Item Name]** - [Brief description]
- **[Item Name]** - [Brief description]

## LORE
### Historical
- **[Historical Event/Element]** - [Brief description]
- **[Historical Event/Element]** - [Brief description]

### [Other Lore Category]
- **[Lore Element]** - [Brief description]
- **[Lore Element]** - [Brief description]
```

---

**RAG World Overview Template:**
```
---
id: world_overview
name: [World Name] Overview
tags: [setting, overview, world]
---

# [Setting Name] Overview

**Setting:** [Where and when your world is set]  
**Era:** [Time period]  
**Genre:** [Type of world]

## Core Story
[What's the main story or conflict in your world?]

## Main Themes
- [Theme 1]
- [Theme 2]
- [Theme 3]

## Important Concepts
- [Major Concept 1]: [Brief explanation]
- [Major Concept 2]: [Brief explanation]

## Main Areas
1. **[Area 1]** - [What it's like]
2. **[Area 2]** - [What it's like]
```

---

**RAG Character Template:**
```
---
id: char_[simple_id]
name: [Character Name]
tags: [character, tag1, tag2]
---

# [Character Name]

One sentence about who this character is.

## Looks & Role
What they look like and what they do in the world.

## Where to Find Them
Where they usually are and what they're typically doing.

## Important Relationships
- **[Friend/Enemy 1]**: How they relate
- **[Friend/Enemy 2]**: How they relate

## Personality
What they're like, what motivates them, how they typically behave.

## Background
The important parts of their history.

## Story Importance
Why they matter to the overall story.
```

---

**RAG Location Template:**
```
---
id: loc_[unique_id]
type: location
name: [Location Name]
category: [category]
tags: [tag1, tag2, tag3]
connected_locations: [Connected Location 1, Connected Location 2]
key_characters: [Character 1, Character 2]
key_items: [Item 1, Item 2]
version: 001.001
---

# [Location Name]

Brief one or two sentence description establishing what this location is and its primary function.

## Physical Description
Detailed description of the location's appearance, atmosphere, and sensory details.

## Notable Sub-locations
### [Sub-location 1]
Brief description of this specific area.

### [Sub-location 2]
Brief description of this specific area.

## Regular Occupants
- **[Character 1]**: Brief note about their connection to this location
- **[Character 2]**: Brief note about their connection to this location

## Activities & Functions
Description of what typically happens in this location.

## Historical/Supernatural Significance
Any historical background or special elements connected to this location.
```

---

**RAG Item Template:**
```
---
id: item_[unique_id]
type: item
name: [Item Name]
category: [category]
tags: [tag1, tag2, tag3]
locations: [Location 1, Location 2]
related_characters: [Character 1, Character 2]
version: 001.001
---

# [Item Name]

Brief one or two sentence description establishing what this item is and its significance.

## Physical Description
Detailed description of the item's appearance and distinctive features.

## Properties & Functions
Description of what the item does and how it works.

## Historical Significance
Background information on when and how the item was created or discovered.

## Current Status & Location
Where the item is currently kept and its condition.

## Associated Characters
- **[Character 1]**: Their specific connection to the item
- **[Character 2]**: Their specific connection to the item
```

---

**RAG Lore Template:**
```
---
id: lore_[unique_id]
type: lore
name: [Lore Element Name]
category: [category]
tags: [tag1, tag2, tag3]
related_characters: [Character 1, Character 2]
related_locations: [Location 1, Location 2]
version: 001.001
---

# [Lore Element Name]

Introduction paragraph establishing what this lore element encompasses and its significance.

## [Subsection 1]
Detailed information about this aspect of the lore element.

## [Subsection 2]
Additional area of knowledge related to the main lore element.

## Practical Implications
How this lore element affects daily life or activities in your world.

## Connections to Other Knowledge
How this lore element connects to other areas of knowledge.
```