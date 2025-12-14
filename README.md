# UI-MP-001 — Document Processing Automation (UiPath)

---

## Brief Description
UiPath-based automation pipeline designed to process large volumes of scanned engineering drawings and lists of materials.  
The workflow standardizes file naming, revision handling, page splitting, merging, and final organization with minimal human intervention.

---

## Objective
Automate the classification, renaming, revision management, and normalization of scanned technical documents used in industrial engineering projects.

---

## Workflow Overview
The automation is composed of modular UiPath processes executed sequentially:

- **Split PDF Pages**  
  Divides multi-page scanned PDFs into individual pages.

- **Rename Based on Excel**  
  Renames each page using document number, description, and revision extracted from an Excel reference.

- **Merge Revision Pages**  
  Automatically merges pages belonging to the same document revision (2–4 pages).

- **Move to Final Structure**  
  Organizes processed files into standardized output folders.

---

## Tools & Technologies
- UiPath Studio
- PDF Activities
- Excel Activities
- Modular XAML workflows
- Rule-based document classification

---

## Outcome & Impact
- Reduced document processing time by ~67%.
- Enabled scalable handling of thousands of scanned pages.
- Ensured consistent naming, revision control, and folder structure across projects.
- Eliminated recurrent manual classification and metadata errors.

---

## Applications
- Digitization of legacy engineering drawings and Bills of Materials
- Maintenance and fabrication documentation
- Industrial archives with scanned or handwritten technical records
