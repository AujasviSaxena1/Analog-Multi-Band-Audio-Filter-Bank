# Active Multi-Band Audio Filter Bank

This is a project which is an LTspice simulation of an active multi-band audio filter bank using op-amp based filters.

# Filters Used
- Single-supply, 2nd-order, Sallen-Key low-pass filter (Bass)
- Single-supply, 2nd-order, Sallen-Key low-pass filter (High Frequency)
- Single-Supply, 2nd-Order, Sallen-Key Band-Pass Filter (Midrange)
- Twin-T Notch Filter (Hum Rejection)

# Software
- LTspice

# Files
- "filter_bank.asc" - LTspice schematic
- "circuit_schematic.png" - circuit screenshot
- "audio_final.log"

# Description
The input audio signal is applied to multiple active filter branches in parallel. Each branch isolates a different frequency range, while the notch filter removes a narrow unwanted band.
