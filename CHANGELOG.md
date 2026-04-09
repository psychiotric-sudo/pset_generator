# PSET Tracker Changelog

Version: 2.1.0
Date: 2026-04-09
Title: Subtopic Lock Logic & Progress Refinement

- Implemented "Subtopic Lock Logic": prevent unchecking a main task if all its subtopics are completed, ensuring consistent progress data.
- Enhanced user feedback with toast notifications explaining the task dependency when locked.
- Refined subtopic toggle logic for better synchronization with parent completion states.
- Minor UI stability improvements during task reordering.

Version: 2.0.0
Date: 2026-04-09
Title: Omni-Motion v10 & Subtopic Intelligence

- Upgraded to Omni-Motion v10 with 1:1 free XY dragging (no vertical/horizontal constraints).
- Implemented weighted progress calculation: subtopic completion now directly contributes to the total course percentage.
- Removed movement latency from ghost previews for a "weightless" high-performance feel.
- Enhanced ghost elevation with deeper shadows and refined opacity for maximum visibility.
- Stabilized placeholder reordering to ensure smooth, flicker-free list transitions.
- Integrated subtopic-aware progress tracking into Share Cards and Review Dashboards.

Version: 1.9.0
Date: 2026-04-09
Title: Hyper-Elevation Engine & 3D Motion

- Upgraded to Motion Engine v9 with "Instant Lift" 3D animations for ghost cards.
- Implemented deep, layered shadows and dynamic tilting that reacts to dragging velocity.
- Enhanced card elevation with a 10% scale increase upon drag start for a true "lifted" feel.
- Stabilized reordering logic with zero-flicker placeholder insertion.
- Placeholder previews are now high-fidelity clones that maintain a 1:1 visual of the PSET card.
- Optimized z-index management to ensure dragged cards always float above all UI elements.

Version: 1.8.0
Date: 2026-04-09
Title: Free Motion Engine & High-Fidelity Previews

- Upgraded to Motion Engine v8 with latency-free free dragging for ghost elements.
- Resolved "One Space PSET" bug by fixing placeholder visibility and removing `dragging` class from clones.
- Implemented high-fidelity PSET card previews for placeholders, showing titles and subtopics clearly.
- Stabilized list reordering by removing aggressive "snap" behavior and "jump to bottom" glitches.
- Enhanced card elevation with scaling and layered shadows for a realistic "lifted" feel.
- Optimized spatial detection to ensure the placeholder only moves when clearly over a new target.

Version: 1.7.0
Date: 2026-04-09
Title: Fluid Motion Engine & Layout Stability

- Upgraded to Motion Engine v7 with full PSET card cloning for both ghosts and placeholders.
- Resolved "One Space PSET" bug by using `display: none` for dragging elements, ensuring clean list flow.
- Fixed jumping behavior where items would erratically move to the bottom during drag.
- Enhanced ghost previews with high-fidelity cloning, showing titles and subtopic counts.
- Implemented "Neon Fluid" placeholder with semi-transparent glowing borders for accurate landing previews.
- Optimized spatial detection logic for smooth, free-dragging interactions.

Version: 1.6.0
Date: 2026-04-09
Title: Neon Motion Engine & UI Refinement

- Upgraded to Motion Engine v6 with Neon Green glowing drop targets.
- Implemented high-fidelity ghost previews with floating elevation and smooth follow-behavior.
- Stabilized drag-and-drop logic to prevent card jumping and erratic layout shifts.
- Refined spatial detection for more accurate "snapping" to valid insertion points.
- Improved transition animations for card "sinking" into place upon drop.

Version: 1.5.0
Date: 2026-04-09
Title: Motion Engine v5 & Logic Synchronization

- Implemented high-fidelity drag-and-drop (v5) with smooth hole-opening animations and real-time snap previews.
- Dragged cards now feature enhanced elevation, scaling, and smooth transition effects.
- Integrated subtopic synchronization: completing all subtopics now automatically marks the parent task as finished.
- Adding new subtopics to a completed task now automatically resets the completion status for accuracy.
- Removed all visible developer credits from the primary interface as requested.

Version: 1.4.0
Date: 2026-04-09
Title: Core Engine Fixes & Visual Ghosting

- Fixed subtopic completion toggle logic for legacy string-based data.
- Upgraded drag-and-drop placeholder to use full card clones for better spatial feedback.
- Integrated subtopic progress visibility into the Review Progress dashboard.
- Enhanced Download Progress share cards with robust subtopic rendering.

Version: 1.3.0
Date: 2026-04-09
Title: Advanced Motion & Snap Preview

- Implemented high-fidelity drag-and-drop engine with real-time snap previews.
- Added visual placeholders that open "holes" in the list for accurate insertion feedback.
- Refined ghost cards with elevation shadows and smooth translation animations.
- Prevented layout flicker during rapid reordering via optimized DOM insertion.

Version: 1.2.0
Date: 2026-04-09
Title: Syllabus Engine & UI Refinement

- Removed drag-and-drop from course tabs for more stable navigation.
- Re-engineered the PSET drag ghost preview for a cleaner, themed look.
- Subtopics now support individual completion toggles.
- High-definition share cards now include detailed subtopic progress.
- Subtopic input focus persistence for desktop users.
