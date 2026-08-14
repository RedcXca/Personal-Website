# Portfolio content refresh

Goal: Bring the personal site content up to date.

Scope: Refresh illustration listings, Ivo branding, client credits, project work, personal details, osu! resources, and footer years.

Requirements:

- Use the current Ivo identity.
- Add YUC'e to client work.
- Remove outdated 3939 and Blue Houraisan Kaguya art.
- Use 2026 in every footer.
- Preserve the established visual direction and responsive behavior.
- Show the Ougonkyou frontend projects with large, visible previews.
- Link the osu! skin and map folder from a dedicated resource card.
- Add current yearly goals to the home page.
- Load the home page immediately without an intro.
- Keep the yearly goals to 1500 blitz chess and finishing Elden Ring.
- Reveal the original Sakura and Beach artwork on hover or keyboard focus.
- Add Chess Evolved Offline to the project list with its supplied board image.

Decisions:

- Keep censored artwork visible until the user hovers or focuses it.
- Use official public profiles and identity assets.
- Use the green Ivo badge with its white mark.
- Restore The Reckoner after confirming it was dropped during an earlier redesign.
- Add the user-provided wide artwork for Nasu Is Not Fruits Desu! to the illustrations page only.
- Balance the 16 client cards into two rows on larger screens and four columns on smaller screens.
- Keep projects in two wide columns with descriptions permanently visible.
- Use the provided padded Ivo badge.
- Feature osu! Atlas at full width above the project grid.
- Include vey3st, channel, Saturn Illustration, Xiaoraini, Takoyoomi, and Essukaa from the Ougonkyou previews.
- Keep the existing Dosis typeface and avoid eyebrow labels throughout the new sections.
- Avoid decorative divider rules in new sections.
- Keep every project title white and linked with a short animated hover and focus underline.
- Give project cards a small lift and keep Atlas and artist site previews free of captions.
- Reuse one shared media card structure for projects and osu achievements.
- Animate the project title underline when any part of its card is hovered.
- Describe Chess Evolved Offline as a project with 26 custom-designed pieces.
- Label the artist portfolio group as Design work.
- Cache-bust stylesheet URLs after moving card styles into shared CSS.
- Present osu achievements with the same image, caption overlay, and title treatment as project cards.
- Keep osu achievement cards neutral without orange accent borders.
- Give the Google Drive CTA its own hover and focus underline.
- Describe the Drive folder as the current skin and fun maps from all modes.

Status: Complete. The home intro is removed. Osu achievements reuse the project card presentation without accent borders. The Google Drive CTA has its own hover and focus underline. The osu page was checked at 1440, 390, and 320 pixels with no card overflow or clipped overlay text.
