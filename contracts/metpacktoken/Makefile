# Makefile for an eosio smart contact

CC=eosio-cpp
Contract=metpacktoken

all:
	@echo "Building"
	$(CC) $(Contract).cpp -o $(Contract).wasm --abigen
	# $(CC) $(Contract).cpp -o $(Contract).wasm

clean:
	rm -f $(Contract).wast
	rm -f *.abi
	rm -f $(Contract).wasm