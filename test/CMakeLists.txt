add_executable( test_feature_extraction test_feature_extraction.cpp )
target_link_libraries( test_feature_extraction 
    ygz-core ygz-algorithm
    ${THIRD_PARTY_LIBS}
)

add_executable( test_feature_alignment test_feature_alignment.cpp )
target_link_libraries( test_feature_alignment 
    ygz-core ygz-algorithm
    ${THIRD_PARTY_LIBS}
)

add_executable( test_LK_tracking test_LK_tracking.cpp )
target_link_libraries( test_LK_tracking 
    ygz-core ygz-algorithm
    ${THIRD_PARTY_LIBS}
)

add_executable( test_initializer test_initializer.cpp )
target_link_libraries( test_initializer 
    ygz-core ygz-algorithm
    ${THIRD_PARTY_LIBS}
)

add_executable( test_orb_match test_orb_match.cpp )
target_link_libraries( test_orb_match 
    ygz-core ygz-algorithm ${THIRD_PARTY_LIBS}
)

add_executable( test_feature_projection test_feature_projection.cpp ) 
target_link_libraries( test_feature_projection 
    ygz-core ygz-algorithm ${THIRD_PARTY_LIBS}
)