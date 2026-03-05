# Product Requirements Document (PRD)
## Project: QuestLingo Kids (working title)
## Version: v1.0 (Foundational PRD)
## Date: 2026-03-05
## Author: Product Team (with founder input)

---

## 1) Product Vision
Create a joyful, game-first language learning app for children ages **2–6** that teaches **early Spanish literacy and communication** through stories, quests, immersive play, and age-appropriate repetition—without ads, in-app purchases, or tracking-based monetization.

The app should feel like a fun adventure game where learning happens naturally, not like a traditional classroom.

---

## 2) Problem Statement
Parents want high-quality language learning tools for young children, but many options are either:
- Too passive (mostly video watching),
- Too repetitive/rote,
- Not developmentally appropriate for pre-readers,
- Not structured enough for measurable proficiency gains,
- Or monetized in ways that conflict with child safety and trust.

Children 2–6 need short, visual, interactive learning loops with strong phonics support, clear progression, and positive motivation.

---

## 3) Goals and Non-Goals

### 3.1 Primary Goals
1. Help children build foundational Spanish skills (listening, speaking, phonics, early reading, early writing patterns).
2. Drive daily habit formation via gentle, fun reminders and rewarding progression.
3. Make lessons engaging through game loops, story quests, visual matching, and native-speaker audio.
4. Provide structured curriculum depth while preserving a playful experience.
5. Support parents with clear progress visibility and safe social features.

### 3.2 Secondary Goals
1. Build a scalable course architecture for future languages.
2. Establish experimentation framework (A/B tests) to improve engagement and outcomes.
3. Prepare foundation for AI-supported roleplay/conversation features.

### 3.3 Non-Goals (MVP)
1. No open social networking/chat between children.
2. No ad-based monetization.
3. No broad multi-language rollout on day one (Spanish-first).
4. No unrestricted generative AI exposed directly to children without guardrails.

---

## 4) Target Users

### 4.1 Primary User
- **Child learner (age 2–6)**
- Subsegments:
  - 2–3: pre-reader, high visual/audio dependency, very short interaction windows.
  - 4–5: beginning phonics and letter recognition.
  - 5–6: early reading confidence, simple sentence practice.

### 4.2 Secondary User
- **Parent/guardian**
- Needs: safety, clear educational value, progress tracking, routine support.

### 4.3 Tertiary User (later)
- Educators/homeschool facilitators.

---

## 5) Core Product Principles
1. **Gamification first**: learning disguised as adventure and play.
2. **Child-safe by default**: privacy-first architecture and moderated interactions.
3. **Dynamic immersion**: Spanish-first experiences with contextual English support.
4. **Bite-sized mastery**: lessons in small chunks with immediate feedback.
5. **Evidence-guided iteration**: test, measure, improve.
6. **No dark patterns**: motivating, non-intrusive reminders and ethical design.

---

## 6) Value Proposition
For families with preschool children, QuestLingo Kids is a playful language-learning app that combines story quests, immersive vocabulary games, and native-speaker pronunciation practice to build real-world Spanish communication foundations—while staying ad-free, safe, and developmentally appropriate.

---

## 7) User Stories

### 7.1 Child Learner Stories
- As a child, I want to play quick language mini-games so learning feels fun.
- As a child, I want to earn stars/coins/badges when I complete lessons.
- As a child, I want to hear native pronunciation and repeat words.
- As a child, I want to unlock story chapters after completing quests.
- As a child, I want visual matching games so I can learn without heavy reading.

### 7.2 Parent Stories
- As a parent, I want to set daily practice goals (e.g., 15 min/day).
- As a parent, I want clear progress reports by skill area.
- As a parent, I want a safe app without ads and invasive tracking.
- As a parent, I want confidence that curriculum quality is credible.

---

## 8) Functional Requirements

## 8.1 Onboarding and Profiles
1. Parent creates account and child profile(s).
2. Child profile captures age band and learning level.
3. Placement starter path (very short) to personalize first lessons.
4. Consent and privacy notices designed for guardians.

## 8.2 Curriculum and Lesson Engine
1. Spanish-first curriculum for ages 2–6.
2. Theme-based units (animals, food, family, transportation, colors, numbers, routines).
3. Learning strands:
   - Listening comprehension
   - Speaking/pronunciation
   - Vocabulary
   - Phonics and letter recognition
   - Early reading
   - Early writing patterns/tracing interactions
