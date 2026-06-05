# .

* SAT 0
* UNSAT 4
* TIMEOUT 113
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/AUFBVFPDTNIRA.tar.zst?download=1 | Source list: quantifier_benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-AUFBVFPDTNIRA.tar.
Runner: rise-runner-1
Z3 repo: Z3Prover/z3
Z3 commit: 30c74fccee4d195424588e28574ecaf0f9335f2c
Z3 branch: 30c74fccee4d195424588e28574ecaf0f9335f2c
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/AUFBVFPDTNIRA.tar.zst?download=1
Z3 commit message: Go bindings: extract CGo slice-conversion helpers to eliminate boilerplate (#9465)

* Initial plan

* simplify Go bindings: extract CGo slice conversion helpers in z3.go

Agent-Logs-Url: https://github.com/Z3Prover/z3/sessions/eb6e05d8-f45a-40fb-b61f-17d4058bccb6

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

---------

Co-authored-by: copilot-swe-agent[bot] <198982749+Copilot@users.noreply.github.com>
Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_62_14_postcondition___00.smt2 |    0.023s | 19.284MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/P816-010__prefix_inline__generic_queue.ads_46_32_some_package.adb_8_4_range_check___00.smt2 |    0.024s | 20.136MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/P816-010__prefix_inline__generic_queue.ads_73_32_some_package.adb_8_4_range_check___00.smt2 |    0.027s | 20.036MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/P816-010__prefix_inline__generic_queue.ads_65_32_some_package.adb_8_4_range_check___00.smt2 |    0.040s | 20.032MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_69_34_unreachable_branch___00.smt2 |   20.006s | 22.868MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_74_34_unreachable_branch___00.smt2 |   20.006s | 22.88MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__test_failsafe.adb_15_19_assert___00.smt2 |   20.006s | 23.904MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/MC12-024__flow_crash__p.ads_27_22_postcondition___00.smt2 |   20.007s | 27.432MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_67_27_unreachable_branch___00.smt2 |   20.007s | 22.836MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_26_14_unreachable_branch___00.smt2 |   20.007s | 29.644MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_67_66_range_check___00.smt2 |   20.007s | 22.928MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_73_30_unreachable_branch___00.smt2 |   20.007s | 22.904MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/MA16-036__flow_missing_globals__logger.adb_39_13_range_check___00.smt2 |   20.007s | 23.616MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__test_failsafe.adb_12_4_precondition___00.smt2 |   20.007s | 23.912MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_71_30_unreachable_branch___00.smt2 |   20.007s | 22.844MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_11_16_dead_code___00.smt2 |   20.007s | 29.028MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/MC12-024__flow_crash__p.adb_32_28_fp_overflow_check___00.smt2 |   20.007s | 28.8MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/MA16-036__flow_missing_globals__logger.adb_44_23_length_check___00.smt2 |   20.007s | 23.732MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_42_59_unreachable_branch___00.smt2 |   20.007s | 22.876MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_14_16_dead_code___00.smt2 |   20.007s | 28.872MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_41_21_unreachable_branch___00.smt2 |   20.007s | 28.896MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/MA16-036__flow_missing_globals__logger.adb_46_31_range_check___00.smt2 |   20.007s | 23.724MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_58_25_assert___00.smt2 |   20.007s | 22.928MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_50_25_assert___00.smt2 |   20.007s | 22.828MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_34_19_contract_case___00.smt2 |   20.007s | 29.728MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_42_28_unreachable_branch___00.smt2 |   20.007s | 22.864MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_19_61_range_check___00.smt2 |   20.007s | 29.072MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_40_17_unreachable_branch___00.smt2 |   20.007s | 29.648MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_39_73_range_check___00.smt2 |   20.007s | 29.564MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/MA16-036__flow_missing_globals__logger.adb_46_20_length_check___00.smt2 |   20.007s | 23.656MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_56_14_postcondition___00.smt2 |   20.007s | 22.84MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/MA16-036__flow_missing_globals__logger.adb_42_35_length_check___00.smt2 |   20.007s | 23.656MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_40_27_unreachable_branch___00.smt2 |   20.007s | 22.876MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_53_30_unreachable_branch___00.smt2 |   20.007s | 22.948MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__test_failsafe.adb_14_4_precondition___00.smt2 |   20.007s | 23.844MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_58_17_unreachable_branch___00.smt2 |   20.007s | 22.832MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_59_54_unreachable_branch___00.smt2 |   20.008s | 22.856MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_43_27_unreachable_branch___00.smt2 |   20.008s | 23.156MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/MA16-036__flow_missing_globals__logger.adb_46_20_range_check___00.smt2 |   20.008s | 23.652MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_39_52_unreachable_branch___00.smt2 |   20.008s | 22.892MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_65_27_unreachable_branch___00.smt2 |   20.008s | 22.852MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/MA16-036__flow_missing_globals__logger.ads_50_55_range_check___00.smt2 |   20.008s | 23.74MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_16_28_assert___00.smt2 |   20.008s | 29.56MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_24_61_range_check___00.smt2 |   20.008s | 29.524MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_78_10_dead_code___00.smt2 |   20.008s | 22.796MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_55_54_unreachable_branch___00.smt2 |   20.008s | 22.864MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_24_18_unreachable_branch___00.smt2 |   20.008s | 29.572MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_38_22_assert___00.smt2 |   20.008s | 22.852MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__test_failsafe.adb_11_19_precondition___00.smt2 |   20.008s | 23.752MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_12_27_range_check___00.smt2 |   20.008s | 29.676MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_45_85_range_check___00.smt2 |   20.008s | 29.076MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_52_25_assert___00.smt2 |   20.008s | 22.928MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/MA16-036__flow_missing_globals__logger.adb_42_23_length_check___00.smt2 |   20.008s | 23.692MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/MA16-036__flow_missing_globals__logger.ads_50_9_postcondition___00.smt2 |   20.009s | 23.736MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_20_22_unreachable_branch___00.smt2 |   20.009s | 29.648MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__test_failsafe.adb_13_19_precondition___00.smt2 |   20.009s | 23.844MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_40_85_range_check___00.smt2 |   20.009s | 29.548MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/MA16-036__flow_missing_globals__logger.adb_45_27_range_check___00.smt2 |   20.009s | 23.724MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_39_22_assert___00.smt2 |   20.009s | 22.896MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_43_52_unreachable_branch___00.smt2 |   20.009s | 29.64MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/MC12-026__overlayed_objects__p2.adb_39_28_overflow_check___00.smt2 |   20.009s | 28.664MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__test_failsafe.adb_7_7_dead_code___00.smt2 |   20.009s | 25.912MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_54_25_assert___00.smt2 |   20.009s | 22.88MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_41_22_assert___00.smt2 |   20.009s | 22.864MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__test_failsafe.adb_9_19_assert___00.smt2 |   20.009s | 23.74MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_62_25_assert___00.smt2 |   20.009s | 22.936MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_46_21_unreachable_branch___00.smt2 |   20.009s | 29.72MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_37_14_unreachable_branch___00.smt2 |   20.009s | 29.068MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_49_31_range_check___00.smt2 |   20.010s | 22.884MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_29_39_unreachable_branch___00.smt2 |   20.010s | 29.476MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_18_16_loop_invariant_preserv___00.smt2 |   20.010s | 29.584MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__test_failsafe.adb_9_23_precondition___00.smt2 |   20.011s | 23.728MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_45_17_unreachable_branch___00.smt2 |   20.011s | 29.076MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_63_62_unreachable_branch___00.smt2 |   20.011s | 22.868MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_18_16_loop_invariant_init___00.smt2 |   20.011s | 28.92MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_25_22_unreachable_branch___00.smt2 |   20.012s | 29.048MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_12_16_dead_code___00.smt2 |   20.012s | 29.068MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/MC12-026__overlayed_objects__p.adb_31_28_overflow_check___00.smt2 |   20.013s | 28.604MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__test_failsafe.adb_11_19_assert___00.smt2 |   20.013s | 23.92MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/MC12-026__overlayed_objects__p2.adb_40_28_fp_overflow_check___00.smt2 |   20.014s | 28.76MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_37_76_range_check___00.smt2 |   20.014s | 28.916MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__test_failsafe.adb_9_23_dead_code___00.smt2 |   20.015s | 23.732MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_25_64_contract_case___00.smt2 |   20.015s | 29.088MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_23_9_disjoint_contract_cases___00.smt2 |   20.015s | 29.024MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_51_30_unreachable_branch___00.smt2 |   20.015s | 22.928MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__test_failsafe.adb_7_7_precondition___00.smt2 |   20.015s | 23.432MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_18_50_range_check___00.smt2 |   20.016s | 29.076MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/MC12-026__overlayed_objects__p2.ads_27_22_postcondition___00.smt2 |   20.016s | 27.504MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_43_17_unreachable_branch___00.smt2 |   20.016s | 29.076MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__test_failsafe.adb_13_19_assert___00.smt2 |   20.016s | 23.684MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_26_36_loop_invariant_preserv___00.smt2 |   20.016s | 29.036MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_55_13_inconsistent_pre___00.smt2 |   20.017s | 22.9MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_49_10_dead_code___00.smt2 |   20.017s | 22.888MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_61_28_unreachable_branch___00.smt2 |   20.017s | 22.932MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__test_failsafe.adb_10_4_precondition___00.smt2 |   20.017s | 23.732MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_22_18_unreachable_branch___00.smt2 |   20.017s | 28.916MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_19_18_unreachable_branch___00.smt2 |   20.017s | 29.02MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_68_30_unreachable_branch___00.smt2 |   20.018s | 22.856MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_22_53_unreachable_branch___00.smt2 |   20.018s | 29.068MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_30_14_unreachable_branch___00.smt2 |   20.018s | 29.08MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_29_80_contract_case___00.smt2 |   20.019s | 29.084MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_63_17_unreachable_branch___00.smt2 |   20.021s | 24.34MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_28_17_dead_code___00.smt2 |   20.021s | 29.076MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_35_14_unreachable_branch___00.smt2 |   20.022s | 29.02MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/MA16-036__flow_missing_globals__logger.adb_42_35_range_check___00.smt2 |   20.023s | 23.692MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_57_28_unreachable_branch___00.smt2 |   20.023s | 22.996MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_73_78_range_check___00.smt2 |   20.024s | 22.94MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/MA16-036__flow_missing_globals__logger.adb_38_61_range_check___00.smt2 |   20.025s | 23.776MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_68_78_range_check___00.smt2 |   20.026s | 22.924MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_71_65_unreachable_branch___00.smt2 |   20.027s | 22.876MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_57_17_unreachable_branch___00.smt2 |   20.027s | 22.864MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_65_69_range_check___00.smt2 |   20.027s | 22.912MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__test_failsafe.adb_15_23_precondition___00.smt2 |   20.028s | 23.724MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_26_36_loop_invariant_init___00.smt2 |   20.028s | 28.96MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_39_14_unreachable_branch___00.smt2 |   20.028s | 29.08MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_61_14_inconsistent_pre___00.smt2 |   20.033s | 24.1MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_76_25_assert___00.smt2 |   20.038s | 22.876MiB| timeout | 0 |  |  |
