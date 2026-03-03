**Goal**: Validate the display logic of ad_banner and start_banner after the launch of experiment AS-1111 and assess whether actual banner impressions follow the defined business rules.

**Role**: Process Analyst responsible for analyzing user event data, validating experiment logic, and identifying discrepancies between expected and actual behavior.

**Tools**: SQL for event extraction and aggregation; timestamp comparison with a 5-second tolerance; Mobile-Web traffic filtering; country-level analysis (Serbia and Azerbaijan).

**Key Results**: ad_banner:
Only 48% of impressions were shown on the expected click numbers. The logic works incorrectly in Azerbaijan and does not function as intended in Serbia; start_banner: Display timing and weekly recurrence meet the defined requirements in both countries, with deviations within acceptable tolerance.

