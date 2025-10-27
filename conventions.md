# Stack
- Stack pointer (`RSP`) is 16 bytes aligned just before `call` instruction

# Parameters
- Function parameters are passed in via registers: `RAX`, `RCX`, `RDX`, `RBX`, `RSI`, `RDI`, `R8`, `R9`, `R10`
- More function parameters are allocated on stack in reverse order and space is reserved by callee

# Registers
- Free registers: `RAX`, `RCX`, `RDX`, `RBX`, `RSI`, `RDI`, `R8`, `R9`, `R10`
- Reserved registers: `RSP`, `RBX`, `R11`, `R12`, `R13`, `R14`, `R15`

# Memory
- 8, 16, 32 and 64-bit values are mostly saved in registers
- Only 64-bit registers are shown, but if smaller value is used, it's equivalent size register should be used
- 128-bit value is saved in 2 64-bit registers
- structures are saved on stack
