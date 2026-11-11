# Xpertloop prototype

Open dist/index.html directly in a browser, or serve dist with any static HTTP server. The current local preview is http://127.0.0.1:4173.

Includes Home, agent library and creation, Chat / Analytics / Content tabs, uploads and manual Q&A, unanswered question resolution, dashboard with metric details, content studio and saved drafts, profile/account settings, notifications, help, billing and plan comparison.

Demo data persists in browser localStorage. Chat retrieves saved Q&A or uses sample responses; it is not connected to an AI model. Uploads retain metadata, not file content. Social content generation uses templates and saved Q&A. No real charges, account authentication, subscription changes, or social publishing occur. The two unprovided agent setup steps are designed for voice configuration and review.

Motion includes spring-style tab and modal transitions, staggered cards, hover lifts, button light sweeps, count-up metrics, line drawing, animated bars, loading dots, and toast feedback. The stylesheet respects prefers-reduced-motion. Inspired by bencho.dev's interaction examples.

Verification: Node syntax check and verify.cjs route/template smoke checks passed. Browser checks verified the knowledge-gap-to-chat loop, three-step creation, account/billing navigation, and content generation/save. Narrow browser layout was visually inspected.

Hosting was registered privately with Sites, but source synchronization and deployment could not complete because Git on this Mac requires missing Apple developer tools. The local prototype remains usable.
