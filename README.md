# SGI Backyard Mosquito School

Static first build for:
- Standalone site: mosquito-school.netlify.app
- SGI entry point: sgimdliving.com/mosquitos

## Deploy
1. Create a GitHub repository, e.g. `sgi-mosquito-school`.
2. Add the contents of this folder to the repository root.
3. In Netlify, create a new site from that repository.
4. Set the desired Netlify site name to `mosquito-school` if available.
5. No build command is required for this static version. Publish directory is the repository root.

## Files
- `index.html` — Mosquito School home page
- `report-1.html` — Initial field report, Aug. 29, 2026
- `styles.css` — site styling
- `assets/` — selected real field photographs

## SGI entry point
In the existing sgimdliving.com site, `/mosquitos` can redirect to the standalone Mosquito School site. Later, this can be changed to a proxy/rewrite if you want visitors to remain visually under the SGI domain.

## Next version ideas
- Field report index
- Structured JSON/YAML bucket observations
- Oviposition-strip protocol
- Photo galleries by bucket
- Supabase community-submission form
- Map / site diagram
