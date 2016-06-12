INCLUDE_DIRECTORIES(${CMAKE_CURRENT_SOURCE_DIR})

create_test_suite(CPTManagerTest CPTManagerTest.cpp BayesNetworkTypes)

create_test_suite(BayesNetworkTest BayesNetworkTest.cpp BayesNetworkTypes)

create_test_suite(BayesNetworkNodeTest BayesNetworkNodeTest.cpp BayesNetworkTypes)

create_test_suite(OctreeNodeTest OctreeNodeTest.cpp OctreeTypes)

create_test_suite(OctreeTest OctreeTest.cpp OctreeTypes)
file(COPY test_cloud.pcd DESTINATION ${CMAKE_CURRENT_BINARY_DIR})
