# OsdagBridge

OsdagBridge is a unified bridge analysis and design add-on for the Osdag software ecosystem (Desktop, Web, and CLI). It provides:

- A shared Python core for geometry, materials, loads, design codes, and validation  
- Support for multiple IRC codes (IRC 6-2017, IRC 5-2015, etc.)  
- Solver adapters (OpenSees, ospgrillage, mock solver for CI)  
- CAD generation (pythonOCC-based)  
- Reporting (LaTeX/PDF)  
- Integration with Osdag Desktop (PySide6) and Osdag Web (Django + React)  

This repository follows a modular architecture with:
- `core/` — headless logic  
- `bridge_types/` — high-level bridge models  
- `components/` — reusable structural components  
- `solvers/` — analysis backends  
- `codes/` — IRC design code implementations  
- `desktop_plugin/` — PySide6 UI for Osdag Desktop  
- `web/` — Django backend + React frontend for Osdag Web  
- `cli/` — standalone command-line interface  

## License
This project is licensed under the **LGPL-3.0** License.
