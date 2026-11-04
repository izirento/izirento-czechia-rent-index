# Czechia: rent and landlord rules index 2026

Open, source-linked data on residential rent and landlord obligations in Czechia: deposits, rent increases, termination notice, lease terms, registration and landlord duties, with a primary-source link for every value.

- Version: 1.0
- Facts checked: 2026-11-04
- Author: Leonid Gorok
- Project site: [izirento.com](https://izirento.com)
- Related: [UK Rent & Landlord Obligations Index 2026](https://izirento.com/en-gb/research/data/uk-rents-and-landlord-duties-index), [UK repository](https://github.com/izirento/izirento-uk-rent-index), [catalog of country repositories](https://github.com/izirento/izirento-rent-index-international)
- EU rent price change for all 27 member states: [izirento-eu-rent-index](https://github.com/izirento/izirento-eu-rent-index)
- Licence: CC BY 4.0 (see [`LICENSE`](LICENSE) and [`LICENSE.md`](LICENSE.md)). Laws and official statistics are cited, not copied.

## Disclaimer

The data is provided as is, without any liability. We only collect and organise what the official sources publish. Laws change and local rules differ: always check each value against the primary source linked next to it before relying on it. This is information, not legal advice.

## IziRento pages for this country

- [Home, Čeština](https://izirento.com/cs-cz)

## Key facts

| Topic | Field | Value | Source |
| --- | --- | --- | --- |
| tenancy_law | Main law | Civil Code (Act No. 89/2012 Coll.), provisions on lease of a flat (§ 2235 and following). | [Collection of Laws portal (Zákony pro lidi)](https://www.zakonyprolidi.cz/cs/2012-89) |
| contract_form | Written contract | A lease of a flat requires a written form; the landlord cannot rely on invalidity for lack of form against the tenant (§ 2237). | [Collection of Laws portal (Zákony pro lidi)](https://www.zakonyprolidi.cz/cs/2012-89) |
| deposit | Maximum deposit | A cash security plus any contractual penalty may not in total exceed three times the monthly rent; at the end of the lease the landlord returns it, setting off what the tenant owes, and the tenant is entitled to interest at least at the statutory rate (§ 2254). | [Collection of Laws portal (Zákony pro lidi)](https://www.zakonyprolidi.cz/cs/2012-89) |
| rent_increase | Annual increase by agreement | The parties may agree on annual rent increases (§ 2248). | [Collection of Laws portal (Zákony pro lidi)](https://www.zakonyprolidi.cz/cs/2012-89) |
| rent_increase | Landlord proposal to comparable rent | If no increase was agreed or excluded, the landlord may propose in writing an increase up to the comparable local rent, provided that together with increases in the previous three years it does not exceed 20 percent; a proposal made before 12 months without an increase has passed is disregarded (§ 2249(1)). | [Collection of Laws portal (Zákony pro lidi)](https://www.zakonyprolidi.cz/cs/2012-89) |
| termination | Landlord notice | The landlord may terminate a fixed-term or open-ended lease with three months notice for gross breach by the tenant, certain criminal convictions, public-interest vacating, or a similarly serious reason (§ 2288(1)); for an open-ended lease also where the flat is needed for the landlord or close relatives (§ 2288(2)). Notice must be in writing and the notice period runs from the first day of the month after delivery; the tenant must be informed of the right to object and to court review, or the notice is invalid (§ 2286). | [Collection of Laws portal (Zákony pro lidi)](https://www.zakonyprolidi.cz/cs/2012-89) |
| termination | Immediate termination | For an especially serious breach, such as non-payment of rent and service costs for at least three months, the landlord may terminate without a notice period, after a prior call to remedy the conduct (§ 2291). | [Collection of Laws portal (Zákony pro lidi)](https://www.zakonyprolidi.cz/cs/2012-89) |
| rent_level_change | Rent price change, 2025 annual average (HICP actual rentals for housing) | 6.1 percent (2024: 6.7 percent) | [Eurostat](https://ec.europa.eu/eurostat/api/dissemination/statistics/1.0/data/prc_hicp_aind?format=JSON&lang=EN&coicop=CP041&unit=RCH_A_AVG&geo=CZ&time=2025) |
| rent_level_change | Rent price change, December 2025 year on year (HICP actual rentals for housing) | 6.4 percent | [Eurostat](https://ec.europa.eu/eurostat/api/dissemination/statistics/1.0/data/prc_hicp_manr?format=JSON&lang=EN&coicop=CP041&unit=RCH_A&geo=CZ&time=2025-12) |

## Čeština

**Česko.** Otevřená data o nájmu a povinnostech pronajímatele: kauce, zvýšení nájemného, výpovědní lhůty a nájemní smlouva, u každé hodnoty odkaz na oficiální zdroj.

*Data poskytujeme tak, jak jsou, bez jakékoli odpovědnosti. Pouze třídíme to, co zveřejňují oficiální zdroje. Zákony se mění: každou hodnotu ověřte v odkazovaném primárním zdroji.*

Details: see the table above and `sources.md`.

## Files

| File | Content |
| --- | --- |
| `czechia_rent_landlord_rules_2026.csv` | One row per fact, with source URL, optional cross-check URL and check date |
| `sources.md` | Every field with publisher and links, plus fields left empty and notes |
| `LICENSE`, `LICENSE.md` | CC BY 4.0 legal code; attribution and source statements |
| `CITATION.cff` | Citation metadata |
| (Eurostat rows) | The last rows of the CSV hold the Eurostat rent price change for this country (HICP actual rentals, item CP041) |

## Field dictionary

| Field | Meaning |
| --- | --- |
| `country_code, country` | Code and name |
| `topic` | Group: tenancy_law, deposit, rent_increase, rent_control, termination, contract_form, registration, rent_payment, landlord_duties, rent_level_change and similar |
| `field` | Specific item |
| `value` | The fact in our own words; empty where no verified figure was found |
| `source_publisher` | Body that publishes the source |
| `source_url` | Link to the primary source |
| `cross_check_url` | Second source actually read, if any |
| `checked_on` | Date the source was read |
| `note` | Scope, language of the source or caveat |

## Method

1. Each value comes from a primary source: the statute on the official legal portal, a government service page or a statistics office dataset. Where a second official or institutional page confirms it, that link is in `cross_check_url`.
2. Values are written in our own words. Nothing is estimated or calculated; where no verified value exists the cell is empty and the reason is given in `sources.md`.
3. Rent price change is the Eurostat HICP index of rents actually paid. It shows how rents moved, not what they cost. The API responses used were last updated by Eurostat on 6 February 2026, so the latest period is December 2025.
4. Where a statute is translated or summarised from another language, the original-language text prevails.

## Citation

Gorok, L. (2026). *Czechia: rent and landlord rules index 2026* (Version 1.0) [Data set]. IziRento. https://github.com/izirento/izirento-czechia-rent-index

## Attribution

Sources are listed in `sources.md` and in `LICENSE.md`.
