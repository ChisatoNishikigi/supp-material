# Style Cue Glossary

This file documents the style labels and the corresponding style-specific cue glossary used to guide subsequent structured analysis.

## Style Label Definitions

### real_shot
Natural live-action footage captured by a camera in the physical world. This category includes ordinary real-world recordings with camera motion, scene lighting, and appearance patterns consistent with natural imaging.

### rendered_3d
Video content primarily presented in a 3D-rendered style. This category includes game-like rendering, CGI-like scenes, and other synthetic content with strong 3D visual characteristics.

### animated_2d
Video content primarily presented in a 2D animated style. This category includes cartoon-like, anime-like, hand-drawn, or otherwise flat 2D visual presentation.

### screen_recording
Video content primarily showing screen-captured digital interfaces or screen-based interaction. This category includes recordings of software, web pages, applications, editing tools, or other on-screen operations.

### mixed_style
Video content containing a substantial mixture of multiple style types, or content whose dominant style cannot be cleanly assigned to one of the categories above. This includes videos with clear transitions or coexistence between different visual styles.

## Cue Glossary

### real_shot

- shadow direction inconsistency
- object identity mismatch within span
- duplicate/static frames
- abrupt time jump
- unnatural lighting flicker
- locally implausible motion physics
- edge halo/over-sharpening
- localized visual glitch

### rendered_3d

- style/texture tiling
- lighting/shadow physically inconsistent
- material/specular behavior unrealistic
- object geometry deformation
- abrupt motion/state jump within span
- edge sharpness changes abruptly
- texture/material inconsistency across frames
- collision or contact physics mismatch

### animated_2d

- copy-paste frame reuse
- line art thickness inconsistency
- character attribute jump
- perspective error between frames
- locally implausible motion
- abrupt time jump
- color/flat shading mismatch
- local action logic break

### screen_recording

- UI state jump without action
- duplicate/static frames
- resolution/scale sudden change
- cursor teleport
- time text jump
- panel appears/disappears
- progress bar jump
- missing intermediate UI step

### mixed_style

- style shift at cut
- identity mismatch around style shift
- object state mismatch around style shift
- lighting model jump
- local continuity break within span
- abrupt time jump
- motion discontinuity
- style-consistency break
