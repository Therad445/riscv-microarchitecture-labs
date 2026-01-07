# RISC-V Microarchitecture Labs

Designing a microprocessor based on the **RISC-V** architecture — a collection of lab works implemented in **SystemVerilog** and **RISC-V Assembly**, simulated in **Vivado (2019.2)**.

> RU section below ↓

## Contents
- [Labs](#labs)
- [Repository structure](#repository-structure)
- [Tooling](#tooling)
- [How to run](#how-to-run)
- [License](#license)
- [Credits](#credits)

## Labs
1. **Lab 1 — Adder**
2. **Lab 2 — ALU (Arithmetic-Logic Unit)**
3. **Lab 3 — Register file & memory**
4. **Lab 4 — Primitive programmable device**

## Repository structure
- `Lab1/`, `Lab2/`, `Lab3/`, `Lab4/` — lab sources and project files
- `IndividualWork1/` — individual assignment (if applicable)
- `all_files/` — shared/combined materials (legacy)
- `assets/` — exported lab archives (`Lab*.zip`) for convenience

## Tooling
- Xilinx **Vivado 2019.2**
- A RISC-V assembler/simulator (optional, if you run `.asm` separately)

## How to run
Typical flow (Vivado):
1. Open the corresponding lab folder as a project (or create a new Vivado project and add sources).
2. Run simulation (behavioral) to validate the design.
3. (Optional) Synthesize / implement if the lab requires FPGA flow.

> Notes: exact steps may differ per lab depending on the provided project files.

## License
MIT — see [LICENSE](LICENSE).

## Credits
This repository contains educational lab works.  
Reference materials / base course repo (if used): https://github.com/MPSU/APS/tree/master


---

# Лабы по микроархитектуре RISC-V (RU)

Проект-подборка лабораторных работ по проектированию процессора на базе **RISC-V**: модули на **SystemVerilog**, фрагменты **ASM**, симуляция в **Vivado 2019.2**.

## Содержание
- [Лабораторные](#лабораторные)
- [Структура репозитория](#структура-репозитория)
- [Инструменты](#инструменты)
- [Как запустить](#как-запустить)
- [Лицензия](#лицензия)
- [Благодарности](#благодарности)

## Лабораторные
1. **Лаба 1 — Сумматор (Adder)**
2. **Лаба 2 — АЛУ (ALU)**
3. **Лаба 3 — Регистровый файл и память**
4. **Лаба 4 — Примитивное программируемое устройство**

## Структура репозитория
- `Lab1/..Lab4/` — исходники и файлы проектов по лабам
- `IndividualWork1/` — индивидуальная работа (если относится к курсу)
- `all_files/` — общие/сводные материалы (legacy)
- `assets/` — архивы `Lab*.zip` для удобной раздачи/проверки

## Инструменты
- **Vivado 2019.2**
- (Опционально) ассемблер/симулятор RISC-V для `.asm`

## Как запустить
Обычно (Vivado):
1. Открыть папку лабы как проект (или создать проект и добавить исходники).
2. Запустить behavioral simulation и проверить корректность.
3. (Опционально) синтез/implementation, если требуется по методичке.

## Лицензия
MIT — см. [LICENSE](LICENSE).

## Благодарности
Учебный проект; возможная база/материалы курса: https://github.com/MPSU/APS/tree/master
