z3_add_component(lp
  SOURCES
    core_solver_pretty_printer.cpp
    dense_matrix.cpp
    dioph_eq.cpp
    emonics.cpp
    factorization.cpp
    factorization_factory_imp.cpp
    gomory.cpp
    hnf_cutter.cpp
    horner.cpp
    indexed_vector.cpp
    int_branch.cpp
    int_cube.cpp
    int_gcd_test.cpp
    int_solver.cpp
    lar_solver.cpp
    lar_core_solver.cpp
    lp_core_solver_base.cpp
    lp_primal_core_solver.cpp
    lp_settings.cpp
    matrix.cpp
    mon_eq.cpp
    monomial_bounds.cpp
    nex_creator.cpp
    nla_basics_lemmas.cpp
    nla_common.cpp
    nla_core.cpp
    nla_divisions.cpp
    nla_grobner.cpp
    nla_intervals.cpp
    nla_monotone_lemmas.cpp
    nla_order_lemmas.cpp
    nla_powers.cpp
    nla_solver.cpp
    nla_tangent_lemmas.cpp
    nra_solver.cpp    
    permutation_matrix.cpp
    random_updater.cpp      
    static_matrix.cpp
  COMPONENT_DEPENDENCIES
    util
    polynomial
    nlsat
    params
  PYG_FILES
    lp_params_helper.pyg
)

include_directories(${src_SOURCE_DIR})
