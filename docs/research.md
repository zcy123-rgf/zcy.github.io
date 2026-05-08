# 1. Motivation & Research

---

## 1.1 Project Background & Motivation
Suzhou Maple Bridge is a well-known cultural landmark deeply connected to poetry, the Grand Canal heritage, and urban memory. However, current on-site experiences remain static, text-based, and lack meaningful interaction, leading to limited visitor engagement, low immersion, and poor memorability.

As shown in our poster’s problem analysis, these pain points are particularly prominent for:
- International tourists who struggle with text-heavy, language-dependent information.
- Domestic visitors who often pass by historical markers without deep engagement.
- Local residents who seek richer, more layered context beyond basic explanations.

This project aims to reimagine Maple Bridge as a **playful and immersive journey through AR, AI dialogue, photo check-ins, and fragment collection**, transforming passive sightseeing into active, memorable cultural exploration.

---

## 1.2 Literature & Competitor Analysis

### Key Insights from Academic Research
We reviewed four studies on digital heritage and AR tourism to inform our design:

1.  **Maubisson et al. (2022)** highlighted the potential of AR to enhance cultural heritage experiences by adding interactive and immersive layers, which inspired our AR overlay and location-based triggers.
2.  **Tang et al. (2026)** discussed how conversational AI can help users query and explore large-scale digitized heritage collections, informing our AI dialogue system design.
3.  **Borges et al. (2023)** provided a systematic review of gamification in cultural heritage, showing that collection-based motivation significantly improves user engagement and long-term retention.
4.  **Garro & Sundstedt (2022)** presented frameworks for location-based storytelling in outdoor heritage sites, which we adapted to the unique environment of Maple Bridge.

- **Common Strengths Across Research**:
  - Proven effectiveness of AR in increasing visitor engagement and cultural learning.
  - Established frameworks for location-based storytelling in heritage contexts.
  - Evidence that gamification improves long-term retention of cultural content.
- **Common Weaknesses & Gaps**:
  - Most studies focus on indoor museum environments, not outdoor heritage sites like Maple Bridge.
  - Few frameworks support dual-mode experiences for both tourists and locals.
  - Limited discussion of integrated AR/AI dialogue systems in on-site, real-time heritage interpretation.

### Commercial Product Benchmarking
We analyzed four similar AR tourism applications to identify strengths and gaps in existing solutions:

1.  **Google Arts & Culture**: Offers virtual tours and AR views of heritage sites, with intuitive map navigation but lacks deep, culturally relevant storytelling and gamified progression.
2.  **Wintor AR Tours**: Provides location-based AR overlays for various destinations, with visually appealing effects but generic content that fails to connect with local history.
3.  **Dunhuang Mogao Grottoes Digital Guide**: Features high-quality AR murals but lacks multilingual support and AI-driven dialogue for personalized learning.
4.  **Pokémon GO (Heritage Events)**: Demonstrates strong gamification and reward systems but has shallow integration with cultural heritage and no educational focus.

- **Common Strengths Across Products**:
  - Intuitive map navigation and location tracking features.
  - Visually appealing AR overlays and photo-sharing tools.
  - Strong gamification and reward systems to keep users engaged.
- **Common Weaknesses & Gaps**:
  - Most lack deep, culturally relevant storytelling and educational content.
  - No support for different experience levels (tourist vs. student) or dual-mode interaction.
  - Limited multilingual support and accessibility features for international users.

Our project addresses these gaps by combining **AR interactions, AI dialogue, photo check-ins, and fragment collection** into a unified experience that works for both casual tourists and curious learners.

---

## 1.3 User Personas & Stakeholders

## 1.3 User Personas & Stakeholders

### Persona 1: Liam (Male, 24, UK)
- **Profile**: 24-year-old solo backpacker from the UK, travelling across China independently. He is interested in traditional Chinese culture and historic heritage, with limited Mandarin.
- **Goals**: Understand the cultural stories behind Maple Bridge; take authentic travel photos; enjoy a simple, engaging, and time-efficient experience.
- **Frustrations**: Language barriers make local introductions hard to understand; traditional text signage is boring and not tourist-friendly; lack of clear guidance.
- **Behaviour**: Curious, open-minded, enjoys interactive AR/AI experiences, and likes sharing travel moments on social media.

![Persona: Liam](../assets/images/personas/liam.jpg)

---

