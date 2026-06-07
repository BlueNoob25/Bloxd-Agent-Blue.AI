<img width="872" height="372" alt="Post_Media_6a07785c884d1" src="https://github.com/user-attachments/assets/4044769b-28bc-4fcc-8270-dc9e35d88173" />

# Introduction to Bloxd Agent Blue
Welcome to the current biggest Bloxd.io AI, Bloxd Agent Blue!

## What does it know?
The AI, being a specialized AI, has a deep understanding of the Bloxd.io platform and its community.

*What can I ask it about?*

You may ask it about:
 - The official games and features on the game, based off of the [Bloxd Wiki](https://bloxd-io.fandom.com/wiki/Bloxd.io_Wiki)
 - The platform's third-party websites, such as [Bloxdhub](https://bloxdhub.com/) and [BloxdForge](https://www.bloxdforge.com/) *(based off of the [Bloxdhub info section](https://bloxdhub.com/info) and [BloxdForge Blogs & Guides](https://www.bloxdforge.com/studio/wiki))*
 - The general community
 - Code generation/Mod creation
 - Texture Packs (image & 3d modeling help)
 - Official Lore

<img width="1366" height="768" alt="Screenshot 2026-06-03 5 36 55 PM" src="https://github.com/user-attachments/assets/4fe9f043-64c5-432c-a1a1-33f393392563" />

*The Homepage*

## How likely is it to present hallucinations?
After thorough testing, we've seen an estimated 10% of hallucinations (Roughly 1/10 responses could contain false information). It may vary, however. We've trained it to be honest and humble, admitting when it may have false information most of the time. It understands the importance of honesty well, and also understands if it's presenting information that it is unsure about.

The AI is able to do a self-review on itself, which means it will check its response's first draft for any inconsistencies, unclickable links, **or halluncinations**.

You can check if the AI is unsure by looking for:
 - words like "likely/unlikely", "maybe", "could/could not be", "may/may not".
 - instances where it tried to look at its training notes/context files or pull information from trusted sources but ultimately could not reach it, yet still tried to present information to you.

## Using the AI

The AI is versatile and has a mediocre ability to analyze web pages, however due to it being a specialist AI meant for the game [Bloxd.io](https://bloxd.io/), feeding it unrelated sites and pages may alter its knowledge and ability.

The AI will NOT generate images/texture packs as a anti-slop filter, the AI is supposed to be a helpful tool. Instead, the AI will only suggest images, but it will never make them.

We actually plan to add a feature where it will generate schematics, however, since it would just pull from existing blocks (and if it tries to add non-existent blocks, the game will likely flag the schematic file as invalid).

The AI has 4 different modes built to guide users on a selected topic. These 4 modes range from general help to coding to analyzing community posts.

These 4 modes include:
### Chatbot
The general AI, with no specific focus on any aspect of Bloxd.io. Great for general help or help that any of the other modes do not promise.
### Code Helper
As the name suggests, when this mode is selected the AI will guide users on Bloxd.io coding. It will generate a code and explain part-by-part what each part does.
### Post Analyst
When this mode is selected, you can give the AI a specific post on any social media site that they have questions about, and the AI will break it down and explain what the post creator's intent may have been on each part, as well as suggesting comments you can make on the post.
### Mod Constructor (suggested by XxDRAGON_OPxX)
When this mod is enabled, you can type an idea for a Bloxd.io mod and the AI will bring it to life! It will provide the code, as well as suggesting a title and description, along with a thumbnail idea and 3 image ideas.
###
<img width="580" height="262" alt="Screenshot 2026-06-03 5 37 08 PM" src="https://github.com/user-attachments/assets/4f4cc6cf-5d14-4dd7-87d4-81636d2957d5" />

*The prompt box, featuring the 4 modes, the connectors, the `"Update Memory"` button, and the `"Prefs"` button in its off state.*

---

## Features

There is a separate page called [`"Script Editor"`](https://bloxd-agent-blue.base44.app/script-editor) that allows you to edit your code, and then simply ask the AI directly on the sidebar to edit the code, give suggestions, package it into a mod, or just describe it without the hassle of copying and pasting after each edit.
*For more info on the Script Editor, scroll down.*

You have the ability to connect one or multiple chats to a current one for a single response. This feature can be accessed by clicking the `"Update Memory"` button above the prompt box. An example use of this feature can be if you want to make a code change from one chat but you also want the AI to remember things from another chat to influence the code change.

Another feature is called `"reprompting"` which is a way for people to resend (and possibly add more context) to a previous prompt. This can be useful if an AI has picked up new information between the last time you sent the prompt and now. It is very useful for long prompts you plan to resend.

When typing a prompt, You have the ability to use markup formatting, especially `inline code`, which can help differentiate the regular text with code. Users may also begin a new line using `Shift` + `Enter`.

You also have the ability to, at the home page, choose one of four prompts to begin a conversation. These are called `"Suggested Prompts"` and range from questions about Bloxd.io to its third-party sites to coding and rules.

You can also personalize the AI. After each response, you can like or dislike the response, optionally explain why, and the AI will save the feedback to its memory. You can disable the preferences anytime by clicking the "`Disable Prefs`" button, and then reenable it by clicking the button again.

Editing prompts and redoing AI responses are possible, but are still in beta.

Simple taglines that will be randomly chosen and will be displayed at the front page upon loading. The `reload` button can also display a random tagline.

Current homepage taglines (4 in total):
 - "Your AI assistant for everything Bloxdhub & Bloxd.io" (Before the other taglines, this was the only one)
 - "Bloxdly's more agentic competition"
 - "Ask me anything Bloxd, or don't. Your choice."
 - "Tips? I am tips."

Current `Script Editor` taglines:
 - "Bloxd coding sucks half the time. Thankfully there's an agent for that now."

There is also a sidebar that allows users to access their previous live and archived chats and rename them.
###
<img width="114" height="384" alt="Screenshot 2026-06-03 5 39 18 PM" src="https://github.com/user-attachments/assets/8c73a202-46eb-4949-8942-968cf2ad1c5f" />

*The Sidebar*
###
## Settings
Another feature is the Settings tab which allows you to customize their experience with Bloxd Agent Blue. The following is in settings:
### Themes
You can pick from one of four themes, `"Blue's Default"` (the default theme), `"Dark Crimson"` (a red variant of the default theme), `"Basic theme"` (A ChatGPT-like style), and `"Old Bhub"` (A version of the old setup of the AI's predecessor *(NOTE: this theme changes much of the UI, while it will not ruin the functions it may still confuse you!)*).
### Glowing Background
When enabled, the background will have a glow effect.
### Liquid Glass (beta)
When enabled, parts of the UI will be partially transparent. The current bugs are:
 - It overlaps the UI that isn't affected by Liquid Glass.
 - It looks bad in general.

*NOTE: The glowing background and Liquid Glass effects only works on the `"Blue's Default"` and `"Dark Crimson"` themes. This is intentional as the other current themes were not intended with a glow (For example the `"Basic theme"` theme doesn't have a glow because it was intended to have a basic UI and color scheme. `"Old Bhub"` is an attempted recreation of UI that the predecessor was in and the original version did not have a glow, so neither will the recreation.)*
### TL;DR Mode (Currently bugged)
This feature allows you to have a short response from the AI instead of a long one. There will be a button at the bottom of the response where users can see the longer, full response. Users can switch between short and long anytime when this mode is on.
### Suggested Prompts
When enabled, there will be a set of 4 entry prompts that users can choose to begin a conversation with the AI. Currently these are static and do not change, but hopefully in the future these will become more versatille.
####
<img width="117" height="384" alt="Screenshot 2026-06-03 5 37 58 PM" src="https://github.com/user-attachments/assets/1dd7bfdc-768a-40be-afe3-adf74a49f3e9" />

*The Settings Tab*
###
# The Script Editor
This is a dedicated page for coding, with the help of the AI agent. It was built to reduce the inconvenience that came with constantly copying and pasting code after each edit, whether by the user or the AI. Instead, users can paste and/or edit their code here, and they can also decide to use the sidebar to communicate with the AI and have their code be edited by it.

Here, you can also copy the code, or save it as a `.js` or `.txt` file.
###
<img width="683" height="384" alt="Screenshot 2026-06-03 5 39 41 PM" src="https://github.com/user-attachments/assets/c5e1240e-389e-41ad-b06f-fdea1ddc42d8" />

*The Script Editor*

---

*Created by BNThegreatestgamer_ev, aka BlueNoob on Bloxdhub, aka u/Zestyclose_Job_5735 on reddit.*
