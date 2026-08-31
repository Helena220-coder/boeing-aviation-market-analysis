Boeing Aviation Market Analysis

**Project Overview**

This project analyzes airline financial and operational data from 2010–2026 to understand trends in the commercial aviation industry and their potential implications for Boeing.

The analysis focuses on airline revenue, passenger volume, operating margins, load factors, fleet size, regional performance, and the impact of COVID-19 on the aviation industry.

This information is important for Boeing because the overall market conditions of major airlines can influence their ability and need to purchase new aircraft. By understanding these trends and disruptions (such as COVID-19), Boeing can better identify market opportunities, anticipate aircraft demand, and make strategic business decisions.

**Business Questions**

Which airlines generated the highest revenue?

Which airlines carried the most passengers?

How has airline revenue changed from 2010–2026?

How did COVID-19 affect the airline industry?

Which regions generated the most revenue?

Which regions have the largest airline fleets?

Which airlines have the highest operating margins?

Does fleet size relate to airline revenue?

Does load factor affect airline profitability?
Which business models perform better?

**Data**

The main dataset used for this project is airline_financials.csv.

The dataset contains information about:

Year
Airline name and IATA code
Country and region
Business model
Revenue
Operating margin
Operating income
Passengers carried
Fleet size
Data Cleaning

I used SQL to check and validate the dataset before performing the analysis.

The data-cleaning process included:

NULL value checks
Duplicate record checks
Invalid and negative value checks
Data validation
Category and consistency checks
SQL Analysis

SQL was used to analyze the cleaned dataset and answer the main business questions.

Examples of the analysis included:

Total airline revenue by year
Revenue by airline
Revenue by region
Passenger trends
Operating margin analysis
Fleet size analysis
COVID-19 impact analysis
Tableau Dashboard

I created interactive Tableau dashboards to visualize the results of the analysis.

The dashboards include:

Executive Overview
Airline Performance
Revenue by Region
Passenger Trends
Fleet Distribution
Revenue Over Time
COVID-19 Impact
Operating Margin Trends

Tableau Dashboard: See the dashboard images in the Main folder for examples (the interactive dashboards were pushed to tableau public and can be requested).

**Key Findings**

1. Fleet demand has fully recovered and is now running ~35% above pre-COVID levels.

Across the 30 carriers examined within the dataset, implied fleet went from 2,583 aircraft in 2019 to 1,007 in 2020, back through 2019 levels in 2022, and up to 3,500 by 2026 — a 4.4% annual growth rate off the 2019 base. The COVID trough was deep but short: North America crossed its 2019 fleet in 2022, Asia not until 2023. For Boeing, the demand signal is not a recovery story any more; it's seven straight years of net expansion with no plateau in the data.

2. The fastest-growing region is also the least able to pay for it.

The Middle East leads fleet growth at 6.7% annually since 2019 (264 → 416 aircraft), but its 2026 average operating margin is -4.3% — the only negative region in a non-COVID year. That's driven by Riyadh Air (-22.7%) and Saudia (-19.1%), both expanding hard while losing money. North America grows slower (4.7%) but adds more absolute units (+336 since 2019) off a profitable 7.4% margin base. Thus, gulf growth likely depends on state backing rather than carrier cash flow, which makes those order books more politically contingent and less credit-driven.

3. Low-cost carriers are the structurally healthier customer segment.

In 2026 LCCs average an 11.0% operating margin against 2.7% for legacy carriers, and they hold the top six load factors in the dataset (Southwest 88.3%, Ryanair 87.9%, IndiGo 87.0%). Their fleets grew 51% since 2019 versus 33% for legacy. Every one of the seven most profitable airlines in 2026 is either low-cost or regional. This points toward single-aisle, high-density demand from operators with the balance sheets to fund it — while the widebody-heavy legacy segment is where margin risk sits.

4. Legacy margins collapsed in 2026 even as fleets kept growing — a leading warning.

Legacy operating margin fell from 8.1% in 2025 to 2.7% in 2026 while legacy fleet still added ~100 aircraft. Meanwhile load factors are pinned at 83–86% in every single non-COVID year across every region, meaning airlines add capacity in lockstep with traffic rather than to relieve full aircraft. Capacity is therefore being added into weakening returns, and because there's no load-factor slack to absorb a traffic shock, any demand slowdown transmits almost immediately into deferred deliveries.

**Boeing Business Implications and Recommendations**

1. Weight narrowbody production capacity ahead of widebody.

The profitable, high-utilization demand in the data is low-cost and regional: 11.0% and 5.5% operating margins in 2026 against 2.7% for legacy, with LCC fleets up 51% since 2019 versus 33% for legacy. Prioritize 737 MAX rate increases and treat widebody ramp-up as the more conditional investment.

2. Underwrite Gulf orders differently than commercial ones.

Middle East fleet growth leads at 6.7% annually, but the region posted a -4.3% margin in 2026 with Riyadh Air at -22.7% and Saudia at -19.1%. Boeing should structure those campaigns around sovereign guarantees and government relationships rather than carrier credit, and stress-test the backlog for what happens if state support tightens.

3. Build the delivery schedule around North America as the volume anchor.

NA has led revenue in all seventeen years, adds the most absolute aircraft (+336 since 2019), and does it at a healthy 7.4% margin. It also recovered from COVID roughly two years faster than Asia, which makes it the most reliable base-load demand and the right region for firm rate commitments.

4. Use legacy operating margin as an early-warning indicator for deferrals.

Legacy margin dropped from 8.1% to 2.7% in a single year while those carriers were still adding capacity. Boeing should formalize a leading-indicator dashboard on customer margins so it can adjust production rates before deferral requests arrive, rather than after — the mistake that has historically been most expensive for the company.

5. Treat load factor as a demand ceiling, not a cushion.

Load factors sit at 83–86% in every non-COVID year across every region, so airlines have no slack to absorb traffic growth without adding aircraft — good for orders, but it also means a traffic shock passes straight through to deliveries with no buffer. Scenario-plan a 2020-style disruption explicitly: fleet demand fell 61% in one year, and Boeing's supply chain and financing structure should be sized to survive that without permanent capability loss.

**Tools Used**

MySQL<br>
Tableau<br>
Canva<br>
Project Presentation<br>
The full project presentation is available in this repository as a PDF.

**Author**

Helena Ehrari<br>
M.S. in Information Systems (MSIS), Expected '27<br>
University of Washington – Foster School of Business
