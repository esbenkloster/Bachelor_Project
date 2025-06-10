# Final Model Validation Report
Generated: 2025-06-07 00:54:43
================================================================================
## Validation Dataset Summary
- Total samples: 110
- Known classes: 96
- Unknown/Other classes: 14

### Label Distribution
- politics: 30 samples (27.3%)
- lifestyle: 22 samples (20.0%)
- other: 14 samples (12.7%)
- economics: 14 samples (12.7%)
- science: 13 samples (11.8%)
- health: 10 samples (9.1%)
- sports: 7 samples (6.4%)

## Model Performance (Threshold: 0.9)
- **Overall Accuracy**: 0.854
- **Accuracy**: 0.891
- **Coverage**: 95.8%
- **Unknown Detection Rate**: 21.4%
- **Abstention Rate**: 6.4%

## Comparison with Previous Test Results
**Previous Results (potentially overfit):**
- Accuracy: 0.906
- Coverage: 84.8%
- Other Capture Rate: 0.0%

**Fresh Validation Results:**
- Accuracy: 0.891
- Coverage: 95.8%
- Unknown Detection Rate: 21.4%

## Performance Across Confidence Thresholds
| Threshold | Accuracy | Coverage | Unknown Detection | Abstention |
|-----------|----------|----------|-------------------|------------|
| 0.50 | 0.874 | 99.0% | 0.0% | 0.9% |
| 0.60 | 0.874 | 99.0% | 0.0% | 0.9% |
| 0.70 | 0.874 | 99.0% | 14.3% | 2.7% |
| 0.80 | 0.872 | 97.9% | 14.3% | 3.6% |
| 0.85 | 0.891 | 95.8% | 14.3% | 5.5% |
| 0.90 | 0.891 | 95.8% | 21.4% | 6.4% |
| 0.95 | 0.900 | 93.8% | 28.6% | 9.1% |
| 0.99 | 0.901 | 84.4% | 35.7% | 18.2% |

## Key Insights
- **Best Accuracy**: 0.901 at threshold 0.99
- **Best Coverage**: 99.0% at threshold 0.5
- **Unknown Sample Handling**: Model correctly abstains on 21.4% of unknown samples
- **Confidence Calibration**: 1.0 of known samples receive confident predictions

## Recommendations
Based on the fresh validation results:

✅ **Model Performance**: Strong performance maintained on fresh data
✅ **Coverage**: Good coverage of known samples
⚠️ **Unknown Detection**: Poor at identifying unknown samples