### Persona 2: Emma (Female, 27, Canada)
- **Profile**: 27-year-old marketing professional and photographer from Canada, travelling with friends. She loves ancient Chinese architecture and cultural heritage.
- **Goals**: Take high-quality artistic photos at Maple Bridge; learn the story of the famous poem easily; gain an immersive and memorable experience.
- **Frustrations**: Long text explanations are overwhelming; hard to find good photo spots; difficult to connect with local history and culture.
- **Behaviour**: Aesthetic-focused, detail-oriented, prefers visual and interactive experiences, and enjoys sharing refined travel content online.

![Persona: Emma](../assets/images/personas/emma.jpg)

---

### 3. Scenarios
#### Scenario 1: Lin using Quick Explore
- **User**: Lin, a tourist
- **Context**: Weekend afternoon at Maple Bridge, with only one hour to spend and her friends.
- **Actions**: Opens the app, selects Quick Explore, follows the interactive map to the bridge, triggers AR overlays, listens to a short AI-generated story about the poem, completes a photo check-in task, and unlocks a cultural fragment.
- **Goal**: Finish the visit quickly and get shareable content for social media.
- **Outcome**: She finds the experience fun and memorable, and easily understands the basic story behind Maple Bridge.

#### Scenario 2: Yuhan using Deep Explore
- **User**: Yuhan, a local student
- **Context**: Weekend morning at Maple Bridge, with two hours for research on the Grand Canal.
- **Actions**: Opens the app, selects Deep Explore, uses the AI dialogue system to ask questions about the bridge’s role in the canal system, browses historical maps, and completes deeper photo tasks to unlock detailed fragments.
- **Goal**: Build a full picture of Maple Bridge’s history for his coursework.
- **Outcome**: He gains detailed, multi-dimensional information that goes beyond the poem, deepening his understanding of the site.

---

### 4. Use Cases (Based on AR/AI Interaction System)
#### Use Case 1: User navigates the app flow (Main Flow)
1. User opens the app and is greeted with the home screen, showing two mode options: Quick Explore / Deep Explore.
2. User selects a mode and is taken to the interactive map.
3. User follows location guidance to the first story point.
4. Upon arrival, the system triggers an AR overlay or AI story prompt.
5. User completes an interaction (photo check-in, AR task, or AI dialogue).
6. The app unlocks a cultural fragment and updates the user’s collection.
7. User can view their progress, leaderboard, and share their achievements.

#### Use Case 2: User interacts with AR content (Main Flow)
1. User reaches a story point with AR-enabled content.
2. The app displays an AR prompt (e.g., “Point your camera at the bridge to see its historical form”).
3. User points their device at the target location.
4. The system renders AR content (e.g., historical reconstructions, animated poems) over the live camera view.
5. User takes a photo or completes a simple task to confirm engagement.
6. The app rewards the user with a fragment and unlocks the next step.

#### Use Case 3: User uses AI dialogue to learn more (Main Flow)
1. User selects Deep Explore mode and taps the AI chat icon.
2. The AI assistant greets the user and asks, “What would you like to learn about Maple Bridge today?”
3. User asks a question (e.g., “What role did Maple Bridge play in the Grand Canal trade?”).
4. The system generates a detailed, context-aware response with additional context.
5. The user can follow up with more questions or return to the map view.

#### Use Case 4: Weak GPS Signal / Location Not Found (Exception Flow)
1. The app cannot get a strong GPS signal to trigger story points.
2. The system displays a message: “Weak signal detected. Please move to an open area or enter your location manually.”
3. The user either moves to a better location or enters the location manually.
4. The system re-establishes location and triggers the relevant AR/AI content.

---

## References
1. Maubisson, L., Rivière, A., & Coutelle, P. (2022). An Analytical and Comparative Approach to Cultural Heritage Experiences Enhanced with Augmented Reality. *Tourism Management Research*.
2. Tang, L., et al. (2026). Conversational AI-Enhanced Exploration System to Query Large-Scale Digitised Collections of Natural History Museums. arXiv preprint.
3. Borges, F., Almeida, M. P., & Silva, C. M. (2023). A Systematic Literature Review of Gamification for Cultural Heritage. *MDPI*.
4. Garro, V., & Sundstedt, V. (2022). Augmented Reality and 3D Printing for Archaeological Heritage: Evaluation of Visitor Experience. In *Extended Reality*. Springer.
