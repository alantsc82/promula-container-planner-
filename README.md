# Promula Container Loading Planner

Original, local-first React + Three.js container packing prototype for Promula Group.

## Start

Requires Node.js 18+.

```bash
npm install
npm run dev
```

Build with `npm run build` and deploy the `dist` directory to a compatible static host.

## Features

- Standard 20GP, 40GP, 40HC, 45HC and custom containers
- Mixed cargo dimensions, weights, quantities, rotation and basic stackability
- Heuristic 3D box placement and interactive visualization
- Payload and volume summaries, CSV export, print/PDF, local browser save/load
- No paid APIs or backend required for the initial version

## Important limitations

This is **v0.1**, not a certified logistics or safety application. The greedy packing heuristic may miss feasible solutions and does not validate door opening, load securing, true structural stacking loads, center of gravity, floor loading, axle limits or applicable transport regulations. Container dimensions and maximum payloads are illustrative and must be verified against the actual equipment. Browser-local storage is not synced to Supabase yet. CSV import, advanced optimization, authentication, cloud storage and production deployment are future phases.

Hosting for commercial use must comply with the selected provider's terms; Vercel Hobby is not permitted for commercial production usage.
