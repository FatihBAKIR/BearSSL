add_executable(testcrypto test_crypto.c)
target_link_libraries(testcrypto PRIVATE bearssl bearssl_private)

add_executable(testspeed test_speed.c)
target_link_libraries(testspeed PRIVATE bearssl bearssl_private)

add_executable(testx509 test_x509.c)
target_link_libraries(testx509 PRIVATE bearssl bearssl_private)
