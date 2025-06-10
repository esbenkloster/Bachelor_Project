# Final Model Validation Report
Generated: 2025-06-06 19:36:05
================================================================================
## Validation Dataset Summary
- Total samples: 100
- Known classes: 86
- Unknown/Other classes: 14

### Label Distribution
- politics: 30 samples (30.0%)
- lifestyle: 22 samples (22.0%)
- other: 14 samples (14.0%)
- science: 13 samples (13.0%)
- health: 10 samples (10.0%)
- sports: 7 samples (7.0%)
- economics: 4 samples (4.0%)

## Model Performance (Threshold: 0.9)
- **Overall Accuracy**: 0.837
- **Accuracy**: 0.878
- **Coverage**: 95.3%
- **Unknown Detection Rate**: 21.4%
- **Abstention Rate**: 7.0%

## Comparison with Previous Test Results
**Previous Results (potentially overfit):**
- Accuracy: 0.906
- Coverage: 84.8%
- Other Capture Rate: 0.0%

**Fresh Validation Results:**
- Accuracy: 0.878
- Coverage: 95.3%
- Unknown Detection Rate: 21.4%

## Performance Across Confidence Thresholds
| Threshold | Accuracy | Coverage | Unknown Detection | Abstention |
|-----------|----------|----------|-------------------|------------|
| 0.50 | 0.859 | 98.8% | 0.0% | 1.0% |
| 0.60 | 0.859 | 98.8% | 0.0% | 1.0% |
| 0.70 | 0.859 | 98.8% | 14.3% | 3.0% |
| 0.80 | 0.857 | 97.7% | 14.3% | 4.0% |
| 0.85 | 0.878 | 95.3% | 14.3% | 6.0% |
| 0.90 | 0.878 | 95.3% | 21.4% | 7.0% |
| 0.95 | 0.889 | 94.2% | 28.6% | 9.0% |
| 0.99 | 0.892 | 86.0% | 35.7% | 17.0% |

## Key Insights
- **Best Accuracy**: 0.892 at threshold 0.99
- **Best Coverage**: 98.8% at threshold 0.5
- **Unknown Sample Handling**: Model correctly abstains on 21.4% of unknown samples
- **Confidence Calibration**: 1.0 of known samples receive confident predictions

## Recommendations
Based on the fresh validation results:

✅ **Model Performance**: Strong performance maintained on fresh data
✅ **Coverage**: Good coverage of known samples
⚠️ **Unknown Detection**: Poor at identifying unknown samples

