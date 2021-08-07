x86_64_asm_source_files :=$(shell find src/impl/x86_64 0name *.asm)
x86_64_asm_object_files :- $(patsubst src/impl/x86_64/%.asm, build/x86_64/%.o,) $(x86_64_asm_source_files)