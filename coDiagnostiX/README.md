# Comprehensive coDiagnostiX Implant Planning Tutorial

**Target Audience:** Dentists with basic implant knowledge transitioning to digital planning.
**Software:** coDiagnostiX (Dental Wings)

---

## 📚 Module Summary & Learning Path

| Module | Topic | Estimated Learning Time | Difficulty |
| :--- | :--- | :--- | :--- |
| **1** | Software Foundations & Interface Mastery | 1 Hour | Basic |
| **2** | Anatomical Analysis Workflow | 1.5 Hours | Basic |
| **3** | Implant Selection & Virtual Placement | 2 Hours | Intermediate |
| **4** | Prosthetic-Driven Planning | 2 Hours | Intermediate |
| **5** | Surgical Guide Design Deep Dive | 2.5 Hours | Advanced |
| **6** | Advanced Techniques (All-on-X, Zygomatic) | 3 Hours | Expert |
| **7** | Export & Manufacturing | 1 Hour | Intermediate |
| **8** | Clinical Integration | 1 Hour | Intermediate |

---

## 🟢 Module 1: Software Foundations & Interface Mastery

### 1.1 Viewport Anatomy & Clinical Relevance

| Viewport | Clinical Purpose | Surgical Significance |
| :--- | :--- | :--- |
| **Axial (Top-Down)** | Cross-sectional view of the arch. | Assesses bucco-lingual width and nerve position relative to ridge width. |
| **Coronal (Frontal)** | Frontal view of anatomy. | Crucial for evaluating sinus floor height and vertical bone availability. |
| **Sagittal (Side)** | Lateral view (slice through the arch). | Key for angulation, A-P spread, and incisive canal identification. |
| **3D Reconstruction** | Spatial visualization. | Patient communication and visualization of the overall ridge topography. |

### 1.2 Step-by-Step: Workspace Customization

1.  **Software Action**: Go to `Tools` > `Options` > `User Interface`. Select "Dental Mode".
    *   **Clinical Purpose**: Ensures tools relevant to implantology are prioritized over orthodontic tools.
    *   **Parameter Settings**: Set background color to black/dark grey for better contrast with CBCT grey scales.
    *   **Time Estimation**: 5 mins.
2.  **Software Action**: Import DICOM. Click `File` > `Import DICOM`. Select folder.
    *   **Common Errors**: Importing "Lossy" JPEG-compressed DICOMs. Always use "Lossless" for surgical accuracy.
    *   **Validation**: Check slice thickness (ideal: 0.2mm - 0.4mm).

