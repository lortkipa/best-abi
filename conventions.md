# Stack
- Stack pointer (`RSP`) is 16 bytes aligned just before `call` instruction

# Parameters
- Function parameters are passed in via registers: `RAX`, `RCX`, `RDX`, `RBX`, `RSI`, `RDI`, `R8`, `R9`, `R10`
- More function parameters are allocated on stack in reverse order and space is reserved by callee

# Registers
- Volatile registers: `RAX`, `RCX`, `RDX`, `RBX`, `RSI`, `RDI`, `R8`, `R9`, `R10`
- Non-volatile registers: `RSP`, `RBX`, `R11`, `R12`, `R13`, `R14`, `R15`
