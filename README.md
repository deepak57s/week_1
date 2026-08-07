# Weather App (Week 1)

A simple weather application built with HTML, React (via CDN), and Tailwind CSS. The app displays current weather conditions and a 5-day weekly forecast.

## Recent Updates

🎨 **Palette: UX & Accessibility Improvements**

*   **Keyboard Navigation:** Added visible hover (`hover:text-blue-700`) and focus (`focus-visible:ring-2`) states to the main navigation links to ensure keyboard users can clearly see which element is active.
*   **Informative vs Decorative Images:**
    *   Added descriptive `alt` tags (e.g., "Sunny", "Rain", "Storm") to the forecast icons to ensure screen readers announce the weather properly for each day.
    *   Set the main weather icon's `alt` attribute to be empty (`alt=""`) because the weather condition ("SUNNY") is explicitly stated directly below it, avoiding redundant announcements for screen reader users.
*   **HTML Semantics:** Fixed base HTML structure by adding proper `<!DOCTYPE html>` and `<html lang="en">` tags.
