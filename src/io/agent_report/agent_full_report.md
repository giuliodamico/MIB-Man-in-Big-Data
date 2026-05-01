# Transit Anomaly Report

## Perimeter
{}

## Summary
- Routes analysed: **564**
- Consensus anomalies (≥ 2/4 detectors): **10**
- Risk distribution: {'MEDIUM': 5, 'LOW': 3, 'HIGH': 2}

## Detector counts
{
  "if_anomaly": 29,
  "lof_anomaly": 29,
  "dbscan_anomaly": 13,
  "z_anomaly": 0,
  "consensus_>=2": 10,
  "consensus_>=3": 0
}

## Top-10 ranked anomalies
|   rank | route   | DEPARTURE_COUNTRY   |   alert_rate | ci95_str        |   tot_investigated |   absolute_alarms |   anomaly_votes | risk_level   |   priority_score | quality_note   |
|-------:|:--------|:--------------------|-------------:|:----------------|-------------------:|------------------:|----------------:|:-------------|-----------------:|:---------------|
|      1 | TIA→BLQ | ALBANIA             |     0.19984  | [19.4%, 20.5%]  |              20061 |              4009 |               2 | MEDIUM       |           0.507  | ok             |
|      2 | TIA→BGY | ALBANIA             |     0.135672 | [13.2%, 13.9%]  |              34458 |              4675 |               2 | LOW          |           0.4779 | ok             |
|      3 | TIA→TSF | ALBANIA             |     0.169234 | [16.3%, 17.6%]  |              12657 |              2142 |               2 | LOW          |           0.4585 | ok             |
|      4 | DOH→MXP | QATAR               |     1        | [61.0%, 100.0%] |                  6 |                 6 |               2 | MEDIUM       |           0.422  | ok             |
|      5 | IST→MXP | TURCHIA             |     0.555556 | [42.4%, 68.0%]  |                 54 |                30 |               2 | HIGH         |           0.3688 | ok             |
|      6 | STN→BGY | REGNO UNITO         |     0.232704 | [17.4%, 30.4%]  |                159 |                37 |               2 | MEDIUM       |           0.2711 | ok             |
|      7 | IST→FCO | TURCHIA             |     0.382353 | [23.9%, 55.0%]  |                 34 |                13 |               2 | HIGH         |           0.2443 | ok             |
|      8 | RAK→CIA | MAROCCO             |     0.571429 | [25.0%, 84.2%]  |                  7 |                 4 |               2 | MEDIUM       |           0.1713 | ok             |
|      9 | JFK→FCO | STATI UNITI         |     0.233333 | [11.8%, 40.9%]  |                 30 |                 7 |               2 | MEDIUM       |           0.169  | ok             |
|     10 | GIG→FCO | BRASILE             |     0        | [0.0%, 43.4%]   |                  5 |                 0 |               2 | LOW          |           0      | ok             |

## Interpretation
The ranked anomalies should be treated as an investigation queue, not as confirmed incidents. Higher-rank items combine high alert rate with meaningful volume and tight confidence intervals.
