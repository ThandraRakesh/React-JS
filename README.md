# Responsible AI & GitHub Copilot — Presentation Generator

This branch contains a small generator to produce a 32-slide PowerPoint deck covering Responsible AI and GitHub Copilot.

Files in this branch:
- generate_presentation.py  # Script to generate Responsible-AI-Copilot.pptx using python-pptx
- slides_content.md        # Slide content (32 slides)
- README.md                # This file
- assets/                  # Place your custom logo here as logo.png if desired

How to generate the PPTX locally
1. Clone the repo and checkout the branch:
   git clone https://github.com/ThandraRakesh/React-JS.git
   cd React-JS
   git checkout -b copilot-respai-presentation origin/HEAD

2. Create a virtualenv and install dependency:
   python -m venv venv
   source venv/bin/activate   # or venv\Scripts\activate on Windows
   pip install python-pptx

3. (Optional) Add your logo at assets/logo.png

4. Run the generator:
   python generate_presentation.py

5. The output will be Responsible-AI-Copilot.pptx in the repository root.

Notes
- The script is intentionally simple and uses slides_content.md to populate slides.
- If you want me to push the generated .pptx directly into the repo, reply and I will generate it and commit the binary as well.
