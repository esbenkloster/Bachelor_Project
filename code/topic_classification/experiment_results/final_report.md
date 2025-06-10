# Comprehensive BART Model Experiments - Final Report
Generated: 2025-05-27 22:44:20
================================================================================
## Experiment Summary
- Total configurations tested: 48
- Experiments: with_other, without_other
- Model modes: tweet, note, combined
- Confidence thresholds: 0.5, 0.6, 0.7, 0.8, 0.85, 0.9, 0.95, 0.99

## Best Overall Performance
**Best Configuration:**
- Experiment: without_other
- Mode: combined
- Confidence Threshold: 0.95
- Committed Accuracy: 0.906
- Coverage: 84.8%
- Other Capture Rate: 0.0%

## Performance by Experiment
### With Other
**Tweet Model:**
- Best Accuracy: 0.848 (threshold: 0.95)
- Coverage: 82.0%
- Other Capture: 0.0%

**Note Model:**
- Best Accuracy: 0.755 (threshold: 0.95)
- Coverage: 85.9%
- Other Capture: 0.0%

**Combined Model:**
- Best Accuracy: 0.887 (threshold: 0.99)
- Coverage: 82.8%
- Other Capture: 0.0%

### Without Other
**Tweet Model:**
- Best Accuracy: 0.868 (threshold: 0.99)
- Coverage: 84.8%
- Other Capture: 66.7%

**Note Model:**
- Best Accuracy: 0.779 (threshold: 0.95)
- Coverage: 83.2%
- Other Capture: 33.3%

**Combined Model:**
- Best Accuracy: 0.906 (threshold: 0.95)
- Coverage: 84.8%
- Other Capture: 0.0%

## Model Comparison Table
### At Confidence Threshold 0.5
| Experiment | Mode | Committed Acc | Coverage | Other Capture |
|------------|------|---------------|----------|---------------|
| with_other | tweet | 0.797 | 100.0% | 0.0% |
| with_other | note | 0.728 | 97.7% | 0.0% |
| with_other | combined | 0.852 | 100.0% | 0.0% |
| without_other | tweet | 0.862 | 98.4% | 0.0% |
| without_other | note | 0.736 | 100.0% | 0.0% |
| without_other | combined | 0.878 | 98.4% | 0.0% |

### At Confidence Threshold 0.8
| Experiment | Mode | Committed Acc | Coverage | Other Capture |
|------------|------|---------------|----------|---------------|
| with_other | tweet | 0.821 | 91.4% | 0.0% |
| with_other | note | 0.741 | 90.6% | 0.0% |
| with_other | combined | 0.869 | 95.3% | 0.0% |
| without_other | tweet | 0.861 | 97.6% | 0.0% |
| without_other | note | 0.765 | 92.0% | 33.3% |
| without_other | combined | 0.890 | 94.4% | 0.0% |

### At Confidence Threshold 0.9
| Experiment | Mode | Committed Acc | Coverage | Other Capture |
|------------|------|---------------|----------|---------------|
| with_other | tweet | 0.836 | 85.9% | 0.0% |
| with_other | note | 0.737 | 89.1% | 0.0% |
| with_other | combined | 0.886 | 89.1% | 0.0% |
| without_other | tweet | 0.866 | 95.2% | 0.0% |
| without_other | note | 0.757 | 88.8% | 33.3% |
| without_other | combined | 0.904 | 91.2% | 0.0% |

## Key Insights
### Impact of Excluding 'Other' Class
- Tweet: +0.040 accuracy improvement when excluding 'other'
- Note: +0.024 accuracy improvement when excluding 'other'
- Combined: +0.021 accuracy improvement when excluding 'other'

### Optimal Confidence Thresholds
- Tweet: 0.99 (Accuracy: 0.868, Coverage: 84.8%)
- Note: 0.95 (Accuracy: 0.779, Coverage: 83.2%)
- Combined: 0.95 (Accuracy: 0.906, Coverage: 84.8%)