### 1.3 Resource Integration
*   📺 [coDiagnostiX Interface Overview](https://www.youtube.com/results?search_query=codiagnostix+interface+tutorial)
*   📺 [Importing DICOM Data Correctly](https://www.youtube.com/results?search_query=codiagnostix+dicom+import)

---

## 🟡 Module 2: Anatomical Analysis Workflow

### 2.1 Nerve Tracing Protocol

**Clinical Rationale**: Avoiding IAN injury is paramount. Digital tracing creates a safety "no-fly zone" for the drill.

#### Step-by-Step:
1.  **Software Action**: Select `Nerve` tool. Locate Mental Foramen in Axial/Coronal view. Click to start point.
2.  **Software Action**: Scroll posteriorly in Pan/Cross-sectional view, clicking every 2-3mm along the canal.
3.  **Parameter Settings**: Set nerve diameter to **2.5mm - 3.0mm** (overestimate slightly for safety).
4.  **Clinical Purpose**: Visual warning system during placement.
5.  **Validation Method**: Rotate 3D view to ensure the nerve tube exits the mental foramen anatomically.
6.  **Surgeon's Note**: *Always identify the "Anterior Loop" of the mental nerve. Extend your safety margin 2mm anterior to the foramen.*

### 2.2 Bone Density Assessment

1.  **Software Action**: Use `Probe` tool or `Hounsfield Unit (HU)` overlay.
2.  **Clinical Purpose**: Predict primary stability.
    *   **> 850 HU (D1)**: Risk of necrosis/overheating. Plan for tapping/countersink.
    *   **< 350 HU (D4)**: Risk of poor stability. Plan for under-drilling or osseodensification.

### 2.3 Resource Integration
*   📺 [Nerve Tracing in coDiagnostiX](https://www.youtube.com/results?search_query=codiagnostix+nerve+tracing)
*   📄 [Study: Accuracy of Digital Nerve Tracing](https://pubmed.ncbi.nlm.nih.gov/)

---

## 🟠 Module 3: Implant Selection & Virtual Placement

### 3.1 Implant Selection Protocol

| Bone Width (Available) | Recommended Diameter | Clinical Rationale |
| :--- | :--- | :--- |
| < 5mm | Narrow (3.0 - 3.5mm) | Maintains >1.5mm buccal/lingual plate. |
| 5 - 7mm | Standard (3.75 - 4.3mm) | Standard loading protocols. |
| > 7mm | Wide (5.0mm+) | Molar sites, immediate placement. |

### 3.2 Step-by-Step: Virtual Placement

1.  **Software Action**: Click `Add Implant`. Select Library (e.g., Straumann, Nobel). Choose diameter/length.
2.  **Software Action**: Drag implant into position on the **Cross-Sectional** view.
3.  **Parameter Settings**:
    *   **Apical Safety**: Keep 2mm from nerve.
    *   **Inter-implant Distance**: 3mm.
    *   **Tooth-to-Implant**: 1.5mm.
4.  **Common Errors**: Placing implant too deep subcrestally without accounting for biologic width.
5.  **Time Estimation**: 10-15 mins per implant.

### 3.3 Resource Integration
*   📺 [Virtual Implant Placement Guide](https://www.youtube.com/results?search_query=codiagnostix+implant+placement)

---

## 🔵 Module 4: Prosthetic-Driven Planning

### 4.1 Importing Intraoral Scans (IOS)

**Clinical Rationale**: CBCT shows bone; IOS shows soft tissue and teeth accurately. Merging them enables true prosthetic-driven planning.

1.  **Software Action**: `File` > `Import STL/PLY`. Select model scan.
2.  **Software Action**: `Registration` > `Point-Based Matching`. Select 3 common landmarks (cusp tips) on CBCT and STL.
3.  **Validation Method**: Check the "Heat Map" or color overlay. Green = good fit. Red = discrepancy.
    *   **Surgeon's Note**: *Scatter from metal fillings in CBCT is the #1 cause of merge errors. Use non-metal landmarks if possible.*

### 4.2 Screw Access Optimization

1.  **Software Action**: Toggle `Prosthetic Sleeve` view.
2.  **Clinical Purpose**: Ensure screw channel exits through the occlusal table (posterior) or cingulum (anterior).
3.  **Adjustment**: Tilt implant axis to move access hole away from incisal edge/facial aspect (esthetic risk).

---

## 🟣 Module 5: Surgical Guide Design Deep Dive

### 5.1 Guide Types & Selection

*   **Tooth-Supported**: Highest accuracy. Use for partially edentulous.
*   **Mucosa-Supported**: Lower accuracy. Requires anchor pins. Use for fully edentulous.
*   **Bone-Supported**: Invasive (requires large flap). Rarely used now.

### 5.2 Step-by-Step: Designing the Guide

1.  **Software Action**: Select `Guide Design Wizard`.
2.  **Software Action**: Define `Insertion Direction` (Block out undercuts).
    *   **Parameter Settings**: **Offset**: 0.1mm - 0.2mm (loosens fit slightly to prevent binding). **Wall Thickness**: 2.5mm - 3.0mm (strength).
3.  **Software Action**: `Add Sleeves`. Choose kit specific (e.g., Guided Surgery Kit).
    *   **Clinical Purpose**: Controls drill depth and angle.
4.  **Software Action**: Add `Inspection Windows` over cusp tips to verify seating during surgery.
5.  **Validation**: Check for "Islands" or unconnected parts of the guide.

### 5.3 Resource Integration
*   📺 [Designing a Surgical Guide Step-by-Step](https://www.youtube.com/results?search_query=codiagnostix+guide+design)

---

## 🔴 Module 6: Advanced Techniques

### 6.1 All-on-X Planning

*   **Tilted Implants**: Use `Angulation Tool` to tilt distal implants 17-30 degrees to avoid sinus/nerve and increase A-P spread.
*   **Bone Reduction Guide**: Plan the "Stackable Guide" workflow. Base guide (pinned) -> Bone reduction guide -> Implant placement guide.

### 6.2 Virtual Sinus Lift

1.  **Software Action**: Use `Segmentation` tool to highlight sinus volume.
2.  **Simulation**: Place implant protruding into sinus. Measure protrusion length to calculate graft volume required (e.g., 0.5cc per 5mm lift).

---

## 🟤 Module 7: Export & Manufacturing

### 7.1 3D Printing Protocols

1.  **Software Action**: `Export` > `Export STL for Manufacturing`.
2.  **Settings**:
    *   **Resolution**: High (50 microns).
    *   **Supports**: Place on the non-fitting surface (outer surface).
3.  **Quality Control**: After printing and curing, insert the metal sleeve. It should fit with firm finger pressure (no glue should be strictly necessary for fit check, but glue is used for final). If it rocks, the printer is not calibrated.

---

## ⚫ Module 8: Clinical Integration

### 8.1 Pre-Surgical Checklist (Downloadable Template)

*   [ ] Guide fits model (if available).
*   [ ] Sleeves are fully seated and glued.
*   [ ] Drill report printed.
*   [ ] Surgical kit matches the planned system (e.g., key handles check).
*   [ ] Backup plan: What if the guide breaks? (Have analog measurements ready).

### 8.2 Intraoperative Troubleshooting

*   **Issue**: Guide rocks.
    *   **Solution**: Check for soft tissue interference or unremoved supports. Use inspection windows.
*   **Issue**: Limited mouth opening.
    *   **Solution**: Use "Lateral Access" sleeves or short drills if planned ahead.

---

## 📝 Proficiency Assessment (Quiz)

**Module 1 & 2:**
1. Why is "Lossy" DICOM compression bad for surgery?
2. What HU value indicates D1 bone?

**Module 3 & 4:**
1. What is the minimum distance between an implant and a natural tooth?
2. Why is "Point-Based Matching" preferred over "Surface Matching" for initial alignment?

---

## 📊 Comparison Tables

### Implant Systems in coDiagnostiX

| System | Library Availability | Guided Kit Compatibility | Notes |
| :--- | :--- | :--- | :--- |
| **Straumann** | Native / Full | Excellent | Highly integrated workflow. |
| **Nobel Biocare** | Full | Good | Check sleeve offsets carefully. |
| **BioHorizons** | Full | Good | Requires specific guided key set. |
| **Neodent** | Full | Good | Popular for All-on-X. |

---

## ⌨️ Efficiency Tips & Shortcuts

*   **Ctrl + Mouse Wheel**: Zoom in/out.
*   **Right Click + Drag**: Pan view.
*   **Double Click Object**: Open properties/settings.
*   **F2**: Rename object/implant.
*   **"Isolate"**: View only the active layer (hide noise).

---

## 📂 Case Difficulty Rating

| Level | Characteristics | Planning Time |
| :--- | :--- | :--- |
| **Level I (Straightforward)** | Single tooth, abundant bone, posterior. | 20-30 mins |
| **Level II (Advanced)** | Multiple teeth, aesthetic zone, sinus lift req. | 45-60 mins |
| **Level III (Complex)** | Full arch, immediate load, zygomatic, extreme atrophy. | 2+ Hours |

---

**References:**
1.  *Accuracy of Static Guided Implant Surgery: A Systematic Review.* (Journal of Clinical Periodontology)
2.  [Dental Wings Official Training Channel](https://www.youtube.com/user/DentalWings)
3.  [International Team for Implantology (ITI) Online](https://www.iti.org/)

*Disclaimer: This tutorial is for educational purposes. Always follow the Instructions for Use (IFU) of the specific medical device and software.*
