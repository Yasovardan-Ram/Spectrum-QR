# Spectrum-QR
An experimental color-based QR-like encoding system using multistate RGB modules for higher-density visual data storage.

## Preview

![example pic](Images/pic1.png)


![example pic](Images/pic2.png)

## How It Works

The encoder converts text into UTF-8 bytes, transforms the bytes into binary, splits the binary stream into 2-bit chunks, and maps each chunk to a unique RGB color state.

Pipeline:

Text
→ UTF-8
→ Binary
→ 2-bit chunks
→ Numerical states
→ RGB matrix
→ PNG image

## Color Mapping

| Bits | Value | Color |
|------|------|------|
| 00 | 0 | Black |
| 01 | 1 | Red |
| 10 | 2 | Green |
| 11 | 3 | Blue |

## Installation

```bash
pip install numpy pillow customtkinter
```

## 9. Add Usage Section

```markdown id="h8ncr7"
```

## Usage

```bash
run.py
```