4. Bite-sized lessons (2–5 min activities).
5. Structured progression with prerequisites and review loops.
6. Grammar explanations:
   - Parent mode: plain-language explanations
   - Child mode: simplified examples and contextual reinforcement
7. Context examples must use real-world, age-appropriate scenarios.

## 8.3 Game and Quest Systems
1. World map with quest path and milestones.
2. Daily goals and streaks with gentle encouragement.
3. Reward system:
   - Stars/coins
   - Avatar customization unlocks
   - Story chapter unlocks
   - "Treasure chest" surprise rewards
4. Leagues/tiers (age-safe, optional, primarily asynchronous).
5. Boss challenge at end of each unit (composite review game).

## 8.4 Story Library
1. Interactive storybook library with leveled stories.
2. Read-along with native-speaker narration.
3. Repeat-listen mode for reinforcement.
4. Tap-on-word image/audio support.

## 8.5 Image-Based Learning
1. Picture-word matching activities.
2. Object-to-word association drills.
3. Scene exploration mini-games (find-and-name objects).

## 8.6 Pronunciation and Speech Feedback
1. Native-speaker audio models for each word/phrase.
2. Speech comparison feature ("TruAccent" concept for roadmap):
   - Detect if pronunciation is close, improving, or needs retry.
   - Use encouraging and non-shaming feedback.
3. Fallback flow when microphone unavailable.

## 8.7 AI Roleplay and Conversation (Phased)
1. Guided roleplay scenarios (e.g., market, park, birthday).
2. Strict prompt constraints and child-safe outputs.
3. Parent controls to enable/disable conversation module.
4. Initially template-driven; later model-assisted personalization.

## 8.8 Social and Motivation Features
1. Family-facing progress sharing (not public child feeds).
2. Optional friend/class cohorts with guardian-mediated invitations.
3. Cooperative events (e.g., "community reading quest") with privacy safeguards.
4. No direct unmoderated child-to-child chat in MVP.

## 8.9 Reminders and Habit Building
1. Default daily practice reminder (15 minutes) with playful copy.
2. Parent-configurable schedule.
3. Non-intrusive reminder frequency caps.
4. Positive reinforcement if session missed (no guilt framing).

## 8.10 Parent Dashboard
1. Progress by skill area and unit.
2. Weekly summary: minutes practiced, words learned, pronunciation trends.
3. Suggested next activities.
4. Resource hub with credible external references.

## 8.11 Maps and Cultural Context
1. Interactive city/country maps integrated into lessons.
2. Simple cultural snapshots linked to vocabulary themes.
3. Age-appropriate geography exploration.

## 8.12 Safety and Compliance
1. Child privacy protections (COPPA/GDPR-K aligned design targets).
2. Minimal data collection.
3. No ads, no third-party behavioral tracking.
4. Human-reviewed content pipelines for child safety.

---

## 9) Non-Functional Requirements
1. **Performance:** core activities load in <2 seconds on typical mobile broadband.
2. **Availability:** 99.9% monthly uptime target for core learning services.
3. **Accessibility:** high contrast modes, clear iconography, audio-first navigation for pre-readers.
4. **Scalability:** architecture supports additional languages and content packs.
5. **Reliability:** lesson progress sync should be robust to intermittent connectivity.
6. **Security:** encryption in transit and at rest; role-based admin controls.

---

## 10) Content and Curriculum Requirements
1. Curriculum framework aligned with early literacy pedagogy.
2. Spanish scope-and-sequence from beginner to upper beginner milestones.
3. Explicit phonics progression (letter sounds, blends, syllable awareness).
4. Repetition strategy: spaced review and mixed-practice retrieval.
5. External references in parent resources must come from credible institutions only.
6. Native-speaker reviewed pronunciation and example quality checks.

---

## 11) Metrics and Analytics (Data-Driven Strategy)

## 11.1 North Star Metric
- **Weekly Active Learners completing 3+ meaningful sessions/week**.

## 11.2 Engagement Metrics
- D1/D7/D30 retention.
- Average sessions per week.
- Average minutes per session.
- Streak continuation rate.
- Quest completion rate.

## 11.3 Learning Metrics
- Vocabulary mastery rate per unit.
- Pronunciation improvement score trend.
- Phonics checkpoint pass rates.
- Story comprehension activity success rate.

## 11.4 Parent Value Metrics
- Parent dashboard weekly open rate.
- Goal-setting adoption rate.
- Satisfaction/NPS.

