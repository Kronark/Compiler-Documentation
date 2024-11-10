♦ root
├── ◘ compiler
│   ├── ◘ custom
│   │   ├── • padding
│   │   ├── • number_to_hex
│   │   └── • bytes_size
│   ├── • settings
│   ├── • condition
│   ├── • port
│   ├── • option
│   ├── • path
│   ├── • bytes
│   ├── • join
│   ├── • format
│   ├── • type
│   ├── • apply
│   ├── • size
│   ├── • file
│   ├── • reverse
│   ├── • value
│   ├── • math
│   ├── • repeat
│   ├── • time
│   ├── • split
│   └── • collect
├── ◘ file_formats
│   ├── ◘ magic_numbers
│   │   ├── • disk_operating_system
│   │   └── • portable_executable
│   └── ◘ portable_executable
│       ├── • pe_file
│       ├── • pe_dos_header
│       ├── • pe_machine
│       ├── • pe_characteristics
│       ├── • pe_file_header
│       ├── • pe_dll_characteristics
│       ├── • pe_optional_header
│       ├── • pe_dos_stub
│       ├── • pe_section_characteristics
│       ├── • pe_section_header
│       ├── • pe_section_headers
│       ├── • pe_section
│       ├── • pe_sections
│       └── • pe_contents
├── ◘ instructions
│   └── ◘ x64
│       ├── ◘ encoding
│       │   ├── ◘ operands
│       │   │   ├── • x64_immediate
│       │   │   ├── • x64_memory_address
│       │   │   └── • x64_register
│       │   ├── • x64_legacy_prefixes
│       │   ├── • x64_sib
│       │   ├── • x64_modrm
│       │   ├── • x64_rex_prefix
│       │   └── • x64_legacy_opcode
│       ├── • mov
│       └── • syscall
└── ◘ types
    └── ◘ integers
        ├── ◘ binary
        │   ├── • signed_16_bit_integer
        │   ├── • unsigned_16_bit_integer
        │   ├── • signed_32_bit_integer
        │   ├── • unsigned_32_bit_integer
        │   ├── • signed_64_bit_integer
        │   ├── • unsigned_64_bit_integer
        │   ├── • signed_8_bit_integer
        │   └── • unsigned_8_bit_integer
        ├── ◘ limits
        │   ├── • signed_16_bit_integer_limits
        │   ├── • signed_32_bit_integer_limits
        │   ├── • signed_64_bit_integer_limits
        │   ├── • unsigned_64_bit_integer_limits
        │   ├── • signed_8_bit_integer_limits
        │   ├── • unsigned_8_bit_integer_limits
        │   ├── • unsigned_16_bit_integer_limits
        │   └── • unsigned_32_bit_integer_limits
        ├── • 16_bit_integer
        ├── • 32_bit_integer
        ├── • 64_bit_integer
        └── • 8_bit_integer
