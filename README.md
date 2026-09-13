# Plot Twist — Three-Screen Design Rationale

[Revised live prototype](https://is-551-first-three-screens-gigi.vercel.app/) · [Initial AI prototype](https://plot-twist-initial-gigi.vercel.app) · [Initial commit](https://github.com/Gegeennaran/IS-551-First-Three-Screens-Gigi/commit/98a752743dd8260724cf5304af40918198630eae)

## 1. Need, Persona, Capability, and Value

1. **Need — why the person is looking:** At the end of a long day, people experience decision fatigue and spend an entire hour choosing a movie to watch.
2. **Persona — who is most likely to jump on board first:** Someone who watches movies two or three times a week, watches movies in the evening, has one or two hours to watch a movie in the evening, and also loves to play quick, fun games on their phone.
3. **Capability — the key observable action the product lets them complete:** Find a movie or show to watch with minimal, clear reference and without much thinking or deciding.
4. **Value — what is materially or emotionally better afterward:** Faster, but fun. The person is able to choose a movie to watch without stress or spending too much time deciding.

## 2. Why These Three Screens?

| Screen | Single job and reason it earned a slot | Design question |
| --- | --- | --- |
| **1. Landing** | Signal the capability and benefit with one “Find my movie” action; establish a reason to begin. | Can someone understand the purpose within five seconds? |
| **2. Preferences** | Collect genre and runtime separately from the game; make the recommendation relevant. | Can users provide enough direction without feeling burdened? |
| **3. Matching game** | Unlock a suitable movie through play; deliver the experience promised on the landing. | Does play make choosing enjoyable, or add effort for tired users? |

The style is minimalist, colorful, and uplifting. The movie reveal completes screen 3’s flow.

## 3. Design Question Plan

### Need

- **Tell me about the last time you were trying to pick a movie at the end of the day. How long did it take?** I am usually so exhausted to pick a movie and there are so many choices. I spent at least 30 min to find a movie to watch.
  - **Part of the prototype it rests on:** The landing message, “Find your movie. Skip the scroll,” addresses endless browsing. The two preference questions narrow the choices before the game reveals one movie.
- **What makes you give up on picking a movie and end up not watching anything?** Exhaustion from choosing a movie, already spent so much time, so I have to sleep.
  - **Part of the prototype it rests on:** The brief preference screen and single movie recommendation are intended to reduce decision effort before the user runs out of time or energy.

### Value

- **If the struggle of picking a movie were solved for you, what is one or two words that describe the value you see? Why?** Time. Because I spend so much time on picking a movie and usually it’s late night, so time is essential for me.
  - **Part of the prototype it rests on:** Two quick questions, one short matching game, and one movie recommendation are intended to save selection time. Actual time savings still need testing.

### Persona

- **Who else do you know who deals with struggling to pick a movie at the end of the day?** My spouse/ friends.
  - **Part of the prototype it rests on:** The evening-focused movie selection flow and runtime choices fit people with limited viewing time. Whether the participant’s spouse or friends would use it still needs testing.

### Capability

- **I am going to show you this screen for five seconds. (Hide it.) What does this product do?** Helps me to find a movie
  - **Part of the prototype it rests on:** The landing headline, “Find your movie. Skip the scroll,” and the “Find my movie” button directly communicate the primary capability.

## 4. Design Justification, First Read, and Revisions

On the live landing, the headline, single button, whitespace, and movie illustration signal purpose before detailed reading. Supporting copy explains the game. Most elements earn their place, although orange **“Skip the scroll”** attracts too much attention relative to the capability line. Reducing that emphasis remains a possible refinement.

- **Landing simplification — visual hierarchy and cognitive load:** The [initial AI prototype](https://plot-twist-initial-gigi.vercel.app) combined slogans, a large illustration, a badge, a three-step strip, and footer messages. Competing signals weakened the primary action. The [revised screen](https://is-551-first-three-screens-gigi.vercel.app/) uses one headline, brief explanation, one button, and a smaller illustration. This addresses the five-second comprehension question.
- **Grouping — similarity and proximity:** Consistent typography and controls connect the screens. Proximity groups genre and runtime choices under their respective questions. Equal blue card backs and grid spacing communicate one matching set. Removing mixed colors avoids implying different categories, addressing whether the game feels clear rather than confusing.
- **Navigation — signifiers and user control:** Explicit Home buttons remove reliance on the logo or ambiguous Back labels. Preferences, game, and result stay on mission while providing an obvious return to the landing.

The important revisions improved hierarchy, grouping, and navigation—not just appearance.