## 11.5 Safety Metrics
- Content safety incident count.
- Moderation response SLA adherence.

---

## 12) A/B Testing Plan
1. Test reminder tone/style and send-time windows.
2. Test reward cadence (small frequent vs milestone-heavy).
3. Test quest map visuals and progression pacing.
4. Test lesson length variants by age band.
5. Guardrails:
   - Never A/B test unsafe experiences.
   - Parent-visible transparency for major experience changes.

---

## 13) Information Architecture
1. **Child App Areas:** Home Quest Map, Play, Stories, Practice, Rewards.
2. **Parent Area:** Dashboard, Settings, Notifications, Progress Reports, Resource Hub.
3. **Admin/Curriculum Area (internal):** Content Management, Review Workflows, Experiment Console.

---

## 14) High-Level Technical Architecture (Lovable + Supabase)

## 14.1 Frontend
- Lovable-generated web app (mobile-first responsive design).
- Component architecture for mini-games, story player, quiz interactions.

## 14.2 Backend (Supabase)
- Postgres for curriculum, progress, rewards, and profile data.
- Supabase Auth for parent authentication.
- Row-Level Security (RLS) for tenant-safe data access.
- Storage for audio, images, and story assets.
- Edge Functions for business logic (quest evaluation, reminder scheduling, AI proxy).

## 14.3 AI/ML Services (phased)
- Speech scoring service integration (initially heuristic, later model-based).
- Roleplay assistant service with strict moderation layers.

## 14.4 Observability
- Event tracking pipeline.
- Experiment assignment + analytics attribution.
- Error monitoring and content quality dashboards.

---

## 15) Proposed MVP Scope (Phase 1)
1. Parent onboarding + child profile creation.
2. Spanish starter curriculum (first 6–8 themed units).
3. Core game loop: quest map, mini-games, rewards, daily goal.
4. Native audio playback and simple repeat-after-me recording.
5. Story library with at least 20 beginner stories.
6. Parent dashboard (basic progress + reminder settings).
7. Privacy-first implementation (no ads/no IAP/no behavioral tracking).

### Out of MVP (Phase 2+)
- Advanced leagues and social cohorts.
- Full conversational AI roleplay.
- Multi-language expansion.
- Deep adaptive learning model.

---

## 16) Roadmap

### Phase 0: Foundations (4–6 weeks)
- Product design system.
- Data model and Supabase schema.
- Content authoring pipeline.

### Phase 1: MVP Build (8–12 weeks)
- Implement core lesson engine and quest loop.
- Ship starter Spanish path and stories.
- Parent dashboard basics.

### Phase 2: Intelligence + Optimization (8–10 weeks)
- A/B testing framework full rollout.
- Improved speech scoring.
- Personalized practice recommendations.

### Phase 3: Scale (ongoing)
- Additional languages.
- Expanded curriculum levels.
- Partnerships with educators.

---

## 17) Risks and Mitigations
1. **Risk:** Speech recognition quality for young children can be noisy.  
   **Mitigation:** Start with confidence bands + generous feedback; collect opt-in improvement data.
2. **Risk:** Over-gamification may reduce learning depth.  
   **Mitigation:** Tie rewards to mastery checkpoints, not only activity volume.
3. **Risk:** Child safety in social features.  
   **Mitigation:** Guardian-mediated interactions only; no open chat in MVP.
4. **Risk:** Content production bottleneck.  
   **Mitigation:** Build reusable templates and internal QA rubric early.

---

## 18) Success Criteria (First 6 Months Post-MVP)
1. D30 retention >= 25% (parent-child accounts).
2. 60%+ of weekly active learners complete >= 3 sessions/week.
3. 70%+ unit completion for first 3 units.
4. Parent satisfaction >= 4.3/5 average.
5. Zero ad/tracking policy violations.

---

## 19) Open Questions
1. Subscription model details (if no IAP, how pricing is presented to guardians).
2. Specific curriculum standards to align with for target launch markets.
3. Which speech engine vendor (or in-house approach) best supports preschool voices.
4. Regional content localization needs (e.g., LATAM vs Spain variants).
5. Parent involvement mode: guided co-play vs mostly independent child play.

---

## 20) Immediate Next Steps
1. Convert this PRD into:
   - UX flow diagrams,
   - Database schema,
   - MVP feature backlog with priorities.
2. Define content pilot for first two themed units.
3. Draft first usability test protocol with 8–12 parent-child households.

