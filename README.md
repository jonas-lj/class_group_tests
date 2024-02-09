# Class group alignment tests

This library contains a test which checks that the class groups implementations of the fastcrypto and class_group 
crates are aligned. Tests are performed over four different class groups with 1024, 2048, 2400 and 3072 bit discriminants.

To run the tests, run `cargo test` from the root of the repository. 

The class_group crate uses pari/gp for the underlying arithmetic, so the gmp library has to be installed.
