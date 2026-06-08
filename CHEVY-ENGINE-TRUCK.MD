# Chevrolet Engine Reference

## RPO Engine Codes

| RPO Code | Engine            | Notes                              |
| -------- | ----------------- | ---------------------------------- |
| LY2      | 4.3L V6           | Base engine                        |
| L20      | 4.8L V8           | Base V8                            |
| LY5      | 5.3L V8           | Most common                        |
| LMG      | 5.3L V8 Flex Fuel | No AFM                             |
| LC9      | 5.3L V8 Flex Fuel | **Has AFM** — known problem engine |
| L76      | 6.0L V8           |                                    |
| L92      | 6.2L V8           | Top trim (LTZ, etc.)               |

## VIN 8th Digit — Engine ID

| 8th Digit | Engine                         |
| --------- | ------------------------------ |
| C         | 4.3L V6                        |
| T         | 4.8L V8                        |
| Z         | 5.3L V8                        |
| Y         | 5.3L V8 Flex Fuel              |
| 3         | 5.3L V8 Flex Fuel w/ AFM (LC9) |
| U         | 6.0L V8                        |
| 8         | 6.2L V8                        |


> **Note:** The 8th VIN digit tells you displacement/type. For the exact RPO code you need the door jamb sticker or a full GM decoder.

## AFM Notes

The **LC9** (VIN digit `3`) is the problematic one — Flex Fuel with Active Fuel Management. Known issues:
- Lifter collapse (often catastrophic)
- Camshaft lobe wear
- Low oil pressure once symptomatic
- Typically shows up with CEL + misfire codes (P0300s)


# GMT Platform Reference

## Full Size (Silverado / Sierra / C/K)

| Years        | Platform                   | Common Name            | Notes                                                  |
| ------------ | -------------------------- | ---------------------- | ------------------------------------------------------ |
| 1973–1987    | GMT 400 (pre-GMT branding) | "Square Body"          | C/K series; classic gen, no airbags                    |
| 1988–1998    | GMT 400                    | "OBS" (Old Body Style) | C/K → transitioned to Silverado name in '99            |
| 1999–2006    | GMT 800                    | "NBS" (New Body Style) | First gen Silverado/Sierra; no AFM                     |
| 2007–2013    | GMT 900                    |                        | AFM introduced ~2007; includes Avalanche, Tahoe, Yukon |
| 2014–2018    | K2XX                       |                        | Major redesign; L83/L86 engines; AFM still present     |
| 2019–present | T1XX                       |                        | DFM (Dynamic Fuel Management) replaces AFM             |

---

## Mid-Size (Colorado / Canyon)

| Years        | Platform | Notes                                  |
| ------------ | -------- | -------------------------------------- |
| 2004–2012    | GMT 355  | 1st gen; inline-4, inline-5, or I5 gas |
| 2015–2022    | GMT 31XX | 2nd gen; complete redesign             |
| 2023–present | GMT 45XX | 3rd gen                                |


---

## Notes on AFM by Platform

- **GMT 800 (1999–2006):** No AFM — the "good" era for the 5.3L (LM7, LY5)
- **GMT 900 (2007–2013):** AFM introduced — LC9, LMG are the problem engines
- **K2XX (2014–2018):** AFM continues — L83 is the common one
- **T1XX (2019+):** DFM (10-cylinder deactivation on a V8) — arguably worse than AFM

---

## Quick Swap Reference (5.3L)

If replacing an AFM engine, target **GMT 800-era** non-AFM 5.3s:
- **LM7** — 1999–2006, iron block, no AFM, bulletproof
- **LY5** — 2007+ but without AFM (less common)

Avoid: LC9, LMG, L83 unless doing a full AFM delete simultaneously.
