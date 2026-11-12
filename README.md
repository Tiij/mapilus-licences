# Mapilus chart data licences

Public licence register and **ODbL offer** for the Mapilus offline chart packs.

> **Not for navigation.** These packs are planning and context aids. They do not
> replace official charts, ENCs, buoyage or SHOM instructions.

## Packs

| Pack | Coverage | Files | Licence |
|---|---|---|---|
| `world-base` | world, z0–z4, bundled in the app | `world-base.mbtiles`, manifest | ODbL 1.0 / public domain |
| `world-detail` | world, z5–z7, downloaded | `world-detail.mbtiles`, manifest | ODbL 1.0 / public domain |
| `cote-opale` | Côte d'Opale, z6–z14, downloaded | MBTiles, routing grid, manifest | ODbL 1.0 / CC BY 4.0 |

Pack download links and manifest hashes are published from the Mapilus
`chart-packs` Storage bucket. The current links are listed in
[`PACKS.md`](PACKS.md).

## ODbL offer

The OSM-derived database contained in the packs — land polygons, coastline,
places, seamarks and fairways — is made available under the **Open Database
License 1.0 (ODbL)**.

You may obtain the current extract from the pack links in [`PACKS.md`](PACKS.md).
If a link is unavailable, open an issue on this repository and we will provide
the current extract.

The ODbL offer covers the OSM-derived layers only. The application code, the
Mapilus community reports/soundings and the GEBCO/EMODnet-derived layers keep
their own terms.

## Sources and attribution

| Source | Licence | Attribution |
|---|---|---|
| OpenStreetMap / OpenSeaMap | ODbL 1.0 | `© OpenStreetMap contributors, OpenSeaMap (ODbL)` |
| OSMData land polygons | ODbL 1.0 | `© OpenStreetMap contributors (ODbL)` |
| OSMNames | ODbL 1.0 | `© OpenStreetMap contributors, OSMNames (ODbL)` |
| GEBCO 2026 Grid | public domain | GEBCO Compilation Group (2026), doi:10.5285/4f68d5c7-45eb-f999-e063-7086abc036fa |
| EMODnet DTM 2024 | CC BY 4.0 | EMODnet Bathymetry Consortium (2024), doi:10.12770/cf51df64-56f9-4a99-b1aa-36b8d7b743a1 — changes were made |

GEBCO depths are reference-only and must not be presented as surveyed chart
data.

## Commercial use

Every source above permits commercial use. ODbL requires attribution and
share-alike for the OSM-derived database; CC BY requires attribution; GEBCO is
public domain. The Mapilus community layer is never merged into the OSM, GEBCO
or EMODnet layers.

We do **not** ship `tile.openseamap.org` or `tile.openstreetmap.org` as a
production background. Those services are donation-funded, have no SLA, and
OSM's tile policy prohibits heavy/commercial use and bulk offline downloads.

## Contact

Open an issue on this repository for licence questions or an ODbL extract.
