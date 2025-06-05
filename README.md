#  Aviation Accident Data Analysis

A data-driven project exploring aircraft safety using real-world aviation accident data. I cleaned the dataset, analyzed patterns in injury and destruction rates, and identified safer aircraft models.

Aviation Accident Data Project

This project analyzes aviation accident records to identify safer aircraft makes and models, focusing on injury and destruction risks. The goal is to support safety-focused decisions for airlines, insurers, or aviation analysts.

⸻

 Data Cleaning Decisions

To prepare the dataset for analysis, I performed the following steps:
	•	Standardized Formatting: Converted all string entries to uppercase and removed leading/trailing spaces.
	•	Handled Inconsistent Entries: Replaced non-standard placeholders like 'UNKNOWN', 'UNK', and 'NAN' with proper NaN values.
	•	Imputed or Removed NaNs:
	•	Filled or removed missing values in key columns such as ENGINE_TYPE, WEATHER_CONDITION, and NUMBER_OF_ENGINES.
	•	Dropped rows missing essential fields like MODEL or AIRCRAFT_DAMAGE.
	•	Created Derived Columns:
	•	INJURY_RATE: Calculated as serious or fatal injuries divided by total people onboard.
	•	AIRCRAFT_DESTROYED: Boolean field showing whether the aircraft was destroyed in the accident.

⸻

Analysis & Visualizations

I explored accident trends by:
	•	Comparing Injury & Destruction Rates:
	•	Grouped results by aircraft make, engine type, and size (small vs. large).
	•	Calculated average injury and destruction rates per group.
	•	Focused Visualizations:
	•	Bar plots for the 15 aircraft makes with the lowest injury and destruction rates.
	•	Violin and strip plots to show distribution of injury rates by aircraft make.
	•	Size-Based Comparison:
	•	Separated small aircraft (< 20 passengers) and large aircraft (≥ 20 passengers).
	•	Produced side-by-side charts to highlight the safest makes in both groups.

⸻

 Summary of Key Findings
	•	Consistently Low-Risk Makes: Aircraft from SAAB, Airbus, Fokker, and Cessna frequently showed lower injury and destruction rates.
	•	Engine Type Matters: Reciprocating and turbojet engines were linked to lower average risk compared to hybrid or experimental engines.
	•	Size Distinctions: Some small aircraft makes had very low injury rates but appeared in fewer incidents overall.

⸻

Client Recommendation

Based on the analysis, I recommend prioritizing aircraft makes that consistently show lower serious/fatal injury and destruction rates, especially Airbus, Cessna, and SAAB for large aircraft, and Cub Crafters or Bombardier for small aircraft.

This can support risk evaluation and underwriting in aviation insurance or safety-oriented aircraft procurement.

⸻

 Tools Used
	•	pandas – for data cleaning and manipulation
	•	matplotlib – for creating static visualizations
	•	seaborn – for advanced plots like violin and strip plots
	•	numpy – for handling numerical operations and NaNs

This project analyzes aviation accident records to identify safer aircraft makes and models, focusing on injury and destruction risks. The goal is to support safety-focused decisions for airlines, insurers, or aviation analysts.

⸻

 Data Cleaning Decisions

To prepare the dataset for analysis, I performed the following steps:
	•	Standardized Formatting: Converted all string entries to uppercase and removed leading/trailing spaces.
	•	Handled Inconsistent Entries: Replaced non-standard placeholders like 'UNKNOWN', 'UNK', and 'NAN' with proper NaN values.
	•	Imputed or Removed NaNs:
	•	Filled or removed missing values in key columns such as ENGINE_TYPE, WEATHER_CONDITION, and NUMBER_OF_ENGINES.
	•	Dropped rows missing essential fields like MODEL or AIRCRAFT_DAMAGE.
	•	Created Derived Columns:
	•	INJURY_RATE: Calculated as serious or fatal injuries divided by total people onboard.
	•	AIRCRAFT_DESTROYED: Boolean field showing whether the aircraft was destroyed in the accident.

⸻

 Analysis & Visualizations

I explored accident trends by:
	•	Comparing Injury & Destruction Rates:
	•	Grouped results by aircraft make, engine type, and size (small vs. large).
	•	Calculated average injury and destruction rates per group.
	•	Focused Visualizations:
	•	Bar plots for the 15 aircraft makes with the lowest injury and destruction rates.
	•	Violin and strip plots to show distribution of injury rates by aircraft make.
	•	Size-Based Comparison:
	•	Separated small aircraft (< 20 passengers) and large aircraft (≥ 20 passengers).
	•	Produced side-by-side charts to highlight the safest makes in both groups.

⸻
 Summary of Key Findings
	•	Consistently Low-Risk Makes: Aircraft from SAAB, Airbus, Fokker, and Cessna frequently showed lower injury and destruction rates.
	•	Engine Type Matters: Reciprocating and turbojet engines were linked to lower average risk compared to hybrid or experimental engines.
	•	Size Distinctions: Some small aircraft makes had very low injury rates but appeared in fewer incidents overall.

⸻

 Client Recommendation

Based on the analysis, I recommend prioritizing aircraft makes that consistently show lower serious/fatal injury and destruction rates, especially Airbus, Cessna, and SAAB for large aircraft, and Cub Crafters or Bombardier for small aircraft.

This can support risk evaluation and underwriting in aviation insurance or safety-oriented aircraft procurement.

⸻

 Tools Used
	•	pandas – for data cleaning and manipulation
	•	matplotlib – for creating static visualizations
	•	seaborn – for advanced plots like violin and strip plots
	•	numpy – for handling numerical operations and NaNs

