

# Power Analysis of RRAM Crossbar With and Without Selector

## Project Overview

- Studied a **1S1M RRAM architecture** using an NPN selector.
- Analyzed **LRS and HRS** operation.
- Compared power consumption of RRAM arrays **with and without a selector**.
- Evaluated both **single-cell and 3×3 crossbar arrays**.

## Motivation

The project investigates **sneak-path leakage** in RRAM crossbar arrays and its impact on power consumption and array scalability.

## Device Architecture

### 1S1M Cell

- The selector acts as a **non-linear switch**.
- Below the threshold voltage, the selector remains highly resistive.
- Under full bias, the selector enables conduction through the selected cell.
- Half-selected cells remain largely isolated.

## Results

| Configuration | State | Total Power |
|---|---|---:|
| Without Selector | LRS | 8 µW |
| With Selector | LRS | 1.174 µW |
| Without Selector | HRS | 8 nW |
| With Selector | HRS | 2.721 nW |

### Key Results

- **LRS power reduction:** ~6.8×
- **HRS power reduction:** ~3×
- Performed **single-cell and 3×3 array analysis**.
- Performed **transient analysis** with and without the selector.

## Conclusion

The 1S1M architecture reduces unwanted current paths and significantly lowers the power consumption of the RRAM crossbar array.
