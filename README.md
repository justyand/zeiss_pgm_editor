# zeiss_pgm_editor

A specialized editor for ZEISS Calypso program files.

---

## ⚠️ Project Status: Alpha
This project is currently in the **alpha stage**. 
- It can read and display the inner structure of Calypso program files.
- While it can technically read any file with the standard ZEISS structure, the open dialog is currently optimized for `.inspection` and `.inspset` files.

### 🚫 Out of Scope
* **No Calculation or Evaluation:** This application will not calculate or evaluate measurement results.<br />
  It does not perform metrology calculations.

## 🚀 Planned Features
- [ ] **XML Export/Import:** A dedicated console tool to export/import files in XML format for integration with other projects.
- [ ] **Direct Modification:** Ability to modify or remove specific program parts to solve issues that cannot be addressed within Calypso.
- [ ] **Version Management:** Change the software version across the entire program to allow opening newer programs in older Calypso versions.
- [ ] **Advanced Search & Edit:** Search, modify, and insert Probes, PCMs, and other program elements.

## 🤝 Contributing & Support
If you have feature requests or would like to provide study materials to help development:

*   **Email:** [justyand@gmail.com](mailto:justyand@gmail.com)
*   **Issues:** [Open a GitHub Issue](link-to-your-git-issue-form-here)

### Study Materials Needed
To improve the parser and compatibility, I am looking for "study materials" such as:
*   **Full Program Folders:** Complete folders with a description of the content.
*   **Dummy Programs:** Programs containing specific features, characteristics, PCMs, and formulas.
*   **Version Variety:** Programs from as many different Calypso versions as possible to ensure wide compatibility.

---

### File Structure Example
The editor currently handles files formatted as follows:
```text
#(
#...
