# Accessibility and Responsive Requirements

## Accessibility baseline

Aim for WCAG 2.2 AA-informed implementation, with actual conformance claims made only after sufficient testing.

- Semantic landmarks and heading hierarchy.
- Keyboard-operable navigation, links, buttons, and language switch.
- Visible, unobscured focus indicators.
- Appropriate color contrast for text and controls.
- Meaningful accessible names for interactive elements.
- Informative images have useful alternative text; decorative images are appropriately ignored by assistive technology.
- Forms, if any, have labels, instructions, and understandable errors.
- Motion respects `prefers-reduced-motion`.
- Do not convey meaning by color alone.
- Avoid auto-playing audio/video and unnecessary animation.

## Responsive requirements

- Validate narrow mobile, larger mobile, tablet, laptop, and wide desktop.
- Prevent horizontal overflow and clipped content.
- Keep text readable without forced zoom.
- Make touch targets comfortably usable.
- Ensure navigation and project media adapt to small screens.
- Test long English/Indonesian strings and language switch behavior.
- Verify layout under enlarged text and browser zoom.

## Verification

Combine automated checks with manual keyboard and visual review. Automated tools do not prove full accessibility. Record tools, tested viewports, and known limitations.
