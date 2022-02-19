.PHONY: run build clean doc prettier

run:
	cargo run

debug:
	cargo build

release:
	cargo build --release

# Quickly checks your code to make sure it compiles but doesn’t produce an executable
check:
	cargo check

clean:
	rm -rf target

doc:
	cargo doc --open

prettier:
	rustfmt src/*.rs

%:
	@:
