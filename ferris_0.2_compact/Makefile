
compile: clean
	mkdir -p ../../../home/vscode/qmk_firmware/keyboards/ferris/keymaps/matburt
	cp -R * ../../../home/vscode/qmk_firmware/keyboards/ferris/keymaps/matburt/
	qmk clean
	qmk compile -kb ferris/0_2/compact -km matburt
	cp ../../../home/vscode/qmk_firmware/ferris_0_2_compact_matburt.bin ..

clean:
	qmk clean

.PHONY: compile