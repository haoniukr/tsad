# Detailed results
We provide files in three formats (csv, latex and markdown) for the convience.

## cleaning_rate
**Eva100\*** (input length 100): the detailed cleaning rate results for each input type, anomaly type and model

**Eva1000\*** (input length 1000): the detailed cleaning rate results for each input type, anomaly type and model

**Overall\***: Averaged cleaning rate among input and anomaly types

cleaning_operation_sum.png: Figure 2 in the submission

## results_length100/results_length1000

Eva100_sample_*_[precision, recall, f1, balanced_accuracy] (input length 100): the detailed [precision, recall, f1, balanced_accuracy] results for each input type, anomaly type and model for sample (i.e., series)-level detection

Eva100_step_*_[precision, recall, f1, balanced_accuracy] (input length 100): the detailed [precision, recall, f1, balanced_accuracy] results for each input type, anomaly type and model for step-level detection

Eva100_sample_level_input_types_average_metrics_on_anomaly_types_anomaly_z0_prf1_bacc (input length 100): the [precision, recall, f1, balanced_accuracy] results averaged on anomaly types for sample (i.e., series)-level detection (Table 4 in the submission)

Eva100_step_level_input_types_average_metrics_on_anomaly_types_anomaly_z0_prf1_bacc (input length 100): the detailed [precision, recall, f1, balanced_accuracy] results for each input type, anomaly type and model for step-level detection (Table 6 in the submission)

The corresponsding files of Eva1000* in "./results_length1000" are the results of input length 1000.

