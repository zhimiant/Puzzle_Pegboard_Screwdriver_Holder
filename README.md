# Modular Puzzle Pegboard Screwdriver Holder

## 1. What is it?

This project is a modular, 3D-printed screwdriver holder designed for a laboratory pegboard. It consists of three puzzle-shaped pieces: a left module, a middle module, and a right module. The pieces fit together to form one holder, but they can also be printed separately in three different colors.

## 2. What does it do?

Each module holds one screwdriver through an approximately 15 mm circular opening. The three-piece design helps organize frequently used screwdrivers on the pegboard while allowing the modules to be combined or separated. The mounting interface is based on the pegboard hook supplied by the instructor.

## Pegboard Slot Dimensions

The holder was designed for the laboratory pegboard using the dimensions shown in the supplied reference diagram. Its mounting slots are **rounded vertical openings** arranged in staggered rows.

| Pegboard measurement | Reference dimension |
| --- | ---: |
| Slot width (short dimension) | **5 mm** |
| Slot length (long dimension) | **15 mm** |
| Horizontal center-to-center distance between slots in the same row | **40 mm** |
| Clear horizontal gap between adjacent slots in the same row | **35 mm** |
| Clear vertical gap between vertically aligned slots | **25 mm** |

The 40 mm horizontal pitch is especially important for positioning the three modules consistently on the pegboard. The design uses the **pegboard hook STL originally provided by the instructor** as its reference mounting interface, rather than creating an unrelated attachment shape. In this project, the approximately **15 mm circular screwdriver openings** are separate from the pegboard's **5 × 15 mm mounting slots**.

## 3. How was it made?

1. **Brainstorming:** I began by identifying a practical storage need in the laboratory and developed the idea of a modular, puzzle-shaped screwdriver holder.
2. **Importing the reference:** After brainstorming, I imported the pegboard hook from the **STL file provided by the instructor** into **Blender**. I used this hook as the mounting interface and developed the holder's geometry around it.
3. **3D modeling:** In Blender, I designed three interlocking modules—left, middle, and right—with a circular opening for a screwdriver in each piece. I refined the sloped upper and lower surfaces and the edges while retaining the pegboard mounting interface.
4. **Exporting the model:** After completing the Blender model, I exported the three parts from Blender as **STL files**.
5. **Slicing:** I imported the STL files into **Bambu Studio** and sliced them for 3D printing. The parts were prepared separately so that different colors could be assigned.
6. **Preparing to print:** I exported the sliced print job as a **G-code file** for the **Bambu Lab H2D** 3D printer, using a **0.4 mm nozzle**.

## Model Files

The `models/` folder contains four models—left, middle, right, and the three-piece assembly—each supplied in both STL and STEP formats:

- `puzzle_pegboard_left.stl` / `puzzle_pegboard_left.step`
- `puzzle_pegboard_middle.stl` / `puzzle_pegboard_middle.step`
- `puzzle_pegboard_right.stl` / `puzzle_pegboard_right.step`
- `puzzle_pegboard_assembled.stl` / `puzzle_pegboard_assembled.step`

The individual STL files are intended for printing the pieces separately; the assembled model shows the complete design.
