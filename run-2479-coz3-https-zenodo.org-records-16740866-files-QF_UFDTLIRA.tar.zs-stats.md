# .

* SAT 80
* UNSAT 66
* TIMEOUT 0
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_UFDTLIRA.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_UFDTLIRA.tar.zs
Runner: rise-runner-1
Z3 repo: Z3Prover/z3
Z3 commit: 9091df56cbb91c668c6ef3e26899d2839d38e8a5
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_UFDTLIRA.tar.zst?download=1
Z3 commit message: Fix instance of "flexible array member". (#9883)

This is another PR towards the goal of getting a clean build with clang,
using the compiler options used in building clang-tidy.

In https://github.com/Z3Prover/z3/pull/9800, we changed the build flags
to eliminate a warning for zero-length arrays. In that PR, I missed this
one: there was one instance of m_arr[] instead of m_arr[0]. In the
clang-tidy build, that gives warnings like:
```
/Users/daviddetlefs/llvm-project/build_dbg/_deps/z3-src/src/model/func_interp.h:43:12: warning: flexible array members are a C99 feature [-Wc99-extensions]
```

The PR fixes this, making it a zero-length array, the idiom used in all
the other similar cases. I also added the compiler flag that produced
this warning, so we can notice such changes in the future.

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/Q130-019__missing_discr_check__p_init.ads_14_24_range_check___00.smt2 |    0.013s | 19.28MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/stopwatch__user.ads_19_17_ceiling__priority_protocol___00.smt2 |    0.013s | 19.052MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/stopwatch__timer.adb_16_17_ceiling__priority_protocol___00.smt2 |    0.013s | 19.064MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/riposte__logic__logic.adb_20_33_unreachable_branch___00.smt2 |    0.013s | 19.032MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/K512-016__task__t.ads_3_9_task_termination___00.smt2 |    0.013s | 19.068MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/P511-009__test_attributes__storage_place_attributes.adb_95_22_assert___00.smt2 |    0.013s | 19.108MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/L531-021__discr__subty.ads_5_20_range_check___00.smt2 |    0.013s | 18.94MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/P715-019__flow_subprogram_termination__nested_packages.adb_56_13_dead_code___00.smt2 |    0.014s | 19.028MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/riposte__logic__logic.adb_51_22_assert___00.smt2 |    0.014s | 18.82MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/P725-016__recursive_spec__main.adb_5_19_precondition___00.smt2 |    0.014s | 18.98MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/KC20-032__succ_pred__p.adb_32_18_range_check___00.smt2 |    0.014s | 18.968MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/P715-019__flow_subprogram_termination__functions.adb_22_10_precondition___00.smt2 |    0.014s | 19.04MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/P715-019__flow_subprogram_termination__nest_in_proc.adb_21_13_dead_code___00.smt2 |    0.014s | 19.064MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/P712-004__prot_discr__p.ads_6_13_range_check___00.smt2 |    0.014s | 18.992MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/L316-015__all__a1.adb_4_5_precondition___00.smt2 |    0.014s | 19.04MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/riposte__logic__logic.adb_66_22_assert___00.smt2 |    0.014s | 19.16MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/Q130-019__missing_discr_check__p_init.ads_15_24_range_check___00.smt2 |    0.014s | 18.848MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/riposte__logic__logic.adb_33_37_unreachable_branch___00.smt2 |    0.014s | 19.248MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/P715-019__flow_subprogram_termination__p.adb_22_10_dead_code___00.smt2 |    0.014s | 18.928MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/S920-003__flow_noret__noret.adb_6_7_raise___00.smt2 |    0.014s | 18.916MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/P715-019__flow_subprogram_termination__functions.adb_16_7_functions.adb_29_4_precondition___00.smt2 |    0.014s | 19.032MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/riposte__logic__logic.adb_87_22_assert___00.smt2 |    0.014s | 19.056MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/KC22-015__succ_overflow__p.adb_21_31_range_check___00.smt2 |    0.014s | 19.052MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/riposte__logic__logic.adb_80_22_assert___00.smt2 |    0.014s | 19.004MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/NC11-033__variant__variants.ads_13_20_range_check___00.smt2 |    0.015s | 19.032MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/Q512-018__null_task_id__main.adb_7_41_precondition___00.smt2 |    0.015s | 19.296MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/KC22-015__succ_overflow__p.adb_21_38_range_check___00.smt2 |    0.015s | 19.544MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/R123-023__flow_unused_variable__q.adb_2_21_range_check___00.smt2 |    0.015s | 18.888MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/P715-019__flow_subprogram_termination__r.adb_53_7_precondition___00.smt2 |    0.015s | 18.848MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/P511-009__test_attributes__storage_place_attributes.adb_73_22_assert___00.smt2 |    0.015s | 18.884MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/O521-002__no_return__p.adb_23_6_precondition___00.smt2 |    0.015s | 18.872MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/P929-043__flow_pkg_elaboration_in_direct_calls__nest_in_proc.adb_9_7_precondition___00.smt2 |    0.015s | 19.024MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/S920-003__flow_implicit_noret__p.adb_5_10_raise___00.smt2 |    0.015s | 19.536MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/S702-024__record_attributes_in_allocators__test_constr.adb_24_22_assert___00.smt2 |    0.015s | 19.46MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/riposte__logic__logic.adb_77_22_assert___00.smt2 |    0.015s | 19.068MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/M809-022__scenario__q.adb_6_7_assert___00.smt2 |    0.015s | 19.028MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/S711-051__constrained_attr__test_constrained.adb_34_28_null_pointer_dereference___00.smt2 |    0.015s | 18.944MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/S702-024__record_attributes_in_allocators__test_constr.adb_39_22_assert___00.smt2 |    0.015s | 19.352MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/P602-007__protected_no_return__p.adb_23_6_precondition___00.smt2 |    0.015s | 19.036MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/M604-044__overflow__misovattr.adb_6_35_range_check___00.smt2 |    0.015s | 19.708MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/OC09-042__po_in_spec_only_pkg__main.adb_3_11_ceiling__priority_protocol___00.smt2 |    0.015s | 18.98MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/M524-002__demorgan__test.adb_6_22_assert___00.smt2 |    0.015s | 19.068MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/riposte__logic__logic.adb_54_22_assert___00.smt2 |    0.015s | 19.024MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/riposte__logic__logic.adb_138_22_assert___00.smt2 |    0.015s | 19.16MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/KC22-015__succ_overflow__p.adb_29_29_overflow_check___00.smt2 |    0.015s | 19.552MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/P715-019__flow_subprogram_termination__r.adb_46_10_dead_code___00.smt2 |    0.015s | 19.024MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/NC11-033__variant__variants.ads_14_20_range_check___00.smt2 |    0.015s | 18.884MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/Q512-013__flow_type_aspects__a.adb_7_10_dead_code___00.smt2 |    0.015s | 19.036MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/PA11-007__depchain__a-reatim.ads_6_4_assert___00.smt2 |    0.015s | 18.936MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/Q412-006__assert_true__p.ads_17_4_assert___00.smt2 |    0.015s | 19.036MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/riposte__logic__logic.adb_24_37_unreachable_branch___00.smt2 |    0.015s | 19.048MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/P712-004__prot_discr__p.ads_7_13_range_check___00.smt2 |    0.015s | 19.112MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/P511-009__test_attributes__component_size_attribute.adb_55_7_assert___00.smt2 |    0.015s | 19.028MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/riposte__logic__logic.adb_112_22_assert___00.smt2 |    0.015s | 19.076MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/riposte__logic__logic.adb_74_22_assert___00.smt2 |    0.015s | 19.024MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/M524-002__demorgan__test.adb_12_22_assert___00.smt2 |    0.015s | 19.072MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/P511-009__test_attributes__component_size_attribute.adb_37_7_assert___00.smt2 |    0.015s | 18.904MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/P715-019__flow_subprogram_termination__imported.ads_14_13_inconsistent_pre___00.smt2 |    0.015s | 19.356MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/riposte__logic__logic.adb_33_22_assert___00.smt2 |    0.015s | 19.032MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/L531-021__discr__special.ads_6_32_range_check___00.smt2 |    0.016s | 19.032MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/PA27-015__nested_no_return__nest_in_proc.adb_14_4_precondition___00.smt2 |    0.016s | 18.896MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/S818-002__might_not_return__pack.adb_5_7_raise___00.smt2 |    0.016s | 19.056MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/P715-019__flow_subprogram_termination__imported.adb_10_7_precondition___00.smt2 |    0.016s | 19.3MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/stopwatch__user.ads_12_17_ceiling__priority_protocol___00.smt2 |    0.016s | 19.008MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/P715-019__flow_subprogram_termination__nested_packages.adb_27_16_dead_code___00.smt2 |    0.016s | 19.052MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/S702-024__record_attributes_in_allocators__test_constr.adb_24_30_null_pointer_dereference___00.smt2 |    0.016s | 19.216MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/riposte__logic__logic.adb_139_44_unreachable_branch___00.smt2 |    0.016s | 19.12MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/P715-019__flow_subprogram_termination__call_proc_no_body.adb_4_7_precondition___00.smt2 |    0.016s | 19.284MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/M524-002__demorgan__test.adb_8_22_assert___00.smt2 |    0.016s | 19.28MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/P511-009__test_attributes__component_size_attribute.adb_43_7_assert___00.smt2 |    0.016s | 19.072MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/P602-007__protected_no_return__p.adb_28_8_precondition___00.smt2 |    0.016s | 19.584MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/riposte__logic__logic.adb_18_22_assert___00.smt2 |    0.016s | 19.004MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/P715-019__flow_subprogram_termination__nested_blocks.adb_11_29_dead_code___00.smt2 |    0.016s | 19.028MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/riposte__logic__logic.adb_45_22_assert___00.smt2 |    0.016s | 19.176MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/P712-004__prot_discr__main.adb_7_19_assert___00.smt2 |    0.016s | 19.064MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/R123-023__flow_unused_variable__q.adb_7_17_discriminant_check___00.smt2 |    0.016s | 19.284MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/stopwatch__user.ads_26_17_ceiling__priority_protocol___00.smt2 |    0.016s | 19.08MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/L323-005__recursive__p.adb_6_23_assert___00.smt2 |    0.016s | 19.532MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/L316-015__all__a2.adb_4_5_precondition___00.smt2 |    0.016s | 18.828MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/P511-009__test_attributes__component_size_attribute.adb_49_7_assert___00.smt2 |    0.016s | 18.904MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/O429-052__flow_tasking_review__unsync_access__bar.adb_16_17_range_check___00.smt2 |    0.016s | 18.956MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/P725-016__recursive_spec__main.adb_5_19_assert___00.smt2 |    0.016s | 19.252MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/O429-052__flow_tasking_exclusivity_checks__two_tasks_single_so.ads_9_9_task_termination___00.smt2 |    0.016s | 19.7MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/riposte__logic__logic.adb_139_33_unreachable_branch___00.smt2 |    0.016s | 19.064MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/M604-044__overflow__misovattr.adb_8_22_assert___00.smt2 |    0.016s | 18.948MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/O402-017__tagged__no_primitive_use.adb_7_4_precondition___00.smt2 |    0.016s | 19.7MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/S702-024__record_attributes_in_allocators__test_constr.adb_39_37_null_pointer_dereference___00.smt2 |    0.016s | 19.216MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/riposte__logic__logic.adb_24_22_assert___00.smt2 |    0.016s | 19.02MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/P715-019__flow_subprogram_termination__nonreturning_spec.ads_2_14_inconsistent_post___00.smt2 |    0.016s | 19.028MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/OB17-029__ceiling_elaboration_task__t.ads_2_9_task_termination___00.smt2 |    0.017s | 18.892MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/KC22-015__succ_overflow__p.adb_37_31_overflow_check___00.smt2 |    0.017s | 19.636MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/KC20-032__succ_pred__p.adb_41_31_overflow_check___00.smt2 |    0.017s | 19.7MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/O429-052__flow_tasking_exclusivity_checks__two_tasks_single_so.ads_7_9_task_termination___00.smt2 |    0.017s | 19.656MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/M604-044__overflow__misovattr.adb_9_35_range_check___00.smt2 |    0.017s | 19.628MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/riposte__logic__logic.adb_40_18_inconsistent_pre___00.smt2 |    0.017s | 19.132MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/riposte__real_world__real_world.adb_44_22_assert___00.smt2 |    0.017s | 19.668MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/KC20-032__succ_pred__p.adb_32_29_overflow_check___00.smt2 |    0.017s | 19.568MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/KB04-032__lib_level__p.adb_6_19_assert___00.smt2 |    0.017s | 19.584MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/P511-009__test_attributes__storage_place_attributes.adb_51_22_assert___00.smt2 |    0.017s | 18.896MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/KC22-015__succ_overflow__p.adb_29_18_range_check___00.smt2 |    0.017s | 19.004MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/riposte__logic__logic.adb_19_22_assert___00.smt2 |    0.017s | 19.188MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/OB16-016__system_default_priority__main.adb_3_11_ceiling__priority_protocol___00.smt2 |    0.017s | 18.932MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/riposte__logic__logic.adb_115_22_assert___00.smt2 |    0.017s | 19.024MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/KC22-015__succ_overflow__p.adb_37_38_overflow_check___00.smt2 |    0.017s | 19.712MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/riposte__logic__logic.adb_30_22_assert___00.smt2 |    0.017s | 19.256MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/N609-025__private_type_discr__record_discr.adb_24_28_discriminant_check___00.smt2 |    0.017s | 19.504MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/S729-004__inline_dispatching__p.adb_6_22_assert___00.smt2 |    0.017s | 19.58MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/KC20-032__succ_pred__p.adb_23_31_range_check___00.smt2 |    0.017s | 19.672MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/P715-019__flow_subprogram_termination__decl_only.ads_8_18_inconsistent_pre___00.smt2 |    0.017s | 19.268MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/N915-008__flow_acats_oo__cc1311a.adb_279_17_cc1311a.adb_441_6_range_check___00.smt2 |    0.017s | 18.98MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/KB10-018__cursor_location__cursor_location.ads_10_23_unreachable_branch___00.smt2 |    0.017s | 19.492MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/Q508-012__flow_null_proc__nullproc.ads_7_9_task_termination___00.smt2 |    0.017s | 18.984MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/riposte__logic__logic.adb_87_40_unreachable_branch___00.smt2 |    0.017s | 19.216MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/riposte__logic__logic.adb_14_18_inconsistent_pre___00.smt2 |    0.017s | 19.136MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/KC20-032__succ_pred__p.adb_41_19_range_check___00.smt2 |    0.018s | 18.916MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/L323-005__recursive__p.ads_7_36_postcondition___00.smt2 |    0.018s | 19.552MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/riposte__logic__logic.adb_27_22_assert___00.smt2 |    0.018s | 19.144MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/KC20-032__succ_pred__p.adb_41_38_overflow_check___00.smt2 |    0.018s | 19.596MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/KC22-015__succ_overflow__p.adb_29_36_overflow_check___00.smt2 |    0.018s | 19.624MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/M524-002__demorgan__test.adb_10_22_assert___00.smt2 |    0.018s | 19.304MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/S920-003__flow_implicit_noret__p.adb_10_10_precondition___00.smt2 |    0.018s | 19.592MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/KC20-032__succ_pred__p.adb_32_36_overflow_check___00.smt2 |    0.018s | 19.712MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/M604-044__overflow__misovattr.adb_6_22_assert___00.smt2 |    0.018s | 19.028MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/P715-019__flow_subprogram_termination__functions.adb_9_10_dead_code___00.smt2 |    0.018s | 19.044MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/KB28-003__succ__p.adb_6_23_range_check___00.smt2 |    0.018s | 19.476MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/Q508-012__flow_null_proc__expanded.ads_7_9_task_termination___00.smt2 |    0.018s | 19.076MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/O429-052__flow_tasking_exclusivity_checks__two_task_type_objects_single_so.ads_7_14_task_termination___00.smt2 |    0.018s | 19.588MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/S325-002__rec_pointers_bad__use_incomplete_type_auto.ads_4_19_assert___00.smt2 |    0.018s | 19.476MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/O429-052__flow_tasking_exclusivity_checks__task_type_array_single_so.ads_7_14_task_termination___00.smt2 |    0.019s | 19.536MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/KB28-003__succ__p.adb_12_23_range_check___00.smt2 |    0.019s | 19.592MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/P715-019__flow_subprogram_termination__nested_packages.adb_62_10_dead_code___00.smt2 |    0.019s | 19.064MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/Q818-007__projection__sc_status_type.adb_5_22_assert___00.smt2 |    0.019s | 19.62MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/riposte__logic__logic.adb_44_22_assert___00.smt2 |    0.019s | 19.068MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/R220-054__fixed_point_small__fp_test.ads_13_23_overflow_check___00.smt2 |    0.019s | 20.284MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/Q512-013__flow_type_aspects__a.adb_9_7_dead_code___00.smt2 |    0.019s | 19.068MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/M604-044__overflow__misovattr.adb_7_35_range_check___00.smt2 |    0.019s | 19.712MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/riposte__logic__logic.adb_71_22_assert___00.smt2 |    0.019s | 19.252MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/riposte__enums__enums.adb_194_29_range_check___00.smt2 |    0.019s | 19.716MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/riposte__logic__logic.adb_19_37_unreachable_branch___00.smt2 |    0.019s | 19.2MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/riposte__real_world__real_world.adb_45_21_range_check___00.smt2 |    0.020s | 19.508MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/P126-025__generic_procedure_renaming__c.adb_8_4_precondition___00.smt2 |    0.020s | 19.008MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/KC22-015__succ_overflow__p.adb_37_19_range_check___00.smt2 |    0.021s | 19.016MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/KB10-018__cursor_location__cursor_location.ads_11_24_unreachable_branch___00.smt2 |    0.021s | 19.548MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/R220-054__fixed_point_small__fp_test.adb_6_17_overflow_check___00.smt2 |    0.022s | 20.04MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/M604-044__overflow__misovattr.adb_8_35_range_check___00.smt2 |    0.022s | 19.588MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIRA/20200306-Kanig/spark2014bench/Q906-011__counterexample__copy_values.adb_6_22_assert___00.smt2 |    0.023s | 28.14MiB| sat | 0 |  |  |
