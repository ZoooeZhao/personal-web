# Flocker Case Study Assets

The new detail page is `flocker.html`. Its content comes from https://www.zoezhaochen.com/flocker. The original image CDN was inaccessible during implementation, so only the existing homepage cover is currently real imagery. Other visuals are explicitly labeled placeholders.

`docs/content/flocker-source.txt` retains the extracted source copy. `docs/content/flocker-assets.json` lists original image URLs and source filenames. `docs/content/flocker-placeholders.json` lists every replacement slot.

## Replacing A Placeholder

Upload the corresponding file to this folder, then replace the `.asset-slot` inside its `<figure data-case-asset="…">` in `flocker.html` with an image using class `asset-image`, a descriptive alt, width/height, and `loading="lazy"`. Keep the existing caption. Assets under this folder are copied into the production build. Do not replace a placeholder with a generic invented screen or present it as the original product UI.

| Slot | Suggested Filename | Content |
| --- | --- | --- |
| `survey-meet-friends` | `survey-meet-friends.png` | Survey Results: How often do you typically meet up with friends in person? |
| `survey-find-events` | `survey-find-events.png` | Survey Results: How do you typically find out about events you are interested in? |
| `survey-go-with-friends` | `survey-go-with-friends.png` | Survey Results: Would you go out more often if you could find potential or existing friends already doing things that match your interests? |
| `survey-friend-attendance` | `survey-friend-attendance.png` | Survey Results: Would you like to see what events your friends are interested in or are planning to attend? |
| `user-journey` | `user-journey.png` | User Journey: Problem, Result, And Solution |
| `event-type-categories` | `event-type-categories.png` | Event-Type Categories |
| `mood-based-categories` | `mood-based-categories.png` | Mood-Based Categories |
| `swipe-demo` | `swipe-demo.png` | Swipable Event Cards |
| `onboarding-interests` | `onboarding-interests.png` | Sign-Up Interests |
| `mood-discovery` | `mood-discovery.png` | Mood-Based Recommendations |
| `event-card-final` | `event-card-final.png` | Event Discovery: Final Card |
| `event-card-rsvp` | `event-card-rsvp.png` | Event Discovery: RSVP |
| `event-card-early` | `event-card-early.png` | Early Event Card |
| `event-card-profile` | `event-card-profile.png` | Profile Access Exploration |
| `event-card-layout` | `event-card-layout.png` | Event Card Layout Exploration |
| `event-card-text` | `event-card-text.png` | Text Hierarchy Exploration |
| `event-card-lfg` | `event-card-lfg.png` | Friend Matching Exploration |
| `event-browser-final` | `event-browser-final.png` | Browse Events |
| `event-map-final` | `event-map-final.png` | Map And Heatmap |
| `browser-drawer` | `browser-drawer.png` | Original Drawer |
| `browser-picture-text` | `browser-picture-text.png` | Picture And Text Exploration |
| `browser-card` | `browser-card.png` | Floating Event Card |
| `map-distant` | `map-distant.png` | Map: Distant View |
| `map-close` | `map-close.png` | Map: Close View |
| `map-categories` | `map-categories.png` | Category Colors |
| `calendar-final` | `calendar-final.png` | Calendar And Weather |
| `calendar-detail-final` | `calendar-detail-final.png` | Event Details In Calendar |
| `calendar-old` | `calendar-old.png` | Earlier Calendar UI |
| `calendar-month` | `calendar-month.png` | Calendar Layout Exploration |
| `calendar-day` | `calendar-day.png` | Day View Exploration |
| `calendar-event` | `calendar-event.png` | Event Detail View |
| `calendar-weather` | `calendar-weather.png` | Weather Integration |
| `attendees-final` | `attendees-final.png` | Manage Attendees |
| `attendee-profile-final` | `attendee-profile-final.png` | Attendee Profile Card |
| `attendees-all` | `attendees-all.png` | All Attendees |
| `attendees-match` | `attendees-match.png` | Attendee Matching |
| `attendees-card` | `attendees-card.png` | Profile Card Exploration |
| `attendees-list` | `attendees-list.png` | List View Exploration |
| `attendees-public` | `attendees-public.png` | Public Profile Exploration |
| `chat-a` | `chat-a.png` | Chat: Screen One |
| `chat-b` | `chat-b.png` | Chat: Screen Two |
| `event-detail-a` | `event-detail-a.png` | Event Detail: Screen One |
| `event-detail-b` | `event-detail-b.png` | Event Detail: Screen Two |
| `post-feed-a` | `post-feed-a.png` | Post Feed: Screen One |
| `post-feed-b` | `post-feed-b.png` | Post Feed: Screen Two |
| `event-check-in-a` | `event-check-in-a.png` | Event Check-In: Screen One |
| `event-check-in-b` | `event-check-in-b.png` | Event Check-In: Screen Two |
| `filter-a` | `filter-a.png` | Filter: Screen One |
| `filter-b` | `filter-b.png` | Filter: Screen Two |
| `ai-image-generation-a` | `ai-image-generation-a.png` | AI Image Generation: Screen One |
| `ai-image-generation-b` | `ai-image-generation-b.png` | AI Image Generation: Screen Two |
| `sign-up-a` | `sign-up-a.png` | Sign Up: Screen One |
| `sign-up-b` | `sign-up-b.png` | Sign Up: Screen Two |
