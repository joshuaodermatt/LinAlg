# LinAlg
LinAlg Cheatsheet 

## Contributing

Contributions, updates, and fixes to this cheat sheet are always welcome! Follow the guide below to set up your editing environment and trigger releases.

### Recommended Setup

I recommend editing with **Visual Studio Code**:

1. Install **VS Code**.
2. Install the **LaTeX Workshop** extension by James Yu.
3. Ensure you have a local LaTeX distribution installed on your machine so the extension can compile files locally:
   * **macOS:** [MacTeX](https://www.tug.org/mactex/)
   * **Windows:** [MiKTeX](https://miktex.org/)
   * **Linux:** TeX Live (`sudo apt install texlive-full`)

*Tip: In VS Code, save your file or press `Ctrl+Alt+B` (`Cmd+Option+B` on macOS) to view the live side-by-side PDF preview.*

---

### Working on the Document

1. Clone the repository and make your edits to the LaTeX source files.
2. If you add new files or subdirectories that need to be included in the release ZIP, add their relative paths to **`archive-list.txt`**.
3. Test your changes locally to ensure `LinAlg.tex` compiles without errors.

---