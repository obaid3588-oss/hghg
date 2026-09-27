OTCC Assessment Tool v1.8 — Compact UX + JSON Obaid Tips

FILES
- assessment.html
- evidence-library.html
- obaid-tips.json (starter/template)

WHAT CHANGED
1. Added one compact “Obaid Tips ▾” button in the top header.
   - Import Tips JSON
   - Export Tips JSON
2. Obaid Tips are no longer saved to browser localStorage by this version.
   - Import the JSON file when opening the tool.
   - Add/edit/remove tips during the session.
   - Export the JSON file after changes to keep them permanently.
3. The left filter area was compressed to give substantially more vertical space to the control list.
   - Smaller search field
   - Smaller Domain and Applicable Level filters
   - Smaller More Filters section
   - Tighter Previous/Next controls and filter footer
4. Assessment response storage and existing assessment logic were not otherwise changed.

RECOMMENDED TIPS WORKFLOW
- Keep OTCC_Global_Obaid_Tips.json next to the HTML files.
- At the start of a session: Obaid Tips ▾ > Import Tips JSON.
- After changing any tip: Obaid Tips ▾ > Export Tips JSON and replace the previous file.

NOTE
A normal offline HTML page cannot silently read or overwrite an arbitrary local JSON file without user permission. For that reason the tool uses explicit Import/Export actions and does not use browser storage for Obaid Tips.
