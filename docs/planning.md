# Desk Buddy: Project Plan

Written in [GitHub issue #1](https://github.com/ibrahim787898m/desk_buddy/issues/1).

## Problem Statement
When I am doing a coding session or studying something or doing a project, sometimes I get exhausted, I feel bored and cant focus on my task. Desk Buddy is a cute little desk companion that will stay with me on my computer screen while I am doing my tasks and interact with me so that I can focus on my tasks or do some relaxation interacting back with it to recharge.

## Requirements (must have / nice to have)
### Must have:
  - A cute little character that can be displayed on the desktop screen maybe in a corner of the screen.
  - I can close it or minimize it if I want to by clicking on it or using a keyboard shortcut.
  - I can move the character around the screen.
  - If I click it or poke it, it should respond with some animation or sound.
  - If I am studying or coding quietly, it should be able to detect that and not disturb me. But if i am not stopping for a long time, it should remind me to take a break. A focus or lecture mode where it will not disturb me, I can turn on or off this mode by clicking on it or using a keyboard shortcut.

### Nice to have:
  - The character should have different personalities or behaviors based on the user's mood or activity.
  - It should be able to learn from the user's interactions and adapt its behavior accordingly.
  - The character should have a unique voice or speech pattern that makes it more engaging.
  - The character should be able to give me reminders or notifications for my tasks or events.
  - If I am taking lecture or studying, it should be able to detect that and not disturb me.

## MVP definition
MVP (Minimum Viable Product) is a cute little character that can be displayed on the desktop screen, can be moved around, and responds to clicks or pokes with animations or sounds. And user can close or minimize the character using keyboard shortcuts.
### MVP includes:
- A cute little character that can be displayed on the desktop screen.
- The character can be moved around the screen.
- The character responds to clicks or pokes with animations or sounds.
- Using keyboard shortcuts, the user can close or minimize the character.

### Not in MVP:
- Break reminder when I've been working too long.

## Design sketch (character + state)

### Character
- Keycap body: two rounded squares (back darker, front lighter)
- Front-facing in all states
- Oval arms, oval feet, no guideline

### States
- **Normal:** dot eyes, "w" mouth, arms down
- **Poked:** wide eyes, "O" mouth, blush, one arm up
- **Dragged:** worried eyes, frown, tilted, legs dangling
- **Busy (after MVP):** round glasses, small smile

### State transitions
- Normal → Poked: when clicked or poked
- Poked → Normal: after 2 seconds of being poked
- Normal → Dragged: when dragged
- Dragged → Normal: when released


## Open Questions
- Clicked vs Dragged: How to differentiate between a click and a drag? Should I use a threshold for the distance moved?