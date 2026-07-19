# Real Estate Property Management Hierarchy

RTL (Hebrew) property-management screen built as a streaming Design Component
using the **SAP Horizon** design system.

## Features
- Drill-down tree table: פרויקט → מבנה → קומה → דגם דירה → נכס → חוזה
- Single expand/collapse-all toggle
- Live search by חוזה / שם לקוח / פרויקט (search icon)
- "הצג חוזים" switch to show/hide contracts as the deepest level
- Status pills: פעיל · בבנייה · נמכר
- Pagination (15 rows per page)
- Donut chart of דירות status (נמכרו / פנויות) that updates to the selected project/building row

## Files
- `Property Hierarchy.dc.html` — the design component (entry point)
- `support.js` — Design Component runtime (do not edit)
- `_ds/` — SAP Horizon design-system bundle, tokens, fonts

## Run
Open `Property Hierarchy.dc.html` in a browser, or serve the folder statically.
