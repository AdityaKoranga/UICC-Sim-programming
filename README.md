# UICC-Sim-programming

## Firstly clone this repository, then change the directory
```bash
cd UICC-Sim-programming/
```
Then run the following commands
```bash
make
```
> should compile with no warnings
* Insert the card in the reader and the reader in a USB socket
```bash
sudo ./program_uicc
```
* perform the same, with trace: all data exchange with the UICC are printed
```bash
sudo ./program_uicc --help
```
* now enter all the identifiers.
```bash
sudo ./program_uicc --adm 12345678 --imsi 208920100001101 --isdn 00000001 --acc 0001 --key 6874736969202073796d4b2079650a73 --opc 504f20634f6320504f50206363500a4f -spn "OpenCells01" --authenticate --noreadafter
```

