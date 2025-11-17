This is LaTeX template for a CV(Curriculum Vitae), Résumé or Cover Letter

#### Requirements

1. You need to install docker and run it
2. Run this cmd from a Bash shell (Linux/macOS/WSL):
   ```
   docker run -u $UID:$GID --rm -v $PWD:/work csmith/awesome-cv-builder
   ```
   On Windows PowerShell, use:
   ```
   docker run --rm -v ${PWD}:/work csmith/awesome-cv-builder
   ```
3. Then you can see the output: cv.pdf
