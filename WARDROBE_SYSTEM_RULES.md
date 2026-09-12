# WARDROBE SYSTEM RULES — Single Master (Do Not Create New Layers)

**Permanent rule for all AI agents and auto-filers:**
- Alice Wardrobe Catalog is the ONLY database for individual garments. Every piece goes here.
- Alice's Closet – Virtual Wardrobe = full looks and outfits only, each linked to the master.
- Wonderland Wardrobe Catalog = pose and content references only.
- Wonderland OS Wardrobe Dashboard = project tracker only.
Never create a new wardrobe catalog, closet, dashboard, or any new layer. If a new need appears, extend the master or one of the three supporting databases. Update this page if the system changes.

## Styling Engine (active in master)
- Fields: Styling Ideas, Suggested Pairings, Freshness Score, Last Suggested.
- When asked for a stream look or refresh, pull ONLY from owned inventory and propose 2-4 new ways to wear existing pieces.
- Keep pose ratings and hashtag suggestions inside the master — no separate layers.
- Goal: never think about what to wear for a stream again.
- **Execution lives in `src/styling_engine.py` in the canon repo `wonderland-wardrobe-ai-stylist`.** Notion managers read signals and hand ranked priorities to the engine. They do not build or act.

## Privacy & Safety (hard rules)
- Only Alice appears on adult sites. Collaborators require verified age proof.
- Kid never appears on adult or NSFW content. SFW family mentions only (vague: "single mom" is fine; no names, ages, faces, schools, locations).
- Non-profit stays strictly SFW and fully separated from adult work.
- Adult-industry business-appropriate is allowed for the professional line; the kid line never bends.

## Repo hygiene
- `wonderland-wardrobe-ai-stylist` is the CANON repo. All engine code goes here.
- This repo and `wonderland-os-wardrobe-ai-stylist` are archived — README + rules only, no new code.
