# Data Quality Issues & Suggested OCM Contributions

## Known Problems

### 1. Unnamed Multi-Connector Station (⚠️ Priority)
- **Location:** ~644m from downtown center (45.5161175, -122.6739227)
- **Problem:** No name, operator identified. Has J-1772 + CCS/SAE + CHAdeMO connectors but no power rating.
- **Action:** Field verification needed. Add operator name, power rating, and any missing connector details.

### 2. Multiple Unnamed/Duplicate Stations
- **Locations:** ~242m, ~315m, ~580m, ~692m, ~735m from center
- **Problem:** At least 4-5 stations listed as "Unnamed" with no operator, connector types, or power info.
- **Action:** OSM contribution — verify and add proper names, operators, and metadata.

### 3. Blink on SE Powell Blvd (⚠️ Status Issue)
- **Location:** ~4.2 km from center (SE Powell Blvd, 97202)
- **Problem:** Marked "Currently inaccessible due to outdoor seating"
- **Action:** Needs status update — is it still accessible? Relocated?

### 4. Missing Fee Information
- **Problem:** Many stations list "Unknown" or "Yes" for fees without specific pricing
- **Action:** Verify and update fee structure for all stations

### 5. Missing Opening Hours
- **Problem:** Most public stations lack opening hours
- **Action:** Verify hours from operator websites (Tesla, Blink, ChargePoint, EVgo, etc.)

### 6. Sunset Highway Corridor Gap
- **Problem:** No DC fast chargers between Portland and Beaverton on Sunset Highway (US-26)
- **Action:** If any charging plazas are planned or recently added, add them to OCM

### 7. Electric Island Needs Update
- **Problem:** Described as having ABB, ChargePoint, BTC, Proterra connectors with 150 kW and planned 350 kW
- **Action:** Verify current status and add Plug Share / OCM entry details

## Suggested OCM Contributions (Priority Order)

1. **Verify multi-connector station** (J-1772 + CCS/SAE + CHAdeMO) — add name, operator, power
2. **Add missing stations** along Sunset Highway corridor
3. **Enrich metadata** — connector types, power ratings, hours, fees
4. **Update Blink SE Powell Blvd** status
5. **Tag stations with bicycle access** info where known
6. **Add Electric Island** as heavy-duty charging hub with 350 kW planned expansion

## How to Contribute to OCM

- **Website:** [map.openchargemap.io](https://map.openchargemap.io)
- **API docs:** [openchargemap.org/site/develop/](https://openchargemap.org/site/develop/)
- **Contribute data via the web map** — click on any station to add comments, photos, or updates
- **Become a country editor** to approve new data additions
- **Report issues** at [github.com/openchargemap/ocm-system/issues](https://github.com/openchargemap/ocm-system/issues)