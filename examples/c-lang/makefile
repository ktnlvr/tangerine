make:
	cargo build --manifest-path ../../Cargo.toml
	cp ../../target/debug/libtangerine.a libtangerine.a
	$(CC) ./main.c libtangerine.a -L. -ldl -lpthread -lm -o main.out
