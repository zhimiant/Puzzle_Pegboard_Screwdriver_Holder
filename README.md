# Modular Puzzle Pegboard Screwdriver Holder

![V3 screwdriver-holder model — front, isometric, side and rear views](images/05_v3_model_multiview.png)

*V3 model overview: front puzzle joints, sloped top and bottom surfaces, and rear pegboard hooks.*

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

## 4. Design and Fabrication Documentation

The images in this section are **original screenshots and photographs from this project**. They are shown directly in the README rather than inside tables. The three printing photographs document the manufacturing process; they do not yet show a finished, tested pegboard installation.

### 4.1 Reference Pegboard Hook

The instructor-provided pegboard hook STL was imported into Blender as the starting point for the mounting interface.

![Pegboard hook STL imported in Blender](images/01_reference_pegboard_hook_blender.png)

*Figure 1. Original pegboard hook reference in Blender.*

### 4.2 Blender Modeling

The holder was developed as three separate puzzle-shaped pieces, each with an approximately 15 mm circular screwdriver opening.

![Three puzzle modules viewed from the front in Blender](images/02_blender_modular_holder_front.png)

*Figure 2. Front view showing the interlocking puzzle joints.*

![Three puzzle modules viewed from above in Blender](images/03_blender_modular_holder_top.png)

*Figure 3. Angled top view showing the screwdriver holes and module geometry.*

![Rear view of the pegboard attachment interface in Blender](images/04_blender_modular_holder_rear.png)

*Figure 4. Rear view showing the mounting hooks.*

### 4.3 V3 Model Presentation

![Three individually colored screwdriver holder modules, isometric view](images/06_v3_three_color_isometric.png)

*Figure 5. Three-module layout with distinct colors.*

![Puzzle-module front view](images/07_v3_three_color_front.png)

*Figure 6. Front view of the left, middle, and right puzzle edges.*

### 4.4 Slicing in Bambu Studio

The STL parts were prepared in **Bambu Studio** for the **Bambu Lab H2D**, using a **0.4 mm nozzle** and separate filament colors. The preview shows automatically generated supports.

![Bambu Studio model preparation screenshot](images/08_bambu_studio_single_module.png)

*Figure 7. Preparing a screwdriver-holder module for slicing.*

![Bambu Studio preview of the three-color print](images/09_bambu_studio_sliced_preview.png)

*Figure 8. Layer-by-layer slicing preview of the three-color layout.*

### 4.5 Actual 3D Printing Process

These three photos show the modules **during printing** on the H2D. They are real process photographs, not renderings or completed-product claims.

<p align="center"><img src="images/10_h2d_printing_blue_module.jpg" alt="Blue screwdriver holder module being printed on the H2D" width="350"></p>

*Figure 9. Printing the blue module.*

<p align="center"><img src="images/11_h2d_printing_green_module.jpg" alt="Green screwdriver holder module being printed on the H2D" width="350"></p>

*Figure 10. Printing the green module.*

<p align="center"><img src="images/12_h2d_printing_orange_module.jpg" alt="Orange screwdriver holder module being printed on the H2D" width="350"></p>

*Figure 11. Printing the orange module.*

## Model Files

The `models/` folder contains four models—left, middle, right, and the three-piece layout—each in STL and STEP formats. Click a file name below to open it on GitHub.

| Module | STL (3D printing) | STEP (CAD model) |
| --- | --- | --- |
| Left piece | [puzzle_pegboard_left.stl](models/puzzle_pegboard_left.stl) | [puzzle_pegboard_left.step](models/puzzle_pegboard_left.step) |
| Middle piece | [puzzle_pegboard_middle.stl](models/puzzle_pegboard_middle.stl) | [puzzle_pegboard_middle.step](models/puzzle_pegboard_middle.step) |
| Right piece | [puzzle_pegboard_right.stl](models/puzzle_pegboard_right.stl) | [puzzle_pegboard_right.step](models/puzzle_pegboard_right.step) |
| Three-part layout (separated for different colors) | [puzzle_pegboard_assembled.stl](models/puzzle_pegboard_assembled.stl) | [puzzle_pegboard_assembled.step](models/puzzle_pegboard_assembled.step) |

The three individual STL files are for printing each module separately. The assembled files preserve the separated three-part layout for multicolor printing, rather than fusing them into a single solid.

### Sliced Print Job

The three-color print job was sliced in **Bambu Studio** for the **Bambu Lab H2D** with a **0.4 mm nozzle**.

**[Download the three-color sliced print job (.gcode.3mf)](models/puzzle_pegboard_three_color_sliced.gcode.3mf)**

The `.gcode.3mf` file is a sliced 3MF print-job container that includes G-code and print-related settings. It is different from the STL/STEP design files above. Use the correct printer and material configuration before running the print.
