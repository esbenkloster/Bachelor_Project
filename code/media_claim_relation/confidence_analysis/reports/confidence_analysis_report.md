# MODEL CONFIDENCE AND CALIBRATION ANALYSIS REPORT

## Executive Summary
- Total Predictions: 1,608
- Unique Models: 24
- Overall Accuracy: 0.3097
- Average Confidence: 0.3796
- Confidence-Accuracy Correlation: 0.1795

## Confidence Threshold Analysis
### High Confidence
- Accuracy: 0.5714
- Predictions: 49 (3.0%)

### Medium Confidence
- Accuracy: 0.4636
- Predictions: 110 (6.8%)

### Low Confidence
- Accuracy: 0.2892
- Predictions: 1,449 (90.1%)

## Model Calibration Summary (Sorted by ECE)
1. **deberta-v3-large**
   - ECE: 0.0070
   - Brier: 0.1958
   - Accuracy: 0.2687
   - Avg Confidence: 0.2756

2. **roberta-base**
   - ECE: 0.0171
   - Brier: 0.1970
   - Accuracy: 0.2687
   - Avg Confidence: 0.2858

3. **deberta-v3-base**
   - ECE: 0.0336
   - Brier: 0.1822
   - Accuracy: 0.2388
   - Avg Confidence: 0.2725

4. **distilbert-base-uncased**
   - ECE: 0.0474
   - Brier: 0.2134
   - Accuracy: 0.3433
   - Avg Confidence: 0.3171

5. **DialoGPT-medium**
   - ECE: 0.0497
   - Brier: 0.2042
   - Accuracy: 0.2687
   - Avg Confidence: 0.3173

6. **deberta-v3-large**
   - ECE: 0.0550
   - Brier: 0.1694
   - Accuracy: 0.2090
   - Avg Confidence: 0.2640

7. **deberta-v3-base**
   - ECE: 0.0594
   - Brier: 0.1713
   - Accuracy: 0.2090
   - Avg Confidence: 0.2684

8. **roberta-large**
   - ECE: 0.0629
   - Brier: 0.1857
   - Accuracy: 0.2388
   - Avg Confidence: 0.3017

9. **deberta-v3-large**
   - ECE: 0.0664
   - Brier: 0.1990
   - Accuracy: 0.2985
   - Avg Confidence: 0.3416

10. **deberta-v3-base**
   - ECE: 0.0666
   - Brier: 0.1763
   - Accuracy: 0.2239
   - Avg Confidence: 0.2827

11. **roberta-large**
   - ECE: 0.0692
   - Brier: 0.2159
   - Accuracy: 0.3284
   - Avg Confidence: 0.2888

12. **distilbert-base-uncased**
   - ECE: 0.0764
   - Brier: 0.1705
   - Accuracy: 0.2090
   - Avg Confidence: 0.2853

13. **bert-base-uncased**
   - ECE: 0.0874
   - Brier: 0.2050
   - Accuracy: 0.3731
   - Avg Confidence: 0.3965

14. **distilbert-base-uncased**
   - ECE: 0.0948
   - Brier: 0.2488
   - Accuracy: 0.4925
   - Avg Confidence: 0.4045

15. **DialoGPT-medium**
   - ECE: 0.1105
   - Brier: 0.2134
   - Accuracy: 0.2687
   - Avg Confidence: 0.3414

16. **DialoGPT-medium**
   - ECE: 0.1109
   - Brier: 0.2052
   - Accuracy: 0.2537
   - Avg Confidence: 0.3491

17. **roberta-base**
   - ECE: 0.1223
   - Brier: 0.1957
   - Accuracy: 0.2687
   - Avg Confidence: 0.3774

18. **bert-base-uncased**
   - ECE: 0.1254
   - Brier: 0.2183
   - Accuracy: 0.3284
   - Avg Confidence: 0.4365

19. **roberta-large**
   - ECE: 0.1360
   - Brier: 0.2073
   - Accuracy: 0.5522
   - Avg Confidence: 0.6120

20. **bert-base-uncased**
   - ECE: 0.1380
   - Brier: 0.2381
   - Accuracy: 0.4179
   - Avg Confidence: 0.3292

21. **roberta-base**
   - ECE: 0.1410
   - Brier: 0.2459
   - Accuracy: 0.4179
   - Avg Confidence: 0.4671

22. **Llama-3.2-1B-Instruct**
   - ECE: 0.3008
   - Brier: 0.3068
   - Accuracy: 0.2836
   - Avg Confidence: 0.5844

23. **Llama-3.2-1B-Instruct**
   - ECE: 0.3105
   - Brier: 0.3080
   - Accuracy: 0.3433
   - Avg Confidence: 0.6538

24. **Llama-3.2-1B-Instruct**
   - ECE: 0.3283
   - Brier: 0.3297
   - Accuracy: 0.3284
   - Avg Confidence: 0.6567
