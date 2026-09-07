# Quill Dashboard Build Specification (v1)

## Objective

Build a new repository for Quill. Do not reuse LessonCanvas for the UI.
Treat LessonCanvas as a future lesson engine.

## Vision

A dream-like, pastel, adventurous learning platform inspired by premium
game UI rather than a traditional LMS.

## Technology

-   Next.js
-   React
-   TypeScript
-   Tailwind CSS
-   Framer Motion (later)
-   Reusable component architecture

## Existing Assets

Use the provided PNG assets wherever possible (owl, islands, buttons,
cards, progress bars).

## Visual Style

-   Pastel colours
-   Rounded corners
-   Soft shadows
-   Cyan-to-cream sky
-   Floating clouds
-   Mountains
-   Plenty of whitespace

## Layout

Hero greeting. Large Learning Journey (≈70% of viewport). Continue
Learning card. Daily Goals. Achievements. Minimal navigation.

## Worlds

Math: Counting Forest, Addition Orchard, Multiplication Castle,
Fractions Bay, Algebra Station, Geometry Peaks. English: Story Woods,
Grammar Grove, Writing Workshop, Poetry Theatre. Science: Volcano
Valley, Nature Park, Discovery Lab, Planetarium. History: Ancient
Shores, Lost Treasure.

## Components

TopBar, JourneyMap, Island, JourneyNode, JourneyPath, ContinueCard,
DailyGoals, AchievementCard, XPWidget, StreakWidget, SubjectBadge,
FloatingCloud, QuillCompanion.

## Quill

Quill should feel alive and eventually support multiple expressions and
poses. Initially static.

## Future Integration

Keep dashboard independent. Later integrate LessonCanvas, AI lesson
generation, maths verification and curriculum validation.

## Pitfalls

Avoid clutter, corporate styling, sidebars dominating the screen,
hardcoded data, tiny touch targets and inconsistent spacing.

## Success

The user should immediately want to continue their learning journey. The
dashboard should feel like entering a game world.
