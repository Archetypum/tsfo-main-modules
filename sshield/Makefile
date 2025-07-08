BIN := $HOME/.replica
SRC := example.py

.PHONY: all install uninstall

all: install

install: $(TUM_SRC)
	@echo "[<==] Installing example to $(BIN)..."
	@install -m 0755 $(SRC) $(BIN)
	@echo "[*] Installed."

uninstall:
	@echo "[<==] Removing $(BIN)..."
	@rm -f $(BIN)
	@echo "[*] Uninstalled."
