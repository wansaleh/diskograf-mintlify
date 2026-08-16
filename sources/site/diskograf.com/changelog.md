# Source: https://diskograf.com/changelog

1. - Improved

 Pages load lighter. Song, artist, and browse pages now send 50-65% less translation data, and grids no longer pre-load a page for every card in view. Links still pre-load the moment you hover one. Catalogue pages also stay cached longer, so they open faster on a repeat visit.

 - Improved

 Artist profile spacing now follows the song grid spacing around the view tabs, catalogue controls, and song results. The duplicate artist name above the tabs is no longer shown. Artist catalogue pages no longer repeat the artist name and subtitle above the search controls, and their search-to-grid spacing now follows the grid gap. Back links now sit inside the avatar and use the shorter “Back” label on artist and profile pages. The controls now match the avatar pill size. Profile view tabs now use balanced outer padding.

 - Fixed

 Owners can now remove songs directly from their loved songs page and drag them to reorder the list again.

 - Fixed

 Edited song artwork and artist names now appear in catalogue cards immediately after a save.

2. - Improved

 Landing reveals now pause briefly before starting and move more slowly, while feature chips stagger from the right and the hero illustration shows stronger parallax depth. The hero renders immediately for a faster first paint. Landing page cards, stats, song artwork and the artwork strip now fade up in a gentle stagger as they enter the viewport. The artwork strip stays centered on one row at a consistent size on small screens, revealed copy rises into place, and the statistics heading sits on a faint grid. Homepage navigation no longer flashes a song-grid loading state while the latest songs load, the artwork strip no longer adds a top border, and the publisher wall now features NAR Publishing in the updated slot. Scroll reveals below the first screen now wait for their section to scroll into view, and the publisher proof wall keeps its four-column logo grid after scroll-reveal changes. Landing page copy now slides up from its baseline through a fixed clip-path mask instead of wiping in from the bottom. The sign-in page now uses a cinematic surreal piano landscape as its background, with the piano centered beside the sign-in panel.

 - Improved

 Paginated catalogue and Backstage lists now support arrow-key navigation, including 10-page jumps with Shift plus an arrow key. Returning to a new page also keeps the first row clear of the sticky site header.

 - Fixed

 Backstage admins can now save profile changes for a linked artist when the artist has a long legacy avatar URL. Alias autocomplete now shows the current user's artist only when it matches the search. The active profile tab now remains visible in dark mode, and artist profiles no longer show an extra explanatory subtitle above the tabs.

 - Improved

 Public artist, profile, and sign-in pages now use more balanced layouts, clearer headings, expandable long biographies, and better spacing beneath the site header.

3. - Improved

 Hovering a publisher logo on the landing page now fades and blurs the logo, switches the tile to black, and reveals the publisher's full name in white.

 - Improved

 The landing page catalogue showcase now uses a shorter, non-full-screen section while keeping the full artwork tunnel visible.

 - Improved

 The landing page publisher wall now features 12 Malaysian music publishers, including Taja Archive, across three rows with more vertical breathing room.

 - Improved

 Landing page spacing now gives the catalogue statistics more room and gives the contribution CTA a clearer “Contribute now” label on a full-width light grey surface.

 - Improved

 The illustrated landing page is now the public homepage. The previous homepage remains available at \`/landing-2026-1\`, the hero starts directly with its main message, and homepage navigation no longer flashes the old blue loading screen.

 - Improved

 Eyebrows now use one consistent site-wide style across public and Backstage pages.

 - Fixed

 The Design tokens page now uses the shared eyebrow component for its section labels.

4. ### A clearer, faster Diskograf experience

 - Improved

 The sign-in page now uses an interactive Pixel Card background with a subtle Diskograf blue palette and a larger, rounded sign-in action with tighter text spacing, a larger description, more heading separation, and a wider sign-in card.

 - Improved

 The search palette now groups profile, language, and theme options under Preferences. Public catalogue data stays cached longer, genre and label pages load instantly instead of streaming in, and song and artist browsing sends less data per page for faster loading, especially on slower connections.

 - New

 Label pages can now show a full company name, logo, and active or defunct status. Display names also drop legal suffixes such as "Sdn Bhd" and "Enterprise" while preserving the full registered name. The Backstage label editor now supports adding these same details.

 - New

 Onboarding now asks for a profile photo before setup is complete.

 - New

 When adding a song credit, artists already credited on the song now show up first in search — instantly, before you even type — tagged with their existing role. Makes it quick to add the same artist under a second role, like composer after lead performer.

5. ### Catalogue browsing became more consistent

 - Fixed

 Public navigation no longer briefly shows a 404 page while prefetched content loads.

 - Fixed

 Catalogue aliases, page metadata, and sitemap entries now use one canonical URL format, including localized and ID-only links.

 - Improved

 Public catalogue pages and metadata now reuse cached results more often, which makes repeat visits faster.

 - Improved

 Artist profiles and cards now use more consistent avatar spacing, overlay text, metadata, statistics, corner radii, and loading states.

 - Fixed

 Song links now use stable ASCII slugs when titles include Arabic or other non-Latin characters.

6. ### A clearer landing page and faster catalogue updates

 - Improved

 The experimental landing hero now has a more balanced two-column layout, wider illustration, and tighter heading and subtitle.

 - Improved

 The landing page closing section now focuses on one clear action: contributing a song.

 - Fixed

 Artist song counts now update as soon as a song is added or published.

 - Improved

 The sign-in page now has a clearer heading and spacing.

7. ### A new illustrated Malaysian identity for the landing page

 - New

 The experimental landing page now uses an illustrated Kuala Lumpur hero, with the Petronas Twin Towers as its visual anchor.

 - Improved

 The catalogue section now uses a full-width Malaysian skyline and a mid-century P. Ramlee illustration.

 - New

 A curated artwork strip and interactive figure-eight artwork path now present selected catalogue covers.

 - Improved

 The landing cards, closing section, header, footer, and dark mode now use a cleaner and more consistent visual treatment.

 - Fixed

 Landing illustrations, buttons, artwork spacing, and narrow-screen framing now render correctly.

8. ### The landing page tells a clearer Malaysian music story

 - Improved

 The experimental landing page now opens with an illustrated Malaysian music landscape and direct catalogue paths.

 - Improved

 Selected Malaysian music publishers now appear in a clear logo grid.

9. ### Curated lists became available throughout the catalogue

 - Improved

 Admins can add songs to curated lists from song pages and song cards across the catalogue. Existing list membership is shown clearly.

 - New

 Curated-list editors can use artwork from a song in the list as the list artwork.

 - Improved

 Song pages now have a more compact header, readable credits, and responsive related-song layouts.

 - Improved

 Page shells, the homepage, and credit-claim song search now load faster.

10. ### Search became smarter about artists and popularity

 - Improved

 Search now ranks strong artist and song matches by catalogue importance and YouTube activity when text relevance is equal.

 - Improved

 Artist aliases and quoted multi-word search filters now work in song search.

 - Improved

 Song completeness, activity dates, and contribution filters now give clearer status information.

 - Improved

 Artist works reports now include recording labels, and the account menu links directly to reports and contribution tools.

Showing 10 of 32 releases

Load more releases