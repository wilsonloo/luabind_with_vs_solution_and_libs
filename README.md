# luabind_with_vs_solution_and_libs

notice: luabind-0.9.1 should use lua5.1 and boost_1_54

1.open the solution my_luabind_solution.sln<br/>
2.open [directions.props] in [Property Manager] tag

3.in the [Common Properies], select [User Macros]
4.set macro [LUA_INCLUDE_DIR] value to your lua5.1 include direction in the install root path
5.set macro [BOOST_HOME_DIR] value to your boost_1_54 install root path
6.build the solution, and you will 
  get luabind_static-rtl_vc110_debug.lib/.pdb
  and luabind_static-rtl_vc110_release.lib
  in the output_libs direction.
