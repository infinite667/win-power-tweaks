# Best Performance Power Plan

This repository contains a **Windows Power Plan** profile designed to help your system stay in **high-performance mode** more consistently.

The goal is simple:  
➡️ reduce system-level power saving and core parking so the CPU can reach and maintain **higher clocks and power usage** when under load.

**File included:**  
- `Best Power.pow`

---

## What this does

- Encourages **maximum performance behavior** from the Windows power manager
- Disables system-side **core parking and sleep states**
- Reduces unnecessary downclocking
- Helps the CPU sustain boost clocks longer (if thermals and power allow)

⚠️ This does **not** overclock your CPU. Hardware limits, cooling, and system power still apply.

---

## How to use

1. Download **Best Power.pow**
2. Open **Command Prompt** (Administrator recommended)
3. Type `powercfg -import "C:\path\to\Best Power.pow"`
4. Press **Enter**
5. Select the plan in **Power Options**

That’s it.

---

## Recommended

- Plug in AC power (especially on laptops)
- Use **Best performance** Windows power mode
- Ensure adequate cooling

---

Built for users who want **maximum performance with minimal hassle**.
