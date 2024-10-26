# messagebox-dll

A simple DLL file that prints a Windows message box and exits.

# Usage

1. Compile the Crate using the following command:

```
cargo build --release
```

2. Run the compiled DLL via command:

```
rundll32.exe .\target\release\messagebox_dll.dll,DllMain
```
