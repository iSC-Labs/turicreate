project(unity_test)


make_boost_test(unity_sarray.cxx REQUIRES unity_core pylambda)
make_boost_test(unity_sarray_lazy_eval.cxx REQUIRES unity_core pylambda)
make_boost_test(unity_sframe.cxx REQUIRES unity_core pylambda)
make_boost_test(unity_sframe_lazy_eval.cxx REQUIRES unity_core pylambda)
make_boost_test(unity_sgraph.cxx REQUIRES unity_core)
make_boost_test(flex_dict_view.cxx REQUIRES unity_core )
make_boost_test(unity_sketch.cxx REQUIRES unity_core pylambda)
make_boost_test(unity_toolkit.cxx REQUIRES unity_core)
make_boost_test(gl_sarray.cxx REQUIRES unity_core)
make_boost_test(gl_sframe.cxx REQUIRES unity_core)
make_boost_test(gl_sgraph.cxx REQUIRES unity_core)
make_boost_test(gl_gframe.cxx REQUIRES unity_core)
make_boost_test(image_util.cxx REQUIRES unity_core)
subdirs(
  toolkits
  )
