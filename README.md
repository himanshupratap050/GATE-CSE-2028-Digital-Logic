# GATE CSE 2028: Digital Logic

Exam-oriented notes, formula sheet, and PYQ solutions for the Digital Logic section of GATE CSE.

## About
- **Goal:** Full marks in Digital Logic
- **Language:** Simple English, standard technical terminology
- **Style:** Concise, structured, exam-oriented. No filler.
- **Reference books:** Mano (primary), Kohavi, Brown and Vranesic, Malvino and Leach

## Official GATE Syllabus
Boolean algebra and minimization (algebraic technique, Karnaugh map, tabular method). Design of combinational and sequential circuits. Number representation and arithmetic (fixed and floating point).

## Repository Structure

```
GATE-CSE-2028-Digital-Logic/
├── README.md
├── LICENSE
├── Resources/
│   ├── Book_References.md
│   ├── Course_Lecture_Map.md
│   ├── Formula_Sheet.md
│   ├── PYQ_Tracker.md
│   └── Error_Log.md
├── _assets/
│
├── 01_Number_Systems/                 (7 chapters)
│   ├── Ch01_Introduction_and_Base_Conversion
│   ├── Ch02_Arithmetic_Operations
│   ├── Ch03_Complements_and_Signed_Numbers
│   ├── Ch04_Overflow_Detection
│   ├── Ch05_Codes (BCD, Excess-3, Self-Complementing, Gray, Alphanumeric)
│   ├── Ch06_Integer_Representation
│   └── Ch07_Floating_Point_and_IEEE_754
│
├── 02_Boolean_Algebra/                (6 chapters)
│   ├── Ch01_Introduction_and_Boolean_Laws
│   ├── Ch02_Logic_Gates_and_Universal_Gates
│   ├── Ch03_Duality_De_Morgan_and_Consensus_Theorem
│   ├── Ch04_SOP_POS_and_Canonical_Forms
│   ├── Ch05_K_Map (up to 5 variables)
│   └── Ch06_Tabular_Method (Quine-McCluskey)
│
├── 03_Combinational_Circuits/         (11 chapters)
│   ├── Ch01_Introduction
│   ├── Ch02_Half_Adder_and_Full_Adder
│   ├── Ch03_Half_Subtractor_and_Full_Subtractor
│   ├── Ch04_BCD_Adder_and_BCD_to_Excess_3_Converter
│   ├── Ch05_Look_Ahead_Carry_Adder
│   ├── Ch06_Multiplexer
│   ├── Ch07_Demultiplexer_and_Decoder
│   ├── Ch08_Encoders_and_Priority_Encoder
│   ├── Ch09_Comparator_and_Parity
│   ├── Ch10_ROM_PLA_PAL_and_Function_Implementation
│   └── Ch11_Hazards
│
└── 04_Sequential_Circuits/            (11 chapters)
    ├── Ch01_Introduction
    ├── Ch02_Latches
    ├── Ch03_Flip_Flops_and_Excitation_Tables
    ├── Ch04_Master_Slave_and_Race_Around
    ├── Ch05_Flip_Flop_Conversions
    ├── Ch06_Registers_and_Shift_Registers
    ├── Ch07_Counters
    ├── Ch08_Finite_State_Machines (Mealy and Moore)
    ├── Ch09_State_Minimization_and_Sequence_Detectors
    ├── Ch10_Booths_Algorithm
    └── Ch11_Memory_Basics
```

Every chapter folder contains:
```
ChXX_Topic_Name/
├── Notes.md
└── PYQs.md
```

## Unit Status
| Unit | Chapters | Lecturer weightage (verify) | Status |
|---|---|---|---|
| 01 Number Systems | 7 | 1-2 marks | Pending |
| 02 Boolean Algebra and Minimization | 6 | 1-2 marks | Pending |
| 03 Combinational Circuits | 11 | 1 mark | Pending |
| 04 Sequential Circuits | 11 | 2 marks | Pending |

## What Each File Holds
| File | Purpose |
|---|---|
| `Notes.md` | Overview, definitions, formulas and tables, shortcuts, common mistakes, GATE question pattern, quick revision summary |
| `PYQs.md` | Question (year, set), concept, step-by-step solution, final answer, shortcut, note |
| `Resources/Book_References.md` | Books and topic-to-chapter map |
| `Resources/Course_Lecture_Map.md` | Lecture topic to repo chapter map |
| `Resources/Formula_Sheet.md` | One-line formulas, unit-wise |
| `Resources/PYQ_Tracker.md` | Year, set, marks, attempted, correct, revisit |
| `Resources/Error_Log.md` | Mistakes and the correct approach |

## Workflow
1. Watch the lecture and log it in `Resources/Course_Lecture_Map.md`
2. Study the chapter notes and add formulas to `Resources/Formula_Sheet.md`
3. Solve PYQs and record them in `Resources/PYQ_Tracker.md`
4. Log every mistake in `Resources/Error_Log.md`
5. Revise by priority: High, then Medium, then Low
