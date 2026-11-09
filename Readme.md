# Pakistan Aviation Maps for Enroute

Aeronautical mapping data for Pakistan, prepared for [Enroute Flight Navigation](https://github.com/Akaflieg-Freiburg/enroute).

**Provided by:** Dr. Jamie J. Alnasir — PakAviation.com

**Initial release** includes Pakistan's aerodromes and runways, radio navigation aids (GeoJSON), and offline terrain/map tiles (MBTiles). Airspace boundaries may be added in future releases.

**Aeronautical data source:** Pakistan Aeronautical Information Publication (AIP), 2025.

The aeronautical data is organised into separate GeoJSON files: `Pakistan_aerodromes_navaids.geojson` contains aerodromes and navigation aids; `Pakistan_private_aerodromes.geojson` contains private airfields; `Pakistan_airspace.geojson` contains ATS airspace; and `Pakistan_prd_areas.geojson` contains prohibited, restricted and danger areas. The data was extracted from the Pakistan Aeronautical Information Publication (AIP), primarily the 2025 edition.

`Pakistan_provisional_TMAs.geojson` contains the Lahore, Karachi, Multan and Islamabad terminal control areas (TMAs). These boundaries are provisional reconstructions based on published AIP information and supplementary sources, and require further verification against official aeronautical charts. For convenience, **`Pakistan_all.geojson` combines all five datasets into a single GeoJSON FeatureCollection**, with duplicate aerodromes removed. The combined dataset retains the provisional TMAs and should not be used for operational flight navigation without verification against the current AIP.

*Data are provided for reference and testing. Verify against current AIP publications and NOTAMs before operational use.*
