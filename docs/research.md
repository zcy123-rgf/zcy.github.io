# 1. Motivation & Research

---

## 1.1 Project Background & Motivation
Suzhou Maple Bridge is a significant cultural heritage site with rich poetic history and deep ties to the Grand Canal. However, current on-site experiences are mostly static and text-based, leading to low visitor engagement, weak immersion, and poor memorability.

This project aims to solve these pain points by building a playful, immersive, and human-centric interactive experience using XR, generative AI, and location-based storytelling. The goal is to transform a passive visit into an active, engaging journey that caters to both casual tourists and curious local students.

---

## 1.2 Literature & Competitor Analysis

### Key Insights from Academic Research
We reviewed four studies on digital heritage and AR tourism to identify proven approaches and existing gaps:

1.  **Huang, Y. (2025)** confirmed that AR and AI significantly increase visitor engagement and cultural learning in heritage contexts, providing a strong theoretical basis for our project.
2.  **Garro & Sundstedt (2022)** presented research frameworks for location-based storytelling, which we adapted for our outdoor site at Maple Bridge.
3.  **Tan et al. (2025)** found that gamification improves long-term retention of cultural content, supporting our fragment collection and reward system design.
4.  **Sánchez-Martín et al. (2025)** discussed AI integration in heritage tourism but noted a lack of real-time, on-site applications, which our project aims to address.

- **Common Strengths Across Research**:
  - Proven effectiveness of AR in increasing visitor engagement and cultural learning.
  - Established frameworks for location-based storytelling in heritage contexts.
  - Evidence that gamification improves long-term retention of cultural content.
- **Common Weaknesses & Gaps**:
  - Most studies focus on indoor museum environments, not outdoor heritage sites.
  - Few frameworks support dual-mode experiences for both tourists and locals.
  - Limited discussion of AI integration in on-site, real-time heritage interpretation.

### Commercial Product Benchmarking
We analyzed four similar AR tourism applications to understand existing market solutions:

1.  **Google Arts & Culture**: Offers virtual tours and AR views of heritage sites, with intuitive map navigation but lacks deep, culturally relevant storytelling.
2.  **Wintor AR Tours**: Provides location-based AR overlays for various destinations, with visually appealing effects but generic content.
3.  **Dunhuang Mogao Grottoes Digital Guide**: Features high-quality AR murals but lacks multilingual support and educational depth.
4.  **Pokémon GO (Heritage Events)**: Demonstrates strong gamification and reward systems but has shallow integration with cultural heritage.

- **Common Strengths Across Products**:
  - Intuitive map navigation and location tracking features.
  - Visually appealing AR overlays and photo-sharing tools.
  - Strong gamification and reward systems to keep users engaged.
- **Common Weaknesses & Gaps**:
  - Most lack deep, culturally relevant storytelling and educational content.
  - No support for different experience levels (tourist vs. student).
  - Limited multilingual support and accessibility features for international users.

---

## 1.3 User Personas & Stakeholders

### 1. Primary User Persona: Lin (Tourist, Quick Explore Mode)
- **Profile**: 21-year-old college student from out of town, visiting Suzhou for the first time with friends. She has limited time and is looking for a fun, shareable experience.
- **Goals**: Quickly understand why Maple Bridge is famous, take memorable photos, and learn basic cultural facts without reading long texts.
- **Frustrations**: Heritage sites rely too much on static text, making it hard to connect the current site with its historical meaning.
- **Behaviour**: Prefers photo-taking and interactive experiences; often uses mobile apps for on-the-go information.

### 2. Secondary User Persona: Yuhan (Local Student, Deep Explore Mode)
- **Profile**: 20-year-old university student in Suzhou, interested in the Grand Canal’s history and local culture. He has more time for in-depth learning.
- **Goals**: Explore the layered history of Maple Bridge, understand its role in the canal system, and find details not covered in textbooks.
- **Frustrations**: Most on-site information only focuses on the famous poem, ignoring the bridge’s broader historical context.
- **Behaviour**: Enjoys reading and asking questions; seeks detailed narratives and visual comparisons (e.g., historical maps).

---

### 3. Scenarios
#### Scenario 1: Lin using Quick Explore
- **User**: Lin, a tourist
- **Context**: Weekend afternoon at Maple Bridge, with only one hour to spend and her friends.
- **Actions**: Opens the app, selects Quick Explore, follows the map to the bridge, triggers AR effects, listens to a short story about the poem, completes a photo task, and unlocks a cultural fragment.
- **Goal**: Finish the visit quickly and get content to share on social media.
- **Outcome**: She finds the experience fun and memorable, and easily understands the basic story behind Maple Bridge.

#### Scenario 2: Yuhan using Deep Explore
- **User**: Yuhan, a local student
- **Context**: Weekend morning at Maple Bridge, with two hours for research on the Grand Canal.
- **Actions**: Opens the app, selects Deep Explore, asks the AI about the bridge’s role in the canal system, browses historical maps, and explores different layers of context.
- **Goal**: Build a full picture of Maple Bridge’s history for his coursework.
- **Outcome**: He gains detailed, multi-dimensional information that goes beyond the poem, deepening his understanding of the site.

---

### 4. Use Cases
#### Use Case 1: User selects Quick Explore (Main Flow)
1. User opens the app and sees two mode options: Quick Explore / Deep Explore.
2. User selects Quick Explore.
3. The app loads a simplified map and light AR content.
4. User navigates to the first story point using location guidance.
5. When the user arrives, the system triggers AR overlays and a short audio story.
6. User completes a photo or simple task to unlock a cultural fragment.
7. The app updates progress and adds the fragment to the collection.

#### Use Case 2: User selects Deep Explore (Main Flow)
1. User opens the app and sees two mode options: Quick Explore / Deep Explore.
2. User selects Deep Explore.
3. The app loads full historical data, maps, and multi-layered narratives.
4. User interacts with the AI chatbot to ask specific questions about history or culture.
5. The system provides detailed explanations, timelines, and related references.
6. User browses additional materials (e.g., historical photos, academic notes).
7. The app saves learning progress and allows users to revisit content later.

#### Use Case 3: Weak GPS Signal / Location Not Found (Exception Flow)
1. The app cannot get a strong GPS signal to trigger story points.
2. The system displays a message: “Weak signal detected. Please move to an open area or enter your location manually.”
3. The user either moves to a better location or enters the location manually.
4. The system re-establishes location and triggers the relevant content.

---

## References
1. Huang, Y. (2025). Embodied Experiences Reshape Tourist Perceptions: A Computational Analysis of VR, AR, and AI in Heritage Tourism. *Proceedings of the 2025 ACM International Conference on Multimedia (MM ’25)*. https://doi.org/10.1145/3788731.3788737
2. Garro, V., & Sundstedt, V. (2022). Augmented Reality and 3D Printing for Archaeological Heritage: Evaluation of Visitor Experience. *Extended Reality*. Springer. https://doi.org/10.1007/978-3-031-15553-6_25
3. Tan, G.-S., Ahmad, Z., & Ab. Aziz, K. (2025). Travelers’ Continuance Intention to Use Mobile Augmented Reality App in UNESCO World Heritage Sites. *Tourism and Hospitality*, 6(4), 192. https://doi.org/10.3390/tourismhosp6040192
4. Sánchez-Martín, J.-M., Guillén-Peñafiel, R., & Hernández Carretero, A.-M. (2025). Artificial Intelligence in Heritage Tourism: Innovation, Accessibility, and Sustainability in the Digital Age. *Heritage*, 8(10), 428. https://doi.org/10.3390/heritage8100428
