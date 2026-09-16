# Nightly Eval Report

- Generated: 2026-09-16T19:41:50.254519+00:00
- Status: failed
- Cases: 14 total / 14 evaluated / 0 skipped

## Aggregate Metrics

- Faithfulness: 0.3236
- Answer relevancy: 0.7824
- Context precision: 1.0000
- DeepEval expected-tools pass rate: 1.0000
- DeepEval no-PII pass rate: 1.0000
- DeepEval no-promises pass rate: 1.0000
- DeepEval length-bound pass rate: 0.9286

## Thresholds

- Faithfulness >= 0.64
- Answer relevancy >= 0.7
- Context precision >= 0.6
- Deterministic DeepEval assertions: 100% pass

## Case Highlights

- `atm_pin_safety_guidance`: ragas={'faithfulness': 0.2727, 'answer_relevancy': 0.84, 'context_precision': 1.0} deepeval={expected_tools=True, no_pii_leak=True, no_forbidden_promises=True, length_bound=True}
- `plan_atm_issue_priority`: ragas={'faithfulness': 0.1333, 'answer_relevancy': 0.6122, 'context_precision': 1.0} deepeval={expected_tools=True, no_pii_leak=True, no_forbidden_promises=True, length_bound=False}
- `plan_min_balance_priority`: ragas={'faithfulness': 0.1333, 'answer_relevancy': 0.6048, 'context_precision': 1.0} deepeval={expected_tools=True, no_pii_leak=True, no_forbidden_promises=True, length_bound=True}
- `low_risk_kyc_frequency`: ragas={'faithfulness': 0.25, 'answer_relevancy': 0.9227, 'context_precision': 1.0} deepeval={expected_tools=True, no_pii_leak=True, no_forbidden_promises=True, length_bound=True}
- `email_update_timing`: ragas={'faithfulness': 0.6, 'answer_relevancy': 0.7447, 'context_precision': 1.0} deepeval={expected_tools=True, no_pii_leak=True, no_forbidden_promises=True, length_bound=True}
- `plan_kyc_update_priority`: ragas={'faithfulness': 0.0, 'answer_relevancy': 0.536, 'context_precision': 1.0} deepeval={expected_tools=True, no_pii_leak=True, no_forbidden_promises=True, length_bound=True}
- `accepted_address_proof`: ragas={'faithfulness': 0.5833, 'answer_relevancy': 0.9427, 'context_precision': 1.0} deepeval={expected_tools=True, no_pii_leak=True, no_forbidden_promises=True, length_bound=True}
- `atm_cash_debited_reversal`: ragas={'faithfulness': 0.5, 'answer_relevancy': 0.8891, 'context_precision': 1.0} deepeval={expected_tools=True, no_pii_leak=True, no_forbidden_promises=True, length_bound=True}
- `atm_standard_limit`: ragas={'faithfulness': 0.2857, 'answer_relevancy': 0.8759, 'context_precision': 1.0} deepeval={expected_tools=True, no_pii_leak=True, no_forbidden_promises=True, length_bound=True}
- `dmat_not_available`: ragas={'faithfulness': 0.2, 'answer_relevancy': 0.7934, 'context_precision': 1.0} deepeval={expected_tools=True, no_pii_leak=True, no_forbidden_promises=True, length_bound=True}

## Notes

- Cases below per-case thresholds: atm_pin_safety_guidance, plan_atm_issue_priority, plan_min_balance_priority, low_risk_kyc_frequency, email_update_timing, plan_kyc_update_priority, accepted_address_proof, atm_cash_debited_reversal, atm_standard_limit, dmat_not_available, closure_within_14_days, atm_wrong_pin_manual_reset, non_maintenance_fee
